---
description: Risposte alle domande comuni su Device Co-op (Identity Services Cooperative e Identity Graph).
title: Domande frequenti su Device Co-op
uuid: 490566e1-4d35-468c-8389-678f9ff02cc8
exl-id: 6511e247-76a7-4960-944c-b49fd046fb28
source-git-commit: 399a4fe2d34957eafe8c4eebed465df8770a9239
workflow-type: tm+mt
source-wordcount: '477'
ht-degree: 1%

---

# Domande frequenti{#faq}

Descrizioni e risposte alle domande comuni su Identity Services Cooperative e Identity Graph.

**Qual è il  [!DNL Device Co-op]?**

Device Co-op è una cooperativa digitale che consente ai clienti Adobe Experience Cloud partecipanti di collaborare per identificare meglio i consumatori tra i dispositivi.

**Quali tecnologie vengono utilizzate in Device Co-op?**

Device Co-op è costituito da due tecnologie:

* **Servizio Experience Cloud ID:** questo servizio di base di Adobe Experience Cloud fornisce un ID comune per identificare in modo coerente i consumatori tra soluzioni, canali, esperienze e dispositivi.
* **Adobe Experience Cloud Device Co-op:** questa tecnologia collega diversi dispositivi utilizzati da un consumatore o una famiglia.

**Come  [!DNL Device Co-op] funziona?**

Man mano che i marchi inseriscono il loro pezzo del puzzle cross-device attraverso accessi anonimi e visite al sito, Adobe elabora questi dati per creare cluster di dispositivi che rappresentano un gruppo di dispositivi utilizzati da una persona sconosciuta. Questi cluster di dispositivi vengono dati ai membri di Device Co-op e utilizzati per fornire ai loro consumatori un&#39;esperienza cross-device migliore e più coerente.

**Come si  [!DNL Device Co-op] collegano i dispositivi?**

Consulta [Collegamenti deterministici e probabilistici](processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931).

**Quali dati forniscono i partecipanti  [!DNL Adobe]?**

Consulta [Strumento di rinuncia del consumatore, Privacy e Device Graph](privacy.md#concept-fa1346e6b95a484eaeafc9bebe3cd6be).

**Quali dati vengono condivisi tra  [!DNL Device Co-op] i membri?**

Consulta [Condivisione collegamenti in Device Graph](processes/link-sharing.md#concept-7168053105a94649a3f092d375d79eaf).

<!--
Removed at Asa's request.
<p><b>What does <span class="keyword"> Adobe </span> see via the <span class="wintitle"> Device Graph </span>?</b> </p>
<p>Adobe can see which devices are most likely being used by the same person, using probabilistic and deterministic device graph algorithms. This match between a group of devices and a person is really two numbers that are linked to each other. One number represents a group of devices believed to belong to the same person while the other number represents a person. Adobe makes this linked device information available to consumers as well, so they can correct misinformation and/or opt-out one or all devices from the Device Co-op. </p>
-->

**Un  [!DNL Device Co-op] membro può visualizzare i collegamenti a dispositivi mai visti prima?**

No. I membri di Device Co-op possono ottenere dati solo in base ai dispositivi che hanno visitato una delle proprietà web del loro marchio. Vedere [Dispositivi noti](processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1) e [Dispositivi sconosciuti](processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40).

**Dovrò condividere informazioni di marketing della mia azienda?**

No. I marchi forniscono solo dati dei dispositivi anonimi ad Adobe.

**Utilizza  [!DNL Adobe] informazioni personali identificabili (PII) in  [!DNL Device Co-op]?**

No. Tutte le informazioni personali identificabili vengono crittografate prima di essere inserite in qualsiasi sistema di Adobe, in modo che le informazioni del cliente non vengano mai trasferite ai sistemi di Adobe.

**I marchi più piccoli che contribuiscono meno dati dei dispositivi a Device Co-op ricevono più valore di quello che inseriscono, rispetto alle loro controparti più grandi?**

No. Tutti i membri della Cooperativa ricevono valore rispetto a quello che hanno messo. Ad esempio, se un marchio fornisce 10.000 dispositivi, potrà ricevere informazioni aggiuntive sui dispositivi collegati associate a tali 10.000. Guardando al quadro generale, questo contributo può sembrare minimo; ma man mano che si uniscono sempre più marchi di tutte le dimensioni, il contributo aggregato è significativo, e fornirà il collegamento mancante per molti dispositivi che molti altri marchi, forse più grandi, stanno cercando. Vedere [Equità e il dispositivo noto](processes/known-device.md#section-0543188729d845d6b95db70b8b25e9f8).

**Come  [!DNL Adobe] gestire gli indirizzi IP se alcuni paesi considerano un indirizzo IP come informazioni personali?**

Device Co-op viene rilasciato per la prima volta negli Stati Uniti e in Canada, dove l’indirizzo IP non è considerato un’informazione personale. Quando la Cooperativa viene rilasciata in paesi in cui l’indirizzo IP è considerato un’informazione personale, l’indirizzo IP non viene utilizzato.
