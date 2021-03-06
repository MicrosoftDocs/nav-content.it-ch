---
title: Correggere o annullare le fatture di acquisto non pagate
description: Descrive come correggere o annullare una fattura di acquisto registrata e creare automaticamente una nota di credito di acquisto.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: undo, credit memo, return
ms.date: 08/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 294094f8483f9b51d47ad614b8702b289b9d1862
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-correct-or-cancel-unpaid-purchase-invoices"></a>Procedura: Correggere o annullare le fatture di acquisto non pagate
È possibile correggere o annullare una fattura di acquisto registrata. Ciò risulta utile se si desidera correggere un errore di digitazione o se si desidera modificare l'acquisto in una fase iniziale dell'elaborazione dell'ordine.

Se è già stato eseguito il pagamento dei prodotti nella fattura di acquisto registrata, non è possibile correggerli o annullarli dalla fattura di acquisto registrata. È necessario creare manualmente una nota di credito acquisto per stornare l'acquisto, facoltativamente gestito con un ordine di reso acquisto. Per ulteriori informazioni vedere [Procedura: Elaborare i resi o gli annullamenti acquisti](purchasing-how-process-purchase-returns-cancellations.md).

Nella finestra **Fattura acquisto registrata** è possibile scegliere il pulsante **Rettifica** o il pulsante **Annulla**. Quando si rettifica o si annulla una fattura di acquisto registrata, la nota di credito di acquisto viene applicata a tutti i movimenti contabili generali e di inventario creati quando la fattura di acquisto iniziale è stata registrata. Ciò consente di stornare la fattura di acquisto nei record finanziari e lascia la nota di credito di acquisto registrata correttiva per l'audit trail. Di seguito viene descritto l'utilizzo di **Rettifica** e di **Annulla**.

## <a name="to-correct-a-posted-purchase-invoice"></a>Per correggere una fattura di acquisto registrata
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Fatture di acquisto registrate**, quindi scegliere il collegamento correlato.  
2. Selezionare la fattura di acquisto che si desidera rettificare.  

    > [!NOTE]  
   >   Se viene selezionata la casella di controllo **Annullata**, non è possibile rettificare la fattura di acquisto registrata poiché è già stata rettificata o annullata.
3. Nella finestra **Fattura acquisto registrata** scegliere **Rettifica**.

    Viene creata una nuova fattura di acquisto con le stesse informazioni in cui è possibile apportare la rettifica. Per ulteriori informazioni, vedere [Procedura: Registrare gli acquisti](purchasing-how-record-purchases.md). Il campo **Annullato** nella fattura di acquisto registrata iniziale viene modificato in **Sì**.

    Una nota di credito di acquisto viene automaticamente creata e registrata per annullare la fattura di acquisto registrata iniziale.
4. Scegliere **Mostra nota credito di rettifica** per visualizzare la nota di credito di acquisto registrata che annulla la fattura di acquisto registrata iniziale.

## <a name="to-cancel-a-posted-purchase-invoice"></a>Per annullare una fattura di acquisto registrata
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Fatture di acquisto registrate**, quindi scegliere il collegamento correlato.  
2. Selezionare la fattura di acquisto che si desidera annullare.

    > [!NOTE]  
   >   Se viene selezionata la casella di controllo **Annullata**, non è possibile annullare la fattura di acquisto registrata poiché è già stata rettificata o annullata.
3. Nella finestra **Fattura acquisto registrata** scegliere **Annulla**.

    Una nota di credito di acquisto viene automaticamente creata e registrata per annullare la fattura di acquisto registrata iniziale. Il campo **Annullato** nella fattura di acquisto registrata iniziale viene modificato in **Sì**.
4. Scegliere **Mostra nota credito di rettifica** per visualizzare la nota di credito di acquisto registrata che annulla la fattura di acquisto registrata iniziale.

## <a name="see-also"></a>Vedi anche
[Acquisti](purchasing-manage-purchasing.md)  
[Procedura: Registrare gli acquisti](purchasing-how-record-purchases.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

