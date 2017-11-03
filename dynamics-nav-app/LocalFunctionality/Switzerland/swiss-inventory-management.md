---
title: Gestione del magazzino per la Svizzera
description: I miglioramenti svizzeri includono funzioni speciali di gestione magazzino.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 98e1c1dd52127710cedf3c849eee0fffc876e02b
ms.contentlocale: it-ch
ms.lasthandoff: 10/26/2017

---
# <a name="swiss-inventory-management"></a>Gestione del magazzino per la Svizzera
[!INCLUDE[navnow](../../includes/navnow_md.md)] include i miglioramenti svizzeri per la gestione magazzino. È incluso quanto segue:  

- Dichiarazione dettagliata.  Per ulteriori informazioni vedere il report Magazzino - Statistiche di vendita e il report Magazzino - Lista.  
- La capacità di monitorare una fattura con più spedizioni.  
- L'inclusione di un codice ubicazione scheda articolo come il codice ubicazione predefinito per le righe di vendita e le registrazioni articoli. Per ulteriori informazioni, vedere [Procedura: Impostare le ubicazioni](../../inventory-how-setup-locations.md). 

## <a name="managing-item-details"></a>Gestione dettagli articolo  
Le aziende possono disporre di magazzini diversi per categorie di prodotti diversi. In questi casi, è necessario utilizzare il codice ubicazione predefinito recuperato dalla scheda articolo. Quando si definisce un codice ubicazione per un articolo, questo viene trasferito nelle righe di vendita e nelle registrazioni articoli come codice di ubicazione articoli predefinito. Per ulteriori informazioni, vedere le tabelle Righe vendite e Righe reg. magazzino.  

È possibile fornire la descrizione di un articolo con un massimo di 50 caratteri e un numero di tariffa con un massimo di 15 caratteri. Per ulteriori informazioni, vedere la finestra Scheda articolo.  

Ulteriori informazioni, come il numero cliente, il codice dell'indirizzo di spedizione e il codice venditore del cliente, vengono memorizzate nei movimenti contabili articoli. Queste informazioni consentono di creare criteri di dichiarazione personalizzati, come i ricavi per cliente e gli accantonamenti per articoli o vendite per i venditori. Per ulteriori informazioni, vedere la tabella Mov. contabili articoli.  

## <a name="invoices-with-multiple-shipments"></a>Fatture con più spedizioni  
Se sono state registrate più spedizioni per un cliente, è possibile creare una fattura combinata con la funzione **Prendi righe di spedizione**. Per ulteriori informazioni, vedere la finestra Prendi righe di spedizione. Quando si utilizza questa funzione, il testo creato nelle righe della fattura include informazioni sul numero di spedizione e sulla data di spedizione. Ad esempio, il testo potrebbe essere Nr. spedizione 102040 di 25.01.01. Ciò consente di tracciare facilmente le fatture con più spedizioni.  

## <a name="see-also"></a>Vedere anche  
 [Procedura: Bloccare la spedizione per le giacenze negative](how-to-block-shipment-for-negative-inventory.md)   
 [Procedura: Bloccare gli articoli in magazzino per le vendite o gli acquisti](how-to-block-inventory-items-for-sales-or-purchases.md)   
 [Procedura: Copiare articoli esistenti in nuovi articoli](how-to-copy-existing-items-to-new-items.md)   
 [Procedura: Disattivare la tracciabilità dei costi articolo](how-to-deactivate-item-cost-tracking.md)   
 [Funzionalità locale per la Svizzera](switzerland-local-functionality.md)   
 [Procedura: Impostare le ubicazioni](../../inventory-how-setup-locations.md)

