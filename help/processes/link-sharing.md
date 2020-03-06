---
description: Informazioni sulla condivisione dei collegamenti in Device Graph.
seo-description: Informazioni sulla condivisione dei collegamenti in Device Graph.
seo-title: Condivisione dei collegamenti in Device Graph
title: Condivisione dei collegamenti in Device Graph
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031

---


# Link sharing in the Device Graph{#link-sharing-in-the-device-graph}

Informazioni sulla condivisione dei collegamenti in Device Graph.

The [!DNL Device Graph] shares deterministic and probabilistic links with different members of the Adobe Experience Cloud Device Co-op. Link sharing is what makes the [!DNL Device Co-op] so powerful. Amplia le conoscenze di ciascun membro sui dispositivi associati a una persona anonima, ma solo se prima hai visto almeno uno dei dispositivi di tale persona.

## Device Graph summary review {#section-7858e9f61b5644c981ffb53626fcc19d}

Prima di iniziare, dedichiamo un momento al riepilogo di come funziona [!DNL Device Graph]. Members of the [!DNL Device Co-op] send data to the [!DNL Device Graph]. Questi [!DNL Device Graph] dati vengono utilizzati per creare l&#39;identità di una persona da collegamenti [](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) deterministici e probabilistici tra dispositivi. Come partecipante di [!DNL Device Co-op], questi collegamenti forniscono informazioni sul rapporto tra gli utenti autenticati, altri utenti e i loro dispositivi. Nella sezione seguente daremo un&#39;occhiata alle modalità di funzionamento.

## Link sharing example {#section-cb410d827cf14f76bc9b0bd4d31ed767}

L&#39;esempio seguente mostra l&#39;efficacia della condivisione di collegamenti in Device Co-op. In questo esempio, abbiamo 2 società fittizie, la Società di notizie e la Società finanziaria. Both companies are members of the [!DNL Device Co-op]. La Persona A è un consumatore che accede o naviga sui siti Web di ciascuna società da più dispositivi.

![](assets/share1.png)

Poiché la Persona A ha eseguito l&#39;autenticazione al sito di notizie con il cellulare e il tablet, la Società di notizie la identifica con un ID consumatore. Invia tale ID a [!DNL Device Graph] come hash di crittografia. La Società finanziaria ha visto questi dispositivi prima, ma la Persona A non ha eseguito l&#39;accesso al sito. Di conseguenza, la Società finanziaria non sa se o come questi dispositivi sono correlati tra loro o come sono associati alla Persona A.

![](assets/share2.png)

Dato l&#39;hash di crittografia dell&#39;ID del consumatore, [!DNL Device Graph] riconosce che questi dispositivi sono correlati tra loro e a una persona specifica. Alle società che non partecipano a [!DNL Device Co-op] queste visite del sito appaiono come provenienti da dispositivi casuali separati. In tutti i casi, quando [!DNL Device Graph] dispone dell&#39;ID crittografato:

* Riconosce che il cellulare e il laptop sono collegati.
* Riconosce che la Società finanziaria desidera sapere se il cellulare e il laptop sono collegati.

Date queste condizioni [!DNL Device Graph] condivide ora il collegamento che collega questi dispositivi per la Società di notizie con la Società finanziaria. Durante questo processo [!DNL Device Graph] duplica e condivide il collegamento da un membro della cooperativa a un altro.

![](assets/share3.png)

At this point, the [!DNL Device Graph] performed its role successfully. La Società di notizie e la Società finanziaria hanno entrambe un&#39;idea chiara di un&#39;identità. Possono raggiungere con precisione la Persona A su tutti i suoi dispositivi.

## Privacy and link sharing {#section-7b566018b3304420a4b3e4c079826110}

Mantenere la privacy del consumatore e l&#39;integrità dei dati per i membri di [!DNL Device Co-op] è fondamentale in tutto il processo di condivisione dei collegamenti. Durante il processo di identificazione del cliente e condivisione dei collegamenti [!DNL Device Graph] non ha:

* Comunicato alla Società finanziaria che il collegamento proveniva dalla Società di notizie.
* Condiviso l&#39;ID del cliente utilizzato da un membro di [!DNL Device Co-op] con un altro.
* Fornito informazioni diverse dal fatto che il dispositivo mobile e il laptop condividono un collegamento in comune.

## Passaggi successivi {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

Leggendo la documentazione su identità, collegamento e condivisione dei collegamenti, dovresti avere un&#39;idea di come [!DNL Device Graph] raggruppa i dati internamente. Come passo successivo, consigliamo di dare un&#39;occhiata alla nostra documentazione che descrive come il concetto di un dispositivo *`known device`* fornisca collegamenti cross-device ai membri di Device Co-op. Consultate Dispositivi [](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) noti e Dispositivi [](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)sconosciuti.
