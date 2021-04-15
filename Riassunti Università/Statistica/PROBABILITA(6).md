# Probabilità (6)

## Media o Valore atteso della variabile casuale X

$$
\mu_X = E(X) = \sum_{x}x*p(x)
$$

**Perché valore atteso?**

un giocatore di dati paga una posta e guadagna in ogni mano un importo pari a:

x = faccia che si presenta

| X    | P(x) |
| ---- | ---- |
| 1    | 1/6  |
| 2    | 1/6  |
| 3    | 1/6  |
| 4    | 1/6  |
| 5    | 1/6  |
| 6    | 1/6  |

$$
E(X) = 1*1/6 + 2*1/6+...+6*1/6 = 3.5
$$

E(X), in base all'approccio frequentista 

E' il guadagno medio che, a priori il giocatore si aspetta di conseguire in una lunga serie di giocate.

Esempio: Un giocatore d’azzardo che ha 7.000 € effettua questo gioco: -al primo lancio di una moneta punta 1.000 € su testa e se vince si ritira. Se invece perde, al secondo lancio punta 2.000 € su testa e, anche in questo caso se vince si ritira. Se perde ancora, al terzo lancio punta gli ultimi 4.000 € su testa. Stabilire se il gioco è equo e determinare quale è la probabilità di vincere 1.000 €.



X = {guadagno}

| Risultato Moneta | xi    | p(xi)                 |
| ---------------- | ----- | --------------------- |
| T                | 1000  | 1/2                   |
| CT               | 1000  | 1/4                   |
| CCT              | 1000  | 1/8                   |
| CCC              | -7000 | 1-(1/2+1/4+1/8) = 1/8 |
|                  | Tot   | 1                     |


$$
E(X) = \sum_{j=1}^{n}n_i*p(x_i) = \frac{1}{2}*1000 +\frac{1}{4}*1000 + \frac{1}{8} *1000 - 7000*\frac{1}{8} = 0 \text{Per cui il gioco è equo}
$$

***

### La Roulette europea è un gioco equo?

La puntata "pieno" : su un solo numero, 35 volte la posta.

| F    | P(G=g) |
| ---- | ------ |
| -1   | 36/37  |
| 35   | 1/37   |
| Tot  | 1      |

$$
E(G) = \sum_{g}gp(g) = -1 * \frac{36}{37}+35*\frac{1}{37} = -\frac{1}{37}
$$

La puntata sul colore: vinciamo due volte la posta cioè guadagniamo il valore della posta stessa.

**Facciamo il calcolo in ambiente R:**

- x <- c(1,-1)
- f <- c(18/37, 19/37)
- sum(x*f)
- Risultato: -0.02702703

Quindi in media, puntando un € sul rosso si perdono circa 27 centesimi.

***

La puntata cavallo: su 2 numeri (x e y), 17 volte la posta

- A = {esce il numero x}
- B = {esce il numero y}

$$
P(A\cup B) = P(A) + P(B) = \frac{1}{37} + \frac{1}{37} = \frac{2}{37}
$$

Usando una tabella:

| G    | P(G = g) |
| ---- | -------- |
| -1   | 35/37    |
| 17   | 2/37     |
| Tot  | 1        |

$$
E(G) = \sum_{g}gp(g) = -1*\frac{35}{37}+17*\frac{2}{37} = \frac{-1}{37}
$$

Altre puntate possibili:

- Trasversale Pleine (terzina): 11 volte la posta 
- Carrè (quarantina): 8 volte la posta
- Trasversale Simple (sestina): 5 volte la posta
- Colonne (colonna): 2 volte la posta


$$
E(G) = -\frac{1}{37}
$$
Qualsiasi sia la giocata, il valore atteso del guadagno è sempre lo stesso...

...ma il rischio associato alle diverse giocate è diverso!

Che indicatore conosciamo capace di catturare questo diverso rischio sotto forma di variabilità associata al risultato?

***

**Analizziamo la situazione utilizzando il software R**

- x <- c(1,-1)
- f <- x(18/37, 19/37)
- m <- sum(x*f)
- sum((x-m)^2*f)

Risultato: 0.9992695



- x <- c(35, -1)
- f <- c(1/37, 36/37)
- m <- sum(x*f)
- sum ((x-m)^2*f)

Risultato: 34.08035



Una varianza (rischio) molto più elevato nel secondo caso!

A voler essere pignoli, evitiamo i problemi di "dimensionalità" e calcoliamo sigma.

***

### Proprietà dell'operatore E

1. **linearità del valore atteso:** Sia Y = g(X) una funzione di X. Allora: E(Y) = E[g(X)] = $\sum_xg(x)p(x)$

2. E è un operatore lineare: $a,b \in R$
   $E(aX + b) = aE(X) + b$

3. X,Y
   $E(X+Y) = E(X)+E(Y)$
4. E(c) = c

***

## Varianza e deviazione standard

Definizione:

Data X come una variabile casuale con media $\mu = E(X)$, si chiama varianza di X $X (\sigma^2_X)$ il valore atteso della funzione $g(X) = (x - \mu)^2$

***

### Proprietà dell'operatore Var

1. $Var(X)\geq 0$

2. $Var (X) = E[(X-\mu)^2] = E[X^2+\mu^2-2\mu X] = \\
   = E(x^2) + E(\mu^2) - 2\mu E(X) = \\
   = E(X^2) + \mu^2 - 2\mu^2 = E(X^2) - \mu^2$



$$
Var(aX+b) = E{[aX+b-E(aX+b)]^2}
\\ = E[(aX+b-aE(x)-b)^2] = E{[a(X-E(x))]^2}
\\ = a^2E{[X-E(x)]^2}
$$

3. $a,b \in R, Var(aX + b) = a^2Var(X)$

***

### Consideriamo l'evento:

- E = {lancio di una moneta e di un dado regolari}
- X = "Punteggio del dato - # croci"



Lo spazio campionario è il seguente:

S = 

| 1T   | 2T   | 3T   | 4T   | 5T   | 6T   |
| ---- | ---- | ---- | ---- | ---- | ---- |
| 1C   | 2C   | 3C   | 4C   | 5C   | 6C   |

***

X ha dominio in S e codominio in R: ad ogni evento elementare $e_i \in S$ associa un numero $x \in R$ 
Infatti:

| ei   | X    |
| ---- | ---- |
| 1T   | 1    |
| 2T   | 2    |
| 3T   | 3    |
| 4T   | 4    |
| 5T   | 5    |
| 6T   | 6    |
| 1C   | 0    |
| 2C   | 1    |
| 3C   | 2    |
| 4C   | 3    |
| 5C   | 4    |
| 6C   | 5    |



**Quindi X ha trasformato gli eventi elementari in numeri!**

in tale trasformazione ha conservato le probabilità associate agli ei Infatti:

![ProbabilitaAssociate](C:\Users\franc\Desktop\Riassunti Università\Immagini\ProbabilitaAssociate.PNG)

 Ovviamente è 
$$
\sum_{i=0}^{6}P(X = i) = 1
$$
La media della variabile casuale X  = "punteggio del dado - # di croci" è:
$$
E(x) = \sum_{x=0}^{6}xp(x) = (0*\frac{1}{12})+(1*\frac{1}{6})+(2*\frac{1}{6})+(3*\frac{1}{6})+(4*\frac{1}{6})+(5*\frac{1}{6})+(6*\frac{1}{12}) = \frac{36}{12} = 3
$$

***

### La Varianza della Variabile casuale X = punteggio del dado - #di croci è:

$$
Var(X) = E[(X-\mu)^2] = \sum_{x=0}^{6}(x-3)^2p(x) = \\ = [(0-3)^2*\frac{1}{12}] + [(1-3)^2*\frac{1}{6}] + [(3-3)^2*\frac{1}{6}]+ \\ +[(4-3)^2*\frac{1}{6}] + [(5-3)^2*\frac{1}{6}] + [(6-3)^2*\frac{1}{12}] = \frac{38}{12} = 3.16
$$

***

#### Esempio

Consideriamo una funzione di variabile casuale $Z = g(X) = (X-1)^2$ dove la variabile casuale X = {# di croci che si possono presentare lanciando per due volte una moneta}

Ovviamente lo spazio campionario è S = {TT,TC,CT,CC}.
Possiamo sintetizzare la situazione nella seguente tabella:



| X    | Z    |
| ---- | ---- |
| 0    | 1    |
| 1    | 0    |
| 2    | 1    |

Ora possiamo calcolare la probabilità di ciascuna determinazione di Z attraverso la probabilità delle diverse realizzazioni di X.

***

![TabellaCalcoloValoreAtteso](C:\Users\franc\Desktop\Riassunti Università\Immagini\TabellaCalcoloValoreAtteso.PNG)

 Per calcolare il valore atteso di Z si ha:
$$
E(Z) = \sum_{z}zp(z) = (0*\frac{2}{4}) + (1*\frac{2}{4}) = \frac{2}{4} = \frac{1}{2}
$$


Vi è un altro modo per calcolare il valore atteso partendo direttamente dalla funzione di probabilità p(x) (proprietà 1):

| X    | Z = (X-1)^2 | p(x) |
| ---- | ----------- | ---- |
| 0    | 1           | 1/4  |
| 1    | 0           | 2/4  |
| 2    | 1           | 1/4  |

