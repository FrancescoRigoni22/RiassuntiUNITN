# STATISTICA



La **STATISTICA** è l'arte e la scienza del disegno di studi e dell'analisi dei dati che tali studi producono.

L'Obiettivo della statistica è quello di tradurre il mondo che ci circonda in dati e conoscenza. Più brevemente acquisire la conoscenza quantitativa dei fenomeni collettivi.



**STATISTICA DESCRITTIVA**: Analisi Statistica eseguita su tutta la popolazione

**STATISTICA INFERENZIALE**: Eseguita attraverso l'analisi di campioni di popolazione.

- La scelta del campione è casuale
- L'indagine campionaria dà risultati validi per la popolazione

> ESEMPIO DI STATISTICA INFERENZIALE CHE INTERAGISCE CON LA STATISTICA DESCRITTIVA
>
> Sondaggio su 834 residenti in Florida fa risultare un 54% della popolazione favorevole all'aumento dei controlli sulle armi.
>
> Il numero si avvicina alla percentuale della popolazione con un errore calcolato di 3,4%
>
> E' Sicuro quindi al 95% che tra il 50,6% e il 57,4% della popolazione sia favorevole all'aumento dei controlli sulle armi

**MOTIVAZIONI PER ESTRARRE UN CAMPIONE**

- Costi Minori
- Tempi Minori
- Facilità di Gestione
- Accuratezza



## IL PROCESSO DI RILEVAZIONE

*"E' il complesso delle operazioni che hanno lo scopo di acquisire informazioni, come risposte o misurazioni, su un insieme di elementi oggetto di studio."*

La **RILEVAZIONE SI SUDDIVIDE IN 2 TIPOLOGIE**:

- Rilevazione di tipo Completo
- Rilevazione di tipo Parziale 



**FASI DELLA RILEVAZIONE**:

- Elaborazione dei Dati
- Presentazione dei Risultati

> Esempio, Censimento della popolazione Italiana prendendo particolarmente in esame il reddito medio del capofamiglia

 

Questo esempio ci porta in uno spezzettamento delle definizioni insite nel processo di rilevazione:

- **Popolazione/Campione**: insieme di elementi reali/virtuali oggetto di analisi statistica

  > Popolazione reale: Studenti dell'università di Trento
  >
  > Popolazione virtuale: Numeri del superenalotto

- **Unità Statistica**: Elemento di osservazione di base della popolazione oggetto di indagine  statistica

  >Unità Statistica: Lo studente dell'università, il numero 23

- **Unità di Rilevazione**: L'elemento di osservazione base della rilevazione e spesso non coincide con l'unità statistica

  > Unità di Rilevazione: La famiglia alla quale viene somministrato il questionario per il censimento

- **Carattere**: Caratteristica oggetto di studio misurata sulle unità statistiche

  - **Quantitativo**: un Attributo **non misurabile**
    - Discreto: Il Numero di Figli
    - Continuo: L'altezza
  - Qualitativo: un Attributo **Misurabile**
    - Ordinale: Il Livello di istruzione
    - Sconnesso: il sesso

- **Modalità**: modo di presentarsi del carattere nelle unità statistiche.

  > Il Colore dei Capelli è Nero

  

  <hr>

  La popolazione è costituita da N unità statistiche.
  $$
  P = (u1,u2,u3,u4,...,u_n)
  $$
  Sulla quale è rilevato il carattere
  $$
  X = (x1,x2,x3,x4,...,x_n)
  $$
  

  <hr>

### La DISTRIBUZIONE di Frequenza

$$
X = (x1,x2,x3,x4,...,x_n)
$$
costituisce una distribuzione unitaria {per dati grezzi} della popolazione P secondo il carattere X.

Xi è la modalità con cui il carattere X si presenta nell'unità statistica.

La **DISTRIBUZIONE UNITARIA** (Tabella individui/modalità) assegna a ciascun soggetto la corrispondente modalità.

![GraficoDistribuzioneFrequenza](C:\Users\franc\Desktop\Riassunti Università\Immagini\GraficoDistribuzioneFrequenza.PNG)

<hr>

Di Fatto dovrò andare a prendere le scale nominali espresse sotto forma di tabella

| **U** | **SESSO** | COLORE OCCHI |
| ----- | --------- | ------------ |
| 1     | M         | Neri         |
| 2     | F         | Marroni      |
| 3     | M         | Marroni      |
| 4     | F         | Marroni      |
| 5     | F         | Azzurri      |
| 6     | F         | Verdi        |
| 7     | F         | Azzurri      |
| 8     | M         | Azzurri      |
| 9     | M         | Neri         |
| 10    | M         | Marroni      |
| 11    | M         | Verdi        |
| 12    | F         | Azzurri      |

 Andrò a trasformare questa tabella in una Distribuzione di Frequenza e quindi a riassumere in.

| SESSO  | Ni   | Pi   |
| ------ | ---- | ---- |
| M      | 6    | 50   |
| F      | 6    | 50   |
| Totale | 12   | 100  |



## RAPPRESENTAZIONE DELLA DISTRIBUZIONE DELLE FREQUENZE 

Per la definizione di frequenze la rappresentazione dei dati può essere fatta attraverso 2 modalità:

### DIAGRAMMA A TORTA

A ciascuna modalità si associa un rettangolo avente base costante ed altezza proporzionale alle frequenze

![DiagrammaaTorta](C:\Users\franc\Desktop\Riassunti Università\Immagini\DiagrammaaTorta.PNG)

### DIAGRAMMA A BARRE

A Ciascuna modalità del carattere si associa un settore circolare avente area proporzionale alle frequenze

![DiagrammaaBarre](C:\Users\franc\Desktop\Riassunti Università\Immagini\DiagrammaaBarre.PNG)

## Riepilogo

Un carattere costituisce una **SCALA NOMINALE** se le modalità non possono essere ordinate secondo alcun criterio ed p possibile affermare solo se le modalità sono = 0 o != da 0

Un carattere costituisce una **SCALA ORDINALE** se è possibile ordinare in modo univoco le sue modalità.

<hr>

## Caratteri quantitativi Discreti

N = 32 Studenti, vado a studiare il carattere votazioni 

Vado quindi a studiare i dati grezzi sintetizzati in una distribuzione di frequenza

| Voto   | Frequenze assolute | Frequenze percentuali |
| ------ | ------------------ | --------------------- |
| 18     | 4                  | 12.50                 |
| 19     | 6                  | 18.75                 |
| 20     | 5                  | 15.63                 |
| 21     | 8                  | 25.00                 |
| 22     | 9                  | 28.13                 |
| Totale | 32                 | 100                   |



![DiagrammaaAste](C:\Users\franc\Desktop\Riassunti Università\Immagini\DiagrammaaAste.PNG)

<hr>

## Caratteri Quantitativi Continui

Un dato quantitativo continuo assume un valore di un intervallo[a,b].

Posso suddividere il detto intervallo in più sotto-intervalli (con uguale o diversa ampiezza)

![LivellidiA](C:\Users\franc\Desktop\Riassunti Università\Immagini\LivellidiA.PNG)

Vado quindi ad associare ogni unità al sotto-intervallo in cui cade la modalità in essa rilevata. In questo caso si parla di **distribuzione in classi**

<hr>

Esempio della raccolta di dati sui pesi di 15 persone.

| Peso   | Ni   | Fi   | Pi    |
| ------ | ---- | ---- | ----- |
| 62-64  | 3    | 0,20 | 20,00 |
| 64-68  | 6    | 0,40 | 40,00 |
| 68-73  | 5    | 0,33 | 33,33 |
| 73-75  | 1    | 0,07 | 6,67  |
| Totale | 15   | 1,00 | 100   |

## Rappresentazione di Caratteri quantitativi Continui

Si utilizza un **Istogramma di frequenza** esso fa corrispondere alle classi del carattere quantitativo (poste sulle ascisse) un rettangolo i area pari alla frequenza delle unità statistiche di quella classe.

L'altezza del rettangolo è pari alla **densità di frequenza**
$$
h_i = \frac{n_i}{n_i-x_{i-1}}
$$
Dove **ni** è la **frequenza assoluta** della classe e (xi - x{i-1}) è l'**ampiezza** della classe.

<hr>

**Come decidiamo ampiezza e numero di classi nell'analisi di variabili quantitative continue?**

Le classi devono essere preferibilmente eguali e devono appartenere all'intervallo 
$$
5 <= \text#classi <= 15
$$

$$
\text Ampiezza = \frac{R}{\text{#desiderato classi}}
$$



## Serie Storiche

Sono una Serie di dati nei quali gli individui sono rappresentati da istanti di tempo. Ovvero c'è un unico soggetto con tanti istanti di tempo.

> Esempi possono essere
>
> - Il prodotto lordo di un paese per ogni anno
> - L'indice dei prezzi al Consumo
> - Il fatturato trimestrale di un impresa