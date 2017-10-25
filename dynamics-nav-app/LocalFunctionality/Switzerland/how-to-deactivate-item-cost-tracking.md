---
title: "Come disattivare la tracciabilità dei costi articolo"
description: "Quando le scorte per un articolo non sono tracciate, non è necessario tenere traccia del costo dell'articolo né creare un movimento contabile articolo."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: c2043fe4506ba4baf1b76509f73d2ee99c7dba8c
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-deactivate-item-cost-tracking"></a><span data-ttu-id="ebe38-103">Procedura: Disattivare la tracciabilità dei costi articolo</span><span class="sxs-lookup"><span data-stu-id="ebe38-103">How to: Deactivate Item Cost Tracking</span></span>
<span data-ttu-id="ebe38-104">Quando le scorte per un articolo non sono tracciate, non è necessario tenere traccia del costo dell'articolo né creare un movimento contabile articolo.</span><span class="sxs-lookup"><span data-stu-id="ebe38-104">When inventory is not tracked for an item, the item cost does not need to be tracked, and an item ledger entry does not need to be created.</span></span>  
  
 <span data-ttu-id="ebe38-105">È possibile disattivare la tracciabilità dei costi per un articolo.</span><span class="sxs-lookup"><span data-stu-id="ebe38-105">You can deactivate item cost tracking for an item.</span></span> <span data-ttu-id="ebe38-106">In genere, la tracciabilità dei costi articolo deve essere disattivata per articoli di consumo, ad esempio prodotti di carta riciclata e servizi contati come articoli, quali i costi di parcheggio forfettari.</span><span class="sxs-lookup"><span data-stu-id="ebe38-106">Generally, item cost tracking should be deactivated for consumable items, such as waste paper products and for services that are counted as items, such as flat rate parking fees.</span></span> <span data-ttu-id="ebe38-107">La tracciabilità dei costi articolo deve essere disattivata per gli articoli per cui potrebbe essere fuorviante.</span><span class="sxs-lookup"><span data-stu-id="ebe38-107">Item cost tracking should be deactivated on items for which tracking could be misleading.</span></span> <span data-ttu-id="ebe38-108">Gli articoli per cui la tracciabilità dei costi è stata disattivata sono esclusi dagli impegni, dal controllo di disponibilità, dalla tracciabilità articolo e dai sistemi di pianificazione dei materiali.</span><span class="sxs-lookup"><span data-stu-id="ebe38-108">Items for which item cost tracking has been deactivated are excluded from reservation, availability check, item tracking, and material planning systems.</span></span>  
  
### <a name="to-deactivate-item-cost-tracking"></a><span data-ttu-id="ebe38-109">Per disattivare la tracciabilità dei costi articolo</span><span class="sxs-lookup"><span data-stu-id="ebe38-109">To deactivate item cost tracking</span></span>  
  
1.  <span data-ttu-id="ebe38-110">Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Articoli**, quindi scegliere il collegamento correlato.</span><span class="sxs-lookup"><span data-stu-id="ebe38-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Items**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="ebe38-111">Selezionare l'articolo desiderato e nel gruppo **Gestisci** della scheda **Pagina iniziale** scegliere **Modifica**.</span><span class="sxs-lookup"><span data-stu-id="ebe38-111">Select the required item, and on the **Home** tab, in the **Manage** group, choose **Edit**.</span></span>  
  
3.  <span data-ttu-id="ebe38-112">Nella Scheda dettaglio **Generale** selezionare la casella di controllo **Nessun stockkeeping**.</span><span class="sxs-lookup"><span data-stu-id="ebe38-112">On the **General** FastTab, select the **No Stockkeeping** check box.</span></span>  
  
     <span data-ttu-id="ebe38-113">Quando si registra una transazione per questo articolo, non verrà creato alcun movimento contabile.</span><span class="sxs-lookup"><span data-stu-id="ebe38-113">An item ledger entry will not be created when you post a transaction for this item.</span></span> <span data-ttu-id="ebe38-114">Per ulteriori informazioni, vedere la tabella Mov. contabili articoli.</span><span class="sxs-lookup"><span data-stu-id="ebe38-114">For more information, see the Item Ledger Entry table.</span></span>  
  
    > [!NOTE]  
    >  <span data-ttu-id="ebe38-115">Non è possibile selezionare la casella di controllo **Nessun stockkeeping** per un articolo per cui i movimenti contabili sono già stati registrati.</span><span class="sxs-lookup"><span data-stu-id="ebe38-115">You cannot select the **No Stockkeeping** check box on an item for which item ledger entries have already been posted.</span></span>  
  
4.  <span data-ttu-id="ebe38-116">Scegliere il pulsante **OK**.</span><span class="sxs-lookup"><span data-stu-id="ebe38-116">Choose the **OK** button.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="ebe38-117">Vedere anche</span><span class="sxs-lookup"><span data-stu-id="ebe38-117">See Also</span></span>  
 <span data-ttu-id="ebe38-118">Articolo</span><span class="sxs-lookup"><span data-stu-id="ebe38-118">Item</span></span>   
 <span data-ttu-id="ebe38-119">Mov. contabili articoli</span><span class="sxs-lookup"><span data-stu-id="ebe38-119">Item Ledger Entry</span></span>   
 <span data-ttu-id="ebe38-120">[Gestione del magazzino per la Svizzera](swiss-inventory-management.md) </span><span class="sxs-lookup"><span data-stu-id="ebe38-120">[Swiss Inventory Management](swiss-inventory-management.md) </span></span>  
 [<span data-ttu-id="ebe38-121">Procedura: Bloccare gli articoli in magazzino per le vendite o gli acquisti</span><span class="sxs-lookup"><span data-stu-id="ebe38-121">How to: Block Inventory Items for Sales or Purchases</span></span>](how-to-block-inventory-items-for-sales-or-purchases.md)
