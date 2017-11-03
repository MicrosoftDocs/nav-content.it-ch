---
title: Pagamenti elettronici svizzeri tramite LSV+
description: "Il metodo di pagamento elettronico svizzero, ovvero Lastschrift Verfahren (LSV+) o addebito diretto, versione migliorata del metodo LSV, consente alle aziende di recuperare i pagamenti direttamente dai conti correnti dei clienti. Per recuperare i pagamenti dei clienti, è necessario inviare un file LSV alla banca, che raccoglierà i pagamenti richiesti nel file."
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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: d7f41ba3ad0706bad87d98b590eda38304bddf85
ms.contentlocale: it-ch
ms.lasthandoff: 10/23/2017

---
# <a name="swiss-electronic-payments-using-lsv"></a>Pagamenti elettronici svizzeri tramite LSV+
Il metodo di pagamento elettronico svizzero, ovvero Lastschrift Verfahren (LSV+) o addebito diretto, versione migliorata del metodo LSV, consente alle aziende di recuperare i pagamenti direttamente dai conti correnti dei clienti. Per recuperare i pagamenti dei clienti, è necessario inviare un file LSV alla banca, che raccoglierà i pagamenti richiesti nel file.  

Il metodo LSV+ è un principio di addebito diretto con facoltà di opporsi. Il metodo BDD (Business Direct Debit) è invece un sistema di addebito diretto senza facoltà di opporsi. Il formato di file da inviare alla banca è lo stesso per i sistemi LSV+ e BDD.  

Prima di usare il modulo LSV, è necessario definire le impostazioni nella finestra **Setup LSV**. Per ulteriori informazioni, vedere la tabella Setup LSV.  

## <a name="automatic-esr-processing"></a>Elaborazione ESR automatica  
È possibile scaricare transazioni creditizie di pagamento nel formato di file ESR (polizza di versamento con numero di riferimento, in tedesco ESR, Einzahlungsschein mit Referenznummer) dalla banca. È possibile ricevere pagamenti LSV nel file ESR se il numero di riferimento ESR è integrato nel sistema LSV+. Se nei file LSV importati sono inclusi pagamenti LSV+, le righe di registrazione LSV correlate vengono chiuse automaticamente. L'elaborazione ESR automatica viene eseguita solo per i pagamenti che utilizzano franchi svizzeri (CHF) e richiede che vengano effettuate queste operazioni:  

- Dopo aver inviato il file LSV+ alla banca, inviare un report di pagamenti entro tre giorni lavorativi dalla data di elaborazione LSV richiesta.  

- Importare i file ESR, quindi inserire le registrazioni ESR. Se una transazione ESR importata è correlata alla riga di pagamento LSV+, la riga di registrazione LSV appropriata viene chiusa automaticamente da ESR.  

    > [!NOTE]  
    >  Quando si importa un file ESR, la riga di registrazione LSV viene chiusa da ESR se viene trovata la registrazione LSV appropriata, indipendentemente dal tipo di transazione ESR.  

- Dopo la data di elaborazione LSV, è possibile controllare le righe di registrazione LSV. Se tutte le righe di registrazione LSV sono chiuse, lo stato del campo **Stato LSV** viene aggiornato sul valore **Completato**.  

## <a name="see-also"></a>Vedere anche  
 [Procedura: Chiudere una riscossione LSV](how-to-process-an-lsv-collection.md)   
 [Procedura: Chiudere una riscossione LSV](how-to-close-an-lsv-collection.md)   
 [Procedura: Registrare pagamenti LSV+](how-to-post-lsv-payments.md)   
 [Procedura: Esportare pagamenti tramite LSV](how-to-export-payments-using-lsv.md)   
 [Pagamenti elettronici svizzeri](swiss-electronic-payments.md)   
 [Pagamenti elettronici svizzeri tramite DTA](swiss-electronic-payments-using-dta.md)   
 [Pagamenti elettronici svizzeri tramite ESR](swiss-electronic-payments-using-esr.md)   
 [Effettuare i pagamenti](../../payables-make-payments.md)

