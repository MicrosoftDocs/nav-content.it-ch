---
title: 'Procedura: Inviare pagamenti DTA'
description: "Per inviare pagamenti DatenTrägerAustausch (DTA) alla banca per il pagamento, è necessario eseguire determinate attività."
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
ms.openlocfilehash: bf79d68ddb398672cccec48812266b8808e1e714
ms.contentlocale: it-ch
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-submit-dta-payments"></a>Procedura: Inviare pagamenti DTA
Per inviare pagamenti DatenTrägerAustausch (DTA) alla banca per il pagamento, è necessario eseguire le seguenti operazioni:  

- Generare un file DTA per il pagamento elettronico dopo aver stampato l'avviso di pagamento.  
- Stampare l'ordine di pagamento DTA.  

Prima di inviare pagamenti DTA, è necessario verificare l'elenco dei fornitori per il pagamento DTA. Per ulteriori informazioni, vedere [Procedura: Verificare una lista di fornitori per pagamenti DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md).  

È possibile registrare le registrazioni pagamenti dopo che i pagamenti bancari sono completati. Nell registrazioni pagamenti i pagamenti DTA possono essere suggeriti in base alle fatture registrate. I pagamenti suggeriti contengono informazioni sui fornitori e sui numeri di documento esterni e possono essere modificati. Per ulteriori informazioni, vedere [Procedura: Suggerire pagamenti DTA per i fornitori](how-to-suggest-dta-payment-for-vendors.md).  

## <a name="to-generate-a-dta-file"></a>Per generare un file DTA  

1.  Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni pagamenti**, quindi scegliere il collegamento correlato.  
2.  Nel campo **Nome batch** selezionare il batch contabile necessario.  
3.  Selezionare il movimento id pagamento che si desidera generare come file DTA quindi scegliere l'azione **Genera file DTA**.  
4.  Compilare i campi nel processo batch **File DTA** come descritto nella tabella riportata di seguito.  

    |Campo|Descrizione|  
    |---------------------------------|---------------------------------------|  
    |**Banca DTA per il File**|Selezionare il codice bancario DTA da cui devono essere trasferite le informazioni relative al nome file e alla copia di backup. Questo campo utilizza il nome della banca principale come valore predefinito, ma è possibile modificare queste informazioni se necessario.|  
    |**Pagamento unico per fornitore**|Specifica se le righe di pagamento con lo stesso fornitore, valuta, banca e banca di addebito nel file DTA generato verranno combinate.|  

5.  Scegliere il pulsante **OK**. Il file DTA viene generato nella cartella determinata in precedenza.  

Dopo aver generato il file DTA, è possibile stampare l'ordine di pagamento DTA e trasferire il file e l'ordine di pagamento alla banca. L'ordine di pagamento DTA elenca tutti i pagamenti fornitori suggeriti in una finestra **Registrazioni pagamenti** basata sul codice valuta. Questo ordine viene inviato alla banca per rilasciare il file DTA per il pagamento.  

## <a name="to-print-a-dta-payment-order"></a>Per stampare l'ordine di pagamento DTA  

1.  Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni pagamenti**, quindi scegliere il collegamento correlato.  
2.  Nel campo **Nome batch** selezionare il batch contabile necessario.  
3.  Selezionare il movimento di pagamento richiesto, quindi scegliere l'azione **Ordine di pagamento DTA**.  
4.  Nel campo **Messaggio** immettere un messaggio per la banca da stampare alla fine dell'ordine di pagamento.  
5.  Scegliere il pulsante **Stampa** per stampare l'ordine di pagamento DTA oppure scegliere il pulsante **Anteprima** per visualizzarla sullo schermo.  

    Inviare l'ordine di pagamento DTA e il file DTA alla banca, dove i pagamenti ai venditori vengono rilasciati in poche ore. Dopo che i pagamenti sono stati elaborati dalla banca, è possibile contabilizzare le registrazioni dei pagamenti.  

## <a name="see-also"></a>Vedere anche  
 [Pagamenti elettronici svizzeri tramite DTA](swiss-electronic-payments-using-dta.md)   
 [Procedura: Suggerire pagamenti DTA ai fornitori](how-to-suggest-dta-payment-for-vendors.md)   
 [Procedura: Verificare una lista di fornitori per pagamenti DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md)   
 [Procedura: Esportare pagamenti tramite EZAG](how-to-export-payments-using-ezag.md)

