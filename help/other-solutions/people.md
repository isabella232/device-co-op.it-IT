---
description: La metrica Persone è il numero di persone (o gruppi di dispositivi) in base a Device Graph di Adobe. Puoi applicare la metrica Persone per identificare i visitatori sui loro dispositivi in Analysis Workspace.
seo-description: La metrica Persone è il numero di persone (o gruppi di dispositivi) in base a Device Graph di Adobe. Puoi applicare la metrica Persone per identificare i visitatori sui loro dispositivi in Analysis Workspace.
seo-title: Metrica Persone
title: Metrica Persone
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Metrica Persone{#people-metric}

La metrica Persone è il numero di persone (o gruppi di dispositivi) in base a Device Graph di Adobe. Puoi applicare la metrica Persone per identificare i visitatori sui loro dispositivi in Analysis Workspace.

## People Metric Prerequisites and Considerations {#section-34551d0435fb4b3cb3fad736b7961541}

<table id="table_120F7EF50042485391E58B22DD00A2A8"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Prerequisito o considerazione </th> 
   <th colname="col2" class="entry"> Descrizione </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Device Co-op </p> </td> 
   <td colname="col2"> <p> To use the People metric, become a member of the <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Adobe Experience Cloud Device Co-op</a>. La cooperativa identifica i diversi dispositivi (o ID Experience Cloud) di una persona. Analytics sfrutta queste informazioni per derivare statisticamente il numero di persone che interagiscono con un brand. La metrica è accurata entro il 5%. </p> <p><b>Zone</b>: Device Co-op è attualmente disponibile solo negli Stati Uniti e in Canada. Pertanto, durante la valutazione della metrica Persone, è necessario applicare un segmento all'analisi che filtra i dati solo per Stati Uniti e Canada. </p> <p>Ogni settimana, Device Graph calcola una nuova versione della cooperativa e la pubblica per l'uso. Il martedì, il sistema raccoglie i dati più recenti e pubblica una versione aggiornata del grafico. Le soluzioni Experience Cloud utilizzano quindi la versione più recente del grafico. In modo specifico per Analytics, le modifiche vengono lette il mercoledì e l'elaborazione delle modifiche richiede in genere tra 1 e 2 giorni lavorativi. </p> <p> <p>Importante:  Quando il grafico viene aggiornato su base settimanale, può avere un impatto storico sulla metrica Persone. In altre parole, i conteggi storici delle persone possono cambiare nel tempo man mano che il grafico viene appreso e aggiornato. Ad esempio, se esegui un rapporto oggi che conta le persone il mese scorso e quindi esegui lo stesso rapporto in una settimana dopo l'aggiornamento del grafico, il conteggio delle persone storiche potrebbe subire delle variazioni lievi. </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Autorizzazioni metriche </td> 
   <td colname="col2"> <p>Puoi utilizzare la metrica Persone solo se ti è stato concesso l’accesso. Gli amministratori possono<a href="https://marketing.adobe.com/resources/help/en_US/reference/groups-metrics.html" format="html" scope="external"> personalizzare le autorizzazioni</a> relative alle metriche in Strumenti di amministrazione. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Mapping all'organizzazione IMS </td> 
   <td colname="col2"> <p>La metrica Persone sarà abilitata per tutte le suite di rapporti che sono <a href="https://marketing.adobe.com/resources/help/en_US/mcloud/map-report-suite.html" format="html" scope="external"> mappate a un IMSORG</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Progetti/Strumenti di analisi </p> </td> 
   <td colname="col2"> <p>Utilizzare la metrica Persone in <span class="wintitle">Analysis Workspace</span>, <span class="wintitle">Analisi ad hoc</span>, <span class="wintitle">Generatore di report</span> e tramite l'API. La puoi usare ovunque potresti usare la metrica Visitatori unici, anche nelle metriche calcolate. </p> <p>Ad esempio, crea una metrica “ricavo per persona” al posto di una metrica “ricavo per visitatore unico”. </p> <p>Un <a href="https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/starter_projects.html" format="html" scope="external">modello di progetto Persone</a> è disponibile per iniziare a utilizzare la metrica Persone in Analysis Workspace. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Attivare le regole bot </p> </td> 
   <td colname="col2"> <p>Adobe consiglia di attivare le <a href="https://marketing.adobe.com/resources/help/en_US/reference/bot_rules.html" format="html" scope="external">Regole bot</a>, soprattutto quando si utilizza la metrica Persone. </p> <p>Quando un bot si intrufola nel sito Web, aumenta artificialmente il numero di Visitatore unico. La rimozione del traffico bot dalla suite per report offre una misurazione più precisa dell'attività sulle proprietà digitali, in termini di Visitatori unici e di Persone. </p> <p>Per farlo, accedi a <span class="uicontrol">Analytics</span> &gt; <span class="uicontrol">Amministratore</span> &gt; <span class="uicontrol">Suite per report</span>. Seleziona la suite per report corretta e accedi a <span class="uicontrol">Modifica impostazioni</span> &gt; <span class="uicontrol">Generale</span> &gt; <span class="uicontrol">Regole bot</span>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Considerazioni sulla segmentazione </p> </td> 
   <td colname="col2"> <p> Quando utilizzi i segmenti con la metrica Persone, il reporting della metrica potrebbe essere notevolmente inferiore a quanto previsto. </p> <p>Consulta <a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local">Uso della metrica Persone con i segmenti</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Cos&#39;è la metrica Persone? {#section-89e2b8f5e80f480391449fc8d1117a6a}

La metrica Persone è una metrica di reporting di Analytics che aiuta ad attribuire i dispositivi alle persone. Fornisce una visualizzazione del marketing basata sulle persone, consentendo la misurazione dell&#39;attività dei visitatori su tutti i loro dispositivi. Può essere considerata una versione deduplicata di Visitatori univoci e puoi utilizzare la metrica Persone per l&#39;analisi dove prima utilizzavi Visitatori univoci.

**I dispositivi sono le persone**

Prima che la metrica Persone fosse disponibile, una persona (ad esempio) poteva visitare il tuo sito, visualizzare una campagna o un marchio su tre dispositivi diversi e fare un acquisto in pochi minuti. A seconda dell&#39;implementazione, Analytics poteva riportare ogni dispositivo come visitatore univoco e attribuire $ 10 a tre dispositivi in un acquisto da $ 30.

La metrica Persone consente di attribuire con precisione l&#39;acquisto da $ 30 a una sola persona:

![](assets/people-centric-results.png)

**Maggiore precisione nei report**

La metrica Persone ti consente di considerare più dispositivi come una singola entità. Il progetto di Analysis Workspace seguente mostra confronti più precisi tra il reporting di Visitatori univoci e Persone:

![](assets/people_report.png)

Confronto di Persone e Visitatori univoci:

![](assets/people-report.png)

**Definizioni**

<table id="table_F8171AF15DA64607B427E3739EF004D6"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Elemento </th> 
   <th colname="col2" class="entry"> Descrizione </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>Persone </p> </td> 
   <td colname="col2"> <p>La metrica Persone si basa sull'idea che i consumatori interagiscano con il marchio utilizzando più dispositivi. Più i dati vengono sezionati o segmentati e minore è la possibilità che la stessa persona abbia utilizzato più dispositivi in quella sezione di dati. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Visitatori unici </p> </td> 
   <td colname="col2"> <p>Ad esempio, più sezioni i dati per data o ora, inferiore sarà la differenza tra Persone e Visitatori univoci. Per una buona comprensione dell'impatto complessivo di Device Co-op, Adobe consiglia di utilizzare un intervallo di date degli ultimi 90 giorni </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Compressione </p> </td> 
   <td colname="col2"> <p>Utilizzando una semplice metrica calcolata, puoi vedere quanto sia più piccola la metrica Persone come percentuale di Visitatori univoci. Fai clic sull'icona info vicino a "Compressione" nella tabella sopra per vedere come creare questa metrica. </p> <p>Persone può essere utilizzata in altre metriche calcolate al posto di Visitatori univoci. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Come si calcola la metrica Persone? {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

L&#39;immagine seguente mostra come si calcola la metrica Persone e come può diminuire nel tempo per lo stesso intervallo di date del report in passato.

![](assets/people-calculations.png)

In questo esempio, verifica che sia presente un set di visitatori fisso. Se esegui un report per un intervallo di tempo fisso nel passato, visualizza un set di visitatori fisso. Se Device Graph emette i dati mostrati nel grafico a sinistra nella settimana 1, risultano 90 persone. Una settimana dopo, dopo la successiva esecuzione di Device Graph, vengono prese in considerazione nuove informazioni. Se esegui lo stesso report eseguito la settimana prima, il numero di persone è sceso a 84. La cronologia è cambiata perché Device Graph ha fornito nuove informazioni sui dispositivi da raggruppare.

## Uso della metrica Persone con i segmenti {#section-d03525420dbe48379fd95b230ef05885}

Quando utilizzi i segmenti con la metrica Persone, i risultati della metrica potrebbero essere notevolmente inferiori a quanto previsto. Questo problema si verifica perché nella segmentazione non ci sono *`person`* container. La segmentazione utilizza il contenitore Visitatore, il contenitore di massimo livello nella definizione e basato sul dispositivo, non sulla persona.

Questo problema si verifica principalmente durante l&#39;impilamento dei segmenti con la metrica Persone.

![](assets/people-stacked-segments.png)

L&#39;impilamento dei segmenti crea un nuovo segmento che rappresenta la combinazione dei segmenti. L&#39;impilamento dei segmenti avviene ogni volta che:

* Posizioni un segmento sopra un altro segmento in Analysis Workspace (vengono uniti automaticamente utilizzando l&#39;operatore *`And`* operatore.)
* Apply a single segment that contains the *`And`* operator.
* Applichi un segmento a livello di progetto e di tabella.
* Usi una suite per report virtuale con un altro segmento.

Ad esempio, presupponiamo di impilare i segmenti seguenti nella metrica Persone:

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

Only the number of people who qualify in both segments *`using a single device`* are counted. (la metrica Persone non visualizza il numero di persone idonee tra dispositivi).

Inoltre, l&#39;utilizzo dell&#39;operatore *`Or`*&#x200B;è sconsigliato in questa situazione. In questo modo si potrebbe generare un numero di persone che si sono viste tra loro, senza poter calcolare le persone idonee a entrambi i segmenti.

Consulta [Creazione di segmenti](https://marketing.adobe.com/resources/help/en_US/analytics/segment/seg_build.html) nella guida Segmentazione per ulteriori informazioni.

## Tipi di dispositivi {#section-8ab378c84ff34574b9c20fecb3848a86}

Device Co-op e la metrica Persone funzionano al meglio in Adobe Analytics quando la suite per report contiene dati da più tipi di dispositivi. Ad esempio, la combinazione di dati web e app nella stessa suite per report rende la metrica Persone più efficace ed effettiva. Maggiore è il crossover di dispositivi nei dati, maggiore è la possibilità che più visitatori univoci vengano raggruppati come persona singola.

![](assets/people-device-types.png)

## Experience Cloud ID Service Coverage {#section-bbf0098cac2e467289e7a644a1dea05c}

Device Co-op richiede che le tue proprietà digitali siano strumentalizzate utilizzando il servizio Experience Cloud ID (MCID). Se i dati nella suite per report contengono un numero significativo di visitatori senza MCID, l&#39;efficacia di Device Co-op e della metrica Persone è ridotta.

<!--
mcdc-people-metric-apply.xml
-->

In Analysis Workspace, create a [project](https://marketing.adobe.com/resources/help/en_US/analytics/analysis-workspace/t_freeform_project.html), then drag the **[!UICONTROL People]** metric to the project table:

![](assets/people-metric.png)

