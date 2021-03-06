---
title: Panoramica dei task per la gestione degli incassi
description: Descrive i task per gestire gli incassi e collegare il pagamento ai movimenti contabili cliente o fornitore.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customer payment, debtor, balance due, AR
ms.date: 08/10/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: b9a486d099a6a52bec6ac6b23c21a3c341c20b14
ms.contentlocale: it-ch
ms.lasthandoff: 10/23/2017

---
# <a name="managing-receivables"></a>Gestione della contabilità clienti
Un passaggio normale nell'iter finanziario consiste nel riconciliare i conti correnti bancari. Per questa operazione è necessario che i pagamenti vengano collegati ai movimenti del registro fornitori o clienti in modo da chiudere le fatture di vendita e le note di credito di acquisto.  

In [!INCLUDE[d365fin](includes/d365fin_md.md)] uno dei modi più rapidi per registrare pagamenti nella finestra **Registrazione riconciliazione pagamenti** consiste nell'importare un file di rendiconto bancario o un feed. I pagamenti sono collegati ai movimenti contabili aperti per clienti o fornitori in base alle corrispondenze tra il testo di pagamento e le informazioni del movimento. È possibile esaminare e modificare le corrispondenze prima di contabilizzare le registrazioni e chiudere i movimenti dei conti correnti bancari per i movimenti contabili quando tale registrazione viene contabilizzata. Il conto bancario viene riconciliato una volta che tutti i pagamenti sono collegati.

Esistono, tuttavia, altre aree pratiche per collegare i pagamenti e riconciliare i conti correnti bancari:  

* La finestra **Riconciliazione C/C bancari** che consente anche di verificare i movimenti contabili. Per ulteriori informazioni, vedere [Procedura: Riconciliare i conti bancari separatamente](bank-how-reconcile-bank-accounts-separately.md).  
* La finestra **Registrazione pagamenti**, nella quale è possibile collegare e controllare manualmente i pagamenti ricevuti come contante, assegno o transazione bancaria rispetto a una lista generata di documenti di vendita non pagati. Questa funzionalità è disponibile solo per i documenti di vendita.  
* La finestra **Registrazioni incassi**, nella quale vengono registrate manualmente le ricezioni nel relativo conto COGE, cliente o altro conto immettendo una riga di pagamento. È possibile collegare la ricezione o il rimborso a uno o più movimenti aperti prima di contabilizzare le registrazioni incassi oppure è possibile eseguire il collegamento dai movimenti contabili clienti.  

Un'altra attività di gestione della contabilità clienti riguarda la riscossione dei saldi inevasi, inclusi gli addebiti interessi e l'emissione dei solleciti. [!INCLUDE[d365fin](includes/d365fin_md.md)] offre modi per effettuare anche tali operazioni. Per ulteriori informazioni, vedere [Procedura: Riscuotere i saldi inevasi](receivables-collect-outstanding-balances.md).  

Nella tabella seguente viene descritta una sequenza di task, con collegamenti agli argomenti che li descrivono.  


|                                                                                      Per                                                                                       |                                                                               Vedere                                                                                |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|   Collegare i pagamenti a movimenti contabili cliente o fornitore aperti in base a un feed bancario o un file di rendiconto bancario importato e riconciliare il conto bancario una volta che tutti i pagamenti sono collegati.    |                   [Collegare i pagamenti automaticamente e riconciliare i conti correnti bancari](receivables-apply-payments-auto-reconcile-bank-accounts.md)                    |
|                                   Collegare i pagamenti a movimenti contabili clienti aperti in base all'immissione manuale in una lista di documenti di vendita non pagati.                                   | [Procedura: Riconciliare i pagamenti dei clienti manualmente dall'elenco dei documenti di vendita non pagati](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md) |
|     Registrare gli incassi o i rimborsi per i clienti nelle registrazioni incassi e collegare ai movimenti contabili clienti, dalle registrazioni o dai movimenti contabili registrati.      |                               [Procedura: Riconciliare manualmente i pagamenti dei clienti](receivables-how-apply-sales-transactions-manually.md)                               |
|                                 Inviare solleciti ai clienti per gli importi insoluti, calcolare interessi e addebiti interessi e gestire i crediti v/clienti.                                  |                                       [Procedura: Riscuotere i saldi inevasi](receivables-collect-outstanding-balances.md)                                        |
| È possibile assicurarsi di conoscere il costo degli articoli spediti assegnando i costi degli articoli, come le spese di spedizione, gestione fisica, assicurazione e il trasporto sostenute dopo la vendita. |                              [Procedura: Utilizzare gli addebiti articolo al conto per i costi aggiuntivi commerciali](payables-how-assign-item-charges.md)                               |
|           Impostare una tolleranza da cui il sistema chiude una fattura anche se il pagamento, incluso un eventuale sconto, non copre interamente l'importo della fattura.           |               [Procedura Utilizzare le tolleranze pagamento e le tolleranze sconto pagamento](finance-payment-tolerance-and-payment-discount-tolerance.md)                |

## <a name="see-also"></a>Vedi anche
[Vendite](sales-manage-sales.md)  
[Gestione della contabilità fornitori](payables-manage-payables.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
[Funzionalità aziendali generali](ui-across-business-areas.md)

