---
title: "Utilizzo delle registrazioni COGE per registrare direttamente in contabilità generale"
description: "Informazioni su come è possibile utilizzare le registrazioni COGE per la contabilizzazione nei conti C/G e in altri conti delle transazioni finanziarie, ad esempio i conti correnti bancari e i conti fornitori."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 07/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 53802fda260538999cc7f3428f739dfa55f23662
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="working-with-general-journals"></a>Utilizzo delle registrazioni COGE
La maggior parte delle transazioni finanziarie vengono registrate nella contabilità generale attraverso i documenti aziendali dedicati quali fatture di acquisto e ordini di vendita. Per le attività aziendali che non vengono rappresentate da un documento in [!INCLUDE[d365fin](includes/d365fin_md.md)], ad esempio le spese più piccole o le ricevute di pagamento, è possibile creare le transazioni correlate registrando le righe nella finestra **Registrazioni COGE**. Per ulteriori informazioni, vedere [Procedura: Registrare le transazioni direttamente nella contabilità generale](finance-how-post-transactions-directly.md).

Ad esempio, è possibile registrare la spesa del dipendente nelle spese correlate all'azienda per un risarcimento successivo. Per altre informazioni, vedere [Procedura: Registrare e rimborsare le spese dei dipendenti](finance-how-record-reimburse-employee-expenses.md).

Le registrazioni generali vengono utilizzate per la contabilizzazione diretta nei conti C/G e in altri conti delle transazioni finanziarie, ad esempio i conti correnti bancari, i conti clienti, fornitori e dipendenti. La contabilizzazione mediante una registrazione generale crea sempre movimenti nei conti di contabilità generale. Ciò è vero anche quando, ad esempio, viene contabilizzata una riga di registrazione in un conto cliente, in quanto tramite una categoria di registrazione viene registrata una riga in un conto crediti nella contabilità generale.

Le informazioni immesse in una registrazione sono temporanee e possono essere modificate mentre si trovano nella registrazione. Quando si contabilizza la registrazione, le informazioni vengono trasferite a movimenti in singoli conti, dove non possono essere modificate. È tuttavia possibile scollegare i movimenti registrati e stornare o correggere i movimenti. Per ulteriori informazioni, vedere [Procedura: Stornare le registrazioni](finance-how-reverse-journal-posting.md).

## <a name="using-journal-templates-and-batches"></a>Utilizzo di batch e definizioni di registrazioni
Esistono numerose definizioni registrazioni COGE. Ogni definizione registrazioni è rappresentata da una finestra dedicata con funzioni specifiche e campi necessari per supportare tali funzioni, ad esempio la finestra **Registrazione riconciliazione pagamenti** per elaborare i pagamenti bancari e la finestra **Registrazioni pagamenti** per pagare i fornitori o rimborsare i dipendenti. Per ulteriori informazioni, vedere [Effettuare i pagamenti](payables-make-payments.md) e [Procedura: Riconciliare manualmente i pagamenti dei clienti](receivables-how-apply-sales-transactions-manually.md).

Per ogni definizione registrazioni è possibile impostare le proprie registrazioni personali come batch registrazioni. Ad esempio, è possibile definire dei batch registrazioni personali per le registrazioni pagamenti che abbiano delle impostazioni e un layout personali. Di seguito viene fornito un suggerimento come esempio per personalizzare una registrazione.

> [!TIP]  
> Se si seleziona la casella di controllo **Suggerisci importo contropartita** nella riga per il proprio batch nella finestra **Batch registrazioni COGE**, il campo **Importo** ad esempio nelle righe di registrazione COGE per lo stesso numero di documento viene precompilato automaticamente con il valore richiesto per saldare il documento. Per ulteriori informazioni, vedere [Suggerimento automatico dei valori in [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-let-system-suggest-values.md).

## <a name="understanding-main-accounts-and-balancing-accounts"></a>Informazioni su conti principali e contropartita
Se sono stati impostati conti di contropartita di default per i batch di registrazioni nella pagina **Registrazioni COGE**, il conto di contropartita verrà compilato automaticamente quando si inserisce un valore nel campo **Nr. conto**. In caso contrario, compilare manualmente sia il campo **Nr. conto** che il campo **Contropartita**. Un importo positivo nel campo **Importo** viene addebitato sul conto principale e accreditato nella contropartita. Un importo negativo viene accreditato sul conto principale e addebitato nella contropartita.

> [!NOTE]  
>   L'IVA viene calcolata separatamente per il conto principale e il conto di contropartita, quindi possono essere utilizzate percentuali IVA diverse.

## <a name="working-with-recurring-journals"></a>Utilizzo delle registrazioni periodiche
Una registrazione periodica è una registrazione generale con campi specifici per la gestione di transazioni registrate frequentemente con poche o nessuna modifica. Se si utilizzano questi campi per le transazioni ricorrenti, è possibile registrare sia gli importi fissi sia quelli variabili. È inoltre possibile specificare i movimenti di storno automatico il giorno successivo alla data di registrazione e utilizzare chiavi di allocazione con i movimenti periodici.

## <a name="working-with-standard-journals"></a>Utilizzo delle registrazioni standard
Quando si creano righe di registrazione che verranno probabilmente create di nuovo successivamente, è possibile scegliere di salvarle come registrazioni standard prima di contabilizzare la registrazione. Questa funzionalità si applica alle registrazioni di magazzino e alle registrazioni COGE.

> [!NOTE]  
>   la seguente procedura si riferisce alle registrazioni magazzino, ma le informazioni sono valide anche per le registrazioni COGE.

### <a name="to-save-a-standard-journal"></a>Per salvare una registrazione standard
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Registrazioni inventario fisico**, quindi scegliere il collegamento correlato.
2. Immettere una o più righe di registrazione.
3. Selezionare le righe di registrazione che si desidera riutilizzare.
4. Scegliere l'azione **Salva come registrazioni standard**.
5. Nella finestra di richiesta **Salva come Registrazioni Magazzino Standard**, definire una registrazione di magazzino standard nuova o esistente in cui devono essere salvate le righe:

    Se sono già state create una o più registrazioni magazzino standard e si desidera sostituirne una con il nuovo insieme di righe di registrazione magazzino, selezionare il codice desiderato nel campo Codice.
6. Scegliere **OK** per verificare l'intenzione di sovrascrivere la registrazione magazzino standard esistente e sostituirne tutto il contenuto.
7. Selezionare il campo **Salva importo unitario** se si desidera salvare i valori nel campo **Importo unitario** delle registrazioni magazzino standard.
8. Selezionare il campo **Salva quantità** se si desidera che vengano salvati i valori nel campo **Quantità** .
9. Scegliere **OK** per salvare le registrazioni magazzino standard.

Al termine del salvataggio della registrazione magazzino standard, viene visualizzata la finestra Registrazioni Magazzino ed è possibile procedere alla contabilizzazione della registrazione, che potrà essere facilmente ricreata nel caso in cui sia nuovamente necessario contabilizzare righe identiche o simili.

### <a name="to-reuse-a-standard-journal"></a>Per riutilizzare registrazioni standard
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Registrazioni inventario fisico**, quindi scegliere il collegamento correlato.
2. Scegliere l'azione **Ottieni registrazioni standard**.

    Verrà visualizzata la finestra Registrazioni magazzino standard, contenente i codici e le descrizioni per tutte le registrazioni di magazzino standard esistenti.
3. Per rivedere una registrazione di magazzino standard prima della relativa selezione a scopo di riutilizzo, scegliere l'azione **Mostra registrazioni**.

    Qualsiasi modifica apportata in una registrazione di magazzino standard viene immediatamente implementata. Sarà presente alla successiva apertura o al successivo riutilizzo della registrazione di magazzino standard in questione. È pertanto opportuno assicurarsi che la modifica sia sufficientemente importante da essere applicata a livello generale. In caso contrario, apportare la modifica specifica nella registrazione di magazzino dopo l'inserimento delle righe della registrazione di magazzino standard. Vedere il passaggio 4 di seguito.
4. Nella finestra **Registrazioni magazzino standard** selezionare la registrazione di magazzino standard che si desidera riutilizzare e quindi scegliere **OK**.

    La registrazione di magazzino sarà ora completata con le righe salvate come registrazione di magazzino standard. Se nella registrazione di magazzino erano già presenti righe di registrazione, le righe inserite verranno posizionate sotto le righe di registrazione esistenti.

    Se non si è selezionato il campo **Salva importo unitario** quando si è utilizzato il processo della funzione **Salva come registrazioni magazzino standard**, il campo **Importo unitario** delle righe inserite dalle registrazioni standard viene automaticamente completato con il valore corrente dell'articolo, copiato dal campo **Costo unitario** della scheda articolo.

    > [!NOTE]  
   >   in caso di selezione dei campi **Salva Importo Unitario** o **Salva Quantità**, è opportuno assicurarsi che i valori inseriti siano corretti per la rettifica di magazzino specifica prima di contabilizzare la registrazione di magazzino.

    Se le righe di registrazione di magazzino inserite contengono importi unitari salvati che non si desidera contabilizzare, è possibile eseguire rapidamente la rettifica al valore corrente dell'articolo come indicato di seguito.

5. Selezionare e righe di registrazioni magazzino che si desidera rettificare e scegliere l'azione **Ricalcola importo unitario**. Il campo Importo unitario verrà così aggiornato con il costo unitario corrente dell'articolo.
6. Scegliere l'azione **Registra**.

## <a name="to-renumber-document-numbers-in-journals"></a>Rinumerare i documenti nei giornali di registrazione
Per evitare errori di registrazione dovuti all'ordine dei numeri di documento, è possibile utilizzare la funzione **Rinumera documenti** prima di effettuare una registrazione.

In tutte le registrazioni basate sulle registrazioni COGE, il campo **Nr. documento** può essere modificato per poter specificare numeri di documento diversi in base alle diverse righe registrazioni o lo stesso numero di documento per le righe registrazioni correlate.

Se il campo **Nr. serie** nel batch registrazioni è compilato, la funzione di registrazione nelle registrazioni COGE richiede che il numero di documento nelle righe registrazioni singole o raggruppate segua un ordine sequenziale. Per evitare errori di registrazione dovuti all'ordine dei numeri di documento, è possibile utilizzare la funzione **Rinumera documenti** prima di effettuare registrazioni. Se le righe registrazioni correlate sono state raggruppate in base al numero del documento prima dell'utilizzo della funzione, rimarranno raggruppate, anche se potrebbero essere assegnate a un numero di documento diverso.

Questa funzione può anche essere utilizzata sulle viste filtrate.

La rinumerazione dei documenti rispetterà i collegamenti correlati, ad esempio il collegamento di un pagamento tra il documento nella riga registrazioni e un conto fornitore. Di conseguenza, è possibile aggiornare i campi **Collega-a ID** e **Collega-a nr. doc.** nei movimenti contabili interessati.

La procedura riportata di seguito è basata sulla finestra **Registrazione COGE**, ma si applica a tutte le altre registrazioni basate sulle registrazioni COGE, ad esempio la finestra **Registraz. pagamenti**.

1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Registrazioni COGE**, quindi scegliere il collegamento correlato.
2. Quando si è pronti per contabilizzare la registrazione, scegliere l'azione **Rinumera documenti**.

I valori nel campo **Nr. documento** vengono modificati, se necessario, in modo che il numero del documento nelle righe registrazioni singole o raggruppate seguano un ordine sequenziale. Dopo la rinumerazione dei documenti, è possibile procedere con la contabilizzazione delle registrazioni.

## <a name="see-also"></a>Vedi anche
[Procedura: Registrare le transazioni direttamente nella contabilità generale](finance-how-post-transactions-directly.md)  
[Procedura: Stornare le registrazioni](finance-how-reverse-journal-posting.md)  
[Procedura: Allocazione di costi e ricavi](year-allocate-costs-income.md)  
[Finanze](finance.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

