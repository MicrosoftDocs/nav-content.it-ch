---
title: Come prelevare per le operazioni interne in configurazioni di warehouse avanzate
description: "Nelle configurazioni di warehouse avanzate in cui l'ubicazione è impostata in modo da utilizzare sia il prelievo che la spedizione, è possibile prelevare componenti per le attività di assemblaggio e produzione tramite la finestra **Prelievo warehouse**."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 08b79f573a9fc013068f7e1f5dd593a596a579a3
ms.contentlocale: it-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-pick-for-assembly-or-production-in-advanced-warehouse-configurations"></a>Procedura: Prelevare per assemblaggio o produzione in configurazioni di warehouse avanzate
Nelle configurazioni di warehouse avanzate in cui l'ubicazione è impostata in modo da utilizzare sia il prelievo che la spedizione, è possibile prelevare componenti per le attività di assemblaggio e produzione tramite la finestra **Prelievo warehouse**.  

In alternativa, è possibile utilizzare la finestra **Prospetto movimentazioni** per spostare gli articoli tra le collocazioni ad hoc, ovvero senza riferimento a un documento di origine. Per ulteriori informazioni, vedere [Procedura: Spostare articoli in configurazioni di warehouse avanzate](warehouse-how-to-move-items-in-advanced-warehousing.md).  

Per informazioni sugli articoli di prelievo per le operazioni interne nelle ubicazioni di warehouse impostate per prelevare solo, vedere [Procedura: Spostare componenti in un'area di operazione nelle configurazioni di warehouse di base](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md)..  

Non è possibile creare un documento di prelievo warehouse da zero perché un'attività di prelievo fa sempre parte di un flusso di lavoro, in uno scenario di tipo push o pull.  

È possibile creare il documento di prelievo warehouse in modalità push selezionando **Crea prelievo whse.** nel documento di origine, ad esempio un ordine di assemblaggio rilasciato o una spedizione warehouse. Per ulteriori informazioni, vedere [Procedura: Prelevare articoli con prelievi warehouse](warehouse-how-to-pick-items-for-warehouse-shipment.md).  

In alternativa, è possibile creare il documento di prelievo warehouse in modalità pull mediante la finestra **Prospetto prelievi** per verificare le richieste di prelievo, sia per la spedizione che per le operazioni interne, quindi creare i documenti di prelievo warehouse necessari.  

La procedura seguente illustra uno scenario di tipo pull in cui si prelevano componenti per un ordine di produzione rilasciato tramite la finestra **Prospetto prelievi**. La procedura si applica anche a un ordine di assemblaggio.  

Per creare richieste di prelievo, sia per scenari pull e push, i documenti di origine in questione devono essere rilasciati. Rilasciare i documenti di origine per le operazioni interne nei seguenti modi.  

|Documento origine|Metodo di rilascio|  
|---------------------|--------------------|  
|Ordine di produzione|Modificare il tipo di ordine in Ordine produzione rilasciato.|  
|Ordine di assemblaggio|Modificare lo stato in Rilasciato.|  

## <a name="to-pick-components-using-the-pick-worksheet"></a>Per prelevare componenti mediante i prospetti prelievi  
1.  Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Prospetto prelievi**, quindi scegliere il collegamento correlato.  
2.  Scegliere l'azione **Prendi documenti warehouse**, quindi selezionare le righe componenti dall'ordine di produzione rilasciato.  
3.  Controllare le righe, ordinarle in modo da ottenere un percorso di prelievo efficiente e combinarle con altre righe del prospetto, se necessario, in modo da ottimizzare i tempi di esecuzione delle attività da parte degli addetti al magazzino.  
4.  Scegliere l'azione **Crea prelievo**.  
5.  Definire come creare documenti di prelievo warehouse e come ordinare le righe prelievo compilando i campi nella finestra **Crea prelievo**.  
6.  Scegliere il pulsante **OK**. I documenti di prelievo warehouse vengono creati con le righe prelievo per ogni componente richiesto nell'operazione interno.  

Se l'area dell'operazione interna, ad esempio il reparto di produzione, è impostata con una collocazione di default per il posizionamento dei componenti da utilizzare nell'operazione, il codice collocazione viene inserito nelle righe dell'area nel documento di prelievo warehouse per indicare agli addetti warehouse dove posizionare gli articoli. Per ulteriori informazioni, vedere il campo **Cod. coll. art. per produzione** o **Cod. coll. art. per assembl**.

## <a name="filling-the-consumption-bin"></a>Rifornimento della collocazione di consumo
Questo diagramma di flusso illustra in che modo il campo **Cod. collocazione** nelle righe del componente dell'ordine di produzione viene compilato in base al setup dell'ubicazione.

![Diagramma di flusso collocazione](media/binflow.png "BinFlow")  

## <a name="see-also"></a>Vedi anche
[Gestione warehouse](warehouse-manage-warehouse.md)  
[Magazzino](inventory-manage-inventory.md)  
[Impostazione gestione warehouse](warehouse-setup-warehouse.md)     
[Gestione assemblaggio](assembly-assemble-items.md)    
[Dettagli di progettazione: Gestione warehouse](design-details-warehouse-management.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

