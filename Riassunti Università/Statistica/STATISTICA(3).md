STATISTICA (3)



## VARIABILITA'

Una media che può assumere lo stesso valore in 2 distribuzioni che hanno diverse modalità

Entrambe le distribuzioni hanno media 4, in una delle 2 la media è più forte OVVERO la seconda, perché con un parametro solo possiamo comprendere l'intera distribuzione.

**INFATTI** esiste la dispersione dei confronti dei caratteri analizzati.

<hr>

### LO STESSO VALE PER QUESTE DISTRIBUZIONI DI FREQUENZA

Nel Secondo grafico la media è rappresentativa perché i grafici sono distribuzioni di frequenza.

| xi   | ni   |
| ---- | ---- |
| 1    | 40   |
| 2    | 40   |
| 3    | 40   |
| 4    | 40   |
| 5    | 40   |

| xi   | ni   |
| ---- | ---- |
| 1    | 10   |
| 2    | 16   |
| 3    | 148  |
| 4    | 16   |
| 5    | 10   |



> La Variabilità si concentra sulla dispersione dei dati da una misura standard, nella maggior parte dei costrutti statistici esiste la variabilità

<hr>

## DEFINIZIONE DI VARIABILITA'

Si chiama **variabilità** l'attitudine dei caratteri ad assumere modalità differenti.

La variabile può essere misurata.

> ALL'ESAME LA VARIANZA NON E' NEGATIVA

Una misura di variabilità:

- Deve **annullarsi se e solo se tutte le unità presentano la stessa modalità**

- Deve **assumere valori crescenti all'aumentare dalla variabilità**.

<hr>

> PLATONE dice che la varianza tra gli elementi è tanto in elementi che si vanno a presentare poco, invece è poca in elementi che si presentano spesso.

Si constata che i caratteri tendono a differire tra i singoli secondo una legge.

<hr>

24 secoli dopo Quetelet trasformerà una formula matematica.

Troverà infatti sorprendenti a**nalogie formali tra variabilità di alcuni caratteri antropometrici, classificati in distribuzioni di frequenze, e il modello di Gauss**.

Nel 1844 Va dal medico militare e dà un occhiata ai dati medici militari e trova una comparazione in termini di comparazione tra frequenza e variabilità

<hr>

# Misure di variabilità

- **Range (Rozza e inutilizzata)**
- **Range Interquartilico (Rozza e inutilizzata)**
- **Varianza**
- **Deviazione Standard**
- **Coefficiente di variazione**

<hr>

### RANGE

Differenza tra intensità Massima e minima rilevata
$$
R = x_{max} - x_{min}
$$

> ESEMPIO: fondi a basso rischio americani; ordinare e calcolare R

![RENDIMENTIBASSORISCHIO](C:\Users\franc\Desktop\Riassunti Università\Immagini\RENDIMENTIBASSORISCHIO.PNG)

- NON è conveniente utilizzarlo perchè con dati estremi andiamo a prenderli entrambi.

- NON è conveniente utilizzarlo perché andiamo a calcolare il range in base a 2 unici valori

## RANGE INTERQUARTILICO (IQR) // DIFFERENZA INTERQUARTILE

$$
Q3 - Q1
$$

E' il range entro il quale cadono il 50% dei casi "normali" (vicini alla tendenza centrale)

E' Più robusta del RANGE.

## LA VARIANZA

Ci interessa di più un **indicatore che misuri la dispersione delle xi attorno ad un valore medio**.

Misuro la distanza di ogni osservazione da 
$$
\mu
$$

$$
(x_i - \mu)^2
$$

$$
---(x_i)-------\mu---->
$$

Mediando, cioè calcolando la media dei quadrati degli scarti della media aritmetica:
$$
\sigma^2 = \frac{1}{N}\sum_{i=1}^{N}(x_i - \mu)^2
$$
LA **VARIANZA** di una distribuzione



E' un indice assoluto ed è espresso nella unità di misura al quadrato del fenomeno.

<hr>

### SCOSTAMENTO QUADRATICO MEDIO

Lo scostamento quadratico dalla media è pesante perché elevato alla seconda.
$$
0 <= \sigma < +\infin
$$
Estraendo la radice quadrata, si ottiene lo scarto quadratico medio (**deviazione standard**)
$$
\sigma = \sqrt{\sigma^2} = \sqrt{\frac{1}{N}\sum_{i=1}^{N}(x_i - \mu)^2}
$$

<hr>

ESEMPIO NUMERICO: Precipitazione in mm a Roma (stazione Roma-Urbe)

Distribuzione per dati grezzi per carattere continuo.

| Anno | Precipitazioni |
| ---- | -------------- |
| 1981 | 608.6          |
| 1982 | 694.0          |
| 1983 | 726.4          |
| 1984 | 1128.6         |
| 1985 | 760.9          |
| 1986 | 887.6          |
| 1987 | 904.6          |

<hr>

Successivamente si va a calcolare lo scarto quadratico medio.

![TABELLASCARTOQUADRATICO](C:\Users\franc\Desktop\Riassunti Università\Immagini\TABELLASCARTOQUADRATICO.PNG)

<hr>

$$
\mu = \frac{\sum_{i=1}^{N}x_i}{N} = \frac{5710.7}{7} = 815.8 mm
$$

$$
\sigma = \sqrt{\frac{179658}{7}} = 160.2mm
$$



Mediamente, nei sette anni considerati, e le precipitazioni differiscono dalla precipitazione media annua di 160.2mm.

<hr>
## Un altra formula per il calcolo della varianza

Nella Pratica il calcolo della varianza si effettua spesso con la seguente formula:


$$
\sigma^2 = \frac{\sum_{i=1}^{N}x_i^2}{N} - \mu^2
$$


Esempio Pratico:

x1 = 6

x2 = 2

x3 = 7

x4 = 17
$$
\mu = \frac{6+2+7+17}{4} = \frac{32}{4} = 8
$$


quindi utilizzando la formula

> $$
> \sigma = \sqrt{\frac{\sum_{i=1}^{N}(xi-\mu^2)}{N}}
> $$


$$
\sqrt{\frac{(6-8)^2+(2-8)^2 + (7-8)^2+(17-8)^2}{4}}
$$
Effettuando tutti i calcoli alla fine la varianza risulterà essere 5.52

*****

Utilizzando invece il calcolo con lo scostamento della media
$$
\sigma = \sqrt{\frac{\sum_{i=1}^{N}(xi)}{N}-\mu^2}
$$

$$
\sqrt{\frac{6^2+7^2+2^2+17^2}{4}-8^2}
$$

Anche questa formula mi darà sempre lo stesso risultato = 5.52

*****

## Varianza di una trasformazione lineare

Data la distribuzione:

x1,x2,....,xN: 
$$
\mu_X \space \sigma^2_X
$$
Successivamente sappiamo che i valori di y sono legati ai valori di x attraverso un rapporto lineare:
$$
y_i = a + bx_i
$$
Allora, se y ha una distribuzione del genere:
$$
y_1,y_2,...,y_n.\space \mu_y = a+b\mu_x
$$
La varianza di Y sarà quindi:
$$
\sigma_Y^2 = b^2 * \sigma_X^2
$$

*****

### TRASFORMAZIONE LINEARE 

![GraficiOutlineati](C:\Users\franc\Desktop\Riassunti Università\Immagini\GraficiOutlineati.PNG)

Traslazione: Y = a + X

*****

### CAMBIO DI UNITA' DI MISURA

![CambioUnitaMisura](C:\Users\franc\Desktop\Riassunti Università\Immagini\CambioUnitaMisura.PNG)

> Ad esempio il cambio di valute 

Se b in valore assoluto è minore di 1 l'istogramma si appuntisce e si stringe attorno al valore medio.

*****

## Se i Dati sono raccolti in una distribuzione di frequenze?

Prendiamo la distribuzione del numero di figli nelle 23 famiglie di Roma.

| X      | ni   | xi^2 | xi^2 * ni |
| ------ | ---- | ---- | --------- |
| 1      | 10   | 1    | 10        |
| 2      | 8    | 4    | 32        |
| 3      | 3    | 9    | 27        |
| 4      | 1    | 16   | 16        |
| 5      | 1    | 25   | 25        |
| Totale | 23   |      | 110       |

La media aritmetica era pari a 1.913



La varianza calcolata con la formula alternativa è:
$$
\sigma^2 = \frac{1}{N}(\sum_{i=1}^{k}x_i^2n_i)- \mu^2 \\= \frac{1}{23} * 110 - 1.913^2 \\= 4.78 - 3.66 = 1.22\\ \\
$$
E quindi, estraendo la radice:
$$
\sigma = \sqrt{1.12} = 1.06
$$

> Considerando quindi, sia la media che la varianza:
>
> Andiamo a vedere che la media è 1.913, la varianza è 1.06, nell'intervallo 1-3 sembrano esserci quindi la maggior parte dei dati, di fatto è proprio così

*****

## UNA MISURA RELATIVA DI VARIABILITA'

Se devo eseguire confronti tra fenomeni espressi con diverse unità di misura o sull'evoluzione di uno stesso fenomeno rilevato in due unità temporali o spaziali diverse.

**OSTACOLI AL CONFRONTO:**

- Le unità di Misura 

- Se anche i fenomeni sono espressi secondo la stessa unità di misura non sono relativi alle stesse intensità medie

> Es: presa del peso dei bambini e degli adulti



Peso kg

Adulti:
$$
\mu = 75kg
\\ \sigma = 4kg
$$
Neonati
$$
\mu = 4kg
\\\sigma = 0.6kg
$$

*****

**INDICI DI VARIABILITA' RELATIVI**

- Indici di variabilità relativi ad una media
- Indici di variabilità relativi al loro massimo



**Coefficiente di variazione**
$$
\frac{\sigma}{\mu} = CV
$$
Il risultato è un numero puro, senza unità di misura.
$$
\frac{4}{75} = 0.053 << \frac{0.6}{4} = 0.15\\
\text{||                        || }\space\space
\\\text{adulti          bambini} 
$$
CV è "scale free" o "numero puro" , esso (non dipende dall'unità di misura adottata). Come tale è adatto ai confronti.

*****

# BOX PLOT

Rappresentazione grafica basata sui 5 numeri EDA

(Exploratory- Data- Analysis)

GLi EDA SONO:

- $$
  x_{min}
  $$

- $$
  Q_1
  $$

- $$
  m_e
  $$

- $$
  Q_3
  $$

- $$
  x_{max}
  $$

  

I quali sono riportati sullo stesso grafico

![BoxPlot1](C:\Users\franc\Desktop\Riassunti Università\Immagini\BoxPlot1.PNG)

![BoxPlot2](C:\Users\franc\Desktop\Riassunti Università\Immagini\BoxPlot2.PNG)

*****

- **Dati Simmetrici**:
  $$
  m_e - x_{min} \approx x_{max} - m_e
  \\ Q_1 - x_{min} \approx x_{max} - Q_3
  $$

- **Dati con asimmetria dx (o positiva)**: 
  $$
  m_{max} - m_e > m_e - x_{min}
  \\ x_{max} - Q_3 > Q_1 - x_{min}
  $$

- **Dati con asimmetria sx (o negativa):**
  $$
  m_{max} - m_e < m_e - x_{min}
  \\ x_{max} - Q_3 < Q_1 - x_{min}
  $$

*****

### VARIABILI EDA CON FONDI PENSIONE AMERICANI

| xmin | Q1    | me    | Q3    | xmax  |
| ---- | ----- | ----- | ----- | ----- |
| 9.77 | 13.80 | 18.42 | 21.49 | 38.16 |


$$
x_{max} - m_e = 38.16 - 18.42 = 19.74
\\ m_e - x_{min} = 18.42 - 9.77 = 8.65
\\ 19.74 >> 8.65
$$
Sulle code invece, e quindi considerando gli intervalli dei quartili:
$$
x_{max} - Q_3 = 38.16 - 21.49 = 16.67
\\ Q1 - x_{min} = 13.80 - 9.77 = 4.03
\\ 16.67 >> 4.03
$$
Asimmetria dx !

*****

## Il Box plot come diagnostico per outlier

Salario mensile per un campione di 12 laureati in facoltà di economia aziendale.

![BoxPLotOutlier](C:\Users\franc\Desktop\Riassunti Università\Immagini\BoxPLotOutlier.PNG)



- Si disegna un Box in cui gli estremi sono posizionati sul Q1 e Q3. Per i Dati sui salari

  > Q1 = 3465
  >
  > Q3 = 3600
  >
  > Il Box contiene il 50% delle osservazioni

- All'interno del box, si disegna un segmento verticale in corrispondenza della posizione della mediana

  > me = 3505

- Utilizzando il range interquartilico:

  > IQR = Q3 - Q1

  Si dispongono i limiti. i limiti del box plot sono:

  > 1.5(IQR) sotto Q1
  >
  > 1.5(IQR) sopra Q3

- LE Linee tratteggiate sono chiamate whisker. I whisker son odisegnati a partire dagli estremi del box fino ai valori più grande e più piccolo, dentro i limiti calcolati al passo 3. 

  > Perciò i whisker terminano ai valori dei salari
  >
  > 3310
  >
  > 3730

- INfine la posizione di ciascun outlier è mostrata con il simbolo *. Nella Figura vediamo un outlier, 3925

*****

**ANDANDO A RAPPRESENTARE IL TUTTO GRAFICAMENTE**

![BoxPlotRegolaarte](C:\Users\franc\Desktop\Riassunti Università\Immagini\BoxPlotRegolaarte.PNG)

*****

Ancora sulla forma di una distribuzione (solo variabili quantitative)

- **Forma di una distribuzione**
  - Esame visivo della forma dell'istogramma
  - Calcolo di alcune misure
    - Misure di asimmetria
    - Misure di curtosi

*****

### Ancora sulla forma di una distribuzione

Il maggiore  o minore "appuntimento" e il peso più o meno accentuato delle code rispetto alla parte centrale della distribuzione

**CURTOSI**

*****

$$
\beta > 3
$$

Per Distribuzioni **ipernormali** o **leptocurtiche** (più alte al centro e nelle code -> code più pesanti)
$$
\beta < 3
$$
Per distribuzioni **iponormali** o **platicurtiche** (più basse al centro e nelle code -> code meno pesanti)



![ipernormali](C:\Users\franc\Desktop\Riassunti Università\Immagini\ipernormali.PNG)