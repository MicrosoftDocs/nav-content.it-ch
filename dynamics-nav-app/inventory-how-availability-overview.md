---
title: "Ottenere una panoramica della disponibilità"
description: "È possibile ottenere informazioni su come visualizzare la disponibilità di articoli o scorte tra le ubicazioni, per eventi di vendita o di acquisto, in base a un periodo di tempo o alla posizione dell'articolo su una DB di assemblaggio o di produzione."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: stock
ms.date: 08/15/2017
ms.author: SorenGP
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 81872839df11a13489bbc192ad97dae04976ebb0
ms.contentlocale: it-ch
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-view-the-availability-of-items"></a>Procedura: Visualizzare la disponibilità di articoli
Dal contesto di un task di business, è possibile ottenere informazioni avanzate relative al momento e all'ubicazione in cui un articolo è disponibile, ad esempio quando si parla con un cliente per proporre una data di consegna.

È possibile visualizzare la disponibilità di tutti gli articoli per ubicazione ed è possibile visualizzare la disponibilità di ciascun articolo per evento, periodo o ubicazione. Per evento si intende qualsiasi transazione articolo pianificata, ad esempio una spedizione o un carico di trasferimento in entrata.

> [!NOTE]  
>   Le visualizzazioni di disponibilità per ubicazione richiedono che si disponga di un magazzino presso più di un'ubicazione. Per ulteriori informazioni, vedere [Procedura: Impostare le ubicazioni](inventory-how-setup-locations.md).

In [!INCLUDE[d365fin](includes/d365fin_md.md)], i dati relativi alla disponibilità vengono visualizzati in due campi diversi, ognuno con una diversa definizione:

* Il campo **Giacenza** mostra l'effettiva quantità in base ai movimenti contabili articoli registrati.
* Nel campo **Disponibilità calcolata** viene calcolato e viene visualizzata la giacenza più i carichi programmati e meno il fabbisogno lordo. (In [!INCLUDE[d365fin](includes/d365fin_md.md)], i carichi programmati includono le quantità degli ordini di acquisto e degli ordini di trasferimento in entrata. Il fabbisogno lordo include le quantità degli ordini di vendita e degli ordini di trasferimento in uscita.)

> [!TIP]  
>   La disponibilità calcolata è particolarmente importante per visualizzare le finestra **Disponibilità art. per periodi** e **Disponibilità articolo per evento** dal momento che contengono le dimensioni per data.  

> [!NOTE]  
>   Di seguito viene descritto come visualizzare le informazioni avanzate sulla disponibilità per articolo dall'elenco articoli e dalla scheda articolo. È inoltre possibile accedere alle informazioni contenute nelle righe dei documenti di vendita, per l'articolo nella riga. Per ulteriori informazioni, vedere [Procedura: Vendere prodotti](sales-how-sell-products.md).

## <a name="to-view-the-availability-of-an-item-according-to-when-it-will-be-received-or-shipped"></a>Per visualizzare la disponibilità di un articolo secondo quando verrà ricevuto o spedito
Si visualizza la disponibilità di un articolo secondo le transazioni pianificate dell'articolo nella finestra **Disponibilità articolo per evento**.

1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Articoli**, quindi scegliere il collegamento correlato.
2. Aprire la scheda di un articolo per cui si desidera visualizzare la disponibilità.
3. Scegliere l'azione **Disponibilità articolo per** quindi scegliere l'azione **Evento**.

    La finestra **Disponibilità articolo per evento** mostra come le quantità di magazzino dell'articolo si svilupperanno nel tempo in base agli eventi programmati per carico e spedizione. La finestra fornisce una visualizzazione ridotta che mostra una riga di informazioni accumulate per intervallo di tempo in cui le quantità di magazzino cambiano. Gli intervalli di tempo in cui non si è verificato alcun evento non sono visualizzati. È possibile espandere ogni riga per mostrare i dettagli sull'evento o gli eventi che hanno generato la quantità accumulata sulla riga.
4. Selezionare il valore nel campo **Disponibilità calcolata** per visualizzare i movimenti articoli o documenti aperti che compongono il valore.

## <a name="to-view-the-availability-of-an-item-in-different-periods"></a>Per visualizzare la disponibilità di un articolo in diversi periodi di tempo
È possibile visualizzare la disponibilità di un articolo nel tempo per periodi specificati nella finestra **Disponibilità art. per periodi**.

1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Articoli**, quindi scegliere il collegamento correlato.
2. Aprire la scheda di un articolo per cui si desidera visualizzare la disponibilità.
3. Scegliere l'azione **Disponibilità articolo per** quindi scegliere l'azione **Periodo**.

    La finestra **Disponibilità articolo per periodo** mostra come le quantità di magazzino dell'articolo si svilupperanno nel tempo in base al periodo selezionato, ad esempio giorno, settimana oppure trimestre.
4. Selezionare il valore nel campo **Disponibilità calcolata** per visualizzare i movimenti articoli o documenti aperti che compongono il valore.

## <a name="to-view-the-availability-of-an-item-at-the-locations-where-it-is-stored"></a>Per visualizzare la disponibilità di un articolo nelle ubicazioni dove è immagazzinato
È possibile visualizzare la disponibilità di un articolo presso i luoghi diversi dove viene immagazzinato nella finestra **Disp. art. per ubicazione**.

1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Articoli**, quindi scegliere il collegamento correlato.
2. Aprire la scheda di un articolo per cui si desidera visualizzare la disponibilità.
3. Scegliere l'azione **Disponibilità articolo per** quindi scegliere l'azione **Ubicazione**.

    La finestra **Disponibilità articolo per ubicazione** mostra come le quantità di magazzino dell'articolo si svilupperanno nel futuro in ogni ubicazione in cui è immagazzinato.
4. Selezionare il valore nel campo **Giacenza disponibile** per visualizzare i movimenti articoli che compongono il valore.
5. Selezionare il valore nel campo **Disponibilità calcolata** per visualizzare i movimenti articoli o documenti aperti che compongono il valore.

## <a name="to-view-the-availability-of-all-items-by-the-location-where-they-are-stored"></a>Per visualizzare la disponibilità di tutti gli articoli in base all'ubicazione in cui sono immagazzinati
È possibile visualizzare la disponibilità di tutti gli articoli in tutte le ubicazioni nella finestra **Articoli per ubicazione**.

1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Articoli**, quindi scegliere il collegamento correlato.
2. Scegliere l'azione **Articoli per ubicazione**.

    La finestra **Articoli per ubicazione** mostra per tutti gli articoli le quantità disponibili in ogni ubicazione.
3. Selezionare il valore nel campo **Giacenza disponibile** per visualizzare i movimenti articoli che compongono il valore.

## <a name="to-view-the-availability-of-an-item-by-its-use-in-assembly-or-production-boms"></a>Per visualizzare la disponibilità di un articolo in base al relativo utilizzo nelle DB di assemblaggio o di produzione
Se un articolo esiste nelle DB di assemblaggio o di produzione, come articolo principale o come componente, è possibile visualizzare il numero di unità che sono necessarie nella finestra **Disponibilità articolo per livello DB**. Nella finestra viene visualizzato il numero delle unità di un articolo padre che è possibile effettuare in base alla disponibilità di articoli figlio nelle righe sottostanti. Ogni articolo che ha una DB di assemblaggio o di produzione è visibile nella finestra come riga comprimibile. È possibile espandere la riga per visualizzare i componenti sottostanti i sottoassemblaggi di livello inferiore con le proprie DB.

È possibile utilizzare la finestra per verificare se è possibile soddisfare un ordine di vendita per un articolo nella data stabilita osservando la disponibilità corrente e le quantità che possono essere fornite dai componenti. È inoltre possibile utilizzare la finestra per identificare i colli di bottiglia nelle DB correlate.

In ogni riga della finestra per gli articoli padre e gli articoli figlio, i seguenti campi chiave specificano le cifre sulla disponibilità. È possibile utilizzare tali cifre per promettere il numero di unità di un articolo padre che è possibile fornire se si inizia il processo assemblaggio correlato.

|Campo|Descrizione|
|------|-----------|
|**Produzione possibile - Padre**|Mostra quante unità di un sottoassemblaggio nell'articolo principale è possibile preparare. Questo campo specifica quante unità dell'articolo padre immediate possono essere assemblate. Il valore è basato sulla disponibilità dell'articolo nella riga.|
|**Produzione possibile - Articolo principale**|Mostra quante unità dell'articolo principale è possibile preparare. Questo campo specifica quante unità dell'articolo DB nella prima riga possono essere assemblate. Il valore è basato sulla disponibilità dell'articolo nella riga.|

### <a name="item-availability-by-bom-level-window"></a>Finestra Disponibilità articolo per livello DB
Nella finestra **Disponibilità articolo per livello DB** vengono visualizzate le informazioni relative all'articolo sulla scheda o la riga del documento per il quale viene viene aperta la finestra. L'articolo viene indicato sempre nella prima riga. È possibile visualizzare informazioni per altri articoli o per tutti gli articoli modificando il valore nel campo **Filtro articolo**.

> [!NOTE]  
>   Per default, le cifre sulla disponibilità nelle righe mostrano la disponibilità totale di tutti gli articoli sotto l'articolo principale. Le cifre vengono visualizzate nel campo **Quantità disponibile** e lo stato attivo è sull'articolo principale. Tuttavia, le informazioni relative al numero di sottoassemblaggi che è possibile preparare potrebbero essere distorte. Per ottenere un'indicazione vera di quanti dei sottoassemblaggi mostrati è possibile preparare, è necessario cancellare il campo **Mostra disponibilità totale**, quindi visualizzare la cifra nel campo **Produzione possibile - Padre**.

Il campo **Collo di bottiglia** specifica quale articolo nella struttura di DB limita la possibilità di produrre una quantità maggiore di quella indicata nel campo **Produzione possibile - Articolo principale**. Ad esempio, l'articolo collo di bottiglia può essere un componente acquistato con una data di carico prevista troppo in ritardo per creare unità aggiuntive dell'articolo principale entro la data presente nel campo **Disponibile entro**.

## <a name="assembly-availability-window"></a>Finestra Disponibilità assemblaggio
Nella finestra **Disponibilità assemblaggio** sono visualizzate le informazioni dettagliate sulla disponibilità per l'articolo di assemblaggio. La finestra viene aperta:

- Automaticamente da una riga ordine di vendita in scenari di assemblaggio su ordine quando si immette una quantità che provoca un problema di disponibilità dei componenti.
- Automaticamente da una testata ordine di assemblaggio quando si immette un valore nel campo Quantità che provoca un problema di disponibilità dei componenti.
- Manualmente quando la si apre da un ordine di assemblaggio. Nel gruppo Funzioni della scheda Azioni scegliere Mostra disponibilità.

Nella Scheda dettaglio **Dettagli** sono visualizzate le informazioni dettagliate sulla disponibilità per l'articolo di assemblaggio, inclusa la quantità dell'ordine di assemblaggio che è possibile assemblare entro la data di scadenza in base alla disponibilità dei componenti necessari. Sono visualizzate nel campo In grado di assemblare nella Scheda Dettaglio Dettagli.

Il valore nel campo **In grado di assemblare** viene visualizzato con un carattere rosso se la quantità è inferiore alla quantità nel campo **Quantità residua**, per indicare che non sono disponibili componenti sufficienti per assemblare la quantità completa.

Nella Scheda dettaglio **Righe** vengono visualizzate le informazioni dettagliate sulla disponibilità per i componenti di assemblaggio.

Se uno o più componenti di assemblaggio non sono disponibili, queste informazioni vengono riflesse nel campo **In grado di assemblare** nella riga in questione come quantità minore della quantità nel campo **Quantità residua** nella Scheda Dettaglio **Dettagli**.

## <a name="see-also"></a>Vedi anche
[Gestire i costi del magazzino](inventory-manage-inventory.md)  
[Gestione assemblaggio](assembly-assemble-items.md)  
[Procedura: Utilizzare le distinte base](inventory-how-work-BOMs.md)    
[Procedura: Impostare le ubicazioni](inventory-how-setup-locations.md)  
[Procedura: Trasferire il magazzino tra le ubicazioni](inventory-how-transfer-between-locations.md)  
[Procedura: Vendere prodotti](sales-how-sell-products.md)      
[Utilizzo di Dynamics NAV](ui-work-product.md)  
[Funzionalità aziendali generali](ui-across-business-areas.md)

