---
title: Come vedere insieme articoli assemblaggio su ordine e articoli in magazzino
description: "Se un articolo di assemblaggio è impostato per l'assemblaggio per magazzino, il processo dell'ordine di vendita di default presuppone che l'articolo sia già assemblato e che possa essere prelevato dal magazzino, se disponibile. Tuttavia se una parte (o tutta) della quantità non è disponibile, è possibile scegliere al volo di creare un ordine di assemblaggio per la quantità rimanente."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/15/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 3c03adc34e009bada13f0f4ff36267d39a987749
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-sell-assemble-to-order-items-and-inventory-items-together"></a>Procedura: Vedere insieme articoli assemblaggio su ordine e articoli in magazzino
Se il campo **Criteri di assemblaggio** nella scheda articolo di un articolo di assemblaggio contiene **assemblaggio per magazzino**, il processo di default dell'ordine di vendita presuppone che l'articolo sia già assemblato e possa essere prelevato dal magazzino, se disponibile. Di conseguenza, un ordine di assemblaggio non viene automaticamente creato e collegato alla riga dell'ordine di vendita. Tuttavia, se la quantità, interamente o in parte, non è disponibile, è possibile creare un ordine di assemblaggio per la quantità rimanente compilando il campo **Qtà per assemblaggio su ordine** nella riga dell'ordine di vendita. In questo modo, è possibile assemblare l'articolo su ordine anche se di default è impostato per l'assemblaggio per magazzino.  

Tale flessibilità è disponibile quando si vendono articoli da assemblare su ordine e in magazzino è presente una parte della quantità, che si desidera dedurre dall'ordine di assemblaggio. Per altre informazioni, vedere [Procedura: Vendere gli articoli di magazzino nei flussi assemblaggio su ordine](assembly-how-to-sell-inventory-items-in-assemble-to-order-flows.md).  

> [!NOTE]  
>  Alcune regole si applicano al campo **Qtà da spedire** nelle righe dell'ordine di vendita che contengono una combinazione di quantità per l'assemblaggio su ordine e quantità di magazzino. Per altre informazioni, vedere la sezione "Scenari di combinazione" in [Assemblaggio su ordine e assemblaggio per magazzino](assembly-assemble-to-order-or-assemble-to-stock.md).  

> [!NOTE]  
>  La procedura seguente non include i passaggi dell'ordine di vendita standard che occorre eseguire prima di creare un ordine di assemblaggio per le quantità non disponibili.

## <a name="to-sell-assemble-to-order-items-and-inventory-items-together"></a>Per vendere articoli di assemblaggio su ordine e articoli di magazzino insieme  
1.  In una riga dell'ordine di vendita per un articolo impostato per l'assemblaggio per magazzino, immettere una quantità che supera quella di magazzino nel campo **Quantità**. Viene visualizzata la finestra **Controllo disponibilità**. Per altre informazioni, vedere [Procedura: Visualizzare la disponibilità di articoli](inventory-how-availability-overview.md). 
2.  Si noti il campo **Quantità totale** (valore negativo), in cui si immetterà un valore nel passaggio successivo.  
3.  Nel campo **Qtà. per assemblaggio su ordine** immettere il valore del passaggio precedente.  
4.  Applicare eventuali modifiche ai componenti di assemblaggio. Per ulteriori informazioni, vedere [Procedura: Vendere articoli assemblati su ordine](assembly-how-to-sell-items-assembled-to-order.md).  
5.  Continuare per rilasciare l'ordine di vendita, prepararlo per il prelievo degli articoli di magazzino e per l'assemblaggio degli articoli non disponibili. Per ulteriori informazioni su questi passaggio di assemblaggio standard, vedere [Procedura: Assemblare articoli](assembly-how-to-assemble-items.md).  

> [!CAUTION]  
>  Il campo **Codice collocazione** nell'ordine di vendita può essere precompilato in base al campo **Cod. coll. sp. ass. su ordine** o il campo **Cod. coll. art. da assembl.** nella scheda ubicazione. In tal caso, il campo **Codice collocazione** nella riga dell'ordine di vendita può essere errato in questa combinazione di quantità di assemblaggio su ordine e assemblaggio per magazzino. Si consiglia di esaminare il campo **Codice collocazione** e verificare che il posizionamento funzioni per tutte le quantità. In alternativa, immettere due quantità diverse in righe separate dell'ordine di vendita.  

## <a name="see-also"></a>Vedi anche  
[Gestione assemblaggio](assembly-assemble-items.md)  
[Procedura: Utilizzare le distinte base](inventory-how-work-BOMs.md)  
[Magazzino](inventory-manage-inventory.md)  
[Dettagli di progettazione: Gestione warehouse](design-details-warehouse-management.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

