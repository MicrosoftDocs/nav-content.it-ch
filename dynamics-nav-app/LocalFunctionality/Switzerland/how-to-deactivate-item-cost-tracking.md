---
title: "Come disattivare la tracciabilità dei costi articolo"
description: "Quando le scorte per un articolo non sono tracciate, non è necessario tenere traccia del costo dell'articolo né creare un movimento contabile articolo."
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
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 862a897adfb7bc5e2e4aaf80e54760a558e87a90
ms.contentlocale: it-ch
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-deactivate-item-cost-tracking"></a><span data-ttu-id="9fbea-103">Procedura: Disattivare la tracciabilità dei costi articolo</span><span class="sxs-lookup"><span data-stu-id="9fbea-103">How to: Deactivate Item Cost Tracking</span></span>
<span data-ttu-id="9fbea-104">Quando le scorte per un articolo non sono tracciate, non è necessario tenere traccia del costo dell'articolo né creare un movimento contabile articolo.</span><span class="sxs-lookup"><span data-stu-id="9fbea-104">When inventory is not tracked for an item, the item cost does not need to be tracked, and an item ledger entry does not need to be created.</span></span>  

<span data-ttu-id="9fbea-105">È possibile disattivare la tracciabilità dei costi per un articolo.</span><span class="sxs-lookup"><span data-stu-id="9fbea-105">You can deactivate item cost tracking for an item.</span></span> <span data-ttu-id="9fbea-106">In genere, la tracciabilità dei costi articolo deve essere disattivata per articoli di consumo, ad esempio prodotti di carta riciclata e servizi contati come articoli, quali i costi di parcheggio forfettari.</span><span class="sxs-lookup"><span data-stu-id="9fbea-106">Generally, item cost tracking should be deactivated for consumable items, such as waste paper products and for services that are counted as items, such as flat rate parking fees.</span></span> <span data-ttu-id="9fbea-107">La tracciabilità dei costi articolo deve essere disattivata per gli articoli per cui potrebbe essere fuorviante.</span><span class="sxs-lookup"><span data-stu-id="9fbea-107">Item cost tracking should be deactivated on items for which tracking could be misleading.</span></span> <span data-ttu-id="9fbea-108">Gli articoli per cui la tracciabilità dei costi è stata disattivata sono esclusi dagli impegni, dal controllo di disponibilità, dalla tracciabilità articolo e dai sistemi di pianificazione dei materiali.</span><span class="sxs-lookup"><span data-stu-id="9fbea-108">Items for which item cost tracking has been deactivated are excluded from reservation, availability check, item tracking, and material planning systems.</span></span>  

## <a name="to-deactivate-item-cost-tracking"></a><span data-ttu-id="9fbea-109">Per disattivare la tracciabilità dei costi articolo</span><span class="sxs-lookup"><span data-stu-id="9fbea-109">To deactivate item cost tracking</span></span>  

1.  <span data-ttu-id="9fbea-110">Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "Cerca pagina o report"), immettere **Articoli**, quindi scegliere il collegamento correlato.</span><span class="sxs-lookup"><span data-stu-id="9fbea-110">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Items**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="9fbea-111">Selezionare l'articolo richiesto, quindi scegliere l'azione **Modifica**.</span><span class="sxs-lookup"><span data-stu-id="9fbea-111">Select the required item, and then choose the **Edit** action.</span></span>  
3.  <span data-ttu-id="9fbea-112">Nella Scheda dettaglio **Generale** selezionare la casella di controllo **Nessun stockkeeping**.</span><span class="sxs-lookup"><span data-stu-id="9fbea-112">On the **General** FastTab, select the **No Stockkeeping** check box.</span></span>  

    <span data-ttu-id="9fbea-113">Quando si registra una transazione per questo articolo, non verrà creato alcun movimento contabile.</span><span class="sxs-lookup"><span data-stu-id="9fbea-113">An item ledger entry will not be created when you post a transaction for this item.</span></span> <span data-ttu-id="9fbea-114">Per ulteriori informazioni, vedere la tabella Mov. contabili articoli.</span><span class="sxs-lookup"><span data-stu-id="9fbea-114">For more information, see the Item Ledger Entry table.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="9fbea-115">Non è possibile selezionare la casella di controllo **Nessun stockkeeping** per un articolo per cui i movimenti contabili sono già stati registrati.</span><span class="sxs-lookup"><span data-stu-id="9fbea-115">You cannot select the **No Stockkeeping** check box on an item for which item ledger entries have already been posted.</span></span>  

4.  <span data-ttu-id="9fbea-116">Scegliere il pulsante **OK**.</span><span class="sxs-lookup"><span data-stu-id="9fbea-116">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="9fbea-117">Vedere anche</span><span class="sxs-lookup"><span data-stu-id="9fbea-117">See Also</span></span>  
 <span data-ttu-id="9fbea-118">[Gestione del magazzino per la Svizzera](swiss-inventory-management.md) </span><span class="sxs-lookup"><span data-stu-id="9fbea-118">[Swiss Inventory Management](swiss-inventory-management.md) </span></span>  
 [<span data-ttu-id="9fbea-119">Procedura: Bloccare gli articoli in magazzino per le vendite o gli acquisti</span><span class="sxs-lookup"><span data-stu-id="9fbea-119">How to: Block Inventory Items for Sales or Purchases</span></span>](how-to-block-inventory-items-for-sales-or-purchases.md)

