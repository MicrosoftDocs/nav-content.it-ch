---
title: Come registrare pagamenti LSV+
description: "È possibile registrare pagamenti dopo aver ricevuto l'avviso di pagamento LSV+ (Lastschrift Verfahren) dalla banca."
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
ms.openlocfilehash: 895dedf4b86157dca24b1107495df2047135fd67
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-post-lsv-payments"></a><span data-ttu-id="e3b9b-103">Procedura: Registrare pagamenti LSV+</span><span class="sxs-lookup"><span data-stu-id="e3b9b-103">How to: Post LSV+ Payments</span></span>
<span data-ttu-id="e3b9b-104">È possibile registrare pagamenti dopo aver ricevuto l'avviso di pagamento LSV+ (Lastschrift Verfahren) dalla banca.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-104">You can post payments after you have received Lastschrift Verfahren (LSV+) payment advice from the bank.</span></span>  
  
### <a name="to-post-lsv-payments"></a><span data-ttu-id="e3b9b-105">Registrare pagamenti LSV+</span><span class="sxs-lookup"><span data-stu-id="e3b9b-105">To post LSV+ payments</span></span>  
  
1.  <span data-ttu-id="e3b9b-106">Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni incassi**, quindi scegliere il collegamento correlato.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-106">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cash Receipt Journals**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="e3b9b-107">Selezionare le registrazioni desiderate e nel gruppo **Elabora** della scheda **Pagina iniziale** scegliere **Modifica registrazioni**.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-107">Select the required journal, and on the **Home** tab, in the **Process** group, choose **Edit Journal**.</span></span>  
  
    > [!NOTE]  
    >  <span data-ttu-id="e3b9b-108">È possibile selezionare il batch registrazioni per LSV in cui è definito il conto di contropartita da considerare.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-108">You can select the journal batch for LSV where the balance account you want to address is defined.</span></span> <span data-ttu-id="e3b9b-109">Non è possibile importare più di una riga delle registrazioni LSV nelle stesse registrazioni incassi.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-109">You cannot import more than one LSV journal line into the same cash receipt journal.</span></span> <span data-ttu-id="e3b9b-110">Per ulteriori informazioni, vedere la finestra Registrazioni incassi.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-110">For more information, see the Cash Receipt Journal window.</span></span>  
  
3.  <span data-ttu-id="e3b9b-111">Nel gruppo **Elabora** della scheda **Pagina iniziale** scegliere **Recupera da registrazioni LSV**.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-111">On the **Home** tab, in the **Process** group, choose **Get From LSV Journal**.</span></span>  
  
4.  <span data-ttu-id="e3b9b-112">Nella finestra **Lista registrazioni LSV** selezionare la riga di registrazioni LSV da importare nelle registrazioni incassi.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-112">In the **LSV Journal List** window, select the LSV journal line that you want to import to the cash receipt journal.</span></span>  
  
    > [!NOTE]  
    >  <span data-ttu-id="e3b9b-113">È possibile importare solo righe di registrazioni in cui il campo **Stato LSV** è impostato su **File creato**.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-113">You can only import journal lines where the **LSV Status** field is set to **File Created**.</span></span>  
  
5.  <span data-ttu-id="e3b9b-114">Scegliere il pulsante **OK**.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-114">Choose the **OK** button.</span></span>  
  
     <span data-ttu-id="e3b9b-115">La riga delle registrazioni LSV viene importata nelle registrazioni incassi.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-115">The LSV journal line is imported into the cash receipt journal.</span></span> <span data-ttu-id="e3b9b-116">Il valore del campo **Stato LSV** nella finestra **Lista registrazioni LSV** viene modificato da **File creato** a **Completato**.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-116">The value in the **LSV Status** field in the **LSV Journal List** window changes from **File Created** to **Finished**.</span></span>  
  
     <span data-ttu-id="e3b9b-117">È possibile verificare i pagamenti importati e confrontarli con l'avviso di pagamento bancario nella finestra **Registrazioni incassi**.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-117">You can check the imported payments, and compare them with your bank payment advice in the **Cash Receipt Journal** window.</span></span> <span data-ttu-id="e3b9b-118">È anche possibile eliminare le righe di pagamento che la banca non ha potuto elaborare e per cui è necessario contattare direttamente il cliente.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-118">You can also delete the payment lines that could not be processed by the bank, and for which you must follow up with the customer manually.</span></span>  
  
6.  <span data-ttu-id="e3b9b-119">Nel gruppo **Registrazione** della scheda **Pagina iniziale** scegliere **Registra**.</span><span class="sxs-lookup"><span data-stu-id="e3b9b-119">On the **Home** tab, in the **Posting** group, choose **Post**.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="e3b9b-120">Vedere anche</span><span class="sxs-lookup"><span data-stu-id="e3b9b-120">See Also</span></span>  
 <span data-ttu-id="e3b9b-121">[Pagamenti elettronici svizzeri tramite LSV+](swiss-electronic-payments-using-lsv-.md) </span><span class="sxs-lookup"><span data-stu-id="e3b9b-121">[Swiss Electronic Payments Using LSV+](swiss-electronic-payments-using-lsv-.md) </span></span>  
 <span data-ttu-id="e3b9b-122">[Procedura: Chiudere una riscossione LSV](how-to-process-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="e3b9b-122">[How to: Process an LSV Collection](how-to-process-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="e3b9b-123">[Procedura: Chiudere una riscossione LSV](how-to-close-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="e3b9b-123">[How to: Close an LSV Collection](how-to-close-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="e3b9b-124">[Procedura: Esportare pagamenti tramite LSV](how-to-export-payments-using-lsv.md) </span><span class="sxs-lookup"><span data-stu-id="e3b9b-124">[How to: Export Payments Using LSV](how-to-export-payments-using-lsv.md) </span></span>  
 <span data-ttu-id="e3b9b-125">Registrazioni incassi</span><span class="sxs-lookup"><span data-stu-id="e3b9b-125">Cash Receipt Journal</span></span>   
 <span data-ttu-id="e3b9b-126">Registro LSV</span><span class="sxs-lookup"><span data-stu-id="e3b9b-126">LSV Journal</span></span>   
 <span data-ttu-id="e3b9b-127">Riga registrazione LSV</span><span class="sxs-lookup"><span data-stu-id="e3b9b-127">LSV Journal Line</span></span>
