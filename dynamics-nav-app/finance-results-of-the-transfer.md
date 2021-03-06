---
title: Risultati del trasferimento
description: Questo argomento descrive i risultati del trasferimento di movimenti C/G a movimenti di costo.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: general ledger, transfer, cost entries
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 05da79520b5568a8b8e63f10efce9c8b3c5395b8
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="results-of-transferring-general-ledger-entries-to-cost-entries"></a>Risultati del trasferimento di movimenti C/G a movimenti di costi
Durante il trasferimento dei movimenti C/G ai movimenti di costo, in [!INCLUDE[d365fin](includes/d365fin_md.md)] vengono creati i collegamenti nei movimenti nelle tabelle **Movimento CG**, **Movimento di costo** e **Registro costi** per consentire di tenere traccia dei collegamenti tra i movimenti di costo e i movimenti C/G.  

## <a name="general-ledger-entries"></a>Movimenti C/G  
Per ogni movimento C/G che viene trasferito alla contabilità industriale, in [!INCLUDE[d365fin](includes/d365fin_md.md)] viene compilato il campo **Nr. movimento** dei costi.  

## <a name="cost-entries"></a>Movimenti di costi  
Per ogni movimento di costo, [!INCLUDE[d365fin](includes/d365fin_md.md)] salva il numero del movimento C/G corrispondente nel campo **Nr. movimento C/G** della tabella **Movimento di costo**.  

Per i movimenti di costi combinati, in [!INCLUDE[d365fin](includes/d365fin_md.md)] viene salvato il numero dell'ultimo movimento C/G, vale a dire il movimento con il numero più alto.  

Nel campo **Conto C/G** della tabella **Movimento di costo** è contenuto il numero del conto di contabilità generale da cui deriva il movimento di costo.  

Per i singoli movimenti di costo, in [!INCLUDE[d365fin](includes/d365fin_md.md)] viene trasferito il testo della registrazione dal movimento C/G al campo di testo **Descrizione**. Per i movimenti combinati, il campo di testo mostra che questi movimenti vengono trasferiti come movimenti combinati. Ad esempio, per un movimento combinato per il mese di ottobre 2013, il testo può essere **Movimenti combinati, ottobre 2013**.  

## <a name="cost-register"></a>Registro costi  
Nella tabella **Registro costi**, [!INCLUDE[d365fin](includes/d365fin_md.md)] crea un movimento con il trasferimento di origine dalla contabilità generale. Il movimento registra il primo e l'ultimo numero dei movimenti C/G trasferiti, oltre al primo e all'ultimo numero dei movimenti di costo creati.  

## <a name="see-also"></a>Vedi anche  
[Procedura: Trasferire movimenti C/G ai movimenti di costi](finance-how-to-transfer-general-ledger-entries-to-cost-entries.md)   
[Criteri per trasferire movimenti C/G ai movimenti di costi](finance-criteria-for-transferring-general-ledger-entries-to-cost-entries.md)   
[Trasferimento automatico e movimenti combinati](finance-automatic-transfer-combined-entries.md)   
[Trasferimento e registrazione di movimenti di costi](finance-transfer-and-post-cost-entries.md)  

