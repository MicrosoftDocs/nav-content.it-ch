---
title: Pagamenti elettronici svizzeri tramite LSV+
description: "Il metodo di pagamento elettronico svizzero, ovvero Lastschrift Verfahren (LSV+) o addebito diretto, versione migliorata del metodo LSV, consente alle aziende di recuperare i pagamenti direttamente dai conti correnti dei clienti. Per recuperare i pagamenti dei clienti, è necessario inviare un file LSV alla banca, che raccoglierà i pagamenti richiesti nel file."
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
ms.openlocfilehash: bde56909ab329a08cb29ae5a372eab2c81d4a2e9
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="swiss-electronic-payments-using-lsv"></a><span data-ttu-id="463e4-104">Pagamenti elettronici svizzeri tramite LSV+</span><span class="sxs-lookup"><span data-stu-id="463e4-104">Swiss Electronic Payments Using LSV+</span></span>
<span data-ttu-id="463e4-105">Il metodo di pagamento elettronico svizzero, ovvero Lastschrift Verfahren (LSV+) o addebito diretto, versione migliorata del metodo LSV, consente alle aziende di recuperare i pagamenti direttamente dai conti correnti dei clienti.</span><span class="sxs-lookup"><span data-stu-id="463e4-105">The Lastschrift Verfahren (LSV+)—or direct debit—electronic payment method, an improved version of LSV, allows companies to retrieve payments directly from its customers’ bank accounts.</span></span> <span data-ttu-id="463e4-106">Per recuperare i pagamenti dei clienti, è necessario inviare un file LSV alla banca, che raccoglierà i pagamenti richiesti nel file.</span><span class="sxs-lookup"><span data-stu-id="463e4-106">To retrieve customer payments, you must send an LSV file to the bank, and the bank will collect the payments requested in the file.</span></span>  
  
 <span data-ttu-id="463e4-107">Il metodo LSV+ è un principio di addebito diretto con facoltà di opporsi.</span><span class="sxs-lookup"><span data-stu-id="463e4-107">The LSV+ method is a direct debit principle with right of objection.</span></span> <span data-ttu-id="463e4-108">Il metodo BDD (Business Direct Debit) è invece un sistema di addebito diretto senza facoltà di opporsi.</span><span class="sxs-lookup"><span data-stu-id="463e4-108">Business Direct Debit (BDD) is a direct debit system without right of objection.</span></span> <span data-ttu-id="463e4-109">Il formato di file da inviare alla banca è lo stesso per i sistemi LSV+ e BDD.</span><span class="sxs-lookup"><span data-stu-id="463e4-109">The file format to be sent to the bank is the same for LSV+ and BDD.</span></span>  
  
 <span data-ttu-id="463e4-110">Prima di usare il modulo LSV, è necessario definire le impostazioni nella finestra **Setup LSV**.</span><span class="sxs-lookup"><span data-stu-id="463e4-110">Before using the LSV module, you must define the settings in the **LSV Setup** window.</span></span> <span data-ttu-id="463e4-111">Per ulteriori informazioni, vedere la tabella Setup LSV.</span><span class="sxs-lookup"><span data-stu-id="463e4-111">For more information, see the LSV Setup table.</span></span>  
  
## <a name="automatic-esr-processing"></a><span data-ttu-id="463e4-112">Elaborazione PVR automatica</span><span class="sxs-lookup"><span data-stu-id="463e4-112">Automatic ESR Processing</span></span>  
 <span data-ttu-id="463e4-113">È possibile scaricare transazioni creditizie di pagamento nel formato di file PVR (polizza di versamento con numero di riferimento, in tedesco ESR, Einzahlungsschein mit Referenznummer) dalla banca.</span><span class="sxs-lookup"><span data-stu-id="463e4-113">You can download payment credit transactions in Einzahlungsschein mit Referenznummer (ESR) file format from the bank.</span></span> <span data-ttu-id="463e4-114">È possibile ricevere pagamenti LSV nel file PVR se il numero di riferimento PVR è integrato nel sistema LSV+.</span><span class="sxs-lookup"><span data-stu-id="463e4-114">You can receive processed LSV payments in the ESR file if the ESR reference number is integrated with the LSV+ system.</span></span> <span data-ttu-id="463e4-115">Se nei file LSV importati sono inclusi pagamenti LSV+, le righe di registrazione LSV correlate vengono chiuse automaticamente.</span><span class="sxs-lookup"><span data-stu-id="463e4-115">If LSV+ payments are included in your imported LSV files, the related LSV journal lines are closed automatically.</span></span> <span data-ttu-id="463e4-116">L'elaborazione PVR automatica viene eseguita solo per i pagamenti che utilizzano franchi svizzeri (CHF) e richiede che vengano effettuate queste operazioni:</span><span class="sxs-lookup"><span data-stu-id="463e4-116">Automatic ESR processing is performed only for payments that use Swiss Francs (CHF), and requires that you do the following:</span></span>  
  
-   <span data-ttu-id="463e4-117">Dopo aver inviato il file LSV+ alla banca, inviare un report di pagamenti entro tre giorni lavorativi dalla data di elaborazione LSV richiesta.</span><span class="sxs-lookup"><span data-stu-id="463e4-117">After you have sent the LSV+ file to the bank, submit a payments report within three business days following the requested LSV processing date.</span></span>  
  
-   <span data-ttu-id="463e4-118">Importare i file PVR, quindi inserire le registrazioni PVR.</span><span class="sxs-lookup"><span data-stu-id="463e4-118">Import the ESR files, and post the ESR journals.</span></span> <span data-ttu-id="463e4-119">Se una transazione PVR importata è correlata alla riga di pagamento LSV+, la riga di registrazione LSV appropriata viene chiusa automaticamente da PVR.</span><span class="sxs-lookup"><span data-stu-id="463e4-119">If an imported ESR transaction is related to an open LSV+ payment line, then the appropriate LSV journal line is automatically closed by ESR.</span></span>  
  
    > [!NOTE]  
    >  <span data-ttu-id="463e4-120">Quando si importa un file PVR, la riga di registrazione LSV viene chiusa da PVR se viene trovata la registrazione LSV appropriata, indipendentemente dal tipo di transazione PVR.</span><span class="sxs-lookup"><span data-stu-id="463e4-120">When importing an ESR file, the LSV journal line is closed by ESR if the appropriate LSV journal is found, regardless of the ESR transaction type.</span></span>  
  
-   <span data-ttu-id="463e4-121">Dopo la data di elaborazione LSV, è possibile controllare le righe di registrazione LSV.</span><span class="sxs-lookup"><span data-stu-id="463e4-121">After the LSV processing date, you can check the LSV journal lines.</span></span> <span data-ttu-id="463e4-122">Se tutte le righe di registrazione LSV sono chiuse, lo stato del campo **Stato LSV** viene aggiornato sul valore **Completato**.</span><span class="sxs-lookup"><span data-stu-id="463e4-122">If all of the LSV journal lines are closed, then the status of the **LSV Status** field is updated to  **Finished**.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="463e4-123">Vedere anche</span><span class="sxs-lookup"><span data-stu-id="463e4-123">See Also</span></span>  
 <span data-ttu-id="463e4-124">[Procedura: Chiudere una riscossione LSV](how-to-process-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="463e4-124">[How to: Process an LSV Collection](how-to-process-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="463e4-125">[Procedura: Chiudere una riscossione LSV](how-to-close-an-lsv-collection.md) </span><span class="sxs-lookup"><span data-stu-id="463e4-125">[How to: Close an LSV Collection](how-to-close-an-lsv-collection.md) </span></span>  
 <span data-ttu-id="463e4-126">[Procedura: Registrare pagamenti LSV+](how-to-post-lsv-payments.md) </span><span class="sxs-lookup"><span data-stu-id="463e4-126">[How to: Post LSV+ Payments](how-to-post-lsv-payments.md) </span></span>  
 <span data-ttu-id="463e4-127">[Procedura: Esportare pagamenti tramite LSV](how-to-export-payments-using-lsv.md) </span><span class="sxs-lookup"><span data-stu-id="463e4-127">[How to: Export Payments Using LSV](how-to-export-payments-using-lsv.md) </span></span>  
 <span data-ttu-id="463e4-128">[Pagamenti elettronici svizzeri](swiss-electronic-payments.md) </span><span class="sxs-lookup"><span data-stu-id="463e4-128">[Swiss Electronic Payments](swiss-electronic-payments.md) </span></span>  
 <span data-ttu-id="463e4-129">[Pagamenti elettronici svizzeri tramite DTA](swiss-electronic-payments-using-dta.md) </span><span class="sxs-lookup"><span data-stu-id="463e4-129">[Swiss Electronic Payments Using DTA](swiss-electronic-payments-using-dta.md) </span></span>  
 <span data-ttu-id="463e4-130">[Pagamenti elettronici svizzeri tramite PVR](swiss-electronic-payments-using-esr.md) </span><span class="sxs-lookup"><span data-stu-id="463e4-130">[Swiss Electronic Payments Using ESR](swiss-electronic-payments-using-esr.md) </span></span>  
 <span data-ttu-id="463e4-131">Setup LSV</span><span class="sxs-lookup"><span data-stu-id="463e4-131">LSV Setup</span></span>
