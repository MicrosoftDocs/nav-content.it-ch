---
title: Chiusura dei periodi contabili per un anno fiscale
description: Descrive come chiudere i periodi contabili alla base di un anno fiscale.
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: year closing, close accounting period, close fiscal year, bank account detailed trial balance
ms.date: 06/02/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: d47196460cf5a52beaa3e94e9a39d3ad8e6b0655
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-close-accounting-periods"></a>Procedura: Chiudere i periodi contabili
Al termine di un anno fiscale, è necessario chiudere i periodi di cui è costituito.

## <a name="to-close-accounting-periods"></a>Per chiudere periodi contabili
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Periodi contabili**, quindi scegliere il collegamento correlato.
2. Nella finestra **Periodi contabili** scegliere l'azione **Chiudi anno**.

    Se più anni fiscali sono aperti, viene automaticamente selezionato quello meno recente per la chiusura. Viene visualizzato un messaggio che identifica l'anno che verrà chiuso e le conseguenze di tale operazione.
3. Per chiudere l'anno, scegliere il pulsante **Sì**.

L'anno fiscale viene chiuso e vengono selezionati i campi **Chiuso** e **Data bloccata** per tutti i periodi dell'anno. L'anno fiscale non può essere riaperto e i segni di spunta nei campi **Chiuso** e **Data bloccata** non possono essere rimossi.

> [!NOTE]  
>   Non è possibile chiudere un anno fiscale prima di crearne uno nuovo. Si noti che una volta chiuso un anno fiscale, non è possibile modificare la data iniziale di quello successivo.

Anche se l'anno fiscale è stato chiuso, è possibile registrarvi dei movimenti C/G. In questo caso, i movimenti vengono contrassegnati come registrati in un anno fiscale chiuso e viene selezionato il campo **Mov. anno prec.**

Una volta chiuso un anno fiscale, è necessario chiudere i conti economici e trasferire i risultati dell'anno su un conto nello stato patrimoniale. È possibile ripetere queste operazioni ogni volta che si effettua una registrazione sull'anno fiscale chiuso.

## <a name="see-also"></a>Vedi anche
[Chiusura registri](year-close-books.md)  
[Procedura: Registrare il movimento di chiusura di fine anno](year-how-post-year-end-close-entry.md)  
[Procedura: aprire un nuovo anno fiscale](finance-how-open-new-fiscal-year.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

