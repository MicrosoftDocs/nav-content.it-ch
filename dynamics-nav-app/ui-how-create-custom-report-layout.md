---
title: 'Procedura: Creare un layout dei report personalizzato'
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 90136439e09deb00a9aed9344fc5f89812caef3a
ms.contentlocale: it-ch
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-create-a-custom-report-layout"></a>Procedura: Creare un layout dei report personalizzato
Per impostazione predefinita, un report avrà un layout predefinito dei di RDLC, di Word o di entrambi i tipi. Non è possibile modificare i layout predefiniti. Tuttavia, è possibile creare i propri layout personalizzati che consentono di modificare l'aspetto del report quando è visualizzato, stampato o salvato. È possibile creare più layout del report personalizzati per lo stesso report e alternare il layout utilizzato in un report in base alle esigenze.

Per creare un layout personalizzato, è possibile effettuare una copia di un layout personalizzato esistente o aggiungere un nuovo layout personalizzato, che nella maggior parte dei casi è basato su un layout predefinito. Quando si aggiunge un nuovo layout personalizzato, è possibile scegliere di aggiungere un tipo di tipo layout del report di RDLC, di Word o entrambi. Il nuovo layout personalizzato si baserà automaticamente sul layout predefinito per il report, se ce n'è uno disponibile. Se non è presente un layout predefinito per il tipo, viene creato un nuovo layout vuoto che si dovrà progettare e modificare da zero. Per ulteriori informazioni sui layout di report RDLC e Word, sui layout personalizzati integrati e altro ancora, vedere [Gestire i layout dei report](ui-manage-report-layouts.md).  

## <a name="to-create-a-custom-layout"></a>Per creare un layout personalizzato
1. Nell'angolo superiore destro scegliere l'icona **Cerca pagina o report**, immettere **Selezione layout report**, quindi scegliere il collegamento correlato.  
Nella finestra **Selezione layout report** sono elencati tutti i report disponibili nella società che è specificata nel campo Società nella parte superiore della finestra.
2. Impostare il campo **Società** alla società per la quale si desidera creare il layout del report.
3. Selezionare la riga per il report per il quale si desidera creare il layout, quindi scegliere **Layout personalizzati**.  
Viene visualizzata la finestra **Layout report personalizzati** nella quale sono elencati tutti i layout personalizzati che sono disponibili per il report selezionato.
4. Per creare una copia di un layout personalizzato esistente, selezionare il layout desiderato nell'elenco, quindi scegliere **Copia**.  
La copia del layout personalizzato viene visualizzata nella finestra **Layout report personalizzati** e nel campo Descrizione è presente la dicitura Copia di.
5. Se si desidera aggiungere un nuovo layout personalizzato basato su un layout predefinito, attenersi alla seguente procedura:  
    1. Selezionare **Nuovo**. Viene visualizzata la finestra **Inserisci layout predefinito per un report**. I campi **ID** e **Nome** vengono automaticamente compilati.
    2. Per aggiungere un tipo di layout del report personalizzato di Word, selezionare la casella di controllo **Inserisci layout Word**.
    3. Per aggiungere un tipo di layout del report personalizzato di RDLC, selezionare la casella di controllo **Inserisci layout RDLC**.
    4. Scegliere il pulsante **OK**.  
    I nuovi layout personalizzati vengono visualizzati nella finestra **Layout report personalizzati**. Se un nuovo layout è basato su un layout predefinito, contiene le parole **Copia di un layout predefinito** nel campo **Descrizione**. Se non è disponibile alcun layout predefinito per il report, il nuovo layout presenta la dicitura **Nuovo layout** nel campo **Descrizione**. Questa dicitura indica che il layout personalizzato è vuoto.
6. Per impostazione predefinita, il campo **Nome società** è vuoto, il che significa che il layout personalizzato sarà disponibile per il report in tutte le società. Per rendere il layout personalizzato disponibile solo a una società specifica, scegliere **Modifica**, quindi impostare il campo **Nome società** sulla società desiderata.

## <a name="see-also"></a>Vedi anche
[Gestire i layout dei report](ui-manage-report-layouts.md)  
[Procedura: Modifica il layout attualmente utilizzato in un report](ui-how-change-layout-currently-used-report.md)
