---
title: Collegare i movimenti in diverse valute
description: "Se si effettua una vendita in una valuta e si riceve il pagamento in un'altra, è possibile collegare il movimento contabile in più valute."
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: multiple currencies, payment, reconcile
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f323b98472f3e2ef0f28000f8a9140b066206945
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enable-application-of-ledger-entries-in-different-currencies"></a>Procedura: Abilitare il collegamento dei movimenti contabili fornitore in valute diverse
Se si acquista da un fornitore con una valuta e si paga con un'altra valuta, è possibile collegare il pagamento all'acquisto.

In modo analogo, se si effettua una vendita a un cliente in una valuta e si riceve il pagamento in un'altra, è possibile collegare il pagamento alla fattura di vendita.

Nella procedura riportata di seguito viene descritto come configurare questa impostazione per i movimenti contabili fornitori nella finestra **Setup contabilità fornitori e acquisti**. L'impostazione è simile per i movimenti contabili clienti nella finestra **Setup contabilità clienti e vendite**.

## <a name="to-enable-application-of-vendor-ledger-entries-in-different-currencies"></a>Per abilitare il collegamento dei movimenti contabili fornitore in valute diverse
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Setup contabilità fornitori e acquisti**, quindi scegliere il collegamento correlato.
2. Nel campo **Collegamenti tra valute** selezionare una delle seguenti opzioni:

| Opzione | Descrizione |
| --- | --- |
| Nessuno |Collegamento fra valute non consentito. |
| UE |Collegamento fra valute UE consentito |
| Tutto |Collegamento fra tutte le valute consentito |

## <a name="to-set-up-gl-accounts-for-currency-application-rounding-differences"></a>Per impostare i conti C/G per le differenze di arrotondamento di applicazione delle valute  
Se movimenti in diverse valute vengono collegati, è necessario impostare il conto di contabilità generale in cui verranno registrate le differenze di arrotondamento.  

> [!NOTE]  
>  È necessario impostare i conti di contabilità generale prima di completare il task. Per ulteriori informazioni, vedere [Contabilità generale e piano dei conti](finance-general-ledger.md).

1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Categorie registrazione clienti**, quindi scegliere il collegamento correlato.  
2. Nei campi **Conto dare arrot. coll. val.** e **Conto avere arrot. coll. val.** immettere i conti di contabilità generale pertinenti per registrare le differenze di arrotondamento.  
3. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Categorie registrazione fornitori**, quindi selezionare il collegamento correlato.  
4. Nei campi **Conto dare arrot. coll. val.** e **Conto avere arrot. coll. val.** immettere i conti di contabilità generale pertinenti per registrare le differenze di arrotondamento.  

## <a name="see-also"></a>Vedi anche
[Gestione della contabilità fornitori](payables-manage-payables.md)  
[Gestione della contabilità clienti](receivables-manage-receivables.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

