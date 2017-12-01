---
title: 'Procedura: Importare codici postali svizzeri'
description: "È possibile importare l'ultimo file di codice postale e utilizzarlo per aggiornare la tabella **CAP**. Il file di codice postale può essere scaricato dal sito Web dei codici postali svizzeri. Dopo l'importazione del codice postale più recente, è possibile definire i codici postali per i clienti o i fornitori."
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
ms.openlocfilehash: c124c0190999a5476e7d99262fe127f16d8d37b3
ms.contentlocale: it-ch
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-import-swiss-post-codes"></a><span data-ttu-id="4b566-105">Procedura: Importare codici NPA svizzeri</span><span class="sxs-lookup"><span data-stu-id="4b566-105">How to: Import Swiss Post Codes</span></span>
<span data-ttu-id="4b566-106">È possibile importare l'ultimo file di codice postale e utilizzarlo per aggiornare la tabella **CAP**.</span><span class="sxs-lookup"><span data-stu-id="4b566-106">You can import the latest post code file and use it to update the **Post Code** table.</span></span> <span data-ttu-id="4b566-107">Il file di codice postale può essere scaricato dal sito Web dei [codici postali svizzeri](http://go.microsoft.com/fwlink/?LinkId=150292).</span><span class="sxs-lookup"><span data-stu-id="4b566-107">The post code file can be downloaded from the [Swiss Post](http://go.microsoft.com/fwlink/?LinkId=150292) website.</span></span> <span data-ttu-id="4b566-108">Dopo l'importazione del codice postale più recente, è possibile definire i codici postali per i clienti o i fornitori.</span><span class="sxs-lookup"><span data-stu-id="4b566-108">After importing the latest post code, you can define post codes for customers or vendors.</span></span> <span data-ttu-id="4b566-109">Per ulteriori informazioni, vedere [Procedura: Registrare nuovi fornitori](../../purchasing-how-register-new-vendors.md).</span><span class="sxs-lookup"><span data-stu-id="4b566-109">For more information, see [How to: Register New Vendors](../../purchasing-how-register-new-vendors.md).</span></span>  

## <a name="to-import-post-codes"></a><span data-ttu-id="4b566-110">Per importare i codici postali</span><span class="sxs-lookup"><span data-stu-id="4b566-110">To import post codes</span></span>  

1.  <span data-ttu-id="4b566-111">Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "Cerca pagina o report"), immettere **Codici postali** e quindi scegliere il collegamento correlato.</span><span class="sxs-lookup"><span data-stu-id="4b566-111">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Post Codes**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="4b566-112">Selezionare l'azione **Importa codici postali**.</span><span class="sxs-lookup"><span data-stu-id="4b566-112">Choose the **Import Post Codes** action.</span></span>  
3.  <span data-ttu-id="4b566-113">Nella finestra **Importa codici postali** nel campo **Nome file** immettere il nome del file di codice postale da importare nella tabella **CAP**.</span><span class="sxs-lookup"><span data-stu-id="4b566-113">In the **Import Post Codes** window, in the **Filename** field, enter the name of the post code file that you want to import to the **Post Code** table.</span></span>  
4.  <span data-ttu-id="4b566-114">Scegliere il pulsante **OK**.</span><span class="sxs-lookup"><span data-stu-id="4b566-114">Choose the **OK** button.</span></span>  

    <span data-ttu-id="4b566-115">Le informazioni più recenti sui codici postali vengono importate.</span><span class="sxs-lookup"><span data-stu-id="4b566-115">The latest post code information is imported.</span></span>  

<span data-ttu-id="4b566-116">Di seguito viene descritto come definire i codici postali per i clienti, ma gli stessi passaggi si applicano anche per definire i codici postali per i fornitori.</span><span class="sxs-lookup"><span data-stu-id="4b566-116">The following procedure describes how to define post codes for customers, but the same steps also apply to defining post codes for vendors.</span></span>  

## <a name="to-define-post-codes-for-customers"></a><span data-ttu-id="4b566-117">Per definire i codici postali per i clienti</span><span class="sxs-lookup"><span data-stu-id="4b566-117">To define post codes for customers</span></span>  

1.  <span data-ttu-id="4b566-118">Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Clienti**, quindi scegliere il collegamento correlato.</span><span class="sxs-lookup"><span data-stu-id="4b566-118">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customers**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="4b566-119">Selezionare il cliente per cui definire un codice postale, quindi scegliere l'azione **Modifica**.</span><span class="sxs-lookup"><span data-stu-id="4b566-119">Select the customer for whom you want to define a post code, and then choose the **Edit** action.</span></span>  
3.  <span data-ttu-id="4b566-120">Nella Scheda dettaglio **Generale** della finestra **Scheda cliente**, nel campo **CAP** selezionare il codice postale per l'indirizzo del cliente.</span><span class="sxs-lookup"><span data-stu-id="4b566-120">In the **Customer Card** window, on the **General** FastTab, in the **Post Code** field, select the post code for the customer's address.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="4b566-121">Una volta selezionato il codice postale, i campi **Città** e **Codice paese** vengono popolati automaticamente con le informazioni della tabella **CAP**.</span><span class="sxs-lookup"><span data-stu-id="4b566-121">When you select the post code, the **City** and **Country/Region Code** fields populate automatically with the information from the **Post Code** table.</span></span> <span data-ttu-id="4b566-122">Per ulteriori informazioni, vedere [Procedura: Registrare nuovi clienti](../../sales-how-register-new-customers.md).</span><span class="sxs-lookup"><span data-stu-id="4b566-122">For more information, see [How to: Register New Customers](../../sales-how-register-new-customers.md).</span></span>  

4.  <span data-ttu-id="4b566-123">Scegliere il pulsante **OK**.</span><span class="sxs-lookup"><span data-stu-id="4b566-123">Choose the **OK** button.</span></span>  

## <a name="see-also"></a><span data-ttu-id="4b566-124">Vedere anche</span><span class="sxs-lookup"><span data-stu-id="4b566-124">See Also</span></span>   
 <span data-ttu-id="4b566-125">[Documenti di acquisto e di vendita per la Svizzera](swiss-purchase-documents-and-sales-documents.md) </span><span class="sxs-lookup"><span data-stu-id="4b566-125">[Swiss Purchase Documents and Sales Documents](swiss-purchase-documents-and-sales-documents.md) </span></span>  
 <span data-ttu-id="4b566-126">[Procedura: Impostare l'archiviazione automatica dei documenti in Svizzera](how-to-set-up-automatic-archiving-of-documents-in-switzerland.md) </span><span class="sxs-lookup"><span data-stu-id="4b566-126">[How to: Set Up Automatic Archiving of Documents in Switzerland](how-to-set-up-automatic-archiving-of-documents-in-switzerland.md) </span></span>  
 <span data-ttu-id="4b566-127">[Procedura: Stampare una lista prelievi magazzino da un ordine di vendita](how-to-print-an-inventory-picking-list-from-a-sales-order.md) </span><span class="sxs-lookup"><span data-stu-id="4b566-127">[How to: Print an Inventory Picking List from a Sales Order](how-to-print-an-inventory-picking-list-from-a-sales-order.md) </span></span>  
 <span data-ttu-id="4b566-128">[Procedura: Stampare ordini di acquisto e vendita durante la registrazione batch](how-to-print-sales-and-purchase-orders-during-batch-posting.md) </span><span class="sxs-lookup"><span data-stu-id="4b566-128">[How to: Print Sales and Purchase Orders During Batch Posting](how-to-print-sales-and-purchase-orders-during-batch-posting.md) </span></span>  
 [<span data-ttu-id="4b566-129">Procedura: Registrare nuovi fornitori</span><span class="sxs-lookup"><span data-stu-id="4b566-129">How to: Register New Vendors</span></span>](../../purchasing-how-register-new-vendors.md)  

