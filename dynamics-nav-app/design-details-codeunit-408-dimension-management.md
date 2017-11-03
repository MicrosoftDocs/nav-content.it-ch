---
title: Dettagli di progettazione - Gestione dimensioni della codeunit 408
description: "La gestione delle dimensioni della Codeunit 408 è una libreria di funzione che gestisce le attività comuni correlate alle dimensioni, ad esempio copia da una tabella a un'altra oppure da un documento a un altro."
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
ms.openlocfilehash: c1b3c745597f96165aec92a08bba50ecb6727a84
ms.contentlocale: it-ch
ms.lasthandoff: 10/23/2017

---
# <a name="design-details-codeunit-408-dimension-management"></a><span data-ttu-id="d71bb-103">Dettagli di progettazione: Gestione dimensioni della codeunit 408</span><span class="sxs-lookup"><span data-stu-id="d71bb-103">Design Details: Codeunit 408 Dimension Management</span></span>
<span data-ttu-id="d71bb-104">La gestione delle dimensioni della Codeunit 408 è una libreria di funzione che gestisce le attività comuni correlate alle dimensioni, ad esempio copia da una tabella a un'altra oppure da un documento a un altro.</span><span class="sxs-lookup"><span data-stu-id="d71bb-104">Codeunit 408 Dimension Management is a function library that handles common tasks that are related to dimensions, such as copying from one table to another or from one document to another.</span></span> <span data-ttu-id="d71bb-105">In questo argomento sono elencate le funzioni che vengono modificate in Microsoft Dynamics NAV 2013 R2 e vengono specificate le azioni da intraprendere per le funzioni.</span><span class="sxs-lookup"><span data-stu-id="d71bb-105">This topic lists the functions that are modified in Microsoft Dynamics NAV 2013 R2 and specifies what has to be done to the functions.</span></span> <span data-ttu-id="d71bb-106">Numerose funzioni sono state eliminate in quanto non è necessario eseguire copie tra le tabelle delle dimensioni.</span><span class="sxs-lookup"><span data-stu-id="d71bb-106">Many functions are deleted because there is no need for copying between dimension tables.</span></span>  

## <a name="modified-functions"></a><span data-ttu-id="d71bb-107">Funzioni modificate</span><span class="sxs-lookup"><span data-stu-id="d71bb-107">Modified Functions</span></span>  

|<span data-ttu-id="d71bb-108">Nome funzione</span><span class="sxs-lookup"><span data-stu-id="d71bb-108">Function Name</span></span>|<span data-ttu-id="d71bb-109">Descrizione modifica</span><span class="sxs-lookup"><span data-stu-id="d71bb-109">Modification Description</span></span>|  
|-------------------|------------------------------|  
|<span data-ttu-id="d71bb-110">CheckDimSetIDComb</span><span class="sxs-lookup"><span data-stu-id="d71bb-110">CheckDimSetIDComb</span></span>|<span data-ttu-id="d71bb-111">Nuova funzione che sostituisce le altre funzioni di controllo e accetta un ID di set di dimensioni come argomento anziché una tabella delle dimensioni.</span><span class="sxs-lookup"><span data-stu-id="d71bb-111">New function that substitutes the other check functions and takes a Dimension Set ID as an argument instead of a dimension table.</span></span>|  
|<span data-ttu-id="d71bb-112">CheckDimSetIDComb</span><span class="sxs-lookup"><span data-stu-id="d71bb-112">CheckDimSetIDComb</span></span><br /><br /> <span data-ttu-id="d71bb-113">CheckDocDimComb</span><span class="sxs-lookup"><span data-stu-id="d71bb-113">CheckDocDimComb</span></span><br /><br /> <span data-ttu-id="d71bb-114">CheckServContractDimComb</span><span class="sxs-lookup"><span data-stu-id="d71bb-114">CheckServContractDimComb</span></span><br /><br /> <span data-ttu-id="d71bb-115">CheckDimBuffer</span><span class="sxs-lookup"><span data-stu-id="d71bb-115">CheckDimBuffer</span></span><br /><br /> <span data-ttu-id="d71bb-116">CheckDimComb</span><span class="sxs-lookup"><span data-stu-id="d71bb-116">CheckDimComb</span></span><br /><br /> <span data-ttu-id="d71bb-117">CheckDimValueComb</span><span class="sxs-lookup"><span data-stu-id="d71bb-117">CheckDimValueComb</span></span>|<span data-ttu-id="d71bb-118">Elimina.</span><span class="sxs-lookup"><span data-stu-id="d71bb-118">Delete.</span></span> <span data-ttu-id="d71bb-119">Tutti gli utilizzi devono essere modificati in CheckDimSetIDComb.</span><span class="sxs-lookup"><span data-stu-id="d71bb-119">All usage should be changed to CheckDimSetIDComb.</span></span>|  
|<span data-ttu-id="d71bb-120">GetDefaultDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-120">GetDefaultDim</span></span>|<span data-ttu-id="d71bb-121">Modificare per restituire un ID di set di dimensioni sotto forma di valore intero anziché un set di record.</span><span class="sxs-lookup"><span data-stu-id="d71bb-121">Modify to return an integer Dimension Set ID instead of a set of records.</span></span>|  
|<span data-ttu-id="d71bb-122">CopyJnlLineDimToICJnlDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-122">CopyJnlLineDimToICJnlDim</span></span><br /><br /> <span data-ttu-id="d71bb-123">CopyICJnlDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-123">CopyICJnlDimToJnlLineDim</span></span><br /><br /> <span data-ttu-id="d71bb-124">CopyDocDimtoICDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-124">CopyDocDimtoICDocDim</span></span><br /><br /> <span data-ttu-id="d71bb-125">CopyICDocDimtoICDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-125">CopyICDocDimtoICDocDim</span></span>|<span data-ttu-id="d71bb-126">Modificare per utilizzare DimSetID -> ICJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-126">Modify to work with DimSetID -> ICJnlLineDim</span></span>|  

## <a name="deleted-functions"></a><span data-ttu-id="d71bb-127">Funzioni eliminate</span><span class="sxs-lookup"><span data-stu-id="d71bb-127">Deleted Functions</span></span>  
 <span data-ttu-id="d71bb-128">Le funzioni che vengono eliminate dalla codeunit 408 in relazione alla funzionalità Movimenti set di dimensioni sono elencate di seguito.</span><span class="sxs-lookup"><span data-stu-id="d71bb-128">Functions that are deleted from codeunit 408 in connection with the Dimension Set Entries feature are listed below.</span></span>  

> [!CAUTION]  
>  <span data-ttu-id="d71bb-129">Durante l'aggiornamento del codice dell'applicazione da Microsoft Dynamics NAV 2009 o versioni precedenti a Microsoft Dynamics NAV 2016, le seguenti funzioni non sono disponibili in Microsoft Dynamics NAV 2016.</span><span class="sxs-lookup"><span data-stu-id="d71bb-129">During the upgrade of application code from Microsoft Dynamics NAV 2009 or earlier versions to Microsoft Dynamics NAV 2016, the following functions are not available in Microsoft Dynamics NAV 2016.</span></span> <span data-ttu-id="d71bb-130">Se si dispone di personalizzazioni in cui vengono utilizzate una o più funzioni, è necessario aggiornare il codice di conseguenza.</span><span class="sxs-lookup"><span data-stu-id="d71bb-130">If you have customizations that use one or more of the functions, you must upgrade that code accordingly.</span></span>

 <span data-ttu-id="d71bb-131">InsertJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-131">InsertJnlLineDim</span></span>  

 <span data-ttu-id="d71bb-132">UpdateJnlLineDefaultDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-132">UpdateJnlLineDefaultDim</span></span>  

 <span data-ttu-id="d71bb-133">GetJnlLineDefaultDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-133">GetJnlLineDefaultDim</span></span>  

 <span data-ttu-id="d71bb-134">GetPreviousDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-134">GetPreviousDocDefaultDim</span></span>  

 <span data-ttu-id="d71bb-135">GetPreviousProdDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-135">GetPreviousProdDocDefaultDim</span></span>  

 <span data-ttu-id="d71bb-136">InsertDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-136">InsertDocDim</span></span>  

 <span data-ttu-id="d71bb-137">UpdateDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-137">UpdateDocDefaultDim</span></span>  

 <span data-ttu-id="d71bb-138">ExtractDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-138">ExtractDocDefaultDim</span></span>  

 <span data-ttu-id="d71bb-139">InsertProdDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-139">InsertProdDocDim</span></span>  

 <span data-ttu-id="d71bb-140">UpdateProdDocDefaultDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-140">UpdateProdDocDefaultDim</span></span>  

 <span data-ttu-id="d71bb-141">InsertServContractDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-141">InsertServContractDim</span></span>  

 <span data-ttu-id="d71bb-142">UpdateServcontractDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-142">UpdateServcontractDim</span></span>  

 <span data-ttu-id="d71bb-143">UpdateDefaultDimNewDimValue</span><span class="sxs-lookup"><span data-stu-id="d71bb-143">UpdateDefaultDimNewDimValue</span></span>  

 <span data-ttu-id="d71bb-144">GetDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-144">GetDocDim</span></span>  

 <span data-ttu-id="d71bb-145">GetProdDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-145">GetProdDocDim</span></span>  

 <span data-ttu-id="d71bb-146">TypeToTableID1</span><span class="sxs-lookup"><span data-stu-id="d71bb-146">TypeToTableID1</span></span>  

 <span data-ttu-id="d71bb-147">TypeToTableID2</span><span class="sxs-lookup"><span data-stu-id="d71bb-147">TypeToTableID2</span></span>  

 <span data-ttu-id="d71bb-148">TypeToTableID3</span><span class="sxs-lookup"><span data-stu-id="d71bb-148">TypeToTableID3</span></span>  

 <span data-ttu-id="d71bb-149">TypeToTableID4</span><span class="sxs-lookup"><span data-stu-id="d71bb-149">TypeToTableID4</span></span>  

 <span data-ttu-id="d71bb-150">TypeToTableID5</span><span class="sxs-lookup"><span data-stu-id="d71bb-150">TypeToTableID5</span></span>  

 <span data-ttu-id="d71bb-151">DeleteJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-151">DeleteJnlLineDim</span></span>  

 <span data-ttu-id="d71bb-152">DeleteDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-152">DeleteDocDim</span></span>  

 <span data-ttu-id="d71bb-153">DeletePostedDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-153">DeletePostedDocDim</span></span>  

 <span data-ttu-id="d71bb-154">DeleteProdDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-154">DeleteProdDocDim</span></span>  

 <span data-ttu-id="d71bb-155">DeleteServContractDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-155">DeleteServContractDim</span></span>  

 <span data-ttu-id="d71bb-156">ShowJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-156">ShowJnlLineDim</span></span>  

 <span data-ttu-id="d71bb-157">SaveJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-157">SaveJnlLineDim</span></span>  

 <span data-ttu-id="d71bb-158">ShowJnlLineNewDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-158">ShowJnlLineNewDim</span></span>  

 <span data-ttu-id="d71bb-159">SaveJnlLineNewDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-159">SaveJnlLineNewDim</span></span>  

 <span data-ttu-id="d71bb-160">ShowDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-160">ShowDocDim</span></span>  

 <span data-ttu-id="d71bb-161">SaveDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-161">SaveDocDim</span></span>  

 <span data-ttu-id="d71bb-162">ShowProdDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-162">ShowProdDocDim</span></span>  

 <span data-ttu-id="d71bb-163">SaveProdDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-163">SaveProdDocDim</span></span>  

 <span data-ttu-id="d71bb-164">ShowTempDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-164">ShowTempDim</span></span>  

 <span data-ttu-id="d71bb-165">SaveTempDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-165">SaveTempDim</span></span>  

 <span data-ttu-id="d71bb-166">ShowTempNewDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-166">ShowTempNewDim</span></span>  

 <span data-ttu-id="d71bb-167">SaveTempNewDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-167">SaveTempNewDim</span></span>  

 <span data-ttu-id="d71bb-168">SaveServContractDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-168">SaveServContractDim</span></span>  

 <span data-ttu-id="d71bb-169">MoveJnlLineDimToLedgEntryDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-169">MoveJnlLineDimToLedgEntryDim</span></span>  

 <span data-ttu-id="d71bb-170">MoveDocDimToPostedDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-170">MoveDocDimToPostedDocDim</span></span>  

 <span data-ttu-id="d71bb-171">MoveOneDocDimToPostedDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-171">MoveOneDocDimToPostedDocDim</span></span>  

 <span data-ttu-id="d71bb-172">MoveLedgEntryDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-172">MoveLedgEntryDimToJnlLineDim</span></span>  

 <span data-ttu-id="d71bb-173">MoveDimBufToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-173">MoveDimBufToJnlLineDim</span></span>  

 <span data-ttu-id="d71bb-174">MoveDimBufToLedgEntryDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-174">MoveDimBufToLedgEntryDim</span></span>  

 <span data-ttu-id="d71bb-175">MoveDimBufToPostedDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-175">MoveDimBufToPostedDocDim</span></span>  

 <span data-ttu-id="d71bb-176">MoveDimBufToGLBudgetDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-176">MoveDimBufToGLBudgetDim</span></span>  

 <span data-ttu-id="d71bb-177">CopyJnlLineDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-177">CopyJnlLineDimToJnlLineDim</span></span>  

 <span data-ttu-id="d71bb-178">CopyLedgEntryDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-178">CopyLedgEntryDimToJnlLineDim</span></span>  

 <span data-ttu-id="d71bb-179">CopyDocDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-179">CopyDocDimToDocDim</span></span>  

 <span data-ttu-id="d71bb-180">CopyPostedDocDimToPostedDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-180">CopyPostedDocDimToPostedDocDim</span></span>  

 <span data-ttu-id="d71bb-181">CopyDocDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-181">CopyDocDimToJnlLineDim</span></span>  

 <span data-ttu-id="d71bb-182">CopyDimBufToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-182">CopyDimBufToJnlLineDim</span></span>  

 <span data-ttu-id="d71bb-183">CopyDimBufToDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-183">CopyDimBufToDocDim</span></span>  

 <span data-ttu-id="d71bb-184">CopySCDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-184">CopySCDimToDocDim</span></span>  

 <span data-ttu-id="d71bb-185">MoveDocDimToLedgEntryDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-185">MoveDocDimToLedgEntryDim</span></span>  

 <span data-ttu-id="d71bb-186">MoveDocDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-186">MoveDocDimToDocDim</span></span>  

 <span data-ttu-id="d71bb-187">MoveDocDimArchvToDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-187">MoveDocDimArchvToDocDim</span></span>  

 <span data-ttu-id="d71bb-188">MoveLedgEntryDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-188">MoveLedgEntryDimToDocDim</span></span>  

 <span data-ttu-id="d71bb-189">MoveProdDocDimToProdDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-189">MoveProdDocDimToProdDocDim</span></span>  

 <span data-ttu-id="d71bb-190">MoveJnlLineDimToProdDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-190">MoveJnlLineDimToProdDocDim</span></span>  

 <span data-ttu-id="d71bb-191">MoveJnlLineDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-191">MoveJnlLineDimToDocDim</span></span>  

 <span data-ttu-id="d71bb-192">MoveJnlLineDimToJnlLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-192">MoveJnlLineDimToJnlLineDim</span></span>  

 <span data-ttu-id="d71bb-193">CopyLedgEntryDimToLedgEntryDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-193">CopyLedgEntryDimToLedgEntryDim</span></span>  

 <span data-ttu-id="d71bb-194">MoveTempFromDimToTempToDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-194">MoveTempFromDimToTempToDim</span></span>  

 <span data-ttu-id="d71bb-195">TransferTempToDimToDocDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-195">TransferTempToDimToDocDim</span></span>  

 <span data-ttu-id="d71bb-196">MoveJnlLineDimToBuf</span><span class="sxs-lookup"><span data-stu-id="d71bb-196">MoveJnlLineDimToBuf</span></span>  

 <span data-ttu-id="d71bb-197">CopyICJnlDimToICJnlDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-197">CopyICJnlDimToICJnlDim</span></span>  

 <span data-ttu-id="d71bb-198">TestDimValue</span><span class="sxs-lookup"><span data-stu-id="d71bb-198">TestDimValue</span></span>  

 <span data-ttu-id="d71bb-199">TestNewDimValue</span><span class="sxs-lookup"><span data-stu-id="d71bb-199">TestNewDimValue</span></span>  

 <span data-ttu-id="d71bb-200">MoveDimBufToItemBudgetDim.</span><span class="sxs-lookup"><span data-stu-id="d71bb-200">MoveDimBufToItemBudgetDim.</span></span> <span data-ttu-id="d71bb-201">(Eliminare perché la tabella ItemBudgetDim viene eliminata).</span><span class="sxs-lookup"><span data-stu-id="d71bb-201">(Delete because the ItemBudgetDim Table is deleted.)</span></span>  

 <span data-ttu-id="d71bb-202">GetServContractDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-202">GetServContractDim</span></span>  

 <span data-ttu-id="d71bb-203">MoveTempDimToBuf</span><span class="sxs-lookup"><span data-stu-id="d71bb-203">MoveTempDimToBuf</span></span>  

 <span data-ttu-id="d71bb-204">UpdateSCInvLineDim</span><span class="sxs-lookup"><span data-stu-id="d71bb-204">UpdateSCInvLineDim</span></span>  

 <span data-ttu-id="d71bb-205">CopyJnlLineDimToBuffer</span><span class="sxs-lookup"><span data-stu-id="d71bb-205">CopyJnlLineDimToBuffer</span></span>  

 <span data-ttu-id="d71bb-206">UpdateDocDefaultDim2</span><span class="sxs-lookup"><span data-stu-id="d71bb-206">UpdateDocDefaultDim2</span></span>  

## <a name="see-also"></a><span data-ttu-id="d71bb-207">Vedi anche</span><span class="sxs-lookup"><span data-stu-id="d71bb-207">See Also</span></span>
 <span data-ttu-id="d71bb-208">[Dettagli di progettazione: Movimenti set di dimensioni](design-details-dimension-set-entries.md) </span><span class="sxs-lookup"><span data-stu-id="d71bb-208">[Design Details: Dimension Set Entries](design-details-dimension-set-entries.md) </span></span>  
 <span data-ttu-id="d71bb-209">[Dettagli di progettazione: Sintesi movimenti set di dimensioni](design-details-dimension-set-entries-overview.md) </span><span class="sxs-lookup"><span data-stu-id="d71bb-209">[Design Details: Dimension Set Entries Overview](design-details-dimension-set-entries-overview.md) </span></span>  
 <span data-ttu-id="d71bb-210">[Dettagli di progettazione: Ricerca delle combinazioni di dimensione](design-details-searching-for-dimension-combinations.md) </span><span class="sxs-lookup"><span data-stu-id="d71bb-210">[Design Details: Searching for Dimension Combinations](design-details-searching-for-dimension-combinations.md) </span></span>  
 <span data-ttu-id="d71bb-211">[Dettagli di progettazione: Struttura della tabella](design-details-table-structure.md) </span><span class="sxs-lookup"><span data-stu-id="d71bb-211">[Design Details: Table Structure](design-details-table-structure.md) </span></span>  
 [<span data-ttu-id="d71bb-212">Dettagli di progettazione: Esempi di codice dei modelli modificati nelle modifiche</span><span class="sxs-lookup"><span data-stu-id="d71bb-212">Design Details: Code Examples of Changed Patterns in Modifications</span></span>](design-details-code-examples-of-changed-patterns-in-modifications.md)

