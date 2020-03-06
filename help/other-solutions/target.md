---
description: Scopri come utilizzare i dati di Device Co-op nelle attività di Adobe Target.
seo-description: Scopri come utilizzare i dati di Device Co-op nelle attività di Adobe Target.
seo-title: 'Target: test A/B, test multivariati e targeting delle esperienze'
title: 'Target: test A/B, test multivariati e targeting delle esperienze'
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Target - A/B tests, multivariate tests, and experience targeting{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Scopri come utilizzare i dati di Device Co-op nelle attività di Adobe Target.

Puoi utilizzare i dati di Device Co-op in test A/B, test multivariati (MVT) e attività di targeting delle esperienze. The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

Non puoi utilizzare i dati di Device Co-op nelle attività di Personalizzazione automatica, Raccomandazione o attività che utilizzano [!DNL Adobe Analytics] come origine di reporting (integrazione di [!DNL Target] e [!DNL Analytics], nota come A4T).

>[!NOTE]
>
>Ensure that you have the required version of `mbox.js`. Puoi utilizzare qualsiasi versione di `at.js`. Per ulteriori informazioni, consultate Requisiti di [iscrizione](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## Deliver relevant content regardless of the device {#section-bba8d41e96914c82a6d267a54f776354}

Gli esperti di marketing desiderano fornire l&#39;esperienza più rilevante a ogni visitatore, a prescindere dal dispositivo che utilizza attualmente per interagire con la società o il marchio.

Gli utenti interagiscono con la stessa società o marchio da molti dispositivi diversi: laptop di lavoro, computer domestici, iPad, iPhone, vari browser e così via. Se non puoi riconoscere che ogni dispositivo o browser specifico viene utilizzato dalla stessa persona che ha interagito in precedenza con il tuo marchio su un altro dispositivo o browser, non puoi offrire un&#39;esperienza coerente e mirata a tale persona.

Con Device Co-op, i vari dispositivi di un utente possono essere identificati come utilizzati dallo stesso utente. Quando l&#39;utente visualizza una pagina con attività [!DNL Target] (attività o contenuto mirato), [!DNL Target] può garantire che l&#39;utente abbia la stessa esperienza sperimentata su un altro dispositivo.

## Analyze Target activities by people instead of by visitors {#section-c25cf4f8483942d7836d60756235e62c}

Gli esperti di marketing desiderano analizzare le attività [!DNL Target] per &quot;persone&quot; invece che per &quot;visitatori&quot;.

È probabile che ogni persona interagisca con la stessa società o marchio su più dispositivi e browser, ma senza Device Co-op, ogni singolo dispositivo o browser viene considerato come &quot;visitatore&quot; separato nei report [!DNL Target].

La visualizzazione di report per singoli dispositivi e browser aumenta il numero di &quot;visitatori&quot; rispetto al numero di persone diverse che interagiscono con la società o marchio. Queste persone generalmente eseguono la conversione solo una volta su questi vari dispositivi e browser, pertanto il tasso di conversione sarà inferiore rispetto alla realtà, perché più &quot;visitatori&quot; saranno conteggiati per una singola conversione.

Con Device Co-op, la fornitura di contenuto e il reporting vengono eseguiti a livello di &quot;persone&quot;, pertanto i report mostrano con precisione quante persone diverse hanno visto l&#39;attività e quante persone hanno eseguito la conversione.

Senza i dati di Device Co-op, potresti determinare che un&#39;attività specifica è la vincitrice, tuttavia, poiché il reporting è più preciso con Device Co-op, un&#39;altra attività potrebbe in realtà avere un tasso di conversione superiore, diventando così la vincitrice.

Per ulteriori informazioni su questo concetto, consulta [Analytics: Metrica Persone](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## Use Device Co-op data per activity {#section-fb46fae482654023abb1a1e26564db9a}

Gli esperti di marketing possono scegliere di utilizzare i dati di Device Co-op per attività. Determinate attività [!DNL Target] potrebbero non essere adatte ai dati di Device Co-op, ad esempio:

* Contenuto specifico adatto agli utenti su un iPad.

   Gli utenti che visualizzano prima un&#39;esperienza di un iPad continueranno a visualizzare tale esperienza sui computer domestici.

* Un&#39;offerta di tasso di interesse disponibile solo per un segmento limitato di visitatori.
* Prodotti la cui pubblicità è consentita solo in uno stato specifico (ad esempio, una polizza assicurativa con limitazioni di licenza).

Quando gli esperti di marketing creano il pubblico in [!DNL Target], vengono avvisati se tale pubblico non è adatto alle attività con dati abilitati di Device Co-op. Il pubblico adatto include tutti i visitatori, i nuovi visitatori e i visitatori che ritornano.
