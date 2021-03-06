---
title: Mantenere aggiornato un layout di report
description: "È possibile che sia necessario aggiornare il layout personalizzato utilizzato per un report. Ciò è obbligatorio in seguito a una modifica di progettazione al set di dati del report, ad esempio, un campo utilizzato nel layout è stato rimosso da set di dati del report."
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: ca0bb5b30a6fded7f36f1380c5d73edb3f0a4ff0
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="updating-report-or-document-layouts"></a>Aggiornamento dei layout di report o documento
Talvolta, potrebbe essere necessario aggiornare il layout personalizzato utilizzato per un report. Ciò è obbligatorio in seguito a una modifica di progettazione al set di dati del report, ad esempio, un campo utilizzato nel layout è stato rimosso da set di dati del report. Se un layout di report necessita di aggiornamento, verrà visualizzato un messaggio di errore quando si tenta di visualizzare l'anteprima, stampare o salvare il report.  
  
È possibile aggiornare automaticamente il layout di report dal messaggio di errore visualizzato quando si esegue il report facendo clic sul pulsante **Sì** nel messaggio di errore. In alternativa, prima dell'esecuzione dei report, è possibile aggiornare i layout di report specifici o tutti i layout di report personalizzati che potrebbero essere interessati da modifiche del set di dati.  
  
Inoltre è possibile verificare gli aggiornamenti senza applicare le modifiche necessarie ai layout di report personalizzati. In questo modo è possibile visualizzare le modifiche che verranno applicate al layout di report e individuare i problemi che si potrebbero verificare durante il processo. Dai risultati dei test è possibile aprire direttamente i layout di report personalizzati per risolvere eventuali problemi. È consigliabile verificare l'aggiornamento del layout di report prima di applicare gli aggiornamenti.  
  
Non tutte le modifiche del set di dati del report possono essere aggiornate automaticamente nei layout di report. Alcune modifiche del layout di report dovranno essere apportate manualmente dall'utente. Per ulteriori informazioni, vedere [Limiti dell'aggiornamento di layout di report personalizzati](ui-update-report-layouts.md#UpdateLimitations).  
  
## <a name="to-update-one-or-more-custom-report-layouts"></a>Per aggiornare uno o più layout di report personalizzati  
  
1.  Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Layout report**, quindi scegliere il collegamento correlato.  
  
2.  Nella finestra **Layout report**, se si desidera aggiornare un report specifico, selezionare il layout dall'elenco, quindi scegliere l'azione **Aggiorna layout**. In alternativa, se si desidera aggiornare tutti i layout di report personalizzati per la società, scegliere l'azione **Aggiorna tutti i layout**.  

Se non si verifica alcun errore, l'aggiornamento viene applicato ai layout di report. Se si verificano errori, viene visualizzato un messaggio contenente gli errori. Sarà quindi necessario modificare manualmente il layout di report personalizzato per correggere l'errore. Per ulteriori informazioni, vedere [Risolvere gli errori](ui-update-report-layouts.md#FixErrors).  

## <a name="to-test-custom-report-layout-updates"></a>Per verificare gli aggiornamenti del layout di report personalizzato  
  
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Selezione layout report**, quindi scegliere il collegamento correlato.  
  
2. Nella finestra **Selezione layout report**, scegliere l'azione **Verifica aggiornamenti layout**.  
  
   Le modifiche ai layout di report vengono verificate ma non applicate ai layout di report effettivi. Viene visualizzata una finestra **Log aggiornamenti layout report** in cui viene indicato lo stato dei potenziali aggiornamenti per ogni layout di report. Se il layout di report presenta errori, è possibile accedervi direttamente dal messaggio per risolverli. Per ulteriori informazioni, vedere [Risolvere gli errori](ui-update-report-layouts.md#FixErrors).  
  
##  <a name="UpdateLimitations"></a> Limiti dell'aggiornamento di layout di report personalizzati  
 Sono disponibili diversi tipi di modifiche che l'aggiornamento automatico può applicare ai layout di report personalizzati, ad esempio la rimozione dal set di dati di un campo che è stato utilizzato nel layout. Tuttavia, l'aggiornamento automatico non può gestire le seguenti modifiche da apportare al set di dati di un report.  
  
1. Eliminazione di campi, etichette o elementi di dati.  
  
2. Duplicazione di nomi di campi nel layout di report dopo la ridenominazione di un campo nel set di dati. Ciò dovrebbe essere considerato come un errore di progettazione.  
  
3. Aggiornamento di scenari in cui sono presenti più iterazioni di un layout di report che comportano diverse azioni di ridenominazione negli stessi campi, etichette o elementi di dati.  
  
   Se il processo di aggiornamento rileva uno qualsiasi di questi problemi, l'aggiornamento non può essere applicato. Sarà necessario risolvere i problemi manualmente, ad esempio modificando il layout di report in Word o, a livello di codice, utilizzando le codeunit di aggiornamento.  
  
##  <a name="FixErrors"></a> Risolvere gli errori  
 Se si visualizza un messaggio di errore quando si eseguono o si verificano gli aggiornamenti del layout di report, molto probabilmente sarà necessario modificare il layout di report per risolvere il problema. Leggere il messaggio di errore per aiutare a determinare la causa del problema.  
  
 Il problema più frequente si verifica quando un campo utilizzato nel layout è stato rimosso dal set di dati del report. In questo caso, verrà visualizzata una riga nel messaggio di errore che indica che un articolo è stato rimosso. Per risolvere il problema, sarà necessario modificare il layout e rimuovere il campo in questione.  
  
 Per ulteriori informazioni, vedere [Procedura: Creare e modificare un layout di report personalizzato](ui-how-create-custom-report-layout.md#ModifyCustomLayout).  
  
 Dopo avere modificato il layout, provare ad aggiornare nuovamente il layout.  
  
## <a name="see-also"></a>Vedi anche  
 [Gestione dei layout di report](ui-manage-report-layouts.md)  
 [Utilizzo dei report](ui-work-report.md)  
