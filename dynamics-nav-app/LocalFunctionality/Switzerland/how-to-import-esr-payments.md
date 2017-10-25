---
title: Come importare pagamenti PVR
description: "Dopo aver ricevuto un pagamento da un cliente, si riceve un file che contiene informazioni sulle fatture pagate. È possibile ricevere questo file dalla banca in formato elettronico oppure tramite e-mail."
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
ms.openlocfilehash: 4cb9cb52eb3c7859b8da44e2743652e140c2d567
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-import-esr-payments"></a>Procedura: Importare pagamenti PVR
Dopo aver ricevuto un pagamento da un cliente, si riceve un file che contiene informazioni sulle fatture pagate. È possibile ricevere questo file dalla banca in formato elettronico oppure tramite e-mail.  
  
 È possibile importare dati di fattura PVR (polizza di versamento con numero di riferimento, in tedesco ESR, Einzahlungsschein mit Referenznummer) dal file, stampare i dati tramite il report PVR della fattura di vendita o tramite il report di tagliandi PVR di vendita ed eseguire la verifica prima della registrazione. Per ulteriori informazioni, vedere [Procedura: Stampare fatture PVR](how-to-print-esr-invoices.md).  
  
### <a name="to-import-esr-payments"></a>Per importare pagamenti PVR  
  
1.  Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Registrazioni incassi**, quindi scegliere il collegamento correlato.  
  
2.  Nel campo **Nome batch** selezionare il batch contabile necessario.  
  
    > [!NOTE]  
    >  Prima di importare il file PVR, è necessario che le registrazioni siano vuote. Non è possibile importare più di un file PVR nelle stesse registrazioni incassi.  
  
3.  Nel gruppo **Elabora** della scheda **Pagina iniziale** scegliere **Leggi file PVR**.  
  
    > [!NOTE]  
    >  Se è stata definita più di una banca PVR, viene visualizzato un messaggio di avviso che indica di scegliere la banca pertinente. Per ulteriori informazioni, vedere la tabella Setup PVR.  
  
4.  Scegliere il pulsante **Sì**, quindi scegliere il pulsante **OK**.  
  
 Le informazioni sui pagamenti vengono importate nelle righe di registrazioni. I pagamenti vengono applicati automaticamente alle rispettive fatture in base a numeri di riferimento PVR univoci.  
  
## <a name="see-also"></a>Vedere anche  
 [Pagamenti elettronici svizzeri tramite PVR](swiss-electronic-payments-using-esr.md)   
 [Procedura: Stampare fatture PVR](how-to-print-esr-invoices.md)   
 Setup PVR   
 Registrazioni incassi   
 Registro PVR Clienti
