---
description: Descrizioni e risposte alle domande comuni su Identity Services Cooperative e Identity Graph.
seo-description: Descrizioni e risposte alle domande comuni su Identity Services Cooperative e Identity Graph.
seo-title: Domande frequenti
title: Domande frequenti
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
translation-type: tm+mt
source-git-commit: c1d0bc05d3f211fa3e899e98fbcc908be7399031
workflow-type: tm+mt
source-wordcount: '491'
ht-degree: 1%

---


# Domande frequenti{#faq}

Descrizioni e risposte alle domande comuni su Identity Services Cooperative e Identity Graph.

**Cos&#39;è il [!DNL Device Co-op]?**

Device Co-op è una cooperativa digitale che consente ai clienti Adobe Experience Cloud partecipanti di collaborare per identificare meglio i consumatori tra i dispositivi.

**Quali tecnologie vengono utilizzate in Device Co-op?**

Device Co-op è costituito da due tecnologie:

* **servizio ID Experience Cloud:** Questo servizio di base dell&#39;Adobe Experience Cloud fornisce un ID comune per identificare i consumatori in modo coerente tra soluzioni, canali, esperienze e dispositivi.
* **Adobe Experience Cloud Device Co-op:** Questa tecnologia collega diversi dispositivi utilizzati da un consumatore o una famiglia.

**Come [!DNL Device Co-op] funziona?**

Quando i marchi inseriscono nel loro pezzo del puzzle cross-device attraverso accessi anonimi e visite al sito,  Adobe elabora questi dati per formare cluster di dispositivi che rappresentano un gruppo di dispositivi utilizzati da una persona sconosciuta. Questi cluster di dispositivi vengono dati ai membri di Device Co-op e utilizzati per fornire ai consumatori un&#39;esperienza cross-device migliore e più coerente.

**In che modo vengono collegati i dispositivi di [!DNL Device Co-op] collegamento?**

Consulta Collegamenti [deterministici e probabilistici](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**Quali dati forniscono i partecipanti [!DNL Adobe]?**

Consulta Strumento di [rinuncia del consumatore, Privacy e Device Graph](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be).

**Quali dati sono condivisi tra [!DNL Device Co-op] i membri?**

Consulta Condivisione dei [collegamenti in Device Graph](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**Un [!DNL Device Co-op] membro può visualizzare i collegamenti a dispositivi mai visti prima?**

No. I membri di Device Co-op possono ottenere dati solo in base ai dispositivi che hanno visitato una delle proprietà Web del loro marchio. Consultate Dispositivi [](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) noti e Dispositivi [](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)sconosciuti.

**Dovrò condividere informazioni di marketing della mia azienda?**

No. I marchi forniscono solo dati dei dispositivi anonimi  Adobe.

**Utilizza [!DNL Adobe] informazioni personali identificabili (PII) nel [!DNL Device Co-op]?**

No. Tutte le informazioni personali identificabili vengono crittografate prima che vengano inserite in un sistema  Adobe, in modo che le informazioni del cliente non vengano mai trasferite  sistemi di Adobe.

**Marchi più piccoli che forniscono meno dati dei dispositivi a Device Co-op ricevono più valore di quello immesso, rispetto alle controparti più grandi?**

No. Tutti i membri della Cooperativa ricevono valore in relazione a ciò che hanno immesso. Ad esempio, se un marchio contribuisce con 10.000 dispositivi, potrà ricevere informazioni aggiuntive sui dispositivi collegati associate a tali 10.000. Considerando il quadro generale, questo contributo può sembrare minimo; ma man mano che si aggiungono sempre più marchi di tutte le dimensioni, il contributo aggregato è significativo, e fornirà il collegamento mancante per molti dispositivi che molti altri marchi, forse più grandi, stanno cercando. Vedi [Equità e dispositivo](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8)noto.

**Come [!DNL Adobe] gestire gli indirizzi IP se alcuni paesi considerano un indirizzo IP come informazioni personali?**

Device Co-op viene rilasciato per la prima volta negli Stati Uniti e in Canada, dove l&#39;indirizzo IP non è considerato un&#39;informazione personale. Quando la Cooperativa viene rilasciata in paesi in cui l&#39;indirizzo IP è considerato un&#39;informazione personale, l&#39;indirizzo IP non sarà utilizzato.
