---
title: "Conti di contabilità generale per la Svizzera"
description: I miglioramenti svizzeri includono funzioni speciali di conto C/G.
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
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: 574a9f233798f0e5bc3945af3391039f2e900112
ms.contentlocale: it-ch
ms.lasthandoff: 10/26/2017

---
# <a name="swiss-general-ledger-accounts"></a>Conti di contabilità generale per la Svizzera
[!INCLUDE[navnow](../../includes/navnow_md.md)] include i miglioramenti svizzeri per i conti C/G.

- Gestire i saldi in valuta estera di un conto bancario nella contabilità generale.  
- Ordinare i numeri di conto della contabilità generale nella finestra **Piano dei conti**.  
- Evitare l'uso dei segni positivi o negativi errati per gli importi inseriti manualmente nelle registrazioni.  
- Visualizzare l'anteprima degli effetti che avrebbe la contabilizzazione delle registrazioni COGE sui saldi di alcuni conti di contabilità generale prima di effettuarla effettivamente.  

## <a name="general-ledger-accounts-and-general-journals"></a>Conti di contabilità generale e registrazioni COGE  
Le aziende hanno spesso conti bancari diversi per le valute estere e hanno un conto C/G per ogni conto bancario. In [!INCLUDE[navnow](../../includes/navnow_md.md)], è possibile impostare le informazioni relative al codice valuta e al saldo in valuta estera nella finestra **Piano dei conti**. Ciò consente di mantenere il saldo originale in valuta estera di un conto bancario. Per ulteriori informazioni, vedere [Finestra Piano dei Conti](assetId:///fa407624-b670-44b6-8397-91aa606e4c39) e [Tabella Conto C/G](assetId:///a65c2b09-9bb2-43db-8c53-c047bfc49777).  

Ad esempio, un'azienda ha due conti bancari: uno per la valuta locale (VL) e uno per gli euro (EUR). È necessario creare un conto C/G per ciascun conto bancario. Per il conto in EUR, definire il codice valuta come **EUR** e contabilizzare le registrazioni in EUR o VL.  

Quando cambia il tasso di cambio per EUR e VL, è possibile aggiornare e modificare il saldo in valuta locale per il conto C/G EUR usando il processo di batch di rettifica dei tassi di cambio. Questo processo batch crea e registra i movimenti di rettifica della valuta nella contabilità generale e aggiorna il saldo VL.  

## <a name="data-type-for-general-ledger-accounts"></a>Tipo di dati per i conti C/G  
Il tipo di dati è impostato su un testo per il numero di conto C/G o il codice conto per supportare i requisiti di ordinamento per il piano dei conti comune Kontenrahmen Käfer (KMU) svizzero standardizzato. Per ulteriori informazioni, vedere [Finestra Piano dei conti](assetId:///fa407624-b670-44b6-8397-91aa606e4c39). La lista dei numeri di conto viene ordinata in base al tipo di dati di testo. Il piano di conti KMU contiene i seguenti numeri di conto:  

- 1176  
- 119.0  
- 1190  

## <a name="correcting-positive-and-negative-signs-in-general-journals"></a>Correzione dei segni positivi e negativi nella contabilità generale  
Quando si immettono manualmente gli importi nelle registrazioni, i segni positivi e negativi per gli importi vengono automaticamente verificati. A seconda del tipo di conto e del tipo di documento, i segni non corretti vengono automaticamente corretti e viene visualizzato un messaggio. Per ulteriori informazioni, vedere [Tabella riga registrazioni COGE](assetId:///5308c791-0964-41d9-bc54-fd87e815d1be).  

Gli importi per le fatture cliente, le note di credito fornitore e i pagamenti devono essere positivi. Gli importi per le fatture fornitore, le note di credito cliente e i pagamenti devono essere negativi.  

## <a name="viewing-temporary-balances-in-general-journals"></a>Visualizzazione di saldi temporanei nelle registrazioni di contabilità generale  
Prima di contabilizzare una registrazione COGE è possibile visualizzare l'anteprima degli effetti che avrebbe la contabilizzazione sui saldi di alcuni conti di contabilità generale. È possibile aprire una finestra di statistiche che mostra i saldi dei conti e i saldi delle righe attive che includevano i valori non registrati per la registrazione corrente. Per ulteriori informazioni, vedere [Procedura: Visualizzare i saldi temporanei nelle registrazioni di contabilità generale](how-to-view-temporary-balances-in-general-ledger-journals.md).  

## <a name="see-also"></a>Vedere anche  
 [Procedura: Visualizzare i saldi temporanei nelle registrazioni di contabilità generale](how-to-view-temporary-balances-in-general-ledger-journals.md)   
 [Funzionalità locale per la Svizzera](switzerland-local-functionality.md)

