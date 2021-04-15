# STATISTICA 5

"***La Probabilità***"



**Prova:** lancio di una moneta 7 volte



I) TTTTCCC

II) CTTCTCC

III) CCCCCCC



**Ordine delle preferenze**

2 - 1- 3



### Illusione Cognitiva

$$
\text{Più Tipico} \neq \text{Più Probabile}
$$



### Legge dei piccoli numeri o illusione del giocatore d’azzardo 

**Prova**: lancio di un dado: 4V e 2R. 

i) R V R R R 

ii) V R V R R R 

iii) V R R R R R

Sequenze sbilanciate sul rosso **meno probabili!**



**Ordine delle preferenze**: 

2) meno sbilanciata! 

1) 

3)
$$
1) = 2) – primo lancio 
$$


2) ha probabilità di 2/3 inferiore di 1)!!!! 



La situazione si ripropone con:

-  la roulette
- il lotto, etc.



Dov'è L'illusione?

- **Serie corte**
- **Serie lunghe**
- **Serie infinite**

***

### PARADOSSO DI MONTHY HALL

Prendo 3 scatole identiche.

1.

2.

3.



E so di queste 3 scatole che:

1) 1000€ in una scatola

2) scelgo una scatola

3) Mostro il contenuto vuoto di una delle 2 non scelte

4) Offro di cambiare la vostra con la rimanente chiusa

***

Immaginiamo un numero n grande di scommesse.

**Che fare?**

La prima scelta è indifferente

P1 = P2 = P3 = 1/3

Scegliamo ad esempio la scatola 1.

IN questo caso la probabilità che nella prima scatola ci sia il malloppone è di 1/3

La probabilità che nelle altre 2 ci sia il malloppone è di 2/3.

Se il conduttore mi rivela che dentro a una delle 2 scatole c'è il vuoto e mi offre lo scambio allora io scambierò sempre.

- Se si cambia infatti 2 volte su 3 si vincono i soldi.

- Se non si cambia si vincono i soldi una volta su 3.

****

***E' verificato che la strategia vincente nell'enigma di monthy all è quella di cambiare sempre***

***

## ELEMENTI DI CALCOLO COMBINATORIO

Definizione: *Dato un insieme In, con Pn si indica il numero di tutte le permutazioni semplici di In*.
$$
P_n = n* (n-1) * ... * 3*2*1 = n!
$$
In quanti modi diversi si possono disporre tre palline colorate (B,N,R) sui vertici di un triangolo?

Se le palline sono 3 allora farò 3 fattoriale e quindi:
$$
P_3 = 3! = 6
$$
**Definizione:** dati n elementi distinti si dicono disposizioni semplici di n elementi presi a k a k $(k\leq n)$ tutti i possibili sottoinsiemi di k elementi distinti e totalmente ordinati presi dagli n dati
$$
D_{n,k} = \frac{n!}{(n-k)!}
$$
**ESEMPIO PRATICO**

Dati i 3 elementi a,b,c, scrivere tutte le possibili disposizioni di classe 2.

**Elementi: 3.**

**Classe: 2.**

- a,b
- b,a
- a,c
- c,a
- b,c
- c,b

$$
D_{3,2}=\frac{3!}{(3-2)!} = 3! = 6
$$

**ESEMPIO PRATICO 2**

Quanti sono i numeri naturali aventi cifre distinte che si possono ottenere con le cifre 1,2,3,4,5?
$$
D_{5,1}+D_{5,2}+D_{5,3}+D_{5,4}+D_{5,5} = 325
$$


**DEFINIZIONE:**

Dati n elementi distinti, si dicono combinazioni semplici di n elementi presi a k a k tutti i possibili sottoinsiemi di k elementi distinti presi dagli n dati.
$$
C_{n,k} = \frac{D_{n,k}}{k!} = \frac{n!}{(n-k)!k!} = (\frac{n}{k})
$$

$$
k\leq n
$$

Nota Bene: 
$$
C_{n,k} \neq D_{n,k} \text{  perchè}\space C_{n,k} \text{non tiene conto dell'ordine}
$$


**ESEMPIO**

Dati i 3 elementi a,b,c scrivere tutte le combinazioni di classe 2:

- a,b
- a,c
- b,c

$$
C_{3,2} = (\frac{3}{2}) = \frac{3!}{2!1!} = 3
$$

***

# Concetti Base di probabilità

***"Teoria degli insiemi"*** -> ***"Teoria della probabilità"***



L'esito di un fenomeno (processo, prova) è un **evento A sottoinsieme di S**

L'insieme di tutti i possibili eventi è lo spazio campionario (S).

Un evento semplice (**elementare**) può essere descritto da una singola caratteristica; si tratta del sottoinsieme {a} contiene S costituito da un solo punto.

***

## La probabilità: definizioni alternative

Definizione **classica**.

$$
P(A) = \frac{\text{# casi favorevoli ad A}}{\text{# casi possibili}}
$$


Il Problema è: equi-probabilità.

***

#### La Definizione **frequentista**.

$$
P(A) = \lim_{n\to \infty}\frac{n_A}{n}
$$

Problema: **ripetitività** dell'esperimento.
Molti eventi che non possiedono tale requisito sono valutabili probabilisticamente!

***

#### La definizione soggettivista

La probabilità è la valutazione che il singolo individuo può coerentemente formulare, in base alle proprie conoscenze, del grado di avverabilità di un evento.

Non esiste una misura obiettiva di P ma vi sono casi in cui le singole valutazioni coincidono.

***

### DEFINIZIONE ASSIOMATICA

Una misura di probabilità P è una funzione di insieme a valori reali definita nello spazio campionario
$$
S(P:S\to R)
$$

1. $$
   P(A) \ge 0 \space \forall A
   $$

2. $$
   P(S)=1
   $$

3. $$
   P(A_1\cup A_2 \cup...)=P(A_1)+P(A_2)+...
   $$

   Per ogni successione finita o infinita di eventi disgiunti



Dai 3 assiomi seguono i teoremi fondamentali del calcolo delle probabilità:

1. $$
   \forall A,B\subset S, P(B\cap A) = P(B) - P(A\cap B)
   $$

2. $$
   \forall A \subset S, P(A) = 1 - P(A)
   $$

3. $$
   P(\empty) = 0
   $$

4. $$
   A\subset B, P(A)\leq P(B)
   $$

5. $$
   \forall A \subset S, 0\leq P(A) \leq 1
   $$

6. $$
   A1,A2\subset S
   $$

   allora:
   $$
   P(A_1 \cup A_2) = P(A_1) + P(A_2) - P(A_1 \cap A_2)
   $$
   



Se:

- P(A) = 0 	A è un evento impossibile
- P(A) = 1     A è un evento certo

Un evento **congiunto** è un evento che dispone di 2 o più caratteristiche.

> Esempio: si consideri la prova:
>
> Lancio di un dado e osservazione del numero che si presenta
>
> S = {1,2,3,4,5,6}



Alcuni eventi:

- A = si presenti un numero pari
- B = si presenti un numero dispari
- C = si presenti un numero primo



A = {2,4,6}

B = {1,3,5}

C = {1,2,3,5}
$$
A \cup B 
\\ \text{si verifica A e/o B}
\\ \text{si presenta un numero pari o dispari}
\\ \text{{1,2,3,4,5,6}}
$$

$$
A \cup C
\\ \text{{1,2,3,4,5,6}}
\\ \text{{si presenta un numeor pari o primo}}
$$

$$
B \cap C 
\\ \text{si verifica B e C}
\\ \text{{si presenta un numero primo dispari}}
\\ \text{{1,3,5}}
$$

$$
!C = \text{{non is presenta un numero primo} = {4,6}}
$$

$$
A \cap B = \empty \to \text{A e B incompatibili o disgiunti}
$$


Si indichi quale delle seguenti coppie di eventi sono **incompatibili (disgiunti)**:

- Essere Fumatore, essere minorenne
- Essere studente universitario, essere coniugato
- Estrarre una carta di cuori, estrarre una carta di quadri da un mazzo di carte da poker
- Osservare un numero pari, osservare un numero dispari nel lancio di un dado

***

Probabilità (approcci):

- Classico 
- Frequentista
- Soggettivista



**Tutte portano all'Approccio assiomatico**.



Esempio: in una indagine su 300 famiglie che possiedono un televisore a grande schermo viene chiesto se il TV è HDTV e se hanno acquistato un DVD negli ultimi 12 mesi:

|          | DVD  | DVD  | Tot  |
| -------- | ---- | ---- | ---- |
| TV       | SI   | NO   |      |
| HDTV     | 38   | 42   | 80   |
| Non HDTV | 70   | 150  | 220  |
| Tot      | 108  | 192  | 300  |

Quel è la probabilità che una famiglia scelta a caso abbia acquistato un TV HDTV?
$$
P(HDTV)=\frac{80}{300}
$$

$$
P(HDTV e DVD) = ?
$$

$$
P(HDTV \cap DVD) = \frac{38}{300} = 0.127
$$

Due eventi sono **incompatibili** se non possono verificarsi contemporaneamente.
$$
P(HDTV \text{o }DVD) = ?
$$

$$
P(HDTV \cup DVD) = \frac{80}{300}+\frac{108}{300}-\frac{38}{300} = \frac{150}{300} = 0.5 
$$

#### LA LEGGE DELLE PROBABILITA' TOTALI

Per eventi qualunque:
$$
P(A \cup B) = P(A) + P(B) - P(A \cap B)
$$
Per eventi incompatibili:
$$
P(A \cup B) = P(A) + P(B)
$$

***

#### EVENTO UNIONE

Quindi, dati 2 eventi A e B, **l'evento Unione:**
$$
A \cup B
$$
è l'evento che si verifica quando si verifica A o B (oppure entrambi)

![insiemiDislocati](C:\Users\franc\Desktop\Riassunti Università\Immagini\insiemiDislocati.PNG)



***

#### EVENTO INTERSEZIONE

Mentre, dati 2 eventi E e H, **l'evento intersezione**:
$$
E \cap H
$$
è l'evento che si verifica quando si verificano E e H contemporaneamente.

![insiemiIntersecati](C:\Users\franc\Desktop\Riassunti Università\Immagini\insiemiIntersecati.PNG)

***

### Riepilogando

Dati 2 eventi E e H **incompatibili:**
$$
P(E\cup H) = P(E + P(H)
$$
![Compatibili](C:\Users\franc\Desktop\Riassunti Università\Immagini\Compatibili.PNG)



Se invece E e H sono **compatibili:**
$$
P(E\cup H) = P(E) + P(H) - P(E\cap H)
$$


![Incompatibili](C:\Users\franc\Desktop\Riassunti Università\Immagini\Incompatibili.PNG)
$$
E \cap H = \empty
$$

***

## Probabilità Condizionata

$$
P(DVD/HDTV) = ? = \frac{38}{80} = 0.475 
$$

$$
P(A/B) = \frac{P(A\cap B)}{P(B)}, con \space P(B)>0
$$

Applicando questa espressione:
$$
P(DVD/HDTV) = \frac{P(DVD\cap HDTV)}{P(HDTV)} = \frac{\frac{38}{300}}{\frac{80}{300}} = 0,475
$$


**ESEMPIO:**

Si lanci per 3 volte una moneta non truccata.
Definiti gli eventi I = (Nessuna testa) e G=(meno di 2 teste), si calcoli P(I|G)



Lo spazio campionario è il seguente:

- (T, T, T) = e1
- (T, T, C) = e2
- (T, C, T) = e3
- (T, C, C) = e4
- (C, T, T) = e5
- (C, T, C) = e6
- (C, C, T) = e7
- (C, C, C) = e8



Poiché gli otto eventi elementari di S sono equiprobabili e poiché
$$
\sum_{i=1}^{8}P(e_i) = 1
$$

$$
P(e_i) = \frac{1}{8} \space \text{ } \space \text{  }i = 1,...,8
$$

$$
G = \text{{ottenere meno di 2 T}} = (e_4 \cup e_6 \cup e_7 \cup e_8)
$$

Che conseguenze ha su S il fatto di sapere che si è realizzato G?
$$
P(I/G) = \frac{1}{4}
$$

1. G va assunto come spazio campionario (lo spazio dei risultati che interessa si riduce a G)
2. I soli elementi di I che interessano sono quelli che appartengono anche a G ($I\cap G$)


$$
A e B \text{ sono} \textbf{ indipendenti se }  P(A/B) = P(A)
$$
Quindi rappresentando tabellarmente:

|          | Soddisfatto dell'acquisto | Soddisfatto dell'acquisto | Tot  |
| -------- | ------------------------- | ------------------------- | ---- |
| TV       | SI                        | NO                        |      |
| HDTV     | 64                        | 16                        | 80   |
| Non HDTV | 176                       | 44                        | 220  |
| Tot      | 240                       | 60                        | 300  |


$$
P (Soddisfatti/HDTV) = \frac{64}{80}=0.8
\\P(Soddisfatti) = \frac{240}{300}= 0.8
$$

***

#### REGOLA DEL PRODOTTO

$$
P(A\cap B) = P(A/B) * P(B)
$$

#### REGOLA DEL PRODOTTO PER EVENTI INDIPENDENTI

$$
P(A\cap B)=P(A)*P(B)
$$

***

### Osservazione

Siano E e G due eventi; 
$$
P(E \cap G) \text{può essere calcolata in 4 differenti modi:}
$$

- Se è nota la **probabilità condizionata** si può ricorrere al principio delle probabilità composte:

  
  $$
  P(E \cap G) = P(E/G)* P(G)
  $$
  
- Se è nota la **probabilità dell'evento unione:**

  
  $$
  P(E\cup G) = P(E) + P(G) - P(E\cap G) \\\to P(E\cap G) = P(E) + P(G) - P(E\cup G)
  $$
  
- Se è noto che E e G sono **indipendenti**, si ottiene per prodotto cioè:

  
  $$
  P(E \cap G) = P(E) P(G)
  $$
  
- Se è noto che E e G sono **incompatibili** 

  
  $$
  P(E \cap G) = 0
  $$

***

### **una soluzione analitica per il problema del "Paradosso di Monthy Hall"**



Dove si considerano gli eventi:

- $$
  S_i = \text{{i soldi sono nella scatola i}}
  $$

- $$
  A_i = \text{{viene aperta la scatola i}}
  $$

  
  



Avevamo scelto la scatola 1.

**Se si cambia** la probabilità di vincere i soldi è:
$$
P[(A_2 \cap S_3)\cup(A_3 \cap S_2)] \text{ = (incompatibilità)}
$$

$$
= P(A_2 \cap S_3) + P(A_3 \cap S_2) = 
$$

$$
P(S_3)P(A_2/S_3)+P(S_2)P(A_3/S_2)= \\
\frac{1}{3}*1 + \frac{1}{3}*1 = \frac{2}{3}
$$

***

### Ritardi nel gioco del Lotto

Facile accettare l'indipendenza di estrazioni successive, difficile concludere che la probabilità di un evento qualsiasi in una certa estrazione non possa essere modificata da qualsiasi evento verificatosi in una precedente estrazione.

Sia $\theta$ la probabilità che un prefissato numero si verifichi ad una data estrazione del lotto.

Si tratta di calcolare la probabilità che non essendosi verificato per t estrazioni, si verifichi alla $(t+1) - ma$


$$
E_K = \text{{il numero esce alla kesima estrazione}}
$$

$$
P(E_{t+1}|E_1 \cap E_2 \cap . . . \cap E_{t-1} \cap E_t) = 
$$

$$
\frac{(1 - \theta)^t\theta}{(1 - \theta)} = \theta = P(E_{t+1})
$$

***

### Diagrammi ad albero

SI lancia una moneta truccata P(T) = 2/3 e P(C)= 1/3.
Se esce T viene scelto a caso un  numero tra 1 e 9; se esce C si sceglie a caso un numero tra 1 e 5. Si determini la probabilità che venga scelto un numero pari.

![AlberoAzzurro](C:\Users\franc\Desktop\Riassunti Università\Immagini\AlberoAzzurro.PNG)

La scatola A contiene nove carte numerate da 1 a 9, la B cinque carte numerate da 1 a 5. Viene scelta una scatola a caso e da questa si estrae una carta. Il numero è pari. Calcolare la probabilità che la carta venga dalla scatola A.

![AlberoVerde](C:\Users\franc\Desktop\Riassunti Università\Immagini\AlberoVerde.PNG)

Dall'esame del diagramma:
$$
P(A \cap P) = \frac{1}{2} * \frac{4}{9} = \frac{2}{9}
$$
"i casi favorevoli" sono individuati dai 2 cammini che conducono ad un numero pari.
$$
P(P)= \frac{1}{2} * \frac{4}{9} + \frac{1}{2} * \frac{2}{5} = \frac{19}{45} \to
\\ P(A|P) = \frac{P(A\cap P)}{P(P)} = \frac{\frac{2}{9}}{\frac{19}{45}} = \frac{10}{19}
$$

***

### La Formula di Bayes

Un evento A è l'effetto di k **possibili cause**: gli eventi $C_1,...,C_I,...,C_k$ necessari ed incompatibili.


$$
P(C_i|A) = ?
$$
Notare la particolarità del problema!

> Le Cause generano una partizione dello spazio campionario

**Prima:**

Le probabilità degli eventi venivano determinate prima degli esperimenti

**Adesso:**

Situazione rivoltata: si conosce il risultato dell'esperimento e si vuole calcolare la probabilità che sia dovuto ad una certa causa.

**Soluzione**
$$
C_I, i = 1, k \text{ costituiscono una partizione di S}
\\
S = C_1 \cup C_2 \cup...\cup C_k
$$

$$
A = A \cap S = A \cap (C_1 \cup...\cup C_k)
\\ = (A\cap C_1)\cup... \cup(A \cap C_k)
$$

$$
(A\cap C_i), i = 1, ..., k \text{ sono disgiunti}
$$

***

$$
P(A) = P(A \cap C_1)+...+P(A \cap C_k)
$$

Oppure
$$
P(A) = P(C_1)P(A|C_1)+...+P(C_k)P(A|C_k)
$$

Ma per definizione:
$$
P(C_I|A) = \frac{P(C_i \cap A)}{P(A)}
$$

$$
P(C_i|A) = \frac{P(C_i)P(A|C_i)}{\sum_{j=1}^{k}P(C_j)P(A|C_j)} = \text{guarda esercitazione 6 santi}
$$

- $P(C_i|A)$ = **probabilità a posteriori**

  > Probabilità di Avere la tosse Dato che si è positivi

- $P(C_i)$ = **probabilità a priori**

  > Si Prende dai Casi Precedenti di Polmonite, il becero rischio di ammalarsi.
  >
  > Semplice rapporto tra ammalati ed esposti al rischio.

- $P(A|C_i)$ = **probabilità probative o verosimiglianza**

  > Verosimile in Statistica significa quantità precisa, che si studierà l'anno prossimo
  >
  > Probabilità di essere Ammalati dato che ho la tosse.

IL verificarsi di A modifica la probabilità di $C_i$ facendola passare da $P(C_i)$ a $P(C_i|A)$; 

A determinare tale modifica sono le probabilità probative.

> conta he ikl denominatore si chiama costante di normalizzazione



**Esempio:**

![Esempioprobative](C:\Users\franc\Desktop\Riassunti Università\Immagini\Esempioprobative.PNG)

Si estrae a sorte un'urna con $P(U_1) = P(U_2) = 0.5$

A = {pallina è bianca}
$$
P(U_1|A) = ?
$$

$$
P(C_i|A) = \frac{P(C_i)P(A|C_i)}{\sum_{j=i}^{k}P(C_j)P(A|C_j)}
$$

$$
P(U_1|A) = \frac{P(U_1)P(A|U_1)}{P(U_1)P(A|U_1)+P(U_2)P(A|U_2)} = \frac{\frac{1}{2}*\frac{4}{10}}{\frac{1}{2}*\frac{4}{10}+\frac{1}{2}*\frac{3}{8}} = 0.52
$$

***

## Inizio Concezione di Modelli per il Calcolo della Probabilità 

### Distribuzione di probabilità di una variabile causale discreta

Distribuzione delle ipoteche sulle case per settimana:

| Ipoteche | Probabilità |
| -------- | ----------- |
| 0        | 0.10        |
| 1        | 0.10        |
| 2        | 0.20        |
| 3        | 0.30        |
| 4        | 0.15        |
| 5        | 0.10        |
| 6        | 0.05        |
| Tot      | 1           |



Una **distribuzione di probabilità** per una variabile aleatoria discreta è l'elenco di tutti i possibili **Esiti** per quella particolare v.c.[variabile Casuale]. A tali esiti è **associata** la probabilità di verificarsi.

> Il Concetto attratto si esprime con la lettera maiuscola.

Esperimento: *lancio di 3 monete*

- X = numero totale delle T

- X è una variabile causale

- P(X = x)distribuzione di probabilità (o funzione di probabilità)

  > Probabilità che la variabile Casuale X assuma il valore x

![DistribuzioneDiProbabilità](C:\Users\franc\Desktop\Riassunti Università\Immagini\DistribuzioneDiProbabilità.PNG)

***

#### Nota Bene

P(x) può essere rappresentata in forma di:

- Tabella
- Grafico
- Formula (veri e propri modelli)

**Definizione più formale:**

*"Una **variabile causale** è una funzione che associa ad ogni evento elementare di S uno ed un solo numero reale"*

---

#### Scopo:

Passare da S ad uno spazio numerico molto più semplice.

Procedura logica 

1. $S \to P(x)$
2. Dimentichiamo S
3. Lavoriamo **molto** più semplicemente sul nuovo spazio

Es: Probabilità di avere al più una testa?


$$
P(X\leq 1) = P(0) + P(1) = \frac{1}{8} + \frac{3}{8} = \frac{1}{2}
$$


- X è una variabile **casuale discreta** se è definita in uno spazio campionario discreto

- X può assumere un numero finito o un'infinità numerabile di valori

- X è una variabile **causale continua** se è definita in uno spazio campionario continuo

- X può assumere tutti i valori di un intervallo (t,T)

***

#### Definizione

Data una variabile causale X discreta:
$$
p(x) = P(X = x)
$$
Si chiama **funzione di probabilità** di X.



E' chiaro che:

- $p(x) \geq 0$
- $\sum_{x}^{} p_{X}(x) = 1$ (somma delle probabilità deve essere 1)

***

### Valore Atteso (E = expectation)

$$
\mu = E(x) = \sum_{i}x_ip(x_i)
$$

Per la tabella delle ipoteche sulle case:
$$
\mu = 0*0.1+1*0.1+...+6*0.05 = 2.8
$$
### Varianza e deviazione standard:

Var è insieme ad E internazionale.
$$
\sigma^2 = Var(X) = \sum_{i}[x_i - E(x)]^2p(x_i)
$$

$$
\sigma = \sqrt{\sum_{i}[x_i-E(x)]^2p(x_i)}
$$

Per l'Esempio delle ipoteche sulle case:
$$
\sigma^2 = (0-2.8)^2*0.1+(1-2.8)^2*0.1+...+(6-2.8)^2*0.05 = 2.8
\\\sigma = 1.57
$$

> Volatilità = Variabilità = Rischio