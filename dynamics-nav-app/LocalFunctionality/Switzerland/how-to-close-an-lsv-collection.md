---
title: Come chiudere una riscossione LSV
description: "Per scrivere file LSV che possono essere inviati alla banca per la riscossione dei pagamenti, è necessario chiudere le riscossioni Lastchrift Verfahren (LSV+). Quando si chiude una riscossione, questa risulta completata e vengono combinati gli inserimenti nelle registrazioni LSV."
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
ms.openlocfilehash: 1d63f24a50024f4561b5827f2b6b1328c207a873
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-close-an-lsv-collection"></a>Procedura: Chiudere una riscossione LSV
Per scrivere file LSV che possono essere inviati alla banca per la riscossione dei pagamenti, è necessario chiudere le riscossioni Lastchrift Verfahren (LSV+). Quando si chiude una riscossione, questa risulta completata e vengono combinati gli inserimenti nelle registrazioni LSV.  
  
 Quando la riscossione è completata, il numero di riscossione corrente viene assegnato nelle registrazioni LSV, in base all'ultima riscossione. Tale numero LSV viene trasferito ai movimenti clienti per tutte le fatture inevase. Il file di riscossione può essere ricostruito in qualsiasi momento tramite il numero LSV. Il campo **In sospeso** viene inoltre popolato con il valore **LSV** nei movimenti clienti per evitare la duplicazione dei movimenti aperti. Per ulteriori informazioni, vedere le tabelle **Registrazioni LSV** e **Mov. contabili clienti**. È inoltre possibile riaprire una riscossione chiusa.  
  
### <a name="to-close-an-lsv-collection"></a>Per chiudere una riscossione LSV  
  
1.  Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Lista registrazioni LSV**, quindi scegliere il collegamento correlato.  
  
2.  Selezionare le registrazioni desiderate, quindi nella scheda **Azioni**, nel gruppo **Funzioni** selezionare **Modifica data di registrazione**. In questo modo verrà modificato il valore nel campo **Data movimento Avere** usando il valore suggerito durante la riscossione LSV.  
  
3.  Nel campo **Nuova data** immettere la nuova data.  
  
4.  Nel gruppo **Funzioni** della scheda **Azioni** selezionare **Chiudi riscossione**.  
  
    > [!NOTE]  
    >  I campi nella Scheda dettaglio **Opzioni** per il processo batch **Chiudi riscossione LSV** non possono essere modificati e corrispondono alla riga di registrazioni selezionata.  
  
5.  Scegliere il pulsante **OK**.  
  
     Nella finestra **Lista registrazioni LSV** il valore del campo **Stato LSV** viene modificato da **Modifica** a **Rilasciato**. Le righe di registrazioni non possono più essere modificate.  
  
### <a name="to-reopen-an-lsv-collection"></a>Per riaprire una riscossione LSV  
  
1.  Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Lista registrazioni LSV**, quindi scegliere il collegamento correlato.  
  
2.  Selezionare la riga di registrazioni per cui si desidera riaprire la riscossione, nella scheda **Azioni**, nel gruppo **Funzioni** selezionare **Riapri riscossione**.  
  
    > [!NOTE]  
    >  È possibile riaprire la riscossione solo se il file LSV+ non è ancora stato inviato alla banca.  
  
3.  Scegliere il pulsante **Sì** per confermare la riapertura della riscossione.  
  
## <a name="see-also"></a>Vedere anche  
 [Pagamenti elettronici svizzeri tramite LSV+](swiss-electronic-payments-using-lsv-.md)   
 [Procedura: Chiudere una riscossione LSV](how-to-process-an-lsv-collection.md)   
 [Procedura: Registrare pagamenti LSV+](how-to-post-lsv-payments.md)   
 [Procedura: Esportare pagamenti tramite LSV](how-to-export-payments-using-lsv.md)   
 Registro LSV   
 Riga registrazione LSV   
 Mov. contabili clienti
