# Statistica 2

Francesco Rigoni



# Gli Strumenti Analitici

Gli **Strumenti Analitici** sono un maniera conveniente per riassumere in pochi "parametri" le caratteristiche principali di una distribuzione di frequenza.

Essi sono misure di tendenza:

- centrale
- posizione
- variabilità
- forma.

Nei data-set le osservazioni mostrano una tendenza a raggrupparsi attorno ad un valore centrale che per noi sarà un **valore tipico utilizzabile per sintetizzare l'intero insieme**



Tale valore sarà una misura di **Posizione** o di **Tendenza centrale**

<hr>

Possiamo quindi Prendere 2 diverse strade:

- **VALORI MEDI**: Valori intorno ai quali si ritiene sia concentrata la variabile dando quindi un'idea sintetica del fenomeno

- **INDICI DI POSIZIONE**: Scegliere alcuni valori caratteristici ("strategici") della distribuzione

## La Media Aritmetica

L'indice più noto ed utilizzato
$$
P = (1,2,3,4)
$$

$$
X = (1,1,8,6)
$$

$$
\mu = \frac{1+1+8+6}{4} = \frac{16}{4} = 4
$$

Da cui possiamo esprimere la formula generale
$$
\mu = \frac{x_1+x_2+...+x_n}{N} = \frac{1}{N}\sum_{i=1}^{N}x_i
$$
Indichiamo con x1 il valore più piccolo e con xn quello più grande della distribuzione:
$$
x_1 <= \mu <= x_N
$$

<hr>

Ricordare che la media conta relativamente e in base all'equi-distribuzione

Esempio: Media dei rendimenti di 17 fondi azionari

| 1    | 2    | 3    | 4    | 5    | 6    | 7    | 8    | 9    | 10   | 11   | 12   | 13   | 14   | 15   | 16   | 17   |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 32.2 | 29.5 | 29.9 | 32.4 | 30.5 | 30.1 | 32.1 | 35.2 | 10   | 20.6 | 28.6 | 30.5 | 38   | 33   | 29.4 | 37.1 | 28.6 |



Calcolando la media su questi dati essa risulta essere uguale a
$$
\mu = 29,86
$$
La media però i un punto di equilibrio tale che le osservazioni più piccole vanno a bilanciare quelle più grandi, risulta infatti influenzata dagli **Outlier** ovvero valori anomali.

![Outlier](C:\Users\franc\Desktop\Riassunti Università\Immagini\Outlier.PNG)

## Definiamo gli scarti

$$
\epsilon = (x_i - \mu) i = 1,2,...,N
$$

$$
\sum_{i=1}^{N}(x_i-\mu)=0
$$

Brevemente la somma degli scarti è sempre zero con la media.



Questa proprietà è la principale ragione perché la media aritmetica è la più diffusa misura di tendenza centrale (baricentro).



La media aritmetica è invariante per trasformazioni lineari:

Data la distribuzioni:
$$
x1,x2,...,x_N; \mu_X
$$
Se si passa alla distribuzione 
$$
y_i = a + bx_i
$$
la media sarà:
$$
\mu_Y = a + b\mu_X
$$

<hr>

Data la distribuzione del numero di figli in 23 famiglie di una sezione di censimento di Rome. 

| 2    | 3    | 2    | 1    |
| ---- | ---- | ---- | ---- |
| 1    | 1    | 2    | 2    |
| 3    | 1    | 4    | 1    |
| 1    | 1    | 3    | 5    |
| 2    | 2    | 1    | 1    |
| 1    | 2    | 2    |      |



Raggruppando i dati in una distribuzione di frequenze?

| X      | ni   |
| ------ | ---- |
| 1      | 10   |
| 2      | 8    |
| 3      | 3    |
| 4      | 1    |
| 5      | 1    |
| Totale | 23   |

Operativamente si tratta di procedere nel modo che segue:

Aggiungiamo una colonna

| X      | Ni   | XiNi |
| ------ | ---- | ---- |
| 1      | 10   | 10   |
| 2      | 8    | 16   |
| 3      | 3    | 9    |
| 4      | 1    | 4    |
| 5      | 1    | 5    |
| Totale | 23   | 44   |

Calcolare il rapporto tra l'intensità totale del carattere e la numerosità del collettivo (44/23)


$$
\mu = \frac{1*10+2*8+3*3+4*1+5*1}{23}=23
$$


Generalizzando:
$$
\mu=\frac{1}{N}\sum_{i=1}^{k}x_i*n_i  = 44/23 = 1,913
$$

<hr>

**OSSERVAZIONE:**

Le 2 formulazioni della media aritmetica:
$$
\mu = \frac{1}{N}\sum_{i=1}^{N}x_i
$$
e
$$
\mu = \frac{1}{N}\sum_{i=1}^{k}x_in_i
$$
non sono 2 formule differenti ma due modi di calcolare la media aritmetica a seconda dei dati a disposizione!

Notiamo che 

![GraficoNuoveMisure](C:\Users\franc\Desktop\Riassunti Università\Immagini\GraficoNuoveMisure.PNG)

1,91 è esattamente la media aritmetica

e quindi possiamo dedurre che 
$$
\mu = \frac{1}{N}\sum_{i=1}^{k}x_in_i = \sum_{i=1}^{k}x_if_i
$$

## L'Utilità della Mediana 

La media aritmetica risulta dal concorso di tutte le N osservazioni individuali ed è molto sensibile alla presenza di eventuali valori anomali.

Esempio:

- 9 individui hanno reddito annuo di €20,000
- 1 individuo ha reddito annuo di €150,000

$$
\mu = €33,000
$$

esso non è assolutamente un valore rappresentativo nel del ceto medio basso ne degli abbienti!

***

### La Mediana

Essa è una modalità che dipende dall'ordine delle osservazioni e non dal loro valore (quindi può essere calcolata per qualsiasi carattere ordinato).

Essa è calcolata:

- mettendo **tutti i valori in ordine non decrescente**
- **scegliendo il valore alla posizione centrale**



La mediana quindi bipartisce i dati in minori e maggiori.

<hr>

La mediana funziona diversamente a seconda del numero di elementi dello studio:	

Per N dispari la mediana occupa il posto
$$
(N+1)/2
$$
Per N pari esistono 2 posti centrali:
$$
N/2 \space \space \space e \space \space \space N/2 +1
$$


Se le modalità ad esse non coincidono, queste individuano 2 mediane.



Per Convenzione, in presenza di caratteri quantitativi vado a calcolare la media tra le 2 mediane differenti.

<hr>

### ESEMPIO DI CALCOLO DELLA MEDIANA

Distribuzione dei voti ottenuti da 7 studenti nell'esame di statistica:

| x1   | x2   | x3   | x4   | x5   | x6   | x7   |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 20   | 23   | 22   | 19   | 27   | 30   | 25   |

Andiamo quindi ad ordinare questi valori in ordine non decrescente.

| x1   | x2   | x3   | x4   | x5   | x6   | x7   |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 19   | 20   | 22   | 23   | 25   | 27   | 30   |

Dato che N=7 è dispari la **MEDIANA = 23**

<hr>

Distribuzione di 8 voti di studenti nell'esame di statistica.

| x1   | x2   | x3   | x4   | x5   | x6   | x7   | x8   |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 19   | 20   | 22   | 23   | 25   | 27   | 29   | 30   |

N = 8 quindi ci sono 2 mediane che sono 23 e 25, per convenzione **LA MEDIANA E' 24**

## RELAZIONE TRA LA MEDIANA E LA MEDIA

Quando mi trovo davanti ad una distribuzione simmetrica allora media e mediana coincidono.

Se però ci troviamo molto più realisticamente davanti ad un grafico asimmetrico, se si cercasse di bilanciare l'istogramma sulla mediana questo cadrebbe verso i lati perché sbilanciato da valori anomali.

![Bilancino](C:\Users\franc\Desktop\Riassunti Università\Immagini\Bilancino.PNG)

In generale quando la media si trova a destra della mediana l'istogramma presenta una coda destra più lunga.

In presenza di distribuzioni con code allungate si preferisce utilizzare la mediana al posto della media.

<hr>

**Come Da regola infatti**

- $$
  \mu = me \space\text{: la distribuzione è simettrica}
  $$

  > La Media e la mediana Corrispondono

- $$
  \mu > me \space\text{: Asimmetria dx o positiva}
  $$

  > Quindi la media è aumentata da valori eccezionalmente alti

- $$
  \mu < me \space\text{ :Asimmetria sx o negativa}
  $$

  > Quindi la media è ridotta da valori eccezionalmente bassi

  

## La Moda

*"La forma di sintesi più rozza che c’è"*

E’ la modalità più frequente in una serie di dati.

> Esempio **MONOMODALE** per i **Fondi pensionistici americani** 

|  Tipo di business   | numero di fondi investitori |
| :-----------------: | :-------------------------: |
|         GI          |             26              |
| IL (internazionale) |             42              |
|         MC          |             20              |
|         SC          |             37              |
|         TK          |             12              |

**La moda** risulta essere il mercato internazionale

<hr>

>Esempio **BIMODALE** fondi pensionistici Americani

|  Tipo di business   | numero di fondi investitori |
| :-----------------: | :-------------------------: |
|         GI          |             26              |
| IL (internazionale) |             42              |
|         MC          |             20              |
|         SC          |             42              |
|         TK          |             12              |

<hr>

### PROPRIETA' DELLA MODA

La **moda è una misura più stabile di media e mediana** (non si modifica quando si aggiungono valori eccezionali)

es : 3,4,7,2,3,1,8,12,1,3,5,6,9

**La moda è 3**

**La media è 4,92**

**La mediana è 4**

- Se aggiungiamo un osservazione uguale a 1000.

**La moda è 3**

**La media è 76**

**La mediana è 4.5**

Come Possiamo Osservare la **MODA** è inamovibile.



## Estensione della mediana

La mediana divide una distribuzione di frequenza le 2 porzioni di eguale frequenza

Possiamo pensare a dei parametri che dividano la distribuzione di frequenza in 4 porzioni (**quartile**) o cento porzioni(**percentili**) di egual frequenza.

![Percentili](C:\Users\franc\Desktop\Riassunti Università\Immagini\Percentili.PNG)

I percentili vanno ad  applicarsi in un grafico di normalità e serve per esempio nella  pediatria a classificare un dato di riferimento in un percentile, e quindi percepirne la posizione rispetto agli altri.

> IL SIGNIFICATO di essere classificati nel 5° percentile significa che di 100 bambini ce ne sono 95 che pesano di più.



## La media ponderata

Media esami ponderata per CFU

| Materia         | Voto | CFU  |
| --------------- | ---- | ---- |
| Statistica      | 27   | 4    |
| Economia        | 30   | 8    |
| Diritto Privato | 24   | 4    |

**Media semplice = 27**
**Media ponderata = 27.75**

Voti per crediti fratto somma dei pesi.

### Esempio 2: indice dei prezzi

**Pane:**

- prezzo anno 1  = 96
- prezzo anno 0  = 88

Indice: I0 = pp1/pp0 * 100 = 96/88 * 100 = 109.09

**Oro:**

- Prezzo anno 1 = p0 = 88
- Prezzo anno 0 = p0 = 96

Indice I0 = p01 / p0 * 100 = 88/96 * 100 = 91.66

<hr>

### Media semplice degli indici di prezzo:

$$
I = \frac{I_p + I_0}{2} = 100
$$

<hr>

### Media con diversi sistemi di pesi

$$
\mu_p = \frac{\sum_{i=1}^{N}w_ix_i}{\sum_{i=1}^{N}w_i}
$$

> L'operatore inferiore rappresenta la somma di quantità eterogenee.

Soluzione 1 = Quantità vendute

Soluzione 2 = Valore dei beni venduti

<hr>

|      | p0                               | p1   |
| ---- | -------------------------------- | ---- |
| q0   | p0q0 (Valore Passato){Laspeyres} | p1q1 |
| q1   | p0q1                             | p1q1 |

<hr>

### SISTEMA DI LASPEYRES

Come il calcolo dell'indice dei prezzi al consumo, è la sommatoria del rapporto dei prezzi.

### SISTEMA DI PAASHE

Eè sempre il calcolo del sistema di laspeyres, ma con le quantità nel periodo 1 

