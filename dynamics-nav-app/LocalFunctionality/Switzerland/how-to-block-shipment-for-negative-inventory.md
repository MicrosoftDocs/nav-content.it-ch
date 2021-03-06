---
title: Come bloccare la spedizione per le giacenze negative
description: "È possibile bloccare la spedizione in uscita per un articolo quando una transazione restituisce come risultato una giacenza negativa per tale articolo."
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
ms.openlocfilehash: 8687c40202ad90e95753ceae09818160ed1ed663
ms.contentlocale: it-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-block-shipment-for-negative-inventory"></a>Procedura: Bloccare la spedizione per le giacenze negative
È possibile bloccare la spedizione in uscita per un articolo quando una transazione restituisce come risultato una giacenza negativa per tale articolo.  

## <a name="to-block-shipment-for-negative-inventory"></a>Per bloccare la spedizione per le giacenze negative  

1.  Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Setup contabilità clienti e vendite**, quindi scegliere il collegamento correlato.  
2.  Nella Scheda dettaglio **Generale** della finestra **Setup contabilità clienti e vendite** selezionare la casella di controllo **Blocca spedizione se giacenza negativa** .  

    Se questa casella di controllo è selezionata, le giacenze per tutti gli articoli vengono calcolate quando si registra una spedizione di vendita. Se la transazione determina una quantità negativa in magazzino per un articolo, viene visualizzato un messaggio di errore.  

3.  Scegliere il pulsante **OK**.  

## <a name="see-also"></a>Vedere anche  
[Setup Vendite](../../sales-setup-sales.md)

