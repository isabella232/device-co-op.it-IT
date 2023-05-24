---
description: Scopri come utilizzare i dati di Device Co-op nelle attività di Adobe Target.
seo-description: Learn how to use Device Co-op data in Adobe Target activities.
seo-title: Target - A/B tests, multivariate tests, and experience targeting
title: 'Target: test A/B, test multivariati e targeting delle esperienze'
uuid: c1b478a4-812e-41ee-913f-29666c5c7ec4
exl-id: 6e630adf-faff-4fe4-b560-febd59964a5f
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '566'
ht-degree: 0%

---

# Target: test A/B, test multivariati e targeting delle esperienze{#target-a-b-tests-multivariate-tests-and-experience-targeting}

Scopri come utilizzare i dati di Device Co-op nelle attività di Adobe Target.

Puoi utilizzare i dati di Device Co-op in test A/B, test multivariati (MVT) e attività di targeting delle esperienze. L’opzione Device Co-op è disponibile durante la creazione dell’attività sul [!DNL Goals & Settings] pagina in [!DNL Target] flusso di lavoro guidato in tre passaggi.

Non è possibile utilizzare i dati di Device Co-op nelle attività di Automated Personalization, nelle attività di Consigli o nelle attività che utilizzano [!DNL Adobe Analytics] come origine per la generazione di rapporti (il [!DNL Target] e [!DNL Analytics] A4T).

>[!NOTE]
>
>Assicurati di disporre della versione richiesta di `mbox.js`. Puoi utilizzare qualsiasi versione di `at.js`. Per ulteriori informazioni, consulta [Requisiti di iscrizione](../about/requirements.md#concept-31d3d165d22546afbedf023d32ad3a43).

## Distribuisci contenuti rilevanti indipendentemente dal dispositivo {#section-bba8d41e96914c82a6d267a54f776354}

Gli addetti al marketing desiderano fornire a ogni visitatore l’esperienza più rilevante, indipendentemente dal dispositivo utilizzato dal visitatore per interagire con l’azienda o il marchio.

Gli utenti interagiscono con la stessa azienda o marchio da molti dispositivi diversi: laptop di lavoro, computer di casa, iPad, iPhone, vari browser e così via. Se non riesci a riconoscere che ogni dispositivo o browser specifico è utilizzato dalla stessa persona che ha precedentemente interagito con il tuo marchio su un altro dispositivo o browser, non puoi fornire un’esperienza coerente e mirata a tale persona.

Con Device Co-op, è possibile identificare i diversi dispositivi di un utente come utilizzati dallo stesso utente. Quando l’utente visualizza una pagina con [!DNL Target] attività, attività o contenuti mirati [!DNL Target] può garantire che l’utente visualizzi la stessa esperienza su un altro dispositivo.

## Analizzare le attività di Target in base alle persone anziché ai visitatori {#section-c25cf4f8483942d7836d60756235e62c}

Gli addetti al marketing vogliono analizzare [!DNL Target] attività di &quot;persone&quot; invece di &quot;visitatori&quot;.

È probabile che ogni persona interagisca con la stessa azienda o lo stesso marchio su diversi dispositivi e browser, ma senza Device Co-op, ogni singolo dispositivo o browser è considerato un &quot;visitatore&quot; separato in [!DNL Target] rapporti.

La visualizzazione dei rapporti per singoli dispositivi e browser aumenta il conteggio dei &quot;visitatori&quot; a un numero più alto rispetto al numero di persone diverse che interagiscono con l’azienda o il brand. In genere queste persone si convertono solo una volta tra questi vari dispositivi e browser, quindi il tasso di conversione sarà inferiore a quello reale perché più &quot;visitatori&quot; verranno conteggiati per una singola conversione.

Con Device Co-op, la distribuzione dei contenuti e il reporting vengono eseguiti a livello di &quot;persone&quot;, in modo che i rapporti mostrino con precisione quante persone diverse hanno visto l’attività e quante delle persone si sono convertite.

Senza i dati di Device Co-op, potresti determinare che una particolare attività è la vincente; tuttavia, poiché il reporting è più accurato con Device Co-op, un’altra attività potrebbe in realtà avere un tasso di conversione più elevato e, quindi, essere la vincente.

Per ulteriori informazioni su questo concetto, consulta [Analytics: metrica Persone](../other-solutions/people.md#concept-8c57cd3904974e078d7fbf84ac9c2d63).

## Utilizzare i dati di Device Co-op per attività {#section-fb46fae482654023abb1a1e26564db9a}

Gli addetti al marketing possono scegliere di utilizzare i dati di Device Co-op per ogni attività. Certi [!DNL Target] Le attività potrebbero non essere appropriate per i dati di Device Co-op, ad esempio:

* Contenuto specifico appropriato per gli utenti su un iPad.

   Gli utenti che visualizzano per la prima volta un’esperienza su un’iPad continueranno a visualizzarla sui propri computer di casa.

* Un’offerta di tasso di interesse disponibile solo per un segmento rigoroso di visitatori.
* I prodotti possono essere pubblicizzati solo in uno stato specifico (ad esempio, una polizza assicurativa con restrizioni di licenza).

Quando gli addetti al marketing creano tipi di pubblico in [!DNL Target], vengono avvisati se il pubblico non è appropriato per le attività abilitate per i dati di Device Co-op. I tipi di pubblico appropriati includono tutti i visitatori, i nuovi visitatori e i visitatori di ritorno.
