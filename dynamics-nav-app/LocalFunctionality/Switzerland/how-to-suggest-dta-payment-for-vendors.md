---
title: 'Procedura: Suggerire pagamenti DTA ai fornitori'
description: "È possibile suggerire i pagamenti fornitori utilizzando le registrazioni di pagamento e trasferire le fatture scadute nelle registrazioni per i singoli fornitori. È inoltre possibile esaminare ogni fornitore per note di credito aperte o pagamenti aperti e creare un elenco di fornitori per l'elaborazione DatenTrägerAustausch (DTA)."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: b51b3f9273e9e737ef09901b0718d55350d44f87
ms.contentlocale: it-ch
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-suggest-dta-payment-for-vendors"></a>Procedura: Suggerire pagamenti DTA ai fornitori
È possibile suggerire i pagamenti fornitori utilizzando le registrazioni di pagamento e trasferire le fatture scadute nelle registrazioni per i singoli fornitori. È inoltre possibile esaminare ogni fornitore per note di credito aperte o pagamenti aperti e creare un elenco di fornitori per l'elaborazione DatenTrägerAustausch (DTA). Per ulteriori informazioni, vedere [Procedura: Verificare una lista di fornitori per pagamenti DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md).  

Durante l'elaborazione batch dei suggerimenti di pagamento DTA, l'importo in valuta estera (VE) viene convertito in valuta locale (VL) all'aliquota corrente per i pagamenti VE e trasferito nelle registrazioni di pagamento. Per ulteriori informazioni, vedere la finestra **Registrazioni pagamenti**. Nel caso di un addebito bancario, l'importo VL viene sovrascritto con l'importo VL addebitato e viene calcolato il tasso di cambio o il fattore di scambio.

## <a name="to-suggest-dta-payment-for-vendors"></a>Per suggerire il pagamento DTA ai fornitori  

1.  Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni pagamenti**, quindi scegliere il collegamento correlato.  
2.  Nel campo **Nome batch** selezionare il batch contabile necessario.  
3.  Selezionare la riga di pagamento richiesto, quindi scegliere l'azione **Suggerisci pagamenti DTA fornitore**.  
4.  Nella finestra **Suggerisci pagamenti DTA fornitore**, nella Scheda dettaglio **Opzioni** compilare i campi come descritto nella tabella seguente.  

    |Campo|Descrizione|  
    |---------------------------------|---------------------------------------|  
    |**Data di Registrazione**|Specificare la data di credito relativa al pagamento. Questa data è utile per determinare se è stato fornito uno sconto di pagamento.|  
    |**Scadenza da**|Specificare la data di inizio per le fatture aperte da includere nel suggerimento di pagamento.|  
    |**Scadenza a**|Specificare la data di fine per le fatture aperte da includere nel suggerimento di pagamento.|  
    |**Considerare sconti possibili**|Specificare se i pagamenti di sconto di cassa non compresi nell'intervallo della data di scadenza dovranno essere considerati per il suggerimento di pagamento.|  
    |**Data sconto da**|Specificare la data di inizio dello sconto di cassa. I movimenti aperti con le date di sconto di cassa entro questo intervallo di date sono inclusi nel suggerimento di pagamento.|  
    |**Data sconto a**|Specificare la data di fine dello sconto di cassa. I movimenti aperti con le date di sconto di cassa entro questo intervallo di date sono inclusi nel suggerimento di pagamento.|  
    |**Importo disponibile (VL)**|Immettere il valore massimo della somma di tutti i pagamenti.|  
    |**Primo nr. documento**|Specificare il numero del documento suggerimento di pagamento. Questo campo viene assegnato in base alla numerazione del log corrente.|  
    |**Banca di addebito**|Selezionare il codice della banca che riceverà l'addebito. La banca deve essere attivata per DTA.|  
    |**Banca di addebito autom.**|Specificare se la banca sarà addebitata automaticamente, a seconda del codice valuta.|  

5.  Scegliere il pulsante **OK**.  

Durante l'elaborazione, ciascun fornitore viene controllato per le note di credito aperte o i pagamenti aperti e viene visualizzato un messaggio al termine del processo. Tutte le righe correlate vengono trasferite alle registrazioni pagamenti. I movimenti contabili fornitore relativi sono contrassegnati da **DTA** per impedire il trasferimento di movimenti duplicati nelle registrazioni pagamenti. È possibile visualizzare, controllare e modificare i pagamenti suggeriti e decidere se ridurre i pagamenti tramite gli importi delle note di credito, oppure applicare le note di credito aperte e le fatture aperte.  

## <a name="see-also"></a>Vedere anche  
 [Pagamenti elettronici svizzeri tramite DTA](swiss-electronic-payments-using-dta.md)   
 [Procedura: Verificare una lista di fornitori per pagamenti DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md)   
 [Procedura: Inviare pagamenti DTA](how-to-submit-dta-payments.md)   
 [Procedura: Esportare pagamenti tramite EZAG](how-to-export-payments-using-ezag.md)   
 [Effettuare i pagamenti](../../payables-make-payments.md)

