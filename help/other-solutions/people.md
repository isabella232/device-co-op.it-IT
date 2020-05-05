---
description: La metrica Persone è il numero di persone (o gruppi di dispositivi) in base a Device Graph di Adobe. Puoi applicare la metrica Persone per identificare i visitatori tra i loro dispositivi in Analysis Workspace.
seo-description: La metrica Persone è il numero di persone (o gruppi di dispositivi) in base a Device Graph di Adobe. Puoi applicare la metrica Persone per identificare i visitatori tra i loro dispositivi in Analysis Workspace.
seo-title: Metrica Persone
title: Metrica Persone
uuid: 8e731779-044d-4d31-a19a-f579a9c8c471
translation-type: tm+mt
source-git-commit: 822882d4f9bb9eed7cf116597b62d07bbe94376c

---


# Metrica Persone{#people-metric}

La metrica Persone è il numero di persone (o gruppi di dispositivi) in base a Device Graph di Adobe. Puoi applicare la metrica Persone per identificare i visitatori tra i loro dispositivi in Analysis Workspace.

## Prerequisiti e considerazioni della metrica Persone {#section-34551d0435fb4b3cb3fad736b7961541}

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
   <td colname="col2"> <p> Per utilizzare la metrica Persone, iscriviti ad <a href="http://landing.adobe.com/en/na/events/summit/275658-summit-co-op.html" format="html" scope="external"> Adobe Experience Cloud Device Co-op</a>. La cooperativa identifica i diversi dispositivi (o ID Experience Cloud) di una persona. Analytics sfrutta queste informazioni per derivare statisticamente il numero di persone che interagiscono con un marchio. La metrica è accurata entro il 5%. </p> <p><b>Regioni</b>: Device Co-op è attualmente disponibile solo negli Stati Uniti e in Canada. Pertanto, quando si valuta la metrica Persone, è necessario applicare un segmento all'analisi che filtra i dati solo per gli Stati Uniti e il Canada. </p> <p>Ogni settimana Device Graph calcola una nuova versione della cooperativa e la pubblica per l'uso. Il martedì, il sistema raccoglie i dati più recenti e pubblica una versione aggiornata del grafico. Le soluzioni Experience Cloud utilizzano quindi la versione più recente del grafico. In modo specifico per Analytics, le modifiche vengono lette il mercoledì e l'elaborazione delle modifiche richiede in genere tra 1 e 2 giorni lavorativi. </p> <p> <p>Importante:  Quando il grafico viene aggiornato su base settimanale, può avere un impatto storico sulla metrica Persone. In altre parole, i conteggi storici delle persone possono cambiare nel tempo man mano che il grafico viene appreso e aggiornato. Ad esempio, se esegui un rapporto oggi che conta le persone il mese scorso e quindi esegui lo stesso rapporto in una settimana dopo l'aggiornamento del grafico, il conteggio delle persone storiche potrebbe subire delle variazioni lievi. </p> </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Autorizzazioni metriche </td> 
   <td colname="col2"> <p>Puoi utilizzare la metrica Persone solo se ti è stato concesso l’accesso. Gli amministratori possono<a href="https://docs.adobe.com/content/help/en/analytics/admin/user-product-management/customize-report-access/groups-metrics.html" format="html" scope="external"> personalizzare le autorizzazioni</a> relative alle metriche in Strumenti di amministrazione. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> Mapping all'organizzazione IMS </td> 
   <td colname="col2"> <p>La metrica Persone sarà abilitata per tutte le suite di rapporti che sono <a href="https://docs.adobe.com/content/help/it-IT/core-services/interface/about-core-services/report-suite-mapping.html" format="html" scope="external"> mappate a un IMSORG</a>. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Progetti/Strumenti di analisi </p> </td> 
   <td colname="col2"> <p>Puoi usare la metrica Persone in <span class="wintitle"> Analysis Workspace</span>, <span class="wintitle"> Analisiad hoc</span>, Generatore <span class="wintitle"></span>di report e tramite l'API. Puoi usarlo ovunque potresti usare la metrica Visitatori unici, comprese le metriche calcolate. </p> <p>Ad esempio, crea una metrica "ricavo per persona" per sostituire una metrica "ricavo per visitatore unico". </p> <p>Un modello <a href="https://docs.adobe.com/content/help/it-IT/analytics/analyze/analysis-workspace/build-workspace-project/starter-projects.html" format="html" scope="external"> di progetto</a> Persone è disponibile per iniziare a utilizzare la metrica Persone in Analysis Workspace. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Attivare le regole bot </p> </td> 
   <td colname="col2"> <p>Adobe consiglia di attivare le regole <a href="https://docs.adobe.com/content/help/en/analytics/admin/admin-tools/bot-removal/bot-rules.html" format="html" scope="external"></a>bot, soprattutto quando si utilizza la metrica Persone. </p> <p>Quando un bot si intrufola nel sito Web, aumenta artificialmente il numero di Visitatori unici. La rimozione del traffico bot dalla suite di rapporti fornisce una misurazione più precisa dell'attività sulle proprietà digitali, sia in termini di Visitatori unici che di Persone. </p> <p>A tal fine, accedi a <span class="uicontrol"> Analytics</span> &gt; <span class="uicontrol"> Amministratore</span> &gt; <span class="uicontrol"> Suite</span>di rapporti. Selezionate la suite di rapporti corretta, quindi andate a <span class="uicontrol"> Modifica impostazioni</span> &gt; <span class="uicontrol"> Generale</span> &gt; <span class="uicontrol"> Regole</span>bot. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Considerazioni sulla segmentazione </p> </td> 
   <td colname="col2"> <p> Quando utilizzi i segmenti con la metrica Persone, il reporting della metrica potrebbe essere notevolmente inferiore al previsto. </p> <p>Consultate <a href="../other-solutions/people.md#section-d03525420dbe48379fd95b230ef05885" format="dita" scope="local"> Utilizzo della metrica Persone con i segmenti</a>. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Cos&#39;è la metrica Persone? {#section-89e2b8f5e80f480391449fc8d1117a6a}

La metrica Persone è una metrica di reporting di Analytics che consente di attribuire i dispositivi alle persone. Fornisce una visualizzazione del marketing basata sulle persone, consentendo di misurare l&#39;attività dei visitatori su tutti i loro dispositivi. Consideralo come una versione deduplicata di Visitatori univoci e puoi usare la metrica Persone per l’analisi in cui precedentemente utilizzavi Visitatori univoci.

**I dispositivi sono persone**

Prima che la metrica Persone fosse disponibile, una persona (ad esempio) poteva visitare il sito e interagire con una campagna o un marchio su tre dispositivi diversi e fare un acquisto, anche in pochi minuti. A seconda dell&#39;implementazione, Analytics potrebbe riportare ogni dispositivo come visitatore univoco e attribuire $ 10 a tre dispositivi in un acquisto da $ 30.

La metrica Persone consente di attribuire con precisione l&#39;acquisto da $ 30 a una sola persona:

![](assets/people-centric-results.png)

**Maggiore precisione nei report**

La metrica Persone consente di considerare più dispositivi come una singola entità. Il seguente progetto di Analysis Workspace mostra confronti più precisi tra il reporting Visitatori unici e Persone:

![](assets/people_report.png)

Confronto di Persone e Visitatori unici:

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
   <td colname="col2"> <p>La metrica Persone si basa sull'idea che i consumatori interagiscano con il tuo marchio utilizzando più dispositivi. Più i dati vengono sezionati o segmentati, minore è la possibilità che la stessa persona abbia utilizzato più dispositivi all'interno di quella sezione di dati. </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Visitatori unici </p> </td> 
   <td colname="col2"> <p>Ad esempio, più sezioni i dati per data o ora, minore sarà la differenza tra Persone e Visitatori univoci. Per una buona comprensione dell'impatto complessivo di Device Co-op, Adobe consiglia di utilizzare un intervallo di date degli ultimi 90 giorni </p> </td> 
  </tr> 
  <tr> 
   <td colname="col1"> <p>Compressione </p> </td> 
   <td colname="col2"> <p>Utilizzando una semplice metrica calcolata potete vedere quanto è più piccola la metrica Persone come percentuale di Visitatori unici. Fai clic sull'icona info accanto a "Compressione" nella tabella sopra per vedere come creare questa metrica. </p> <p>Le persone possono essere utilizzate in altre metriche calcolate al posto di Visitatori unici. </p> </td> 
  </tr> 
 </tbody> 
</table>

## Come viene calcolata la metrica Persone? {#section-0dfb762867e14a7f927796ef3c50592b}

<!--
<p>Analytics uses the HyperLogLog statistical algorithm to calculate People. This means that the smaller the data set, the margin for error may increase. No more than 5% of the numbers should be off by more than 5% </p>
-->

L&#39;immagine seguente mostra come viene calcolata la metrica Persone e come può diminuire nel tempo per lo stesso intervallo di date del rapporto in passato.

![](assets/people-calculations.png)

In questo esempio, supponiamo che esista un set fisso di visitatori. Se esegui un rapporto per un intervallo di tempo fisso in passato, visualizzerà un set fisso di visitatori. Se Device Graph emette i dati mostrati sull&#39;elemento grafico sinistro nella settimana 1, il risultato sarà 90 persone. Una settimana dopo, dopo la successiva esecuzione di Device Graph, vengono prese in considerazione nuove informazioni. Se esegui lo stesso rapporto che hai fatto una settimana fa, il numero di persone è sceso a 84. La cronologia è cambiata perché Device Graph ha fornito nuove informazioni sui dispositivi da raggruppare.

## Utilizzo della metrica Persone con i segmenti {#section-d03525420dbe48379fd95b230ef05885}

Quando utilizzi i segmenti con la metrica Persone, i risultati della metrica potrebbero essere notevolmente inferiori a quanto previsto. Questo problema si verifica perché, nella segmentazione, non è presente alcun *`person`* contenitore. La segmentazione utilizza il contenitore Visitatore, che è il contenitore di livello più alto nella definizione e si basa sul dispositivo, non sulla persona.

Questo problema si verifica principalmente quando si sovrappongono segmenti con la metrica Persone.

![](assets/people-stacked-segments.png)

L&#39;impilamento dei segmenti crea un nuovo segmento che rappresenta la combinazione dei segmenti. L&#39;impilamento dei segmenti avviene ogni volta che:

* Posiziona un segmento sopra un altro segmento in Analysis Workspace. (vengono uniti automaticamente utilizzando l&#39; *`And`* operatore).
* Applicare un singolo segmento che contiene l&#39; *`And`* operatore.
* Applicare un segmento a livello di progetto e di tabella.
* Utilizza una suite di rapporti virtuale con un altro segmento.

Ad esempio, supponiamo di impilare i segmenti seguenti nella metrica Persone:

* `Campaign = Spring Promotion`
* `Site Section = Product Overview`

Viene conteggiato solo il numero di persone idonee in entrambi i segmenti *`using a single device`* . (La metrica Persone non visualizza il numero di persone idonee tra i dispositivi.)

Inoltre, in questa situazione non è consigliabile utilizzare l&#39; *`Or`* operatore. In questo modo si otterrebbe un numero di persone che hanno visto l&#39;una o l&#39;altra, senza poter contare quante persone si qualificano per entrambi i segmenti.

Per ulteriori informazioni, consulta [Creazione di segmenti](https://docs.adobe.com/content/help/it-IT/analytics/components/segmentation/segmentation-workflow/seg-build.html) nella guida Segmentazione.

## Tipi di dispositivi {#section-8ab378c84ff34574b9c20fecb3848a86}

Device Co-op e la metrica Persone funzionano al meglio in Adobe Analytics quando la suite di rapporti contiene dati da più tipi di dispositivi. Ad esempio, la combinazione di dati Web e app nella stessa suite di rapporti rende la metrica Persone più efficace ed efficace. Maggiore è il crossover dei dispositivi nei dati, maggiore è la possibilità che più visitatori univoci vengano raggruppati come una singola persona.

![](assets/people-device-types.png)

## Experience Cloud ID Service Coverage {#section-bbf0098cac2e467289e7a644a1dea05c}

Device Co-op richiede che le tue proprietà digitali siano strumentalizzate utilizzando il servizio Experience Cloud ID (MCID). Se i dati nella suite di rapporti contengono un numero significativo di visitatori senza un MCID, l&#39;efficacia di Device Co-op e della metrica Persone risulta ridotta.

<!--
mcdc-people-metric-apply.xml
-->

In Analysis Workspace, crea un [progetto](https://docs.adobe.com/content/help/en/analytics/analyze/analysis-workspace/build-workspace-project/t-freeform-project.html), quindi trascina la metrica **[!UICONTROL People]** nella tabella del progetto:

![](assets/people-metric.png)

