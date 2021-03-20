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

## Karl Pearson, allievo di Galson

Pearson raccolse le altezze di 1078 padri e dei loro figli in età matura

![ScatterPalloneRugby](C:\Users\franc\Desktop\Riassunti Università\Immagini\ScatterPalloneRugby.PNG)

Più sarà appiattito ai lati il pallone e migliore sarà la sintesi costituita dalla retta che saremo in grado di stimare.

Altre forme di scatter non sono a disposizione dello studio della correlazione lineare.



Quando esiste una forte associazione fra X e Y conoscere il valore di una di esse aiuta a prevedere il corrispondente dell'altra.

La dispersione attorno alla retta indica la debolezza della relazione tra X e Y.



***"Come sintetizzare numericamente questa situazione?"***

 