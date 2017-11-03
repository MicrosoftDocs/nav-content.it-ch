---
title: Pagamenti elettronici svizzeri
description: I miglioramenti svizzeri consentono di inviare le fatture ai clienti elettronicamente. Le fatture vengono presentate e pagate direttamente utilizzando il software bancario online del cliente.
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
ms.openlocfilehash: e08f2c3d911e20c631f32683c284c0988a2b55b9
ms.contentlocale: it-ch
ms.lasthandoff: 10/26/2017

---
# <a name="swiss-electronic-payments"></a>Pagamenti elettronici svizzeri
[!INCLUDE[navnow](../../includes/navnow_md.md)] consente di inviare le fatture ai clienti elettronicamente. Le fatture vengono presentate e pagate direttamente utilizzando il software bancario online del cliente.  

## <a name="electronic-payment-methods"></a>Metodi di pagamento elettronico  
È possibile effettuare pagamenti elettronici utilizzando i seguenti metodi:  

- DatenTrägerAustausch (DTA)  
- Elektronischer Zahlungsauftrag (EZAG)  
- Einzahlungsschein mit Referenznummer (ESR)  
- Lastschrift Verfahren (LSV+)  
- Bonifici SEPA  

## <a name="dta-and-ezag"></a>DTA e EZAG  
Il metodo di pagamento elettronico DTA è un servizio universale adottato dalle banche svizzere per liquidare pagamenti in modo efficiente in formato DTA tramite record di pagamenti standardizzati. Questo metodo di basa su vettori e trasferimento dati. Le specifiche sono coordinate da Swiss Interbank Clearing (SIC). Per ulteriori informazioni, vedere [Pagamenti elettronici svizzeri tramite DTA](swiss-electronic-payments-using-dta.md).  

EZAG è il metodo di pagamento elettronico della PostFinance svizzera e richiede un conto giro. È possibile creare e inviare ordini per pagamenti fornitori nel formato bancario DTA o nel formato PostFinance EZAG.  

## <a name="esr"></a>ESR  
ESR è un servizio debitore elettronico che utilizza distinte di pagamento per riscuotere fondi. È il sistema di pagamento elettronico standard creato da Swiss Post. È possibile stampare le distinte di pagamento ESR come allegati a fattura, calcolare i numeri di riferimento ESR e importare file ESR che hanno informazioni di pagamento delle banche. Per ulteriori informazioni, vedere [Pagamenti elettronici svizzeri tramite ESR](how-to-print-esr-invoices.md). Inoltre, è possibile effettuare pagamenti ESR e ESR+ utilizzando la versione della banca di questo metodo di pagamento denominato Bank-ESR (BESR).  

## <a name="lsv"></a>LSV+  
LSV+ è un servizio di addebito diretto che viene utilizzato per l'elaborazione dei pagamenti. Le aziende possono rilasciare i pagamenti dei clienti direttamente dalla banca del cliente utilizzando l'addebito diretto. È possibile richiedere e riscuotere i pagamenti dei clienti utilizzando l'addebito diretto nel formato bancario LSV+ o nel formato DebitDirect PostFinance. Per ulteriori informazioni, vedere [Pagamenti elettronici svizzeri tramite LSV+](swiss-electronic-payments-using-lsv-.md).  

## <a name="sepa-credit-transfers"></a>Bonifici SEPA  
Per esportare i pagamenti secondo lo standard SEPA, è necessario utilizzare un conto bancario. Per assicurarsi che i movimenti contabili corrispondenti siano coerenti con quelli generati per i metodi di pagamento svizzeri locali (vedere sopra), il valore nel campo **Cat. reg. C/C bancario** della finestra **Scheda conto corrente bancario** deve indicare il relativo conto C/G. Per ulteriori informazioni su come esportare i pagamenti SEPA, vedere [Procedura: Creare movimenti riscossione addebiti diretti SEPA ed esportarli in un file della banca](../../finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md).  

## <a name="see-also"></a>Vedere anche  
 [Procedura: Importare numeri di clearing bancari svizzeri](how-to-import-swiss-bank-clearing-numbers.md)   
 [Pagamenti elettronici svizzeri tramite DTA](swiss-electronic-payments-using-dta.md)   
 [Pagamenti elettronici svizzeri tramite ESR](swiss-electronic-payments-using-esr.md)   
 [Procedura: Stampare fatture ESR](how-to-print-esr-invoices.md)   
 [Pagamenti elettronici svizzeri tramite LSV+](swiss-electronic-payments-using-lsv-.md)   
 [Funzionalità locale per la Svizzera](switzerland-local-functionality.md)  ' [Procedura: Creare movimenti riscossione addebiti diretti SEPA ed esportarli in un file della banca](../../finance-how-create-sepa-direct-debit-collection-entries-export-bank-file.md)  
 [Effettuare i pagamenti](../../payables-make-payments.md)

