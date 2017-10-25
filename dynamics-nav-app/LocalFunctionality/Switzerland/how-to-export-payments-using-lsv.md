---
title: Come esportare pagamenti tramite LSV
description: "È possibile esportare o creare file LSV+ (Lastschrift Verfahren) che contengono informazioni sui pagamenti dopo aver chiuso la riscossione LSV. È possibile inviare i file generati alla banca su un disco oppure usare un trasferimento file elettronico, ad esempio tramite il servizio di online banking o tramite un portale Internet."
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
ms.openlocfilehash: b71163a277189dfecdd408c1fbbb1a9883862407
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-export-payments-using-lsv"></a><span data-ttu-id="c5c18-104">Procedura: Esportare pagamenti tramite LSV</span><span class="sxs-lookup"><span data-stu-id="c5c18-104">How to: Export Payments Using LSV</span></span>
<span data-ttu-id="c5c18-105">È possibile esportare o creare file LSV+ (Lastschrift Verfahren) che contengono informazioni sui pagamenti dopo aver chiuso la riscossione LSV.</span><span class="sxs-lookup"><span data-stu-id="c5c18-105">You can export or write Lastschrift Verfahren (LSV+) files that contain payments information after closing the LSV collection.</span></span> <span data-ttu-id="c5c18-106">È possibile inviare i file generati alla banca su un disco oppure usare un trasferimento file elettronico, ad esempio tramite il servizio di online banking o tramite un portale Internet.</span><span class="sxs-lookup"><span data-stu-id="c5c18-106">You can send the generated files to the bank on a disk, or use an electronic file transfer such as your online banking software or an Internet portal.</span></span>  
  
### <a name="to-export-payments-using-lsv"></a><span data-ttu-id="c5c18-107">Per esportare pagamenti tramite LSV</span><span class="sxs-lookup"><span data-stu-id="c5c18-107">To export payments using LSV</span></span>  
  
1.  <span data-ttu-id="c5c18-108">Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Lista registrazioni LSV**, quindi scegliere il collegamento correlato.</span><span class="sxs-lookup"><span data-stu-id="c5c18-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **LSV Journal List**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="c5c18-109">Nella finestra **Lista registrazioni LSV** selezionare le registrazioni LSV desiderate.</span><span class="sxs-lookup"><span data-stu-id="c5c18-109">In the **LSV Journal List** window, select the required LSV journal.</span></span>  
  
3.  <span data-ttu-id="c5c18-110">Nel gruppo **Funzioni** della scheda **Azioni** scegliere **Scrivi file LSV**.</span><span class="sxs-lookup"><span data-stu-id="c5c18-110">On the **Actions** tab, in the **Functions** group, select **Write LSV File**.</span></span>  
  
4.  <span data-ttu-id="c5c18-111">Nella finestra **Scrivi file LSV**, nella Scheda dettaglio **Opzioni** compilare i campi come descritto nella tabella seguente.</span><span class="sxs-lookup"><span data-stu-id="c5c18-111">In the **Write LSV File** window, on the **Options** FastTab, fill in the fields as described in the following table.</span></span>  
  
    |<span data-ttu-id="c5c18-112">Campo</span><span class="sxs-lookup"><span data-stu-id="c5c18-112">Field</span></span>|<span data-ttu-id="c5c18-113">Descrizione</span><span class="sxs-lookup"><span data-stu-id="c5c18-113">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="c5c18-114">**Nr.**</span><span class="sxs-lookup"><span data-stu-id="c5c18-114">**No.**</span></span>|<span data-ttu-id="c5c18-115">Specifica il numero di registrazioni LSV da esportare.</span><span class="sxs-lookup"><span data-stu-id="c5c18-115">Specify the LSV journal number that you want to export.</span></span>|  
    |<span data-ttu-id="c5c18-116">**Test**</span><span class="sxs-lookup"><span data-stu-id="c5c18-116">**Test**</span></span>|<span data-ttu-id="c5c18-117">Specifica se si inviano consegne di prova alla banca.</span><span class="sxs-lookup"><span data-stu-id="c5c18-117">Specify if you are sending test deliveries to your bank.</span></span> <span data-ttu-id="c5c18-118">La banca non elabora file di test.</span><span class="sxs-lookup"><span data-stu-id="c5c18-118">The bank does not process test files.</span></span>|  
  
5.  <span data-ttu-id="c5c18-119">Tutte le righe correlate vengono trasferite alle registrazioni LSV.</span><span class="sxs-lookup"><span data-stu-id="c5c18-119">All related lines are transferred to the LSV journal.</span></span> <span data-ttu-id="c5c18-120">Il file LSV viene generato nella cartella determinata in precedenza.</span><span class="sxs-lookup"><span data-stu-id="c5c18-120">The LSV file is generated in the predetermined folder.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="c5c18-121">Vedere anche</span><span class="sxs-lookup"><span data-stu-id="c5c18-121">See Also</span></span>  
 <span data-ttu-id="c5c18-122">[Pagamenti elettronici svizzeri tramite LSV+](swiss-electronic-payments-using-lsv-.md) </span><span class="sxs-lookup"><span data-stu-id="c5c18-122">[Swiss Electronic Payments Using LSV+](swiss-electronic-payments-using-lsv-.md) </span></span>  
 <span data-ttu-id="c5c18-123">[Procedura: Chiudere una riscossione LSV](how-to-process-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="c5c18-123">[How to: Process an LSV Collection](how-to-process-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="c5c18-124">[Procedura: Chiudere una riscossione LSV](how-to-close-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="c5c18-124">[How to: Close an LSV Collection](how-to-close-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="c5c18-125">[Procedura: Registrare pagamenti LSV+](how-to-post-lsv-payments.md) </span><span class="sxs-lookup"><span data-stu-id="c5c18-125">[How to: Post LSV+ Payments](how-to-post-lsv-payments.md) </span></span>  
 <span data-ttu-id="c5c18-126">Registro LSV</span><span class="sxs-lookup"><span data-stu-id="c5c18-126">LSV Journal</span></span>   
 <span data-ttu-id="c5c18-127">Riga registrazione LSV</span><span class="sxs-lookup"><span data-stu-id="c5c18-127">LSV Journal Line</span></span>   
 <span data-ttu-id="c5c18-128">Setup LSV</span><span class="sxs-lookup"><span data-stu-id="c5c18-128">LSV Setup</span></span>
