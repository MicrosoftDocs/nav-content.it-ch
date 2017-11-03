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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 856a98e6c4d0f8820fa993deac3d44898f9420b3
ms.contentlocale: it-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-export-payments-using-ezag"></a><span data-ttu-id="8f0a5-103">Procedura: Esportare pagamenti tramite EZAG</span><span class="sxs-lookup"><span data-stu-id="8f0a5-103">How to: Export Payments Using EZAG</span></span>
<span data-ttu-id="8f0a5-104">È possibile generare un file per il pagamento elettronico tramite il metodo EZAG (Elektronischer Zahlungsauftrag) ed esportarlo alla banca per essere usato per i pagamenti.</span><span class="sxs-lookup"><span data-stu-id="8f0a5-104">You can generate a file for electronic payment using the Elektronischer Zahlungsauftrag (EZAG) method, and export it for the bank to use for the payments.</span></span>  

## <a name="to-export-payments-using-ezag"></a><span data-ttu-id="8f0a5-105">Per esportare pagamenti tramite EZAG</span><span class="sxs-lookup"><span data-stu-id="8f0a5-105">To export payments using EZAG</span></span>  

1.  <span data-ttu-id="8f0a5-106">Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni pagamenti**, quindi scegliere il collegamento correlato.</span><span class="sxs-lookup"><span data-stu-id="8f0a5-106">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="8f0a5-107">Nel campo **Nome batch** selezionare il nome batch registrazioni desiderato.</span><span class="sxs-lookup"><span data-stu-id="8f0a5-107">In the **Batch Name** field, select the journal batch name.</span></span>  
3.  <span data-ttu-id="8f0a5-108">Scegliere l'azione **Genera file EZAG**.</span><span class="sxs-lookup"><span data-stu-id="8f0a5-108">Choose the **Generate EZAG File** action.</span></span>  
4.  <span data-ttu-id="8f0a5-109">Nel processo batch **File EZAG**, nella Scheda dettaglio **Opzioni** compilare i campi come descritto nella tabella seguente.</span><span class="sxs-lookup"><span data-stu-id="8f0a5-109">In the **EZAG File** batch job, on the **Options** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="8f0a5-110">Campo</span><span class="sxs-lookup"><span data-stu-id="8f0a5-110">Field</span></span>|<span data-ttu-id="8f0a5-111">Descrizione</span><span class="sxs-lookup"><span data-stu-id="8f0a5-111">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="8f0a5-112">**Banca di addebito**</span><span class="sxs-lookup"><span data-stu-id="8f0a5-112">**Debit to bank**</span></span>|<span data-ttu-id="8f0a5-113">Specifica il codice della banca da addebitare.</span><span class="sxs-lookup"><span data-stu-id="8f0a5-113">Specify the code of the bank to be charged.</span></span>|  
    |<span data-ttu-id="8f0a5-114">**Pagamento unico per fornitore**</span><span class="sxs-lookup"><span data-stu-id="8f0a5-114">**Combined payment for vendor**</span></span>|<span data-ttu-id="8f0a5-115">Specifica se le righe di pagamento con lo stesso fornitore, valuta, banca e banca di addebito nel file EZAG generato verranno combinate.</span><span class="sxs-lookup"><span data-stu-id="8f0a5-115">Specify if the payment lines that have the same vendor, currency, bank, and debit bank in the generated EZAG file will be combined.</span></span>|  
    |<span data-ttu-id="8f0a5-116">**Spedizione con disco**</span><span class="sxs-lookup"><span data-stu-id="8f0a5-116">**Shipment with disk**</span></span>|<span data-ttu-id="8f0a5-117">Specifica se il file EZAG verrà salvato su un disco per essere consegnato alla banca.</span><span class="sxs-lookup"><span data-stu-id="8f0a5-117">Specify if the EZAG file will be saved to a disk so that you can deliver it to the bank.</span></span>|  

5.  <span data-ttu-id="8f0a5-118">Scegliere il pulsante **OK**.</span><span class="sxs-lookup"><span data-stu-id="8f0a5-118">Choose the **OK** button.</span></span> <span data-ttu-id="8f0a5-119">Il file EZAG viene generato.</span><span class="sxs-lookup"><span data-stu-id="8f0a5-119">The EZAG file is generated.</span></span>  

## <a name="see-also"></a><span data-ttu-id="8f0a5-120">Vedere anche</span><span class="sxs-lookup"><span data-stu-id="8f0a5-120">See Also</span></span>  
 <span data-ttu-id="8f0a5-121">[Pagamenti elettronici svizzeri tramite DTA](swiss-electronic-payments-using-dta.md) </span><span class="sxs-lookup"><span data-stu-id="8f0a5-121">[Swiss Electronic Payments Using DTA](swiss-electronic-payments-using-dta.md) </span></span>  
 <span data-ttu-id="8f0a5-122">[Procedura: Suggerire pagamenti DTA ai fornitori](how-to-suggest-dta-payment-for-vendors.md) </span><span class="sxs-lookup"><span data-stu-id="8f0a5-122">[How to: Suggest DTA Payment for Vendors](how-to-suggest-dta-payment-for-vendors.md) </span></span>  
 <span data-ttu-id="8f0a5-123">[Procedura: Verificare una lista di fornitori per pagamenti DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md) </span><span class="sxs-lookup"><span data-stu-id="8f0a5-123">[How to: Verify a List of Vendors for DTA Payments](how-to-verify-a-list-of-vendors-for-dta-payments.md) </span></span>  
 [<span data-ttu-id="8f0a5-124">Procedura: Inviare pagamenti DTA</span><span class="sxs-lookup"><span data-stu-id="8f0a5-124">How to: Submit DTA Payments</span></span>](how-to-submit-dta-payments.md) 

