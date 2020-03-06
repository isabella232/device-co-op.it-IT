---
description: In che modo Device Graph analizza i dati deterministici e probabilistici per creare una mappa che collega i dispositivi insieme.
seo-description: In che modo Device Graph analizza i dati deterministici e probabilistici per creare una mappa che collega i dispositivi insieme.
seo-title: Collegamenti deterministici e probabilistici
title: Collegamenti deterministici e probabilistici
uuid: 00693a0a-f73d-460d-84a4-b7c745b9fe0a
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Deterministic and probabilistic links{#deterministic-and-probabilistic-links}

In che modo Device Graph analizza i dati deterministici e probabilistici per creare una mappa che collega i dispositivi insieme.

In [!DNL Device Graph], i processi interni creano una gerarchia delle identità che mappa i dispositivi e li connette a singole persone anonime. L&#39;output del grafico include collegamenti cross-device che puoi utilizzare per il targeting insieme ai dati esposti in soluzioni Experience Cloud selezionate. The Adobe solutions that work with [!DNL Device Graph] data include Analytics, Audience Manager, Media Optimizer, and Target.

[!DNL Device Graph] analizza dati deterministici e probabilistici per creare una mappa che collega insieme i dispositivi. I dati deterministici collegano i dispositivi in base alle informazioni di accesso crittografate. I dati probabilistici collegano in dispositivi in base a informazioni quali indirizzi IP e altri metadati. [!DNL Device Graph] associa i cluster di dispositivi collegati a una singola persona anonima. Tali collegamenti consentono agli esperti di marketing digitale di raggiungere persone, e non semplicemente dispositivi. In [!DNL Device Graph], il proprietario di un dispositivo è la rappresentazione anonima di una persona reale. I collegamenti deterministici e probabilistici contribuiscono a creare una struttura di identità dell&#39;utente.

>[!NOTE]
>
>In Adobe Experience Cloud Device Co-op, termini come *dispositivo*, *persona* e *identità* hanno significati specifici. For example, *device* can refer to physical hardware such as a phone or tablet and the applications that run on that hardware. Consulta il [glossario](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) per le definizioni.

## What are links? {#section-2df4c6f01eba49369993146df0661f13}

Quando parliamo di collegamenti, è importante tenere presente cosa si intende davvero nel contesto di [!DNL Experience Cloud] Device Graph. In questo contesto, i collegamenti non sono collegamenti fisici tra dispositivi. Per collegamento si intende piuttosto il modo in cui Device Graph associa diversi dispositivi alla stessa persona sconosciuta. Ad esempio, se sono presenti un cellulare e un browser desktop, il telefono e il browser possono essere considerati &quot;collegati&quot; quando Device Graph determina che entrambi i dispositivi sono utilizzati dalla stessa persona sconosciuta. Come leggerai di seguito, Device Graph crea identità con collegamenti deterministici e probabilistici. Inoltre, in Device Graph, il proprietario di un dispositivo è la rappresentazione anonima di una persona reale.

## Deterministic links {#section-33d41e828a674b398e36fe63da20ac09}

I collegamenti deterministici associano un dispositivo a una persona in base a un evento di autenticazione (ad es. operazione di accesso a un sito da un dispositivo). Questa azione crea un identificatore anonimo noto come ID del consumatore. Diamo un&#39;occhiata alle modalità di funzionamento dei collegamenti deterministici. In questo esempio, la Persona A accede a un sito di notizie tramite un&#39;app sul suo dispositivo mobile. Più tardi nello stesso giorno, la Persona A accede di nuovo, ma questa volta utilizzando un browser sul laptop.

![](assets/link1.png)

In base alle informazioni di accesso, Device Graph:

* Riconosce che la Persona A ha eseguito l&#39;autenticazione al sito di notizie con una combinazione di cellulare/app e laptop/browser.
* Collega questi dispositivi alla Persona A.
* Crea un&#39;identità basata sui dispositivi collegati associati a una persona anonima.

![](assets/link2.png)

>[!NOTE]
>
>Neither the [!DNL Adobe Experience Cloud Device Co-op] or the [!DNL Device Graph] receives actual authentication information or personally identifiable information (PII) in this data. Members of the [!DNL Experience Cloud Device Co-op], pass in cryptographically hashed, unique consumer IDs to the Device Graph. L&#39;ID del consumatore rappresenta un utente autenticato nel grafico e tutela la privacy del consumatore.

## Probabilistic links {#section-5f5aa755da984f9d851f7cb380262998}

I collegamenti probabilistici collegano un dispositivo a una persona algoritmicamente, in base a caratteristiche e metadati quali:

* Comportamento di navigazione
* Indirizzi IP
* Sistemi operativi
* Identificatori IDFA e GAID

Diamo un&#39;occhiata alle modalità di funzionamento dei collegamenti probabilistici. In questo esempio, la Persona A naviga su un sito di notizie sul tablet e più tardi da un computer desktop. Durante la navigazione, la Persona A non effettua l&#39;accesso al sito di notizie. Durante ogni visita separata, il tablet e il desktop condividono lo stesso indirizzo IP.

![](assets/link3.png)

In base a queste informazioni, [!DNL Device Graph] valuta gli schemi di condivisione dell&#39;indirizzo IP tra entrambi i dispositivi e li collega insieme se i risultati suggeriscono che appartengono alla Persona A. Il risultato finale è una gerarchia di identità derivata da calcoli algoritmici delle probabilità.

![](assets/link4.png)

In questo esempio, Device Graph ha collegato entrambi i dispositivi dopo essere stati utilizzati per accedere allo stesso sito di notizie. Tuttavia, non è necessario che i dispositivi siano visti sullo stesso sito per essere collegati. Per spiegare questo punto, diciamo che ciascun dispositivo in questo esempio visita siti Web completamente diversi. L&#39;algoritmo di [!DNL Device Graph] può comunque eseguire un collegamento probabilistico in base all&#39;indirizzo IP condiviso e da un&#39;analisi dei loro dati. Questo processo contribuisce a rendere il collegamento probabilistico molto efficiente per i membri di [!DNL Experience Cloud] Device Co-op.

## Both types of data provide value {#section-43d22d8c10634edcb261e7bda6fdf323}

I dati deterministici e probabilistici si completano. Un grafico del dispositivo che include solo dati deterministici, invece, offre una panoramica limitata dell&#39;identità di una persona. Senza autenticazione, un grafico del dispositivo non può fornire informazioni sugli altri dispositivi e sulle altre persone che navigano sul sito. I dati probabilistici possono creare questi collegamenti e aiutare a raggiungere dispositivi, persone e famiglie non autenticati.

Tuttavia, anche i dati deterministici sono importanti. Ad esempio, possono migliorare il processo decisionale probabilistico rimuovendo falsi collegamenti generati in posti in cui i segnali probabilistici sono numerosi e sovrapposti (ad es. caffetterie, biblioteche, aeroporti ecc.).

Con entrambi i tipi di dati, Device Graph offre una panoramica più completa dell&#39;identità di una persona rispetto ai singoli tipi di dati da soli.

![](assets/link5.png)

