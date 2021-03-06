---
title: "Setup dell'IVA ad esigibilità differita"
description: "Se si utilizza contabilità basata su contanti, è possibile specificare come gestire l'IVA ad esigibilità differita per le vendite e acquisti."
documentationcenter: 
author: bholtorf
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: cash, VAT, unrealized, cash-based
ms.date: 09/08/2017
ms.author: bholtorf
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f5786a79e8f12bd86b3d6f7ce53e0c698b19cef4
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-set-up-unrealized-vat-for-cash-based-accounting"></a>Procedura: Setup dell'IVA ad esigibilità differita per la contabilità basata su contanti
Se si utilizzano metodi di contabilità basata su contanti, è possibile impostare [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)] affinché gestisca l'IVA ad esigibilità differita.

## <a name="to-use-general-ledger-accounts-for-unrealized-vat"></a>Per utilizzare conti C/G per l'IVA a esigibilità differita
Gli importi IVA possono essere calcolati e registrati in un conto di contabilità generale temporaneo al momento della registrazione di una fattura, quindi registrati nel conto corretto e inclusi nelle dichiarazioni IVA al momento della registrazione del pagamento effettivo della fattura. Prima di effettuare questa operazione, è necessario completare l'impostazione della registrazione dell'IVA.

Per utilizzare conti per l'IVA a esigibilità differita, procedere nel modo seguente:
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report") e immettere **Setup contabilità generale**. 
2. Nella Scheda dettaglio **Generale** della pagina **Setup contabilità generale** scegliere **Mostra di più**, quindi la casella di controllo **IVA ad esigibilità differita**.
3. Chiudere la pagina.
4. Nell'angolo superiore destro scegliere l'icona **Cerca pagina o report** ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report") e inserire **Setup registrazioni IVA**. 
5. Nella pagina **Setup registrazioni IVA** selezionare la categoria di registrazione IVA, quindi scegliere **Modifica**. 
6. Nel campo **Ripart. IVA ad esig. diff.** scegliere un'opzione per specificare come assegnare i pagamenti all'importo di una fattura (IVA esclusa) e all'importo stesso dell'IVA e come trasferire gli importi dell'IVA dal conto IVA ad esigibilità differita al conto realizzato. Nella seguente tabella vengono illustrate le opzioni.

| Opzione | Descrizione |
| --- | --- |
| Vuoto | Scegliere questa opzione se non si desidera utilizzare la funzione IVA ad esigibilità differita. |
| Percentuale | I pagamenti coprono sia l'IVA che l'importo della fattura, proporzionalmente alla percentuale di pagamento dell'importo totale della fattura. L'importo dell'IVA pagato viene trasferito dal conto IVA ad esigibilità differita al conto IVA realizzata. |
| Primo | I pagamenti coprono prima l'IVA e dopo gli importi delle fatture. In tal caso, l'importo trasferito dal conto dell'IVA ad Esigibilità Differita al conto dell'IVA sarà uguale all'importo del pagamento finché non verrà pagato l'importo totale dell'IVA. |
| Ultimo | I pagamenti coprono prima l'importo della fattura e dopo l'IVA. In tal caso, non verrà trasferito alcun importo dal conto dell'IVA ad esigibilità differita al conto dell'IVA finché non verrà pagato l'importo totale della fattura, esclusa l'IVA. |
| Primo (Interam. Pagato) | I pagamenti copriranno prima l'IVA (come con l'opzione _Primo_), ma non verrà trasferito alcun importo sul conto dell'IVA finché non verrà pagato l'importo totale dell'IVA. |
| Ultimo (Interam. Pagato) | I pagamenti copriranno prima l'importo della fattura (come con l'opzione _Ultimo_), ma non verrà trasferito alcun importo sul Conto IVA finché non verrà pagato l'importo totale dell'IVA. |

6. Nel campo **Conto IVA ven. ad esig. diff.** scegliere il conto per l'IVA di vendita a esigibilità differita.

    > [!NOTE]  
   >   L'importo dell'IVA verrà registrato su questo conto e vi rimarrà fino alla registrazione del pagamento effettuato dal cliente. L'importo viene quindi trasferito sul conto relativo all'IVA sulle vendite.
7. Nel campo **Conto IVA acq. ad esig. diff.** immettere il conto C/G per l'IVA di acquisto a esigibilità differita.

    > [!NOTE]  
   >   L'importo dell'IVA verrà registrato su questo conto e vi rimarrà fino alla registrazione del pagamento effettuato dal cliente. L'importo viene quindi trasferito sul conto relativo all'IVA sulle vendite.

## <a name="see-also"></a>Vedi anche
[impostazione dell'IVA](finance-setup-vat.md)
