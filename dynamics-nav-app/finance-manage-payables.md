---
title: "Gestione della contabilità fornitori"
description: "Panoramica di come Dynamics NAV contribuisce a gestire la contabilità fornitori, inclusi i pagamenti fornitore, i creditori, i debiti e saldi scaduti."
documentationcenter: 
author: bholtorf
manager: edupont
editor: 
ms.prod: dynamics-nav-2018
ms.workload: na
ms.tgt_pltfrm: na
ms.devlang: na
ms.topic: article
ms.search.keywords: vendor payment, creditor, debt, balance due, AP
ms.date: 06/02/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 698cb92c4209f2675fda3a4b2280ab8afad0c9cc
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="managing-payables"></a>Gestione della contabilità fornitori
[!INCLUDE[d365fin_long](includes/d365fin_long_md.md)] consente di gestire in modo efficace il conto pagamenti fornitori.  

## <a name="payments"></a>Pagamenti
Consente di assegnare priorità ai pagamenti, tenere conto delle penalità per i pagamenti scaduti e gestire gli sconti per i pagamenti anticipati.

È possibile contabilizzare i pagamenti in una registrazione COGE, quindi stampare gli assegni prima delle registrazioni di pagamento.

È possibile collegare i pagamenti per consentire la chiusura delle fatture al momento della registrazione del pagamento o in un momento successivo. Il **Metodo collegamento PA** specificato per il fornitore ( **Scheda fornitore**) determina se il pagamento viene collegato manualmente o automaticamente. Le transazioni possono essere sempre collegate manualmente. Tuttavia, se il metodo di collegamento per il fornitore è **Collega alla più vecchia** e non si specifica un documento cui collegare il pagamento, questo viene collegato al movimento aperto meno recente relativo al fornitore.

## <a name="suggest-vendor-payments"></a>Sugg. pagamenti fornitore
[!INCLUDE[d365fin](includes/d365fin_md.md)] può fornire suggerimenti di pagamento ai fornitori, ad esempio pagamenti con scadenza a breve termine oppure pagamenti che prevedono uno sconto. Il suggerimento di pagamento può includere un importo indicato come fondi disponibili per il pagamento e il diritto all'applicazione di sconti sul pagamento.

## <a name="issue-checks"></a>Emettere assegni
[!INCLUDE[d365fin](includes/d365fin_md.md)] consente di emettere assegni ai fornitori manualmente ed elettronicamente. È possibile eseguire entrambe le operazioni nella finestra **Registrazioni pagamenti**, in cui è possibile anche annullare assegni e visualizzare movimenti contabili degli assegni.

## <a name="export-payments-to-a-bank-file"></a>Esportare pagamenti in un file della banca
Quando si è pronti a pagare un fornitore, nella finestra **Registrazioni pagamenti** è possibile esportare un file con le informazioni di pagamento dalle righe di registrazione. È quindi possibile caricare il file sul sito elettronico della banca per elaborare i trasferimenti di denaro.

Se non si desidera registrare una riga di registrazione pagamenti per un pagamento esportato, ad esempio perché si sta attendendo dalla banca la conferma della transazione, è possibile eliminare la riga di registrazione. In seguito quando si crea una riga di registrazione pagamenti per pagare l'importo residuo della fattura, il campo **Importo totale esportato** visualizza la quantità dell'importo pagamento già esportata. Inoltre, è possibile trovare informazioni dettagliate sul totale esportato scegliendo il pulsante **Movimenti dei registri di bonifici**.

Se si aspetta di registrare i pagamenti fino a dopo che la banca ha confermato l'elaborazione delle transazioni, sono disponibili due modi per evitare di riesportare casualmente i pagamenti per i documenti aperti:  

* Nelle registrazioni pagamenti con le righe di pagamento suggerite, è possibile ordinare la colonna **Esportato su file pagamento** o **Importo totale esportato** e poi eliminare i suggerimenti di pagamento per le fatture aperte per le quali i pagamenti sono già stati effettuati e per le quali non si desidera creare pagamenti.

    **Nota:** potrebbe essere necessario aggiungere queste colonne alla lista. Per ulteriori informazioni, vedere [Personalizzazione utente](ui-user-personalization.md).  
* In alternativa, nel processo batch di **Sugg. pagamenti fornitore**, in cui vengono specificati i pagamenti da inserire nelle registrazioni pagamenti, è possibile indicare di non inserire le righe delle registrazioni pagamenti che sono già state esportate, scegliendo la casella di controllo **Ignora pagamenti esportati**.

## <a name="see-also"></a>Vedi anche
[Metodi di pagamento](finance-payment-methods.md)  
[Finanze](finance.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

