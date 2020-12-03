---
description: Scopri come utilizzare i dati di Device Co-op nelle attività  Adobe Target.
seo-description: Scopri come utilizzare i dati di Device Co-op nelle attività  Adobe Target.
seo-title: 'Target: test A/B, test multivariati e targeting delle esperienze'
title: 'Target: test A/B, test multivariati e targeting delle esperienze'
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '586'
ht-degree: 0%

---


# Target: test A/B, test multivariati e targeting delle esperienze{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Scopri come utilizzare i dati di Device Co-op nelle attività  Adobe Target.

Puoi utilizzare i dati di Device Co-op in test A/B, test multivariati (MVT) e attività di targeting delle esperienze. The Device Co-op option is available during activity creation on the [!DNL Goals & Settings] page in the [!DNL Target] three-step guided workflow.

Non puoi utilizzare i dati di Device Co-op  attività di Automated Personalization, le attività di Recommendations o le attività utilizzando [!DNL Adobe Analytics] come origine di reporting (l&#39; [!DNL Target] integrazione e [!DNL Analytics] l&#39;integrazione, nota come A4T).

>[!NOTE]
>
>Verificate di disporre della versione richiesta di `mbox.js`. Potete utilizzare qualsiasi versione di `at.js`. Per ulteriori informazioni, consultate Requisiti di [iscrizione](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## Distribuzione di contenuti rilevanti indipendentemente dal dispositivo {#section-bba8d41e96914c82a6d267a54f776354}

Gli esperti di marketing desiderano fornire l&#39;esperienza più rilevante a ogni visitatore, a prescindere dal dispositivo che utilizza attualmente per interagire con la propria azienda o marchio.

Gli utenti interagiscono con la stessa società o marchio da molti dispositivi diversi: laptop di lavoro, computer domestici, iPad, iPhone, vari browser e così via. Se non riesci a riconoscere che ogni dispositivo o browser specifico è utilizzato dalla stessa persona che ha interagito in precedenza con il tuo marchio su un altro dispositivo o browser, non puoi fornire a tale persona un&#39;esperienza coerente e mirata.

Con Device Co-op, i diversi dispositivi di un utente possono essere identificati come utilizzati dallo stesso utente. Quando l&#39;utente visualizza una pagina con [!DNL Target] attività, attività o contenuto mirato [!DNL Target] può garantire che l&#39;utente visualizzi la stessa esperienza su un altro dispositivo.

## Analizzare le attività Target per persone invece che per visitatori {#section-c25cf4f8483942d7836d60756235e62c}

Gli esperti di marketing desiderano analizzare [!DNL Target] le attività per &quot;persone&quot; invece che per &quot;visitatori&quot;.

È probabile che ogni persona interagisca con la stessa società o marchio su più dispositivi e browser, ma senza Device Co-op, ogni singolo dispositivo o browser viene considerato un &quot;visitatore&quot; separato nei [!DNL Target] rapporti.

La visualizzazione dei rapporti per singoli dispositivi e browser aumenta il numero di &quot;visitatori&quot; rispetto al numero di persone diverse che interagiscono con la società o il marchio. Queste persone generalmente convertono solo una volta tra i vari dispositivi e browser, quindi il tasso di conversione sarà inferiore a quello della realtà perché più &quot;visitatori&quot; saranno conteggiati per una singola conversione.

Con Device Co-op, la distribuzione dei contenuti e il reporting vengono eseguiti a livello di &quot;persone&quot;, pertanto i report mostrano con precisione quante persone diverse hanno visto l&#39;attività e quante persone hanno eseguito la conversione.

Senza i dati di Device Co-op, potresti determinare che una particolare attività è vincente; tuttavia, poiché il reporting è più preciso con Device Co-op, un&#39;altra attività potrebbe avere in realtà un tasso di conversione più elevato e, pertanto, essere il vincitore.

Per ulteriori informazioni su questo concetto, consulta [Analisi: Metrica Persone](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## Utilizzare i dati di Device Co-op per attività {#section-fb46fae482654023abb1a1e26564db9a}

Gli addetti al marketing possono scegliere di utilizzare i dati di Device Co-op per attività. Alcune [!DNL Target] attività potrebbero non essere appropriate per i dati di Device Co-op, ad esempio:

* Contenuto specifico adatto agli utenti su un iPad.

   Gli utenti che visualizzano per la prima volta un&#39;esperienza su un iPad continueranno a visualizzare tale esperienza sui propri computer domestici.

* Un&#39;offerta di tasso di interesse disponibile solo per un segmento di visitatori rigoroso.
* Prodotti autorizzati a essere pubblicizzati solo in uno stato specifico (ad esempio, una polizza assicurativa con limitazioni di licenza).

Quando gli esperti di marketing creano i tipi di pubblico in [!DNL Target], vengono avvisati se il pubblico non è adatto alle attività abilitate ai dati di Device Co-op. Le audience appropriate includono tutti i visitatori, i nuovi visitatori e i visitatori di ritorno.
