---
title: Come utilizzare famiglie di articoli nella produzione
description: "L'operazione principale da eseguire per personalizzare un calendario di base per la propria società, o per uno dei partner commerciali, è la modifica dello stato dei giorni lavorativi e non lavorativi."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/05/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4ad54585baef119db06bf69476739174af1209bb
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-work-with-production-families"></a>Procedura: Utilizzare famiglie di prodotti
Una famiglia di prodotti consiste in un gruppo di articoli individuali la cui relazione si basa sulla similarità dei rispettivi processi di lavorazione. Formando delle famiglie di produzione, è possibile che alcuni articoli siano lavorati due o più volte nel corso di una produzione; questa operazione ottimizzerà il consumo di materiale.

Nel campo **Quantità** della finestra **Famiglie di prodotti**, immettere la quantità che sarà prodotta quando l'intera famiglia sarà stata lavorata una volta.

## <a name="example"></a>Esempio
Nei processi di perforazione, è possibile che da una lamina vengano prodotti contemporaneamente quattro pezzi di un articolo e 10 pezzi di un altro articolo differente. La perforatrice perforerà tutti i 14 pezzi in un'unica fase.

La creazione di famiglie di produzione riduce le quantità di scarto perché ciò che generalmente costituisce gli scarti rimanenti dalla produzione di pezzi di grandi dimensioni viene utilizzato per produrre i pezzi di piccole dimensioni.

## <a name="to-set-up-a-production-family"></a>Per impostare una famiglia di prodotti
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Famiglie di prodotti**, quindi scegliere il collegamento correlato.
2. Compilare i campi come necessario. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-produce-based-on-a-production-familily"></a>Per produrre in base a una famiglia di prodotti
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Ord. produzione confermato**, quindi scegliere il collegamento correlato.
2. Creare un nuovo ordine di produzione. Per ulteriori informazioni, vedere [Procedura: Creare ordini di produzione](production-how-to-create-production-orders.md).
3. Nel campo **Tipo origine**, selezionare **Famiglie di prodotti**.  
4. Nel campo **Nr. risorsa**, selezionare la famiglia di prodotti pertinente.

## <a name="see-also"></a>Vedi anche
[Procedura: Creare distinte base di produzione](production-how-to-create-production-boms.md)  
[Impostazione della produzione](production-configure-production-processes.md)  
[Manufacturing](production-manage-manufacturing.md)    
[Pianif.](production-planning.md)   
[Magazzino](inventory-manage-inventory.md)  
[Acquisti](purchasing-manage-purchasing.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

