---
title: Come registrare il consumo tramite processo batch
description: "Se il metodo di consuntivazione è **Manuale**, i componenti devono essere registrati manualmente nelle registrazioni consumi."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: bd4cedaf3fdb2d0f5627120836580fc82f4befa3
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-batch-post-production-consumption"></a>Procedura: Registrare il consumo produzione tramite processo batch
Se il metodo di consuntivazione è **Manuale**, i componenti devono essere registrati manualmente nelle registrazioni consumi.

È inoltre possibile impostare il sistema sulla registrazione (*consuntivazione*) automatica dei componenti quando si avviano o si chiudono ordini di produzione. Per ulteriori informazioni vedere [Attivare la consuntivazione dei componenti in base all'output dell'operazione](production-how-to-flush-components-according-to-operation-output.md).

## <a name="to-post-consumption-for-one-or-more-production-order-lines"></a>Per registrare il consumo per una o più righe dell'ordine di produzione  
1.  Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni consumi**, quindi scegliere il collegamento correlato.  
2.  Compilare i campi inserendo i dati relativi agli ordini di produzione e al consumo. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  

    Se l'ubicazione della warehouse in cui sono immagazzinati i componenti prevede l'utilizzo di collocazioni, ma non richiede l'elaborazione dei prelievi, assegnare un codice collocazione alla riga delle registrazioni per indicare da dove dovranno essere prelevati gli articoli nella warehouse. Per ulteriori informazioni, vedere [Procedura: Prelevare per la produzione o l'assemblaggio](warehouse-how-to-pick-for-production.md).  
3.  Per registrare il consumo scegliere l'azione **Registra**. I movimenti articolo collegati vengono ridotti.

## <a name="see-also"></a>Vedi anche  
[Manufacturing](production-manage-manufacturing.md)    
[Impostazione della produzione](production-configure-production-processes.md)  
[Pianif.](production-planning.md)      
[Magazzino](inventory-manage-inventory.md)  
[Acquisti](purchasing-manage-purchasing.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

