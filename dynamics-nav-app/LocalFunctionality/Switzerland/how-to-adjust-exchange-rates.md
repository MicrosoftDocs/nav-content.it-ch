---
title: Come rettificare i tassi di cambio
description: "Se è presente una vendita imponibile in una valuta estera, è necessario usare il tasso ufficiale per la conversione di valuta IVA, come definito dall'ente Federal Tax Administration."
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
ms.openlocfilehash: 1a1732d1aee02919a5a5e19670d8903e53e65a78
ms.contentlocale: it-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-adjust-exchange-rates"></a>Procedura: Come rettificare i tassi di cambio
Se è presente una vendita imponibile in una valuta estera, è necessario usare il tasso ufficiale per la conversione di valuta IVA, come definito dall'ente Federal Tax Administration.  

Se tali tassi non corrispondono ai tassi di valuta usati nelle fatture di acquisto o di vendita, in seguito sarà necessario rettificare le aliquote IVA con un processo batch. Tali rettifiche possono essere eseguite solo tramite un'aliquota IVA autorizzata.  

È possibile eseguire questo processo batch ogni volta che si desidera, purché si verifichi di eseguirlo sempre prima di creare una dichiarazione IVA.  

> [!NOTE]  
>  Quando si usa una valuta contabile, verificare che il campo **Rettif. tasso di cambio IVA** nella finestra **Setup contabilità generale** sia impostato su **Nessuna rettifica**.  

Per ulteriori informazioni sulla valute IVA ed estere, vedere il sito Web [ESTV](http://go.microsoft.com/fwlink/?LinkId=285999).  

## <a name="to-adjust-an-exchange-rate"></a>Per rettificare un tasso di cambio  

1.  Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Valute**, quindi scegliere il collegamento correlato.  
2.  Scegliere l'azione **Tassi di cambio**.  
3.  Nella finestra **Tassi di cambio valuta** immettere l'aliquota IVA ufficiale per periodo per ogni valuta nei campi **Importo tasso di cambio IVA** e **Importo tasso di cambio IVA relazionale**.  
4.  Scegliere il pulsante **OK**.  
5.  Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Rettifica tassi di cambio**, quindi scegliere il collegamento correlato.  
6.  Nella Scheda dettaglio **Opzioni** compilare i campi come descritto nella tabella riportata di seguito.   

    |Campo|Descrizione|  
    |---------------------------------|---------------------------------------|  
    |**Data inizio**|Immettere una data per specificare l'inizio del periodo per cui verranno rettificati i movimenti.|  
    |**Data fine**|Immettere la data finale per la quale i movimenti verranno rettificati. Solitamente questa data equivale alla data di registrazione indicata nel campo **Data di registrazione**.|  
    |**Rettifica cambio per ammin. IVA**|Specificare se si desidera rettificare il tasso di cambio IVA.|  

7.  Scegliere **Stampa** per avviare il processo batch. Il processo batch controlla se i movimenti IVA devono essere rettificati e prepara un movimento di rettifica per ciascuno di tali movimenti per i conti di rettifica del tasso di cambio per IVA a esigibilità immediata o differita. Vengono rettificati anche i movimenti IVA esistenti.  

## <a name="see-also"></a>Vedere anche  
 [IVA svizzera](swiss-value-added-tax.md)   
 [Aliquote IVA per la Svizzera](vat-rates-for-switzerland.md)   
[Procedura: Aggiornare i tassi di cambio delle valute](../../finance-how-update-currencies.md)

