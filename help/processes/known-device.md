---
description: Informazioni sui dispositivi noti in Device Graph.
seo-description: Informazioni sui dispositivi noti in Device Graph.
seo-title: Dispositivi noti
title: Dispositivi noti
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371
workflow-type: tm+mt
source-wordcount: '571'
ht-degree: 1%

---


# Dispositivi noti{#known-devices}

Informazioni sui dispositivi noti in Device Graph.

In Device Graph, esiste il concetto di *`known device`*. Un dispositivo noto è un dispositivo utilizzato da un cliente per interagire con il tuo marchio.

>[!NOTE]
>
>In termini [!DNL Adobe Experience Cloud Device Co-op]come *`device`*, *`person`*, *`identity`* ecc. hanno significati specifici. Ad esempio, &quot;dispositivo&quot; può fare riferimento a hardware fisico come un telefono o un tablet e alle applicazioni eseguite su tale hardware. Vedere il [glossario](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) delle definizioni.

## Supporto di obiettivi con il dispositivo noto {#section-80deae33660e4280ac65c659ceff5601}

Il concetto di dispositivo noto supporta alcuni obiettivi essenziali per la creazione e la manutenzione di un [!DNL Device Co-op] programma efficace. Un dispositivo noto è un dispositivo noto a un [!DNL Device Co-op] membro per l&#39;interazione con un consumatore (ad esempio, una visita al sito o l&#39;utilizzo di un&#39;app mobile). In base a tali azioni, i dispositivi noti di un [!DNL Device Graph] membro [!DNL Device Co-op] vengono collegati ai dispositivi forniti da altri [!DNL Device Co-op] membri. Questi collegamenti possono essere [deterministici o probabilistici](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931). Questo va a vantaggio [!DNL Device Co-op] dei membri in quanto ricevono:

* Maggiori dati sui loro dispositivi noti.
* Nuove informazioni su altri dispositivi collegati.

![](assets/known-device.png)

L&#39;utente non [!DNL Device Graph] fornirà informazioni sui cluster di dispositivi che un membro di Device Co-op non ha visto.

## Obiettivi di Device Co-op {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

Tre obiettivi principali animano il [!DNL Device Co-op]. Comprendono:

* **Scala:** Condividi il numero massimo di collegamenti possibili tra diversi casi di utilizzo.
* **Equità:** Garantire che ciascun membro dei [!DNL Device Co-op] benefici sia commisurato ai loro contributi.

* **Fiducia del consumatore:** Mantenete e rafforzate la fiducia dei consumatori assicurandovi che l&#39;esperienza cross-device dei consumatori coinvolga marchi già noti e affidabili.

## Scala e dispositivo noto {#section-67f734109762457ca62ec306284ea082}

I seguenti metodi sono i modi più comuni in cui un dispositivo si qualifica come dispositivo noto. Dati questi metodi, [!DNL Device Co-op] i membri avranno quasi sempre almeno un dispositivo noto. Ciò supporta l&#39;obiettivo di fornire la scala massima a tutti i membri del [!DNL Device Co-op].

**Organico**

* Da una visita del cliente al sito o tramite l&#39;utilizzo dell&#39;app. Questa è qualifica da dati di prime parti.
* Tramite la registrazione di clienti da un sistema CRM.

**Marketplace**

* Acquisto dei dati del segmento da  Audience Marketplace.
* Dall&#39;acquisto di dati da un provider di dati di terze parti.

**Pubblicità**

Vincendo le scorte in un&#39;asta e distribuendo un annuncio a un dispositivo. Il dispositivo diventa noto se l’annuncio contiene un [!DNL Audience Manager] pixel.

## Dispositivi noti e casi di utilizzo di equità {#section-0543188729d845d6b95db70b8b25e9f8}

I membri del gruppo [!DNL Device Co-op] ottengono collegamenti commisurati ai loro contributi al gruppo [!DNL Device Graph]. Le aziende che forniscono molti dispositivi al [!DNL Device Graph] destinatario ricevono più collegamenti rispetto ai membri che contribuiscono solo a pochi. Crediamo che questo aiuti a rendere [!DNL Device Co-op] giusto per tutti i suoi membri. Vediamo come funziona con i casi di utilizzo grandi e piccoli descritti di seguito.

**Marchio A: caso di utilizzo ampio**

In questo esempio, il marchio A ha 100 visitatori del sito ogni mese e avvia una nuova campagna marchio cross-device. Per semplicità, presupponiamo che tutti i visitatori del marchio A siano [!DNL Device Graph] collegati a 1 dispositivo aggiuntivo. Ciò significa che il marchio A potrebbe raggiungere altri 100 dispositivi. Inoltre, [!DNL Device Graph] contiene circa 200 dispositivi collegati tra loro.

<table id="table_78C38DC522F94BC38C1DB73740C058AC"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Dispositivi noti/Mese </th> 
   <th colname="col2" class="entry"> Dispositivi collegati ricevuti da Device Co-op </th> 
   <th colname="col3" class="entry"> Dispositivi totali per campagna </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>100 </p> </td> 
   <td colname="col3"> <p>200 </p> </td> 
  </tr> 
 </tbody> 
</table>

**Marchio B: Caso di utilizzo piccolo**

In questo esempio, il marchio B ha 100 visitatori del sito ogni mese e avvia una nuova campagna marchio cross-device. Per semplicità, presupponiamo che tutti i visitatori del marchio B siano [!DNL Device Graph] collegati a 50 dispositivi aggiuntivi. Ciò significa che il marchio B può raggiungere 150 dispositivi. Inoltre, [!DNL Device Graph] contiene circa 1.000 dispositivi collegati tra loro.

<table id="table_A6C9CCF9C6564A89BA7060E075A8E73C"> 
 <thead> 
  <tr> 
   <th colname="col1" class="entry"> Dispositivi noti/Mese </th> 
   <th colname="col2" class="entry"> Dispositivi collegati ricevuti da Device Co-op </th> 
   <th colname="col3" class="entry"> Dispositivi totali per campagna </th> 
  </tr>
 </thead>
 <tbody> 
  <tr> 
   <td colname="col1"> <p>100 </p> </td> 
   <td colname="col2"> <p>50 </p> </td> 
   <td colname="col3"> <p>150 </p> </td> 
  </tr> 
 </tbody> 
</table>

>[!MORELIKETHIS]
>
>* [Dispositivi sconosciuti](../processes/unknown-device.md#concept-95090d341cdc4c22ba4319d79d8f6e40)

