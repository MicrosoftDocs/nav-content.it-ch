---
title: Come esportare pagamenti tramite LSV
description: "È possibile esportare o creare file LSV+ (Lastschrift Verfahren) che contengono informazioni sui pagamenti dopo aver chiuso la riscossione LSV. È possibile inviare i file generati alla banca su un disco oppure usare un trasferimento file elettronico, ad esempio tramite il servizio di online banking o tramite un portale Internet."
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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: e1dd42bb9338f431cc5bbdb78d579c54888a511b
ms.contentlocale: it-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-export-payments-using-lsv"></a>Procedura: Esportare pagamenti tramite LSV
È possibile esportare o creare file LSV+ (Lastschrift Verfahren) che contengono informazioni sui pagamenti dopo aver chiuso la riscossione LSV. È possibile inviare i file generati alla banca su un disco oppure usare un trasferimento file elettronico, ad esempio tramite il servizio di online banking o tramite un portale Internet.  

## <a name="to-export-payments-using-lsv"></a>Per esportare pagamenti tramite LSV  

1.  Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "Cerca pagina o report"), immettere **Lista registrazioni LSV**, quindi scegliere il collegamento correlato.  
2.  Nella finestra **Lista registrazioni LSV** selezionare le registrazioni LSV desiderate.  
3.  Scegliere l'azione **Scrivi file LSV**.  
4.  Nella finestra **Scrivi file LSV**, nella Scheda dettaglio **Opzioni** compilare i campi come descritto nella tabella seguente.  

    |Campo|Descrizione|  
    |---------------------------------|---------------------------------------|  
    |**Nr.**|Specifica il numero di registrazioni LSV da esportare.|  
    |**Test**|Specifica se si inviano consegne di prova alla banca. La banca non elabora file di test.|  

5.  Tutte le righe correlate vengono trasferite alle registrazioni LSV. Il file LSV viene generato nella cartella determinata in precedenza.  

## <a name="see-also"></a>Vedere anche  
 [Pagamenti elettronici svizzeri tramite LSV+](swiss-electronic-payments-using-lsv-.md)   
 [Procedura: Chiudere una riscossione LSV](how-to-process-an-lsv-collection.md)   
 [Procedura: Chiudere una riscossione LSV](how-to-close-an-lsv-collection.md)   
 [Procedura: Registrare pagamenti LSV+](how-to-post-lsv-payments.md)

