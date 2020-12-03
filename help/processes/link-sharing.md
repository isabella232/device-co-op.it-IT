---
description: Informazioni sulla condivisione dei collegamenti in Device Graph.
seo-description: Informazioni sulla condivisione dei collegamenti in Device Graph.
seo-title: Condivisione dei collegamenti in Device Graph
title: Condivisione dei collegamenti in Device Graph
uuid: 6c7202f0-c6d9-48a4-82ad-ee57d7a518a0
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '557'
ht-degree: 0%

---


# Condivisione dei collegamenti in Device Graph{#link-sharing-in-the-device-graph}

Informazioni sulla condivisione dei collegamenti in Device Graph.

I [!DNL Device Graph] collegamenti deterministici e probabilistici sono condivisi con diversi membri di Adobe Experience Cloud Device Co-op. La condivisione dei collegamenti è ciò che rende [!DNL Device Co-op] così potenti. Estende ciò che ogni membro sa sui dispositivi associati a una persona anonima, ma solo se hai già visto almeno uno dei dispositivi di tale persona anonima.

## Riepilogo di Device Graph {#section-7858e9f61b5644c981ffb53626fcc19d}

Prima di iniziare, dedichiamo un momento alla verifica del [!DNL Device Graph] funzionamento. I membri del [!DNL Device Co-op] gruppo inviano i dati al [!DNL Device Graph]. Questi [!DNL Device Graph] dati vengono utilizzati per creare l&#39;identità di una persona da collegamenti [](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931) deterministici e probabilistici tra dispositivi. In qualità di [!DNL Device Co-op] partecipante, questi collegamenti forniscono informazioni sulla relazione tra gli utenti autenticati, altri utenti e i loro dispositivi. Vediamo come funziona nella sezione seguente.

## Esempio di condivisione dei collegamenti {#section-cb410d827cf14f76bc9b0bd4d31ed767}

L&#39;esempio seguente illustra l&#39;efficacia della condivisione dei collegamenti in Device Co-op. In questo esempio, abbiamo 2 società fittizie, la Società di notizie e la Società finanziaria. Entrambe le società sono membri del [!DNL Device Co-op]. La Persona A è un consumatore che accede o naviga sui siti Web di ciascuna società da più dispositivi.

![](assets/share1.png)

Poiché la Persona A ha eseguito l&#39;autenticazione al sito di notizie con il cellulare e il tablet, la Società di notizie le identifica con un ID consumatore. Invia l&#39;ID all&#39;utente [!DNL Device Graph] come hash di crittografia. La Società finanziaria ha già visto questi dispositivi, ma la Persona A non ha effettuato l&#39;accesso al sito. Di conseguenza, la Società finanziaria non sa se o come questi dispositivi si relazionano tra loro o come sono associati alla Persona A.

![](assets/share2.png)

Dato l&#39;hash crittografico dell&#39;ID del consumatore, l&#39;utente [!DNL Device Graph] riconosce che questi dispositivi sono correlati tra loro e a una persona specifica. Alle aziende che non partecipano a [!DNL Device Co-op] queste visite del sito apparirebbero dispositivi casuali separati. In ogni caso, una volta che l’ [!DNL Device Graph] ID crittografato è:

* Sa che il cellulare e il laptop sono collegati.
* Riconosce che la Società finanziaria vuole sapere se il cellulare e il laptop sono collegati.

Date queste condizioni, il [!DNL Device Graph] momento condivide il collegamento che collega questi dispositivi per la Società di notizie con la Società finanziaria. Durante questo processo, il collegamento [!DNL Device Graph] viene duplicato e condiviso da un membro della cooperativa a un altro.

![](assets/share3.png)

A questo punto, il [!DNL Device Graph] ruolo ha avuto successo. Sia la Società di notizie che la Società finanziaria hanno un quadro chiaro di un&#39;identità. Possono raggiungere con precisione la Persona A su tutti i suoi dispositivi.

## Privacy e condivisione dei collegamenti {#section-7b566018b3304420a4b3e4c079826110}

Mantenere la privacy dei consumatori e l&#39;integrità dei dati per [!DNL Device Co-op] i membri è fondamentale per tutto il processo di condivisione dei collegamenti. Durante questo processo di identificazione e condivisione dei collegamenti del cliente, [!DNL Device Graph] non è stato possibile:

* Comunica alla Società finanziaria che il collegamento proveniva dalla Società di notizie.
* Condividere l&#39;ID cliente utilizzato da un [!DNL Device Co-op] membro con un altro.
* Fornire informazioni diverse da quelle che il dispositivo mobile e il laptop condividono un collegamento in comune.

## Passaggi successivi {#section-ac6e61f1eb6e45b1bb4be8ece39147c7}

Leggendo la documentazione su identità, collegamento e condivisione dei collegamenti è possibile comprendere in che modo i dati vengono [!DNL Device Graph] assemblati internamente. Come passo successivo, consigliamo di dare un&#39;occhiata alla nostra documentazione che descrive come il concetto di un dispositivo *`known device`* fornisca collegamenti cross-device ai membri di Device Co-op. Consultate Dispositivi [](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) noti e Dispositivi [](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)sconosciuti.
