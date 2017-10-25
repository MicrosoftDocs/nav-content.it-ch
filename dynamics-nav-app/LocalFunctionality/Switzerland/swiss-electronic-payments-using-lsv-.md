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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: bde56909ab329a08cb29ae5a372eab2c81d4a2e9
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="swiss-electronic-payments-using-lsv"></a>Pagamenti elettronici svizzeri tramite LSV+
Il metodo di pagamento elettronico svizzero, ovvero Lastschrift Verfahren (LSV+) o addebito diretto, versione migliorata del metodo LSV, consente alle aziende di recuperare i pagamenti direttamente dai conti correnti dei clienti. Per recuperare i pagamenti dei clienti, è necessario inviare un file LSV alla banca, che raccoglierà i pagamenti richiesti nel file.  
  
 Il metodo LSV+ è un principio di addebito diretto con facoltà di opporsi. Il metodo BDD (Business Direct Debit) è invece un sistema di addebito diretto senza facoltà di opporsi. Il formato di file da inviare alla banca è lo stesso per i sistemi LSV+ e BDD.  
  
 Prima di usare il modulo LSV, è necessario definire le impostazioni nella finestra **Setup LSV**. Per ulteriori informazioni, vedere la tabella Setup LSV.  
  
## <a name="automatic-esr-processing"></a>Elaborazione PVR automatica  
 È possibile scaricare transazioni creditizie di pagamento nel formato di file PVR (polizza di versamento con numero di riferimento, in tedesco ESR, Einzahlungsschein mit Referenznummer) dalla banca. È possibile ricevere pagamenti LSV nel file PVR se il numero di riferimento PVR è integrato nel sistema LSV+. Se nei file LSV importati sono inclusi pagamenti LSV+, le righe di registrazione LSV correlate vengono chiuse automaticamente. L'elaborazione PVR automatica viene eseguita solo per i pagamenti che utilizzano franchi svizzeri (CHF) e richiede che vengano effettuate queste operazioni:  
  
-   Dopo aver inviato il file LSV+ alla banca, inviare un report di pagamenti entro tre giorni lavorativi dalla data di elaborazione LSV richiesta.  
  
-   Importare i file PVR, quindi inserire le registrazioni PVR. Se una transazione PVR importata è correlata alla riga di pagamento LSV+, la riga di registrazione LSV appropriata viene chiusa automaticamente da PVR.  
  
    > [!NOTE]  
    >  Quando si importa un file PVR, la riga di registrazione LSV viene chiusa da PVR se viene trovata la registrazione LSV appropriata, indipendentemente dal tipo di transazione PVR.  
  
-   Dopo la data di elaborazione LSV, è possibile controllare le righe di registrazione LSV. Se tutte le righe di registrazione LSV sono chiuse, lo stato del campo **Stato LSV** viene aggiornato sul valore **Completato**.  
  
## <a name="see-also"></a>Vedere anche  
 [Procedura: Chiudere una riscossione LSV](how-to-process-an-lsv-collection.md)   
 [Procedura: Chiudere una riscossione LSV](how-to-close-an-lsv-collection.md)   
 [Procedura: Registrare pagamenti LSV+](how-to-post-lsv-payments.md)   
 [Procedura: Esportare pagamenti tramite LSV](how-to-export-payments-using-lsv.md)   
 [Pagamenti elettronici svizzeri](swiss-electronic-payments.md)   
 [Pagamenti elettronici svizzeri tramite DTA](swiss-electronic-payments-using-dta.md)   
 [Pagamenti elettronici svizzeri tramite PVR](swiss-electronic-payments-using-esr.md)   
 Setup LSV
