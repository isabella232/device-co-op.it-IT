---
description: Informazioni sui dispositivi noti in Device Graph.
seo-description: Informazioni sui dispositivi noti in Device Graph.
seo-title: Dispositivi noti
title: Dispositivi noti
uuid: 53c21105-45b1-4bed-a473-d3ccc4bae965
translation-type: tm+mt
source-git-commit: 4f972a4ae3f0c5ee11b21876bd8a6966cad90371

---


# Known devices{#known-devices}

Informazioni sui dispositivi noti in Device Graph.

In Device Graph, esiste il concetto di *`known device`*. Un dispositivo noto è un dispositivo utilizzato da un consumatore per interagire con il tuo marchio.

>[!NOTE]
>
>In termini [!DNL Adobe Experience Cloud Device Co-op]come *`device`*, *`person`*, *`identity`* ecc. hanno significati specifici. Ad esempio, &quot;dispositivo&quot; può fare riferimento ad hardware fisico come un telefono o un tablet e alle applicazioni in esecuzione su tale hardware. Consulta il [glossario](../glossary.md#glossgroup-0f47d7fbd76c4759801f565f341a386c) per le definizioni.

## Supporting goals with the known device {#section-80deae33660e4280ac65c659ceff5601}

Il concetto di dispositivo noto supporta alcuni obiettivi essenziali per la creazione e la manutenzione di un programma [!DNL Device Co-op] efficiente. Un dispositivo noto è quello conosciuto da un membro di [!DNL Device Co-op] grazie all&#39;interazione con un consumatore (ad es. una visita al sito o l&#39;utilizzo di un&#39;app mobile). Based on these actions, the [!DNL Device Graph] links the known devices of a [!DNL Device Co-op] member to devices contributed by other [!DNL Device Co-op] members. Questi collegamenti possono essere [deterministici o probabilistici](../processes/links.md#concept-58bb7ab25f904f5f98d645e35205c931). This benefits [!DNL Device Co-op] members because they receive:

* Più dati sui loro dispositivi noti.
* Nuove informazioni su altri dispositivi collegati.

![](assets/known-device.png)

[!DNL Device Graph] non fornirà informazioni su cluster di dispositivi che un membro di Device Co-op non ha visto.

## Device Co-op goals {#section-75aea5a102d54733aae2a7c6ee9ec6c7}

Three main goals animate the [!DNL Device Co-op]. Questi includono:

* **Scala:** condividere il numero massimo di collegamenti possibile tra svariati casi di utilizzo.
* **Equità:** garantire che ogni membro di [!DNL Device Co-op] tragga vantaggio in modo commisurato ai suoi contributi.

* **Fiducia del consumatore:** mantenere e creare la fiducia del consumatore garantendogli un&#39;esperienza cross-device che coinvolga i marchi a lui noti e di cui si fida già.

## Scale and the known device {#section-67f734109762457ca62ec306284ea082}

I seguenti metodi sono i modi più comuni in cui un dispositivo si qualifica come dispositivo noto. Dati questi metodi, i membri di [!DNL Device Co-op] avranno praticamente sempre almeno 1 dispositivo noto. Ciò supporta l&#39;obiettivo di fornire una scala massima a tutti i membri di [!DNL Device Co-op].

**Naturale**

* Da una visita del cliente al tuo sito o tramite l&#39;utilizzo della tua app. Questa è la qualifica da dati proprietari.
* Tramite la registrazione di clienti da un sistema di CRM.

**Marketplace**

* Tramite l&#39;acquisto di dati di segmento da Audience Marketplace.
* Tramite l&#39;acquisto di dati da un provider di dati di terze parti.

**Pubblicità**

Tramite la vincita di dati di inventario a un&#39;asta e la distribuzione di un annuncio su un dispositivo. Il dispositivo diventa noto se l&#39;annuncio contiene un pixel [!DNL Audience Manager].

## Known devices and fairness use cases {#section-0543188729d845d6b95db70b8b25e9f8}

Members of the [!DNL Device Co-op] get links commensurate with their contributions to the [!DNL Device Graph]. Le società che offrono molti dispositivi a [!DNL Device Graph] ricevono più collegamenti rispetto ai membri che contribuiscono meno. Crediamo che in questo modo [!DNL Device Co-op] sia più equo per tutti i membri. Diamo un&#39;occhiata a come funziona nei casi di utilizzo di grandi e piccole dimensioni descritti di seguito.

**Marchio A: caso di utilizzo ampio**

In questo esempio, il marchio A ha 100 visitatori al mese sul proprio sito e avvia una nuova campagna di marchio cross-device. For simplicity, assume the [!DNL Device Graph] knows all of the visitors to Brand A are linked to 1 additional device. Ciò significa che il marchio A potrebbe raggiungere altri 100 dispositivi. Additionally, the [!DNL Device Graph] contains about 200 devices linked together.

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

**Marchio B: caso di utilizzo piccolo**

In questo esempio, il marchio B ha 100 visitatori del sito ogni mese e avvia una nuova campagna di marchio cross-device. For simplicity, assume the [!DNL Device Graph] knows all of the visitors to Brand B are linked to 50 additional devices. Ciò significa che il marchio B può raggiungere 150 dispositivi. Additionally, the [!DNL Device Graph] contains about 1,000 devices linked together.

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

