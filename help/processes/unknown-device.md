---
description: Quando una persona dispone di dispositivi non utilizzati per interagire con il brand, tali dispositivi vengono chiamati dispositivi sconosciuti.
seo-description: When a person has devices that are not used to interact with your brand, those devices are called unknown devices.
seo-title: Unknown devices
title: Dispositivi sconosciuti
uuid: 18e69dad-bdb3-4ac1-a690-374aba1aa0a6
exl-id: 7841bf32-7327-4981-86a2-600e2bfe5901
source-git-commit: 573744525fcc00f35540af9ffec46530111940ed
workflow-type: tm+mt
source-wordcount: '227'
ht-degree: 0%

---

# Dispositivi sconosciuti{#unknown-devices}

Quando una persona dispone di dispositivi non utilizzati per interagire con il brand, tali dispositivi vengono chiamati dispositivi sconosciuti.

## Categorie di dispositivi sconosciute {#section-014b83fd0f2e4d50aa19dd9fbb46f6ab}

Esistono diversi modi o categorie in base alle quali un dispositivo può essere considerato &quot;sconosciuto&quot;. Comprendono:

* **Visite di prime parti ad altri membri di Device Co-op:** Visite ad altri [!DNL Device Co-op] siti membri o pubblicità su un dispositivo non rende, di per sé, un dispositivo noto al tuo marchio.

* **Inventario annunci non tracciati:** L’inventario pubblicitario disponibile, ma non ancora servito o acquisito, non rende noto un dispositivo al tuo marchio.
* **Rinuncia del consumatore:** Per rispettare il desiderio dei consumatori, i dispositivi che hanno rinunciato non sono considerati dispositivi noti.

A differenza dei dispositivi noti, i dispositivi sconosciuti non sono collegati ad altri dispositivi o associati a singoli utenti.

## Regole per l&#39;impostazione dello stato noto/sconosciuto {#section-fa5c85e59e2d4f88bb79f27f17f02344}

Il [!DNL Device Graph] tenta di essere il più inclusivo possibile durante la classificazione dei dispositivi come noti rispetto a sconosciuti. Le regole che aiutano a determinare lo stato conosciuto/sconosciuto lavorano in ordine di priorità (1 è il più alto) come mostrato di seguito:

* **Regola 1:** Il dispositivo è escluso? In caso affermativo, il dispositivo è sconosciuto.
* **Regola 2:** Il dispositivo è noto a *qualsiasi* metodo? In caso affermativo, il dispositivo è noto.

* **Regola 3: ** se il precedente non si applica, il dispositivo è sconosciuto.

>[!MORELIKETHIS]
>
>* [Dispositivi noti](../processes/known-device.md#concept-8e87c276819a48bfac5cef10b45216d1)

