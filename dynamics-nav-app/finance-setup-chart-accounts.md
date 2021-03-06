---
title: Impostazione del piano dei conti
description: "È possibile modificare i conti predefiniti nel piano dei conti ed è possibile aggiungere nuovi conti."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: COA, cha of acc
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: b9ed31ae8e7478f57457ad68fd69d7809f706e2a
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="setting-up-or-changing-the-chart-of-accounts"></a>Impostazione o modifica del piano dei conti
Il piano dei conti mostra i conti di contabilità che memorizzano i dati finanziari. [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)] include un piano dei conti standard pronto per supportare l'azienda.
Tuttavia, è possibile modificare i conti predefiniti ed è possibile aggiungere nuovi conti.  

## <a name="adding-or-changing-accounts"></a>Aggiungere o modificare i conti
Nel piano dei conti, è possibile aprire ogni conto C/G e aggiungere o modificare le impostazioni.

> [!NOTE]  
>   È possibile eliminare un conto di contabilità generale. Tuttavia, prima che venga eliminato, è necessario soddisfare le seguenti condizioni:  

* Il saldo nel conto deve essere pari a zero.  
* Nel campo **Consenti Eliminaz. Conti C/G Anteriori a** della finestra **Setup Contabilità Generale** deve essere impostata una data ed è necessario che il conto non includa movimenti contabili in tale data o dopo tale data.  
* Se il campo **Verifica Uso Conti C/G** della finestra **Setup Contabilità Generale** è selezionato, il conto non deve essere utilizzato in tutte le categorie di registrazione o impostazioni delle registrazioni.  

[!INCLUDE[d365fin](includes/d365fin_md.md)] impedirà di eliminare un conto di contabilità generale che memorizza i dati necessari per il piano dei conti.  

## <a name="see-also"></a>Vedi anche
[Contabilità generale e piano dei conti](finance-general-ledger.md)  
[Gestione di conti correnti bancari](bank-manage-bank-accounts.md)  
[Utilizzo delle dimensioni](finance-dimensions.md)  
[Importazione dei dati da altri sistemi contabili](upload-data.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

## 

