---
keywords: adobe experience cloud;Adobe Experience Cloud;device co-op;Device Co-op;fine del ciclo di vita
solution: Adobe Experience Cloud
title: Domande frequenti sulla fine del ciclo di vita di Device Co-op
description: Scopri i piani di fine del ciclo di vita di Device Co-op.
source-git-commit: b9e21ba2f749b7a4ad69c122e2273b7f3309da58
workflow-type: tm+mt
source-wordcount: '1017'
ht-degree: 2%

---

# Domande frequenti sulla fine del ciclo di vita di Device Co-op

Questo documento fornisce le risposte alle domande più frequenti sul piano EOL (end-of-life) di Adobe Experience Cloud Device Co-op. Quando questo piano entrerà in vigore, Adobe fornirà un avviso avanzato nelle [note sulla versione di Experience Cloud](https://experienceleague.adobe.com/docs/release-notes/experience-cloud/current.html?lang=it) e in [Aggiornamenti dei prodotti di priorità](https://www.adobe.com/subscription/priority-product-update.html).

## Domande frequenti

Di seguito è riportato un elenco delle risposte alle domande più frequenti sul piano [!DNL Device Co-op] EOL.

## Perché [!DNL Device Co-op] viene dichiarato obsoleto?

Le prossime modifiche nell’ambiente AdTech dovrebbero tradursi in [!DNL Device Co-op] una soluzione obsoleta nei prossimi anni. [!DNL Device Co-op] è composto per lo più da cookie di terze parti e l’ [!DNL Google's] annuncio che bloccheranno i cookie di terze parti  [!DNL Google Chrome] entro il 2022 ridurrà l’efficacia di  [!DNL Device Co-op]. [!DNL Chrome] ha circa il 65% della quota di mercato del browser e altri principali browser hanno già implementato il blocco dei cookie di terze parti. Una volta che [!DNL Chrome] blocca i cookie di terze parti, la maggior parte dei cookie di terze parti verrà bloccata e [!DNL Device Co-op] diventerà obsoleta.

## Perché Adobe termina ora le iscrizioni [!DNL Device Co-op]?

Le registrazioni cessano per evitare il rischio di non soddisfare le aspettative dei clienti a causa dei prossimi cambiamenti del settore rispetto ai cookie di terze parti. [!DNL Device Co-op] ci vogliono alcuni mesi per essere preparati e altri pochi mesi per estrarre valore dal servizio. Qualsiasi ulteriore iscrizione a questo punto potrebbe comportare che i marchi non abbiano il pieno valore di [!DNL Device Co-op].

## I nuovi clienti possono registrarsi?

A partire dall’11 giugno 2021, Adobe non accetterà più nuove iscrizioni a [!DNL Device Co-op].

## Vengono rinnovati i contratti esistenti?

A partire dall’11 giugno 2021, Adobe non rinnoverà più i contratti [!DNL Device Co-op]. Se desideri continuare a utilizzare i servizi [!DNL Device Co-op], puoi continuare a farlo in base ai termini della licenza corrente fino al termine del programma.

## Qual è la data di fine esatta del programma [!DNL Device Co-op]?

Il programma [!DNL Device Co-op] terminerà nel 2022. La data e la data specifiche dipendono da quando [!DNL Google] inizia a bloccare i cookie di terze parti.

## Quali applicazioni saranno influenzate dalla fine del ciclo di vita di Device Co-op?

Le procedure di fine del ciclo di vita di [!DNL Device Co-op] avranno effetto sulle seguenti applicazioni:

- [Adobe Analytics](https://experienceleague.adobe.com/docs/analytics.html?lang=en)  
- [Adobe Audience Manager](https://experienceleague.adobe.com/docs/audience-manager/user-guide/overview/aam-overview.html?lang=en)
- [Adobe Advertising Cloud](https://experienceleague.adobe.com/docs/advertising-cloud.html?lang=en)
- [Adobe Target](https://experienceleague.adobe.com/docs/target/using/introduction/intro.html?lang=en)

## Quali opzioni ho come alternativa a [!DNL Device Co-op]?

### [!DNL Analytics]

Puoi utilizzare la funzione [!DNL Analytics] [Analisi multidispositivo (CDA)](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html) in quanto supporta sia il servizio Adobe Experience Platform Identity [Private Graph](https://experienceleague.adobe.com/docs/analytics/components/cda/device-graph.html?lang=en) che [Stitching basato su campi](https://experienceleague.adobe.com/docs/analytics/components/cda/field-based-stitching.html?lang=en).

### [!DNL Audience Manager]

[!DNL Audience Manager] mantiene integrazioni con partner grafici per dispositivi di terze parti, inclusi  [!DNL LiveRamp] e  [!DNL Tapad], anche se è necessario stabilire relazioni commerciali con i partner grafici direttamente, al fine di sfruttare  [!DNL Audience Manager].

### [!DNL Real-time Customer Data Platform]

Non è previsto di modificare il file [!DNL Audience Manager Data Management Platform] (DMP) corrente. Tuttavia, la deprecazione dei cookie di terze parti probabilmente creerà problemi di scala per la maggior parte degli utenti DMP. Per aiutare i clienti a sviluppare le proprie pratiche di gestione dei dati, l’Adobe incoraggia la riduzione delle dipendenze dagli identificatori che dovranno affrontare restrizioni nel prossimo anno. I team di marketing devono creare strategie per i dati di prime parti incentrate su identificatori durevoli che includono informazioni personali identificabili (PII), che possono essere risolte con [!DNL Real-time Customer Data Platform] (Real-time CDP).

[!DNL Real-time CDP] riduce le dipendenze da cookie di terze parti e ID dispositivo espandendo il set di identificatori disponibili per la creazione di un pubblico in modo da includere i PII. Fondativo di [!DNL Real-time CDP] è il Profilo del cliente in tempo reale, che riunisce in tempo reale i dati degli attributi delle persone con i dati comportamentali e consente agli esperti di marketing di creare segmenti di pubblico avanzati con controlli brevettati sulla governance dei dati. Come [!DNL Audience Manager], [!DNL Real-time CDP] fornisce informazioni approfondite e casi d’uso di personalizzazione, ma genera anche informazioni più dettagliate a livello di persona e può attivare il pubblico in una gamma più ampia di destinazioni che si estendono su tecnologie pubblicitarie e di marketing, compresi i media a pagamento, social media, e-mail e sistemi cliente.

[!DNL Real-time CDP] includerà anche l’accesso a  [Adobe Experience Platform Segment Match (Alpha)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en), che consente ai brand di espandere i propri set di dati di prime parti tramite partnership e ottenere migliori informazioni e personalizzazione.

### [!DNL Target]

Al momento non sono disponibili alternative per [!DNL Target] perché [!DNL Target] fornisce una funzionalità deterministica di unione delle identità tra dispositivi nota come `mbox3rdPartyId`, che funziona in modo simile all’ID cliente di Adobe. Questa funzionalità consente ai clienti [!DNL Target] di unire profili e partecipazione alle attività tra [!DNL Target] test e personalizzazione eseguiti nei canali in entrata.

### Adobe Advertising Cloud

[!DNL Advertising Cloud] i clienti non potranno più utilizzare  [!DNL Device Co-op] per il targeting e la misurazione dell’audience su più dispositivi. Con [!DNL Advertising Cloud], potrai comunque sfruttare la collaborazione di Adobe [!DNL Device Graph] con [!DNL LiveRamp] per continuare a eseguire queste funzioni fino alla [!DNL LiveRamp’s] capacità e scalabilità. È necessario consentire la fine delle campagne che utilizzano [!DNL Device Co-op], quindi passare al provider di grafici dei dispositivi [!DNL LiveRamp] o non utilizzare più il targeting basato sulle persone.

## Quali funzionalità e implementazioni esistenti possono aiutare la mia preparazione a un futuro senza cookie?

L&#39;implementazione del servizio ID visitatori esistente potenzia Analytics [CDA](https://experienceleague.adobe.com/docs/analytics/components/cda/overview.html). Se l’ID dichiarato esistente è un’e-mail con hash, può essere utilizzato per abilitare le seguenti funzionalità:

- [!DNL Audience Manager] [Destinazioni basate su persone](https://experienceleague.adobe.com/docs/audience-manager/user-guide/features/destinations/people-based/people-based-destinations-overview.html).
- [Experience Platform di corrispondenza del segmento (alfa)](https://experienceleague.adobe.com/docs/experience-platform/segmentation/ui/segment-match.html?lang=en).

## È possibile conservare i dati da [!DNL Device Co-op]?

Per gli utenti [!DNL Audience Manager] e [!DNL Advertising Cloud], i dati di [!DNL Device Co-op] non saranno disponibili per il trasferimento a grafici di terze parti. [!DNL Device Co-op] i dati verranno migrati solo per  [!DNL Analytics Ultimate] gli utenti che utilizzano CDA con il  [!DNL Device Co-op] passaggio a Stitching basato su campi. Tutte le altre soluzioni non effettueranno la migrazione dei dati.

## È obbligatorio adottare altre caratteristiche?

Anche se l’adozione di altre funzioni di Adobe non è obbligatoria, è necessario avviare l’implementazione di altre funzioni il prima possibile per consentire tempo e un coordinamento appropriato prima che [!DNL Device Co-op] diventi obsoleto.

## Entro quando devo adottare soluzioni alternative, se lo scelgo?

L’adozione di altre funzioni non è obbligatoria. Si consiglia solo se si desidera continuare a gestire i casi di utilizzo affrontati da [!DNL Device Co-op]. Se si sceglie di adottare altre funzioni, è necessario farlo entro il 2022 (data esatta da annunciare) prima della fine del programma [!DNL Device Co-op].

## Quanto tempo ci vorrà per l&#39;adozione?

Questo dipenderà dalla funzione. Ad esempio, se un cliente Analytics Ultimate che utilizza Cross-Device Analytics con [!DNL Device Co-op] deve migrare a Real-time Private Device Graph o a Stitching basato su campi, l&#39;adozione richiederà un po&#39; di tempo.