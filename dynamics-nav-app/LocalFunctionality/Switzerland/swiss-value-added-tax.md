---
title: IVA svizzera
description: I miglioramenti svizzeri includono funzioni speciali di dichiarazione IVA.
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
ms.openlocfilehash: 2060d66d895c907186ac3dbcf22ada1925b73f17
ms.contentlocale: it-ch
ms.lasthandoff: 10/26/2017

---
# <a name="swiss-value-added-tax"></a>IVA svizzera
[!INCLUDE[navnow](../../includes/navnow_md.md)] includono i seguenti miglioramenti alla dichiarazione IVA svizzera:  

- Rettifica automatica degli importi IVA per fatture, in base agli sconti di pagamento.  
- Tassi di cambio IVA aggiuntivi per le fatture in valute estere.  
- Percentuali IVA e importi inclusi nelle registrazioni.  

Per ulteriori informazioni sui requisiti svizzeri di dichiarazione e codifica IVA, vedere [Informazioni sull'IVA svizzera](http://www.estv.admin.ch/mwst/dokumentation/00130/00947/00948/index.html?lang=fr) e in particolare il documento 605.525.01. Le informazioni sono disponibili in francese, tedesco e italiano.  

## <a name="vat-amounts-and-vat-exchange-rates"></a>Importi IVA e tassi di cambio IVA  
Secondo le leggi locali dell'IVA, l'importo base dell'IVA per una fattura può essere ridotto dello sconto di pagamento se viene concesso uno sconto. Per consentire la rettifica automatica dell'IVA per uno sconto di pagamento su una fattura, il campo **Rettifica per sconto pagamento** viene attivato per impostazione predefinita nella finestra **Setup contabilità generale**. È anche possibile attivare questa funzione nel setup registrazioni IVA. Per ulteriori informazioni, vedere la tabella Setup contabilità generale e Setup registrazioni IVA.  

### <a name="currency-exchange-rates-for-vat-reporting"></a>Tassi di cambio valuta per dichiarazione IVA   
Per le fatture in valuta estera è necessario utilizzare il tasso di cambio ufficiale fornito dal governo per il calcolo dell'IVA. È inoltre possibile impostare ulteriori tassi di cambio per l'IVA, che è possibile utilizzare per aspetti della fattura diversi dal calcolo dell'IVA. È possibile fornire il corretto tasso di cambio dell'IVA di governo per ogni valuta estera rilevante nel setup dei tassi di cambio per le fatture. Per ulteriori informazioni, vedere la tabella Tassi di cambio valute.  

È inoltre possibile rettificare tutti gli importi IVA nei movimenti IVA risultanti da transazioni in valuta estera. Quando si attiva la funzione di rettifica del tasso di cambio IVA, i tassi di cambio IVA vengono rettificati automaticamente. Le differenze positive derivanti dai tassi di cambio sono registrate in conti di utili di conversione. Le differenze negative derivanti dai tassi di cambio sono registrate in conti di perdite di conversione. Per ulteriori informazioni, vedere il processo batch Rettifica tassi di cambio.  

Ulteriori informazioni, come l'aliquota IVA e l'importo in valuta originale, vengono trasferiti ai movimenti IVA. Per ulteriori informazioni, vedere la tabella Movimenti IVA.  

## <a name="vat-information-in-journals"></a>Informazioni IVA nelle registrazioni  
Quando si inserisce una nuova riga in una registrazione, le percentuali IVA e gli importi IVA relativi al conto e al conto saldo per la riga registrazioni selezionata vengono popolati nell'area di stato della registrazione. Per ulteriori informazioni, vedere la finestra Registrazioni COGE, Registrazioni vendite e Registrazioni acquisti.  

## <a name="see-also"></a>Vedere anche  
 [Aliquote IVA per la Svizzera](vat-rates-for-switzerland.md)   
 [Procedura: Come creare e stampare una dichiarazione IVA svizzera](how-to-create-and-print-a-swiss-vat-statement.md)   
 [Funzionalità locale per la Svizzera](switzerland-local-functionality.md)   

