---
title: Pagamenti elettronici svizzeri tramite DTA
description: "In [!INCLUDE[navnow](../../includes/navnow_md.md)] è possibile eseguire pagamenti elettronici per le fatture tramite il metodo DatenTrägerAustausch (DTA). Le banche svizzere utilizzano il metodo di pagamento elettronico DTA per liquidare pagamenti in modo efficiente tramite record di pagamenti standardizzati. Questo metodo di basa su vettori e trasferimento dati. Questo servizio elettronico consente di convertire i pagamenti elettronici in formato DTA e quindi di inviarli alla banca per il pagamento effettivo."
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
ms.openlocfilehash: cc84201548ca2c1ff6be7963310ea83bc81de94d
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="swiss-electronic-payments-using-dta"></a>Pagamenti elettronici svizzeri tramite DTA
In [!INCLUDE[navnow](../../includes/navnow_md.md)] è possibile eseguire pagamenti elettronici per le fatture tramite il metodo DatenTrägerAustausch (DTA). Le banche svizzere utilizzano il metodo di pagamento elettronico DTA per liquidare pagamenti in modo efficiente tramite record di pagamenti standardizzati. Questo metodo di basa su vettori e trasferimento dati. Questo servizio elettronico consente di convertire i pagamenti elettronici in formato DTA e quindi di inviarli alla banca per il pagamento effettivo.  
  
> [!NOTE]  
>  Prima di usare il metodo di pagamento elettronico DTA, è necessario definire le impostazioni DTA per effettuare i pagamenti nel setup DTA. Per ulteriori informazioni, vedere la tabella Setup DTA.  
  
 Con i pagamenti elettronici DTA è possibile effettuare le seguenti operazioni:  
  
-   Generare pagamenti fornitori elaborando il pagamento DTA automatico. Per ulteriori informazioni, vedere [Procedura: Suggerire pagamenti DTA per i fornitori](how-to-suggest-dta-payment-for-vendors.md).  
  
-   Verificare la lista dei fornitori e le informazioni di pagamento. Per ulteriori informazioni, vedere [Procedura: Verificare una lista di fornitori per pagamenti DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md).  
  
-   Inviare il file DTA alla banca in formato elettronico, per consentire ai pagamenti fornitori di essere rilasciati in poche ore. Per ulteriori informazioni, vedere [Procedura: Inviare pagamenti DTA](how-to-submit-dta-payments.md). Al termine dell'operazione, le registrazioni pagamenti possono essere inserite.  
  
 Nell registrazioni pagamenti i pagamenti DTA possono essere suggeriti in base alle fatture registrate. I pagamenti suggeriti contengono informazioni sui fornitori e sui numeri di documento esterni e possono essere modificati. Per ulteriori informazioni, vedere [Procedura: Suggerire pagamenti DTA per i fornitori](how-to-suggest-dta-payment-for-vendors.md) e la finestra Registrazioni pagamenti DTA.  
  
 Quando si desidera pagare un fornitore tramite DTA, si genera un file DTA che contiene i dati della riga di registrazioni pagamenti e della riga di registrazioni COGE. Se si desidera, il file DTA può combinare più pagamenti per il fornitore. Il file DTA contiene anche testo di registrazione.  
  
> [!NOTE]  
>  Se si combinano più pagamenti per il fornitore, il testo di registrazione deve includere i numeri di documento delle fatture. Se la lunghezza dei numero di documento supera i 50 caratteri, la parola "ecc." verrà aggiunta al campo.  
  
## <a name="see-also"></a>Vedere anche  
 [Pagamenti elettronici svizzeri](swiss-electronic-payments.md)   
 [Procedura: Suggerire pagamenti DTA ai fornitori](how-to-suggest-dta-payment-for-vendors.md)   
 [Procedura: Verificare una lista di fornitori per pagamenti DTA](how-to-verify-a-list-of-vendors-for-dta-payments.md)   
 [Procedura: Inviare pagamenti DTA](how-to-submit-dta-payments.md)   
 [Procedura: Esportare pagamenti tramite EZAG](how-to-export-payments-using-ezag.md)   
 [Pagamenti elettronici svizzeri tramite PVR](swiss-electronic-payments-using-esr.md)   
 [Pagamenti elettronici svizzeri tramite LSV+](swiss-electronic-payments-using-lsv-.md)   
 Registraz. pagamenti   
 Setup DTA
