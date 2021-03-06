---
title: Come esportare e importare workflow
description: "Per trasferire i workflow ad altri database di [!INCLUDE[d365fin](includes/d365fin_md.md)], ad esempio per risparmiare tempo durante la creazione di nuovi workflow, è possibile esportare e importare i workflow."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7ce7c6bd83efaacaed53f5d5ca5c2eb1521c0e6e
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-export-and-import-workflows"></a>Procedura: Esportare e importare workflow
Per trasferire i workflow ad altri database di [!INCLUDE[d365fin](includes/d365fin_md.md)], ad esempio per risparmiare tempo durante la creazione di nuovi workflow, è possibile esportare e importare i workflow.  

 Un altro modo per creare rapidamente i flussi di lavoro prevede la creazione dei flussi di lavoro dai modelli di flusso di lavoro. Per ulteriori informazioni, vedere [Procedura: Creare workflow da modelli di workflow](across-how-to-create-workflows-from-workflow-templates.md).  

 Nella finestra **Workflow** creare un workflow elencando le fasi interessate nelle righe. Ogni fase consiste in un evento del flusso di lavoro, moderato dalle condizioni di evento, e in una risposta del flusso di lavoro, moderata dalle opzioni di risposta. È possibile definire le fasi workflow compilando i campi delle righe del workflow in base a elenchi fissi di valori di evento e di risposta che rappresentano gli scenari supportati dal codice dell'applicazione. Per ulteriori informazioni, vedere [Procedura: Creare workflow](across-how-to-create-workflows.md).  

## <a name="to-export-a-workflow"></a>Per esportare un flusso di lavoro  
1.  Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Workflow** e quindi scegliere il collegamento correlato.  
2.  Selezionare un workflow e scegliere l'azione **Esporta in file**.  
3.  Nella finestra **Esporta file** fare clic sul pulsante **Salva**.  
4.  Nella finestra **Esporta** selezionare un percorso per il file e scegliere il pulsante **Salva**.  

## <a name="to-import-a-workflow"></a>Per importare un flusso di lavoro  
1.  Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Workflow** e quindi scegliere il collegamento correlato.  
2.  Selezionare l'azione **Importa da file**.  
3.  Nella finestra **Importa** selezionare il file XML contenente il flusso di lavoro e quindi scegliere il pulsante **Apri**.  

> [!CAUTION]  
>  Se il codice del flusso di lavoro è già esistente nel database, i passaggi del flusso di lavoro verranno sovrascritti dai passaggi il flusso di lavoro importato.  

## <a name="see-also"></a>Vedi anche  
 [Procedura: Creare workflow](across-how-to-create-workflows.md)   
 [Procedura: Creare workflow da modelli di workflow](across-how-to-create-workflows-from-workflow-templates.md)   
 [Procedura: Visualizzare le istanze di fasi workflow archiviate](across-how-to-view-archived-workflow-step-instances.md)   
 [Procedura: Eliminare i workflow](across-how-to-delete-workflows.md)   
 [Procedura dettagliata: Impostazione e utilizzo di un workflow di approvazione di acquisto](walkthrough-setting-up-and-using-a-purchase-approval-workflow.md)   
 [Impostazione dei workflow](across-set-up-workflows.md)   
 [Utilizzo dei workflow](across-use-workflows.md)   
 [Workflow](across-workflow.md)   

