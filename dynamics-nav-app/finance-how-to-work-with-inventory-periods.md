---
title: Come utilizzare periodi di magazzino
description: "È possibile controllare l'intervallo temporale durante il quale si possono registrare modifiche al magazzino defininendo periodi di magazzino."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: inventory, periods
ms.date: 08/07/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 289b12d39c9f67913d862cb3500cccae0b3823d2
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-work-with-inventory-periods"></a>Procedura: Utilizzare periodi di magazzino
I periodi di magazzino definiscono un periodo di tempo durante il quale è possibile registrare modifiche al magazzino. Un periodo di magazzino è definito dalla data in cui termina, ovvero la data di fine. Quando il periodo di magazzino è chiuso, non è possibile registrare modifiche al magazzino, previsto o fatturato, precedente alla data di fine. Non è inoltre possibile inserire qualsiasi nuovo valore nel magazzino prima della data di fine. Se nel periodo chiuso sono presenti movimenti articoli aperti, ovvero quantità positive non ancora consumate da, o collegate a, transazioni in uscita, è ancora possibile collegare quantità in uscita a questi movimenti, anche se il periodo è chiuso.  

Nelle sezioni successive viene descritto come effettuare le seguenti operazioni:  

* Creare periodi di magazzino.  
* Chiudere periodi di magazzino.  
* Riaprire periodi di magazzino.  

## <a name="to-create-an-inventory-period"></a>Per creare un periodo di magazzino  
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Periodi magazzino**, quindi scegliere il collegamento correlato.  
2. Creare una nuova riga.  
3. Nel campo **Data fine** immettere l'ultima data del periodo di magazzino che si desidera definire. Quando il periodo è chiuso, non sarà possibile registrare modifiche al magazzino prima di tale data.  
4. Nel campo **Nome** immettere un nome descrittivo. Scegliere il pulsante **OK**.  

## <a name="closing-inventory-periods"></a>Chiusura di periodi di magazzino  
Il campo **Chiuso** indica se il periodo di magazzino è chiuso, ovvero se non è più possibile apportare modifiche al relativo valore. Non è possibile modificare questo campo.  

È possibile chiudere qualsiasi periodo di magazzino, purché si verifichino le seguenti condizioni:  

* Non devono esserci movimenti contabili articoli in uscita, ovvero giacenze negative, nel periodo.  
* Il costo di tutti gli articoli deve essere stato rettificato tramite il processo batch **Rettifica costo - Mov. art.**.  

Questo significa che tutte le quantità relative a transazioni in uscita, ad esempio ordini di vendita, trasferimenti in uscita, fatture di vendita, resi di acquisto o note di credito di acquisto, devono essere collegate a quantità esistenti in magazzino.  

### <a name="to-close-an-inventory-period"></a>Per chiudere un periodo di magazzino  
1. Prima di chiudere un periodo di magazzino, eseguire il processo batch **Rettifica costo - Mov. art.** per assicurarsi di registrare tutte le rettifiche dei costi. Nel gruppo **Funzioni** della scheda **Azioni** scegliere **Rettifica costo - Mov. art.**.  

     Eseguire il report **Chiudi periodo magazzino - Test** per determinare se vi sono movimenti articoli in uscita inclusi nel periodo di magazzino o se vi sono articoli il cui costo non è ancora stato rettificato.  
2. Scegliere l'azione **Chiudi periodo di magazzino - Test**.  

     Eseguire il processo batch **Registra costo magazzino in C/G** per fare in modo che tutti i costi vengano registrati nella contabilità generale.  
3. Scegliere l'azione **Registra magazzino in C/G**.  
4. Nella finestra **Periodi magazzino** selezionare il periodo di magazzino che si desidera chiudere.  
5. Scegliere l'azione **Chiudi periodo**. Dopo che il periodo viene chiuso non è possibile registrare modifiche al magazzino prima della data di fine. Prima di chiudere il periodo di magazzino, è necessario rettificare il costo di tutti gli articoli tramite il processo batch **Rettifica costo - Mov. art.**.  
6. Fare clic su **Sì** per confermare la chiusura del periodo oppure su **No** per annullarla.  
7. Il periodo di magazzino verrà chiuso e, al termine dell'operazione, verrà visualizzato un messaggio di conferma.  

## <a name="reopening-inventory-periods"></a>Riapertura di periodi di magazzino  
Dopo aver chiuso una volta il periodo di magazzino, non è più possibile eliminarlo. È tuttavia possibile riaprirlo se si desidera consentire la registrazione prima della data di fine del periodo stesso. Riaprendo un periodo vengono riaperti anche tutti i periodi con date di fine successive a quella del periodo riaperto.  

### <a name="to-reopen-an-inventory-period"></a>Per riaprire un periodo di magazzino  
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Periodi magazzino**, quindi scegliere il collegamento correlato.  
2. Selezionare il periodo di magazzino che si desidera riaprire.  
3. Scegliere l'azione **Riapri periodo**. Confermare che si desidera riaprire il periodo.  
4. Vengono riaperti anche tutti i periodi con date di fine successive a quella del periodo selezionato.  

## <a name="see-also"></a>Vedi anche  
[Dettagli di progettazione: Periodi di magazzino](design-details-inventory-periods.md)  
[Finanze](finance.md)  
[Magazzino](inventory-manage-inventory.md)  
[Utilizzo di Dynamics NAV](ui-work-product.md)

