---
title: Come esportare pagamenti tramite EZAG
description: "È possibile generare un file per il pagamento elettronico tramite il metodo EZAG (Elektronischer Zahlungsauftrag) ed esportarlo alla banca per essere usato per i pagamenti."
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
ms.openlocfilehash: b9ea004d65e3d288c1c1db9771f4ed486c9f232b
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-export-payments-using-ezag"></a><span data-ttu-id="45563-103">Procedura: Esportare pagamenti tramite EZAG</span><span class="sxs-lookup"><span data-stu-id="45563-103">How to: Export Payments Using EZAG</span></span>
<span data-ttu-id="45563-104">È possibile generare un file per il pagamento elettronico tramite il metodo EZAG (Elektronischer Zahlungsauftrag) ed esportarlo alla banca per essere usato per i pagamenti.</span><span class="sxs-lookup"><span data-stu-id="45563-104">You can generate a file for electronic payment using the Elektronischer Zahlungsauftrag (EZAG) method, and export it for the bank to use for the payments.</span></span>  
  
### <a name="to-export-payments-using-ezag"></a><span data-ttu-id="45563-105">Per esportare pagamenti tramite EZAG</span><span class="sxs-lookup"><span data-stu-id="45563-105">To export payments using EZAG</span></span>  
  
1.  <span data-ttu-id="45563-106">Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni pagamenti**, quindi scegliere il collegamento correlato.</span><span class="sxs-lookup"><span data-stu-id="45563-106">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="45563-107">Nel campo **Nome batch** selezionare il nome batch registrazioni desiderato.</span><span class="sxs-lookup"><span data-stu-id="45563-107">In the **Batch Name** field, select the journal batch name.</span></span>  
  
3.  <span data-ttu-id="45563-108">Nel gruppo **Elabora** della scheda **Pagina iniziale** scegliere **Genera file EZAG**.</span><span class="sxs-lookup"><span data-stu-id="45563-108">On the **Home** tab, in the **Process** group, choose **Generate EZAG File**.</span></span>  
  
4.  <span data-ttu-id="45563-109">Nel processo batch **File EZAG**, nella Scheda dettaglio **Opzioni** compilare i campi come descritto nella tabella seguente.</span><span class="sxs-lookup"><span data-stu-id="45563-109">In the **EZAG File** batch job, on the **Options** FastTab, fill in the fields as described in the following table.</span></span>  
  
    |<span data-ttu-id="45563-110">Campo</span><span class="sxs-lookup"><span data-stu-id="45563-110">Field</span></span>|<span data-ttu-id="45563-111">Descrizione</span><span class="sxs-lookup"><span data-stu-id="45563-111">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="45563-112">**Banca di addebito**</span><span class="sxs-lookup"><span data-stu-id="45563-112">**Debit to bank**</span></span>|<span data-ttu-id="45563-113">Specifica il codice della banca da addebitare.</span><span class="sxs-lookup"><span data-stu-id="45563-113">Specify the code of the bank to be charged.</span></span>|  
    |<span data-ttu-id="45563-114">**Pagamento unico per fornitore**</span><span class="sxs-lookup"><span data-stu-id="45563-114">**Combined payment for vendor**</span></span>|<span data-ttu-id="45563-115">Specifica se le righe di pagamento con lo stesso fornitore, valuta, banca e banca di addebito nel file EZAG generato verranno combinate.</span><span class="sxs-lookup"><span data-stu-id="45563-115">Specify if the payment lines that have the same vendor, currency, bank, and debit bank in the generated EZAG file will be combined.</span></span>|  
    |<span data-ttu-id="45563-116">**Spedizione con disco**</span><span class="sxs-lookup"><span data-stu-id="45563-116">**Shipment with disk**</span></span>|<span data-ttu-id="45563-117">Specifica se il file EZAG verrà salvato su un disco per essere consegnato alla banca.</span><span class="sxs-lookup"><span data-stu-id="45563-117">Specify if the EZAG file will be saved to a disk so that you can deliver it to the bank.</span></span>|  
  
5.  <span data-ttu-id="45563-118">Scegliere il pulsante **OK**.</span><span class="sxs-lookup"><span data-stu-id="45563-118">Choose the **OK** button.</span></span> <span data-ttu-id="45563-119">Il file EZAG viene generato.</span><span class="sxs-lookup"><span data-stu-id="45563-119">The EZAG file is generated.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="45563-120">Vedere anche</span><span class="sxs-lookup"><span data-stu-id="45563-120">See Also</span></span>  
 <span data-ttu-id="45563-121">[Pagamenti elettronici svizzeri tramite DTA](swiss-electronic-payments-using-dta.md) </span><span class="sxs-lookup"><span data-stu-id="45563-121">[Swiss Electronic Payments Using DTA](swiss-electronic-payments-using-dta.md) </span></span>  
 <span data-ttu-id="45563-122">[Procedura: Suggerire pagamenti DTA ai fornitori](how-to-suggest-dta-payment-for-vendors.md) </span><span class="sxs-lookup"><span data-stu-id="45563-122">[How to: Suggest DTA Payment for Vendors](how-to-suggest-dta-payment-for-vendors.md) </span></span>  
 <span data-ttu-id="45563-123">[Procedura: Verificare una lista di fornitori per pagamenti DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md) </span><span class="sxs-lookup"><span data-stu-id="45563-123">[How to: Verify a List of Vendors for DTA Payments](how-to-verify-a-list-of-vendors-for-dta-payments.md) </span></span>  
 <span data-ttu-id="45563-124">[Procedura: Inviare pagamenti DTA](how-to-submit-dta-payments.md) </span><span class="sxs-lookup"><span data-stu-id="45563-124">[How to: Submit DTA Payments](how-to-submit-dta-payments.md) </span></span>  
 <span data-ttu-id="45563-125">Setup DTA</span><span class="sxs-lookup"><span data-stu-id="45563-125">DTA Setup</span></span>   
 <span data-ttu-id="45563-126">Registraz. pagamenti</span><span class="sxs-lookup"><span data-stu-id="45563-126">Payment Journal</span></span>
