---
title: Come impostare i centri di costo
description: "I centri di costo sono i reparti responsabili dei costi e delle entrate. Il grafico dei centri di costo è simile alle informazioni sulle dimensioni relative alla contabilità generale."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 97c462edcfbc15153eb64037869c7e9e048e1fa1
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-cost-centers"></a>Procedura: Impostare i centri di costo
I centri di costo sono i reparti responsabili dei costi e delle entrate. Il grafico dei centri di costo è simile alle informazioni sulle dimensioni relative alla contabilità generale. È possibile impostare il grafico dei centri di costo nelle modalità seguenti:  

-   Trasferire i valori dimensioni nella contabilità generale al grafico dei centri di costo. È possibile apportare tutte le rettifiche necessarie dopo il trasferimento.  
-   Creare un nuovo grafico del centro di costo che sia indipendente dalla contabilità generale o aggiungere un nuovo centro di costo a un grafico del centro di costo esistente. È necessario creare ogni centro di costo singolarmente.  

## <a name="to-transfer-dimension-values-in-the-general-ledger-to-the-chart-of-cost-centers"></a>Per trasferire i valori dimensioni nella contabilità generale al grafico dei centri di costo  
1.  Impostare una dimensione come dimensione centro di costo nella finestra **Aggiorna dimensioni cont. industriale** . Solo i valori di questa dimensione vengono trasferiti.  
2.  Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Piano dei centri di costo**, quindi scegliere il collegamento correlato.  
3.  Nel gruppo **Funzioni** della scheda **Azioni** selezionare **Ottieni centri di costo da dimensione** per trasferire i valori dimensioni al grafico dei centri di costo. Con la funzione è possibile trasferire i valori dimensioni definiti nel passaggio 1.  

    > [!NOTE]  
    >  È possibile impostare il campo **Allinea dimensione centro di costo** per definire una sincronizzazione unidirezionale dei valori delle dimensioni della contabilità generale con il piano dei centri di costo. Non è possibile definire una sincronizzazione del grafico dei centri di costo con i valori dimensioni della contabilità generale.  

Il grafico dei centri di costo contiene ora tutti i valori dimensioni specificati della contabilità generale e include i titoli e i subtotali.  

## <a name="to-create-new-cost-centers-in-the-chart-of-cost-centers-window"></a>Per creare nuovi centri di costo nella finestra Piano dei centri di costo  
È possibile impostare e gestire centri di costo nella scheda **Scheda centro di costo** o nella finestra **Piano dei centri di costo**. In questa procedura è possibile impostare i centri di costo nella finestra  **Piano dei centri di costo**.  

1. Aprire la finestra **Piano dei centri di costo** in modalità di modifica.  
2. Nel campo  **Codice** immettere il codice centro di costo. Tutti i centri di costo devono disporre di un codice.  
3. Nel campo **Nome** immettere il nome del centro di costo.  
4. Fare clic sulla freccia a discesa nel campo **Tipo riga** per specificare lo scopo del centro di costo.  

    - Per i centri di costo di tipo **Totale** compilare il campo **Totale**. Utilizzare l'operatore **or**, che è una barra verticale (**&#124;**) per impostare intervalli di centri di costo.  
    - Per i centri di costo del tipo di riga **Fine-Totale**, questo campo viene compilato automaticamente quando si utilizza la funzione di indentazione.  
5.  Compilare i campi **Ordinamento** e **Sottotipo costo**.  
6.  Scegliere la successiva riga vuota per creare un nuovo centro di costo, quindi ripetere i passaggi da 2 a 5.  
7.  Dopo aver impostato tutti i centri di costo, scegliere l'azione **Indentazione centri di costo**. Scegliere il pulsante **Sì**.  

> [!IMPORTANT]  
>  Se sono state immesse definizioni nei campi **Totale** per i centri di costo **Fine-Totale** prima di eseguire la funzione di indentazione, è necessario inserirle di nuovo. Questa funzione consente di sovrascrivere i valori in tutti i campi **Fine-Totale**.  

## <a name="see-also"></a>Vedi anche  
[Contabilizzazione dei costi](finance-manage-cost-accounting.md)  
[Impostazione della contabilità industriale](finance-set-up-cost-accounting.md)   
[Terminologia della contabilità industriale](finance-terminology-in-cost-accounting.md)   
[Informazioni sulla contabilità industriale](finance-about-cost-accounting.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

