---
description: Analisi dei dati deterministici e probabilistici da parte di Device Graph per creare una mappa che colleghi i dispositivi.
seo-description: How the Device Graph analyzes deterministic and probabilistic data to build a map that links devices together.
seo-title: Deterministic and probabilistic links
title: Legami deterministici e probabilistici
uuid: 00693a0a-f73d-460d-84a4-b7c745b9fe0a
exl-id: e9bd2b7a-7d39-425d-adbb-298944009fcc
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '845'
ht-degree: 0%

---

# Legami deterministici e probabilistici{#deterministic-and-probabilistic-links}

Analisi dei dati deterministici e probabilistici da parte di Device Graph per creare una mappa che colleghi i dispositivi.

In [!DNL Device Graph], i processi interni creano una gerarchia di identità che mappa i dispositivi e li collega a singole persone anonime. L’output del grafico include collegamenti tra dispositivi utilizzabili per il targeting insieme ai dati esposti in alcune soluzioni di Experience Cloud. Gli Adobi di soluzioni che funzionano con [!DNL Device Graph] I dati includono Analytics, Audience Manager, Media Optimizer e Target.

Il [!DNL Device Graph] analizza i dati deterministici e probabilistici per creare una mappa che colleghi i dispositivi. I dati deterministici collegano i dispositivi in base a informazioni di accesso con hash. I dati probabilistici collegano i dispositivi in base a informazioni quali indirizzi IP e altri metadati. Il [!DNL Device Graph] associa i cluster di dispositivi collegati a una persona singola anonima. Queste connessioni consentono agli addetti al marketing digitale di raggiungere le persone anziché i dispositivi. In [!DNL Device Graph], il proprietario di un dispositivo è la rappresentazione anonima di una persona reale. Sia i collegamenti deterministici che probabilistici aiutano a creare una struttura di identità utente.

>[!NOTE]
>
>In Adobe Experience Cloud Device Co-op, termini quali *dispositivo*, *persona*, e *identità* hanno un significato specifico. Ad esempio: *dispositivo* può fare riferimento all&#39;hardware fisico, ad esempio un telefono o un tablet, e alle applicazioni eseguite su tale hardware. Consulta la [glossario](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) definizioni.

## Cosa sono i collegamenti? {#section-2df4c6f01eba49369993146df0661f13}

Quando parliamo di collegamenti, è importante tenere a mente cosa si tratta in realtà nel contesto del [!DNL Experience Cloud] Device Graph (Grafico dispositivo). In questo contesto, i collegamenti non sono connessioni fisiche tra dispositivi. Al contrario, un collegamento è il modo in cui il grafico dei dispositivi associa diversi dispositivi alla stessa persona sconosciuta. Ad esempio, supponiamo di avere un telefono cellulare e un browser desktop. Il telefono e il browser possono essere considerati &quot;collegati&quot; una volta che Device Graph determina che entrambi i dispositivi sono utilizzati dalla stessa persona sconosciuta. Come vedrai di seguito, Device Graph crea identità con collegamenti deterministici e probabilistici. Nel grafico dei dispositivi, il proprietario di un dispositivo è la rappresentazione anonima di una persona reale.

## Collegamenti deterministici {#section-33d41e828a674b398e36fe63da20ac09}

I collegamenti deterministici associano un dispositivo a una persona in base a un evento di autenticazione (ad esempio, un’azione di accesso a un sito da un dispositivo). Questa azione crea un identificatore anonimo noto come ID consumatore. Vediamo come funziona il collegamento deterministico. In questo esempio, la persona A accede a un sito di notizie tramite un’app sul proprio dispositivo mobile. Più tardi quel giorno, la persona A accede di nuovo, ma questa volta attraverso un browser sul proprio laptop.

![](assets/link1.png)

In base alle informazioni di accesso, il grafico dei dispositivi:

* Sa che la persona A si è autenticata sul sito di notizie con una combinazione di telefono cellulare/app e laptop/browser.
* Collega questi dispositivi alla persona A.
* Crea un’identità in base ai dispositivi collegati associati a una persona anonima.

![](assets/link2.png)

>[!NOTE]
>
>Né il [!DNL Adobe Experience Cloud Device Co-op] o [!DNL Device Graph] riceve informazioni di autenticazione effettive o informazioni personali (PII, personally identifiable information) da questi dati. Membri del [!DNL Experience Cloud Device Co-op], passare in Device Graph con hash crittografico ID consumer univoci. L’ID consumatore rappresenta un utente autenticato nel grafico e protegge la privacy del consumatore.

## Collegamenti probabilistici {#section-5f5aa755da984f9d851f7cb380262998}

I collegamenti probabilistici collegano un dispositivo a una persona in modo algoritmico, in base a caratteristiche e metadati quali:

* Comportamento di navigazione
* Indirizzi IP
* Sistemi operativi
* Identificatori IDFA e GAID

Vediamo come funziona il collegamento probabilistico. In questo esempio, la persona A passa a un sito di notizie sul proprio tablet e successivamente da un computer desktop. Durante la navigazione, la persona A non accede al sito delle notizie. Durante ogni visita separata, il tablet e il desktop condividono lo stesso indirizzo IP.

![](assets/link3.png)

In base a queste informazioni, [!DNL Device Graph] valuta i modelli di condivisione degli indirizzi IP tra entrambi i dispositivi e collega questi dispositivi se i risultati suggeriscono che appartengono alla persona A. Il risultato finale è la gerarchia di identità derivata dai calcoli di probabilità algoritmica.

![](assets/link4.png)

In questo esempio, Device Graph ha collegato entrambi i dispositivi dopo che erano stati utilizzati per accedere allo stesso sito di notizie. Tuttavia, i dispositivi non devono essere visualizzati sullo stesso sito per essere collegati. Per illustrare questo punto, supponiamo che ogni dispositivo in questo esempio visiti siti web completamente diversi. Il [!DNL Device Graph] L’algoritmo può comunque creare un collegamento probabilistico in base al suo indirizzo IP condiviso e da un’analisi di altri dati. Questo processo contribuisce a rendere il collegamento probabilistico così potente per i membri del [!DNL Experience Cloud] Device Co-op

## Entrambi i tipi di dati forniscono valore {#section-43d22d8c10634edcb261e7bda6fdf323}

I dati deterministici e probabilistici si completano a vicenda. Al contrario, un grafico dei dispositivi che include solo dati deterministici offre una visione limitata dell’identità di una persona. Senza autenticazione, un grafico dei dispositivi non può fornire informazioni su altri dispositivi e utenti che navigano nel sito. I dati probabilistici possono creare queste connessioni e aiutarti a raggiungere dispositivi non autenticati, persone e famiglie.

Tuttavia, anche i dati deterministici sono importanti. Può, ad esempio, migliorare il processo decisionale probabilistico rimuovendo i falsi collegamenti generati in luoghi in cui i segnali probabilistici sono abbondanti e sovrapposti (ad esempio, bar, biblioteche, aeroporti, ecc.).

Con entrambi i tipi di dati, il grafico dei dispositivi offre un’immagine più completa dell’identità di una persona rispetto a quella fornita da ciascun tipo da solo.

![](assets/link5.png)
