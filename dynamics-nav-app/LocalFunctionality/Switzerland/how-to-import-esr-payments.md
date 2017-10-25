---
title: Come importare pagamenti PVR
description: "Dopo aver ricevuto un pagamento da un cliente, si riceve un file che contiene informazioni sulle fatture pagate. È possibile ricevere questo file dalla banca in formato elettronico oppure tramite e-mail."
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
ms.openlocfilehash: 4cb9cb52eb3c7859b8da44e2743652e140c2d567
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-import-esr-payments"></a><span data-ttu-id="7f496-104">Procedura: Importare pagamenti PVR</span><span class="sxs-lookup"><span data-stu-id="7f496-104">How to: Import ESR Payments</span></span>
<span data-ttu-id="7f496-105">Dopo aver ricevuto un pagamento da un cliente, si riceve un file che contiene informazioni sulle fatture pagate.</span><span class="sxs-lookup"><span data-stu-id="7f496-105">After you receive payment from a customer, you receive a file that contains information about paid invoices.</span></span> <span data-ttu-id="7f496-106">È possibile ricevere questo file dalla banca in formato elettronico oppure tramite e-mail.</span><span class="sxs-lookup"><span data-stu-id="7f496-106">You can receive this file from your bank electronically, or by mail.</span></span>  
  
 <span data-ttu-id="7f496-107">È possibile importare dati di fattura PVR (polizza di versamento con numero di riferimento, in tedesco ESR, Einzahlungsschein mit Referenznummer) dal file, stampare i dati tramite il report PVR della fattura di vendita o tramite il report di tagliandi PVR di vendita ed eseguire la verifica prima della registrazione.</span><span class="sxs-lookup"><span data-stu-id="7f496-107">You can import the Einzahlungsschein mit Referenznummer (ESR) invoice data from the file, print the data by using the sales invoice ESR report or the sales ESR coupon report, and verify before posting.</span></span> <span data-ttu-id="7f496-108">Per ulteriori informazioni, vedere [Procedura: Stampare fatture PVR](how-to-print-esr-invoices.md).</span><span class="sxs-lookup"><span data-stu-id="7f496-108">For more information, see [How to: Print ESR Invoices](how-to-print-esr-invoices.md).</span></span>  
  
### <a name="to-import-esr-payments"></a><span data-ttu-id="7f496-109">Per importare pagamenti PVR</span><span class="sxs-lookup"><span data-stu-id="7f496-109">To import ESR payments</span></span>  
  
1.  <span data-ttu-id="7f496-110">Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni incassi**, quindi scegliere il collegamento correlato.</span><span class="sxs-lookup"><span data-stu-id="7f496-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Cash Receipt Journals**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="7f496-111">Nel campo **Nome batch** selezionare il batch contabile necessario.</span><span class="sxs-lookup"><span data-stu-id="7f496-111">In the **Batch Name** field, select the required journal batch.</span></span>  
  
    > [!NOTE]  
    >  <span data-ttu-id="7f496-112">Prima di importare il file PVR, è necessario che le registrazioni siano vuote.</span><span class="sxs-lookup"><span data-stu-id="7f496-112">The journal must be empty before you import the ESR file.</span></span> <span data-ttu-id="7f496-113">Non è possibile importare più di un file PVR nelle stesse registrazioni incassi.</span><span class="sxs-lookup"><span data-stu-id="7f496-113">You cannot import more than one ESR file into the same cash receipt journal.</span></span>  
  
3.  <span data-ttu-id="7f496-114">Nel gruppo **Elabora** della scheda **Pagina iniziale** scegliere **Leggi file PVR**.</span><span class="sxs-lookup"><span data-stu-id="7f496-114">On the **Home** tab, in the **Process** group, choose **Read ESR File**.</span></span>  
  
    > [!NOTE]  
    >  <span data-ttu-id="7f496-115">Se è stata definita più di una banca PVR, viene visualizzato un messaggio di avviso che indica di scegliere la banca pertinente.</span><span class="sxs-lookup"><span data-stu-id="7f496-115">If you have defined more than one ESR bank, a warning message displays instructing you to choose the relevant bank.</span></span> <span data-ttu-id="7f496-116">Per ulteriori informazioni, vedere la tabella Setup PVR.</span><span class="sxs-lookup"><span data-stu-id="7f496-116">For more information, see the ESR Setup table.</span></span>  
  
4.  <span data-ttu-id="7f496-117">Scegliere il pulsante **Sì**, quindi scegliere il pulsante **OK**.</span><span class="sxs-lookup"><span data-stu-id="7f496-117">Choose the **Yes** button, and then choose the **OK** button.</span></span>  
  
 <span data-ttu-id="7f496-118">Le informazioni sui pagamenti vengono importate nelle righe di registrazioni.</span><span class="sxs-lookup"><span data-stu-id="7f496-118">The payments information is imported to the journal lines.</span></span> <span data-ttu-id="7f496-119">I pagamenti vengono applicati automaticamente alle rispettive fatture in base a numeri di riferimento PVR univoci.</span><span class="sxs-lookup"><span data-stu-id="7f496-119">The payments are automatically applied to the respective invoices according to unique ESR reference numbers.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="7f496-120">Vedere anche</span><span class="sxs-lookup"><span data-stu-id="7f496-120">See Also</span></span>  
 <span data-ttu-id="7f496-121">[Pagamenti elettronici svizzeri tramite PVR](swiss-electronic-payments-using-esr.md) </span><span class="sxs-lookup"><span data-stu-id="7f496-121">[Swiss Electronic Payments Using ESR](swiss-electronic-payments-using-esr.md) </span></span>  
 <span data-ttu-id="7f496-122">[Procedura: Stampare fatture PVR](how-to-print-esr-invoices.md) </span><span class="sxs-lookup"><span data-stu-id="7f496-122">[How to: Print ESR Invoices](how-to-print-esr-invoices.md) </span></span>  
 <span data-ttu-id="7f496-123">Setup PVR</span><span class="sxs-lookup"><span data-stu-id="7f496-123">ESR Setup</span></span>   
 <span data-ttu-id="7f496-124">Registrazioni incassi</span><span class="sxs-lookup"><span data-stu-id="7f496-124">Cash Receipt Journal</span></span>   
 <span data-ttu-id="7f496-125">Registro PVR Clienti</span><span class="sxs-lookup"><span data-stu-id="7f496-125">Customer ESR Journal</span></span>
