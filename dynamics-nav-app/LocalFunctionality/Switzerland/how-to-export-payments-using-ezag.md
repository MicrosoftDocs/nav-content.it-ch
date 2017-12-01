---
title: Come esportare pagamenti tramite EZAG
description: "È possibile generare un file per il pagamento elettronico tramite il metodo EZAG (Elektronischer Zahlungsauftrag) ed esportarlo alla banca per essere usato per i pagamenti."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 856a98e6c4d0f8820fa993deac3d44898f9420b3
ms.contentlocale: it-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-export-payments-using-ezag"></a>Procedura: Esportare pagamenti tramite EZAG
È possibile generare un file per il pagamento elettronico tramite il metodo EZAG (Elektronischer Zahlungsauftrag) ed esportarlo alla banca per essere usato per i pagamenti.  

## <a name="to-export-payments-using-ezag"></a>Per esportare pagamenti tramite EZAG  

1.  Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni pagamenti**, quindi scegliere il collegamento correlato.  
2.  Nel campo **Nome batch** selezionare il nome batch registrazioni desiderato.  
3.  Scegliere l'azione **Genera file EZAG**.  
4.  Nel processo batch **File EZAG**, nella Scheda dettaglio **Opzioni** compilare i campi come descritto nella tabella seguente.  

    |Campo|Descrizione|  
    |---------------------------------|---------------------------------------|  
    |**Banca di addebito**|Specifica il codice della banca da addebitare.|  
    |**Pagamento unico per fornitore**|Specifica se le righe di pagamento con lo stesso fornitore, valuta, banca e banca di addebito nel file EZAG generato verranno combinate.|  
    |**Spedizione con disco**|Specifica se il file EZAG verrà salvato su un disco per essere consegnato alla banca.|  

5.  Scegliere il pulsante **OK**. Il file EZAG viene generato.  

## <a name="see-also"></a>Vedere anche  
 [Pagamenti elettronici svizzeri tramite DTA](swiss-electronic-payments-using-dta.md)   
 [Procedura: Suggerire pagamenti DTA ai fornitori](how-to-suggest-dta-payment-for-vendors.md)   
 [Procedura: Verificare una lista di fornitori per pagamenti DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md)   
 [Procedura: Inviare pagamenti DTA](how-to-submit-dta-payments.md) 

