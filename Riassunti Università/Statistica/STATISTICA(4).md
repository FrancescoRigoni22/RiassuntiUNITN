

# STATISTICA 4

***"Distribuzioni Bivariate"***

## Distribuzioni doppie di dati

Possiamo sempre costruire distribuzioni di frequenza bivariate contando il numero di individui che presentano simultaneamente una certa modalità delle 2 variabili.



Anche nella statistica bivariata faremo uso di:

- Tabelle
- Frafici
- Strumenti Analitici

*****

### TABELLE DI CONTINGENZA

Obiettivi dei fondi pensionistici + Avere o meno un prezzo di vendita

| Sales charge | GI   | IL   | MC   | SC   | TK   | Totale |
| ------------ | ---- | ---- | ---- | ---- | ---- | ------ |
| N            | 9    | 17   | 14   | 22   | 3    | 65     |
| Y            | 17   | 25   | 6    | 15   | 9    | 72     |
| Totale       | 26   | 42   | 20   | 37   | 12   | 137    |



> Obiettivi dei Fondi
>
> GI = Growth & Income
>
> IL = International
>
> MC = Mid-Capital
>
> SC = Small-Capital
>
> TK = Technology

> Significato simboli colonna di testata
>
> N = non quotate in borsa
>
> Y = quotata in borsa





Struttura tabellare di frequenze assolute.

La Tabella in questione si chiama tabella di contingenza:

- Sulla testata rappresenta le modalità di primo carattere
- Sulla colonna madre rappresenta le modalità del secondo carattere



Chiudono la tabella i margini:

- Margini di riga
- Margini di colonna



In questa vengono riportati i totali:

- Totali di Riga
- Totali di Colonna
- Totale Complessivo



Nel corpo della tabella ci sono le frequenze congiunte:

> 9 dei fondi pensionistici Americani non sono dotati di un prezzo di vendita E Investono sul mercato del reddito



il fatto che noi abbiamo 3 tipi di totale a disposizione consente di costruire 3 diverse distribuzioni di frequenze relative:

- Riferimento totale di riga
- Riferimento totale Marginale (collocato al margine della tabella) di colonna
- Riferimento totale complessivo

*****

### TABELLE DI FREQUENZA RELATIVE AI 3 TIPI DI TOTALE

**Tabella sul totale complessivo:**

| Sales charge       | GU   | IL   | MC   | SC   | TK   | Totale Complessivo |
| ------------------ | ---- | ---- | ---- | ---- | ---- | ------------------ |
| N                  | 6.6  | 12.4 | 10.2 | 16.1 | 2.2  | 47.4               |
| Y                  | 12.4 | 18.3 | 4.4  | 10.9 | 6.6  | 52.6               |
| Totale Complessivo | 19.0 | 30.7 | 14.6 | 27.0 | 8.8  | 100                |



**Tabella sul totale di Riga**

| Sales charge       | GU   | IL   | MC   | SC   | TK   | Totale Complessivo |
| ------------------ | ---- | ---- | ---- | ---- | ---- | ------------------ |
| N                  | 13.8 | 26.2 | 21.5 | 33.8 | 4.6  | 100                |
| Y                  | 23.6 | 34.7 | 8.3  | 20.8 | 12.5 | 100                |
| Totale Complessivo | 19.0 | 30.7 | 14.6 | 27.0 | 8.8  | 100                |



**Tabella sul totale di colonna**

| Sales charge       | GU   | IL   | MC   | SC   | TK   | Totale Complessivo |
| ------------------ | ---- | ---- | ---- | ---- | ---- | ------------------ |
| N                  | 34.6 | 40.5 | 70.0 | 59.5 | 25.0 | 47.4               |
| Y                  | 65.4 | 59.5 | 30.0 | 40.5 | 75.0 | 52.6               |
| Totale Complessivo | 100  | 100  | 100  | 100  | 100  | 100                |

*****

# La Correlazione

Immaginiamo di aver collezionato 2 caratteri quantitativi discreti.

Per Rappresentare tutte le combinazioni vado ad utilizzare un grafico cartesiano.

Scatter di punti.

![Scatter](C:\Users\franc\Desktop\Riassunti Università\Immagini\Scatter.PNG)

Studio della **correlazione**: correlazione tra due variabili quantitative discrete.

Devo creare un criterio che ci permetta di individuare la migliore di queste rette.

*****

## Teoria del sangue blu

Il Talento ed il carattere sono ereditari

In questo contesto nasce l'analisi della regressione lineare.

La statura dei figli può essere prevista sulla base di quella dei genitori?

**Se è così, l'altezza è ereditaria**.

Smentisce lo studio sull'ereditarietà del talento lo studio verso le altezze

*****

![ScatterSangueBlu](C:\Users\franc\Desktop\Riassunti Università\Immagini\ScatterSangueBlu.PNG)

Genitori Bassi generano figli più alti di loro.

Genitori alti a volte generano figli mediamente più bassi di loro.

Il mondo regredisce verso la mediocrità.

*****

## PEARSON e SCATTER PLOT

Pearson raccolse le altezze di 1078 padri e dei loro figli in età matura

![ScatterPalloneRugby](C:\Users\franc\Desktop\Riassunti Università\Immagini\ScatterPalloneRugby.PNG)

Più sarà appiattito ai lati il pallone e migliore sarà la sintesi costituita dalla retta che saremo in grado di stimare.

Altre forme di scatter non sono a disposizione dello studio della correlazione lineare.



Quando esiste una forte associazione fra X e Y conoscere il valore di una di esse aiuta a prevedere il corrispondente dell'altra.

La dispersione attorno alla retta indica la debolezza della relazione tra X e Y.



***"Come sintetizzare numericamente questa situazione?"***

***

#### Baricentro

il punto che ha per coordinate la media del carattere x e del carattere y.

> A uno stesso baricentro corrispondono infiniti scatterplot

Coppia di valori medi per i caratteri x e y

 ![Baricentro](C:\Users\franc\Desktop\Riassunti Università\Immagini\Baricentro.PNG)

***

#### DISPERSIONE NELLE 2 DIREZIONI

Aggiungiamo alla coppia di punti medi anche la coppia di scarti quadratici medi in x e in y.

![DispersioneDirezioni](C:\Users\franc\Desktop\Riassunti Università\Immagini\DispersioneDirezioni.PNG)

***

Le sintesi 
$$
\mu_X , \sigma_X \\ \mu_Y,\sigma_Y
$$
***"Sono il centro della nuvole e la sua dispersione in orizzontale e in verticale, questi non dicono niente sull'intensità del legame"***

2 scatter possono avere lo stesso centro e dispersioni ma mostrare un diverso grado di addensamento rispetto ad una retta.

![ScatterUgualiMaDiversi](C:\Users\franc\Desktop\Riassunti Università\Immagini\ScatterUgualiMaDiversi.PNG)

***

### COEFFICIENTE DI CORRELAZIONE LINEARE R

E' lo strumento per misurare l'intensità del legame lineare
$$
r \in [-1,1]
$$
![R1](C:\Users\franc\Desktop\Riassunti Università\Immagini\R1.PNG)

![R2](C:\Users\franc\Desktop\Riassunti Università\Immagini\R2.PNG)



#### CALCOLO DI R (RIFERIMENTO A COVARIANZA)

$$
r = \frac{\sigma_{XY}}{\sigma_X\sigma_Y}
$$

dove l'operatore al numeratore, ovvero la **Covarianza**
$$
\sigma_{XY} = \frac{\sum_i(x_i - \mu_X)(y_i - \mu_Y)}{N}
$$
Inoltre la covarianza va contenuta in un intervallo:
$$
\sigma_{XY} \in (-\infty;+\infty)
$$
A seconda del suo valore possiamo rilevare un diverso tipo di relazione:

- $\sigma_XY = 0$ assenza di relazione lineare
- $\sigma_{XY} > 0$ relazione diretta
- $\sigma_{XY} < 0$ relazione inversa



Si dimostra che:
$$
-\sigma_x\sigma_Y \leq \sigma_{XY} \leq +\sigma_X\sigma_Y
$$


Normalizzando quindi:
$$
-1\leq\frac{\sigma_{XY}}{\sigma_x\sigma_Y} = r\leq1
$$
R infatti misura **l'associazione tra X e Y**.

A numeratore di r c'è una media di prodotti:

$(x_i - \mu_x)(y_i-\mu_Y)$



- Se predominano i prodotti + allora r  > 0

![Prodottipiu](C:\Users\franc\Desktop\Riassunti Università\Immagini\Prodottipiu.PNG)

- Se predominano i prodotti - allora r < 0

![Prodottimeno](C:\Users\franc\Desktop\Riassunti Università\Immagini\Prodottimeno.PNG)

---

### Esempio del Calcolo dell'Indice di Correlazione

Per esempio prendiamo una tabella di dati con una distribuzione bivariata.

![tabellabivariatafrequenze](C:\Users\franc\Desktop\Riassunti Università\Immagini\tabellabivariatafrequenze.PNG)


$$
\mu_X = 4; \space \mu_Y = 7 \\
\sigma^2_X = \frac{\sum_ix_i^2}{N}-\mu_x^2 = 4
\\
\sigma^2_Y = \frac{\sum_iy_i^2}{N}-\mu_y^2 = 16
$$
Quindi unendo le 2 dispersioni:
$$
\sigma_{XY} = \frac{\sum_i(x_i - \mu_X)(y_i - \mu_Y)}{N} = \frac{16}{5} = 3.2
$$

$$
r = \frac{\sigma_{XY}}{\sigma_x\sigma_y} = \frac{3.2}{2*4} = 0.4
$$

Di conseguenza R misura la tendenza dei dati a raggrupparsi non in termini assoluti ma relativi!
$$
r = \frac{1}{N}\sum_i(\frac{x_i-\mu_X}{\sigma_X})(\frac{y_i - \mu_Y}{\sigma_Y})
$$
r è un numero puro

Il valore assoluto di r è invariante per trasformazioni lineari di X e di Y (a+bX; c+dY , a, b, c, d $\in R$) 
$$
r_{XY} = r_{YX}
$$


***

### UTILITA' COEFFICIENTE DI CORRELAZIONE LINEARE

r è una misura molto utile in tutti i casi in cui lo scatter abbia una forma ovale:

![FORMAOVALESCATTER](C:\Users\franc\Desktop\Riassunti Università\Immagini\FORMAOVALESCATTER.PNG)

A volte r può essere una misura fuorviante e non opportuna:

- quando ci sono outlier
- quando c'è una relazione non lineare

**A quel punto non è un coefficiente di correlazione lineare**

***

#### PARADOSSO DI ASCOMBE

![ParadossoDiAscombe](C:\Users\franc\Desktop\Riassunti Università\Immagini\ParadossoDiAscombe.PNG)

Escludo tutti tranne il primo perché y non è correlato a x, quindi non è una distribuzione a ovale obliquo

***

### Correlazione tra medie o percentuali

**I dati di Doll (1955)**

| Paese         | Consumo di Sigarette | Tasso di mortalità (# morti su un milione) |
| ------------- | -------------------- | ------------------------------------------ |
| Australia     | 480                  | 180                                        |
| Canada        | 500                  | 150                                        |
| Danimarca     | 380                  | 170                                        |
| Finlandia     | 1100                 | 350                                        |
| Gran Bretagna | 1100                 | 460                                        |
| Islanda       | 230                  | 60                                         |
| Paesi Bassi   | 490                  | 240                                        |
| Norvegia      | 250                  | 90                                         |
| Svezia        | 300                  | 110                                        |
| Svizzera      | 510                  | 250                                        |
| Stati Uniti   | 1300                 | 200                                        |

Si riferivano al Consumo pro capite nel 1930 e i tassi di mortalità registrati nel 1950.

![DatiDollaFumo](C:\Users\franc\Desktop\Riassunti Università\Immagini\DatiDollaFumo.PNG)

Il Coefficiente di correlazione lineare era r = 0.7



R determinato a partire da percentuali o medie può essere fuorviante.

Esempio:

- Correlazione tra reddito e livello di istruzione per i residenti in Italia con età tra 25-54 anni, r;
- Reddito medio e livello di istruzione medio per ogni regione e poi coefficiente di correlazione tra le coppie di medie regionali r' > r

Perché?

Perché in ogni regione c'è una notevole variabilità attorno alla media...

...dispersione che eliminiamo associando ad ogni regione le sua media!

***

### Correlazione e casualità

Bambini:

il numero di scarpe  sembra essere correlato alla capacità di dizione. **C'è una forte correlazione**

Esiste un fattore di disturbo: l'età!



Quando un bambino cresce:

- impara più parole
- ha una crescita nei piedi



IL Coefficiente di correlazione lineare non protegge dai fattori di disturbo

R misura la forza e il verso della relazione lineare tra X e Y questo è diverso da un nesso di casualità.

Dunque in questo caso abbiamo **UNA CORRELAZIONE SPURIA**.