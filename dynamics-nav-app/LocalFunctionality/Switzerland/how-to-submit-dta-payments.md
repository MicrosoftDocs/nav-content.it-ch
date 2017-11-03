---
title: 'Procedura: Inviare pagamenti DTA'
description: "Per inviare pagamenti DatenTrägerAustausch (DTA) alla banca per il pagamento, è necessario eseguire determinate attività."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: bf79d68ddb398672cccec48812266b8808e1e714
ms.contentlocale: it-ch
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-submit-dta-payments"></a><span data-ttu-id="b65f3-103">Procedura: Inviare pagamenti DTA</span><span class="sxs-lookup"><span data-stu-id="b65f3-103">How to: Submit DTA Payments</span></span>
<span data-ttu-id="b65f3-104">Per inviare pagamenti DatenTrägerAustausch (DTA) alla banca per il pagamento, è necessario eseguire le seguenti operazioni:</span><span class="sxs-lookup"><span data-stu-id="b65f3-104">To submit DatenTrägerAustausch (DTA) payments to your bank for payment, you must do the following:</span></span>  

- <span data-ttu-id="b65f3-105">Generare un file DTA per il pagamento elettronico dopo aver stampato l'avviso di pagamento.</span><span class="sxs-lookup"><span data-stu-id="b65f3-105">Generate a DTA file for electronic payment after printing the payment advice.</span></span>  
- <span data-ttu-id="b65f3-106">Stampare l'ordine di pagamento DTA.</span><span class="sxs-lookup"><span data-stu-id="b65f3-106">Print the DTA payment order.</span></span>  

<span data-ttu-id="b65f3-107">Prima di inviare pagamenti DTA, è necessario verificare l'elenco dei fornitori per il pagamento DTA.</span><span class="sxs-lookup"><span data-stu-id="b65f3-107">Before you submit DTA payments, you must verify the list of vendors for DTA payment.</span></span> <span data-ttu-id="b65f3-108">Per ulteriori informazioni, vedere [Procedura: Verificare una lista di fornitori per pagamenti DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md).</span><span class="sxs-lookup"><span data-stu-id="b65f3-108">For more information, see [How to: Verify a List of Vendors for DTA Payments](how-to-verify-a-list-of-vendors-for-dta-payments.md).</span></span>  

<span data-ttu-id="b65f3-109">È possibile registrare le registrazioni pagamenti dopo che i pagamenti bancari sono completati.</span><span class="sxs-lookup"><span data-stu-id="b65f3-109">You can post the payment journal after the bank payments are complete.</span></span> <span data-ttu-id="b65f3-110">Nell registrazioni pagamenti i pagamenti DTA possono essere suggeriti in base alle fatture registrate.</span><span class="sxs-lookup"><span data-stu-id="b65f3-110">In the payment journal, you can have the DTA payments suggested based on posted invoices.</span></span> <span data-ttu-id="b65f3-111">I pagamenti suggeriti contengono informazioni sui fornitori e sui numeri di documento esterni e possono essere modificati.</span><span class="sxs-lookup"><span data-stu-id="b65f3-111">The suggested payments contain vendor and external document number information, and can be modified.</span></span> <span data-ttu-id="b65f3-112">Per ulteriori informazioni, vedere [Procedura: Suggerire pagamenti DTA per i fornitori](how-to-suggest-dta-payment-for-vendors.md).</span><span class="sxs-lookup"><span data-stu-id="b65f3-112">For more information, see [How to: Suggest DTA Payment for Vendors](how-to-suggest-dta-payment-for-vendors.md).</span></span>  

## <a name="to-generate-a-dta-file"></a><span data-ttu-id="b65f3-113">Per generare un file DTA</span><span class="sxs-lookup"><span data-stu-id="b65f3-113">To generate a DTA file</span></span>  

1.  <span data-ttu-id="b65f3-114">Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni pagamenti**, quindi scegliere il collegamento correlato.</span><span class="sxs-lookup"><span data-stu-id="b65f3-114">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="b65f3-115">Nel campo **Nome batch** selezionare il batch contabile necessario.</span><span class="sxs-lookup"><span data-stu-id="b65f3-115">In the **Batch Name** field, select the required journal batch.</span></span>  
3.  <span data-ttu-id="b65f3-116">Selezionare il movimento id pagamento che si desidera generare come file DTA quindi scegliere l'azione **Genera file DTA**.</span><span class="sxs-lookup"><span data-stu-id="b65f3-116">Select the payment entry that you want to generate as a DTA file, and then choose the **Generate DTA File** action.</span></span>  
4.  <span data-ttu-id="b65f3-117">Compilare i campi nel processo batch **File DTA** come descritto nella tabella riportata di seguito.</span><span class="sxs-lookup"><span data-stu-id="b65f3-117">In the **DTA File** batch job, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="b65f3-118">Campo</span><span class="sxs-lookup"><span data-stu-id="b65f3-118">Field</span></span>|<span data-ttu-id="b65f3-119">Descrizione</span><span class="sxs-lookup"><span data-stu-id="b65f3-119">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="b65f3-120">**Banca DTA per il File**</span><span class="sxs-lookup"><span data-stu-id="b65f3-120">**DTA Bank for File**</span></span>|<span data-ttu-id="b65f3-121">Selezionare il codice bancario DTA da cui devono essere trasferite le informazioni relative al nome file e alla copia di backup.</span><span class="sxs-lookup"><span data-stu-id="b65f3-121">Select the DTA bank code from which the information for the file name and backup copy is to be transferred.</span></span> <span data-ttu-id="b65f3-122">Questo campo utilizza il nome della banca principale come valore predefinito, ma è possibile modificare queste informazioni se necessario.</span><span class="sxs-lookup"><span data-stu-id="b65f3-122">This field uses the main bank name as the default, but you can modify this information if you want.</span></span>|  
    |<span data-ttu-id="b65f3-123">**Pagamento unico per fornitore**</span><span class="sxs-lookup"><span data-stu-id="b65f3-123">**Combined payment for vendor**</span></span>|<span data-ttu-id="b65f3-124">Specifica se le righe di pagamento con lo stesso fornitore, valuta, banca e banca di addebito nel file DTA generato verranno combinate.</span><span class="sxs-lookup"><span data-stu-id="b65f3-124">Specify if the payment lines that have the same vendor, currency, bank, and debit bank will be combined in the generated DTA file.</span></span>|  

5.  <span data-ttu-id="b65f3-125">Scegliere il pulsante **OK**.</span><span class="sxs-lookup"><span data-stu-id="b65f3-125">Choose the **OK** button.</span></span> <span data-ttu-id="b65f3-126">Il file DTA viene generato nella cartella determinata in precedenza.</span><span class="sxs-lookup"><span data-stu-id="b65f3-126">The DTA file is generated in the predetermined folder.</span></span>  

<span data-ttu-id="b65f3-127">Dopo aver generato il file DTA, è possibile stampare l'ordine di pagamento DTA e trasferire il file e l'ordine di pagamento alla banca.</span><span class="sxs-lookup"><span data-stu-id="b65f3-127">After you have generated the DTA file, you can print the DTA payment order and transfer both the file and the payment order to your bank.</span></span> <span data-ttu-id="b65f3-128">L'ordine di pagamento DTA elenca tutti i pagamenti fornitori suggeriti in una finestra **Registrazioni pagamenti** basata sul codice valuta.</span><span class="sxs-lookup"><span data-stu-id="b65f3-128">The DTA payment order lists all suggested vendor payments in a **Payment Journal** window based on currency code.</span></span> <span data-ttu-id="b65f3-129">Questo ordine viene inviato alla banca per rilasciare il file DTA per il pagamento.</span><span class="sxs-lookup"><span data-stu-id="b65f3-129">This order is sent to the bank to release the DTA file for payment.</span></span>  

## <a name="to-print-a-dta-payment-order"></a><span data-ttu-id="b65f3-130">Per stampare l'ordine di pagamento DTA</span><span class="sxs-lookup"><span data-stu-id="b65f3-130">To print a DTA payment order</span></span>  

1.  <span data-ttu-id="b65f3-131">Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni pagamenti**, quindi scegliere il collegamento correlato.</span><span class="sxs-lookup"><span data-stu-id="b65f3-131">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="b65f3-132">Nel campo **Nome batch** selezionare il batch contabile necessario.</span><span class="sxs-lookup"><span data-stu-id="b65f3-132">In the **Batch Name** field, select the required journal batch.</span></span>  
3.  <span data-ttu-id="b65f3-133">Selezionare il movimento di pagamento richiesto, quindi scegliere l'azione **Ordine di pagamento DTA**.</span><span class="sxs-lookup"><span data-stu-id="b65f3-133">Select the required payment entry, and then choose the **DTA Payment Order** action.</span></span>  
4.  <span data-ttu-id="b65f3-134">Nel campo **Messaggio** immettere un messaggio per la banca da stampare alla fine dell'ordine di pagamento.</span><span class="sxs-lookup"><span data-stu-id="b65f3-134">In the **Message** field, enter a message for the bank, to be printed at the bottom of the payment order.</span></span>  
5.  <span data-ttu-id="b65f3-135">Scegliere il pulsante **Stampa** per stampare l'ordine di pagamento DTA oppure scegliere il pulsante **Anteprima** per visualizzarla sullo schermo.</span><span class="sxs-lookup"><span data-stu-id="b65f3-135">Choose the **Print** button to print the DTA payment order or choose the **Preview** button to view it on the screen.</span></span>  

    <span data-ttu-id="b65f3-136">Inviare l'ordine di pagamento DTA e il file DTA alla banca, dove i pagamenti ai venditori vengono rilasciati in poche ore.</span><span class="sxs-lookup"><span data-stu-id="b65f3-136">You must submit the DTA payment order and the DTA file to the bank, where payments to the vendors are released in a few hours.</span></span> <span data-ttu-id="b65f3-137">Dopo che i pagamenti sono stati elaborati dalla banca, è possibile contabilizzare le registrazioni dei pagamenti.</span><span class="sxs-lookup"><span data-stu-id="b65f3-137">After the payments have been processed by the bank, you can post the payment journal.</span></span>  

## <a name="see-also"></a><span data-ttu-id="b65f3-138">Vedere anche</span><span class="sxs-lookup"><span data-stu-id="b65f3-138">See Also</span></span>  
 <span data-ttu-id="b65f3-139">[Pagamenti elettronici svizzeri tramite DTA](swiss-electronic-payments-using-dta.md) </span><span class="sxs-lookup"><span data-stu-id="b65f3-139">[Swiss Electronic Payments Using DTA](swiss-electronic-payments-using-dta.md) </span></span>  
 <span data-ttu-id="b65f3-140">[Procedura: Suggerire pagamenti DTA ai fornitori](how-to-suggest-dta-payment-for-vendors.md) </span><span class="sxs-lookup"><span data-stu-id="b65f3-140">[How to: Suggest DTA Payment for Vendors](how-to-suggest-dta-payment-for-vendors.md) </span></span>  
 <span data-ttu-id="b65f3-141">[Procedura: Verificare una lista di fornitori per pagamenti DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md) </span><span class="sxs-lookup"><span data-stu-id="b65f3-141">[How to: Verify a List of Vendors for DTA Payments](how-to-verify-a-list-of-vendors-for-dta-payments.md) </span></span>  
 [<span data-ttu-id="b65f3-142">Procedura: Esportare pagamenti tramite EZAG</span><span class="sxs-lookup"><span data-stu-id="b65f3-142">How to: Export Payments Using EZAG</span></span>](how-to-export-payments-using-ezag.md)

