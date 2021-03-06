---
title: Come registrare pagamenti LSV+
description: "È possibile registrare pagamenti dopo aver ricevuto l'avviso di pagamento LSV+ (Lastschrift Verfahren) dalla banca."
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
ms.openlocfilehash: 628c8e23bbd6cdd1dd518d57eb05b1be6f1245fa
ms.contentlocale: it-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-post-lsv-payments"></a>Procedura: Registrare pagamenti LSV+
È possibile registrare pagamenti dopo aver ricevuto l'avviso di pagamento LSV+ (Lastschrift Verfahren) dalla banca.  

## <a name="to-post-lsv-payments"></a>Registrare pagamenti LSV+  

1.  Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni incassi**, quindi scegliere il collegamento correlato.  
2.  Selezionare le registrazioni richieste, quindi scegliere l'azione **Modifica registrazioni**.  

    > [!NOTE]  
    >  È possibile selezionare il batch registrazioni per LSV in cui è definito il conto di contropartita da considerare. Non è possibile importare più di una riga delle registrazioni LSV nelle stesse registrazioni incassi. Per ulteriori informazioni, vedere la finestra Registrazioni incassi.  

3.  Scegliere l'azione **Recupera da registrazioni LSV**.  
4.  Nella finestra **Lista registrazioni LSV** selezionare la riga di registrazioni LSV da importare nelle registrazioni incassi.  

    > [!NOTE]  
    >  È possibile importare solo righe di registrazioni in cui il campo **Stato LSV** è impostato su **File creato**.  

5.  Scegliere il pulsante **OK**.  

    La riga delle registrazioni LSV viene importata nelle registrazioni incassi. Il valore del campo **Stato LSV** nella finestra **Lista registrazioni LSV** viene modificato da **File creato** a **Completato**.  

    È possibile verificare i pagamenti importati e confrontarli con l'avviso di pagamento bancario nella finestra **Registrazioni incassi**. È anche possibile eliminare le righe di pagamento che la banca non ha potuto elaborare e per cui è necessario contattare direttamente il cliente.  

6.  Scegliere l'azione **Registra**.  

## <a name="see-also"></a>Vedere anche  
 [Pagamenti elettronici svizzeri tramite LSV+](swiss-electronic-payments-using-lsv-.md)   
 [Procedura: Chiudere una riscossione LSV](how-to-process-an-lsv-collection.md)   
 [Procedura: Chiudere una riscossione LSV](how-to-close-an-lsv-collection.md)   
 [Procedura: Esportare pagamenti tramite LSV](how-to-export-payments-using-lsv.md) 

