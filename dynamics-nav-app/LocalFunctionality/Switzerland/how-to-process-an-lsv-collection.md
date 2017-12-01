---
title: 'Procedura: Elaborare una riscossione LSV'
description: "Utilizzare **Registrazioni LSV** per creare ed elaborare i pagamenti di clienti Lastschrift Verfahren (LSV+). È possibile registrare questi pagamenti nella registrazione incassi, creare un file LSV e stampare il RIBA."
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: a7503fec71d315d3a2bf4e9e1e3a734209990e14
ms.contentlocale: it-ch
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-process-an-lsv-collection"></a>Procedura: Elaborare una riscossione LSV
Utilizzare **Registrazioni LSV** per creare ed elaborare i pagamenti di clienti Lastschrift Verfahren (LSV+). È possibile registrare questi pagamenti nella registrazione incassi, creare un file LSV e stampare il RIBA. Per ulteriori informazioni, vedere la finestra Registrazioni incassi e [Procedura: Esportare pagamenti tramite LSV](how-to-export-payments-using-lsv.md).  

Quando si esegue il processo batch **Riscossione suggerimenti LSV**, ogni riscossione suggerita viene registrata nella riga registrazioni LSV e le fatture aperte vengono trasferite nelle registrazioni LSV. Per ulteriori informazioni, vedere la tabella Registrazioni LSV.  

È possibile visualizzare, modificare o eliminare le righe pagamenti suggeriti. Se si corregge l'importo suggerito, la differenza viene contrassegnata come uno sconto. È possibile eseguire più volte il processo batch per diversi gruppi di clienti. Le linee di suggerimento possono essere collocate nelle stesse registrazioni.  

## <a name="to-create-an-lsv-collection"></a>Per creare una riscossione LSV  

1.  Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "Cerca pagina o report"), immettere **Lista registrazioni LSV**, quindi scegliere il collegamento correlato.  
2.  Scegliere l'azione **Nuovo**.  
3.  Nella finestra **Lista registrazioni LSV** compilare i campi obbligatori come indicato nella tabella riportata di seguito.  

    |Campo|Descrizione|  
    |---------------------------------|---------------------------------------|  
    |**Codice banca LSV**|Selezionare il codice banca LSV per la banca che eseguirà la riscossione.|  
    |**Descrizione Registro LSV**|Immettere una descrizione per il movimento.|

4.  Selezionare il movimento registrazioni LSV e scegliere l'azione **Riscossione suggerimenti LSV** per creare i pagamenti da riscuotere automaticamente da LSV+.  
5.  Nella finestra **Riscossione suggerimenti LSV**, nella Scheda dettaglio **Opzioni** compilare i campi come descritto nella tabella seguente.  

    |Campo|Descrizione|  
    |---------------------------------|---------------------------------------|  
    |**Nr.**|Immettere il numero registrazioni LSV.|  
    |**Scadenza dal**|Specificare la data di scadenza iniziale per i movimenti aperti da suggerire per la riscossione.|  
    |**Scadenza fino al**|Specificare la data di scadenza finale per i movimenti aperti da suggerire per la riscossione.|  
    |**Data incasso**|Specifica la data di chiusura della riscossione. L'ordine LSV+ deve essere inviato almeno tre giorni lavorativi prima della data di riscossione.|  

6.  Scegliere il pulsante **OK**.  

Tutte le righe correlate vengono trasferite alle registrazioni LSV. Dopo aver elaborato la riscossione LSV, è possibile visualizzare, controllare o modificare i pagamenti suggeriti nella finestra **Registrazioni LSV**. Per ulteriori informazioni, vedere la tabella Riga delle registrazioni LSV.  

## <a name="to-manage-suggested-payments"></a>Per gestire i pagamenti suggeriti  

1.  Nella finestra **Lista registrazioni LSV**, selezionare il movimento registrazioni richiesto e scegliere l'azione **Riga delle registrazioni LSV**.  

    È possibile visualizzare e modificare i pagamenti suggeriti in questa finestra. È possibile inserire manualmente i pagamenti richiesti. Perle righe registrazioni nuove, il campo **Stato LSV** è impostato su **Aperto** per indicare che la fattura non è pagata.  

3.  Scegliere il pulsante **OK**.  

## <a name="see-also"></a>Vedere anche  
 [Pagamenti elettronici svizzeri tramite LSV+](swiss-electronic-payments-using-lsv-.md)   
 [Procedura: Chiudere una riscossione LSV](how-to-close-an-lsv-collection.md)   
 [Procedura: Registrare pagamenti LSV+](how-to-post-lsv-payments.md)   
 [Procedura: Esportare pagamenti tramite LSV](how-to-export-payments-using-lsv.md)

