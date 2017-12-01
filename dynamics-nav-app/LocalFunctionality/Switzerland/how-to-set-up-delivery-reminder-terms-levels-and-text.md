---
title: 'Procedura: Impostare termini, livelli e testo dei solleciti di consegna'
description: "Per creare i solleciti di consegna, è necessario impostare i termini, i livelli e i testi dei solleciti di consegna. messaggi"
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
ms.openlocfilehash: d1bb57cce6c6a681e31bdfaafe05a1d8f42979e4
ms.contentlocale: it-ch
ms.lasthandoff: 10/26/2017

---
# <a name="how-to-set-up-delivery-reminder-terms-levels-and-text"></a>Procedura: Impostare termini, livelli e testo dei solleciti di consegna
Per creare i solleciti di consegna è necessario impostare quanto segue:  

- Termini di sollecito di consegna  
- Livelli del sollecito di consegna  
- Messaggi di testo di sollecito di consegna  

Ogni termine di sollecito di consegna ha due o più livelli di sollecito di consegna e per ogni livello di sollecito di consegna è possibile specificare il testo che fa parte del sollecito di consegna.  

Per ulteriori informazioni, vedere [Solleciti di consegna](delivery-reminders.md).  

## <a name="to-set-up-delivery-reminder-terms"></a>Per impostare i termini di sollecito di consegna  

1.  Scegliere l'icona ![Cerca pagina o report](../../media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Termini di sollecito di consegna**, quindi scegliere il collegamento correlato.  
2.  Scegliere l'azione **Nuovo**.  
3.  Compilare i campi come indicato nella tabella seguente.  

    |Campo|Descrizione|  
    |---------------------------------|---------------------------------------|  
    |**Codice**|Codice per i termini di sollecito di consegna. È possibile immettere un massimo di 10 caratteri alfanumerici.|  
    |**Descrizione**|Descrizione per i termini di sollecito di consegna. È possibile immettere un massimo di 30 caratteri alfanumerici.|  
    |**Nr. Max di Solleciti Consegna**|Numero massimo di solleciti di consegna che è possibile creare per un ordine.<br /><br /> **NOTA:** questo è il numero massimo per tutti i livelli di sollecito per questo termine di sollecito. Ad esempio, se si impostano tre livelli e si imposta **Numero massimo di solleciti di consegna** su 5, il primo sollecito viene creato al livello 1, il secondo al livello 2 e gli ultimi tre al livello 3.|  

4.  Scegliere il pulsante **OK**.  

## <a name="to-add-delivery-reminder-levels-to-a-delivery-reminder-term"></a>Per aggiungere livelli di sollecito di consegna a un termine di sollecito di consegna  

1.  Nella finestra **Termini di sollecito di consegna** selezionare il termine di sollecito di consegna per cui si desidera impostare i livelli e scegliere l'azione **Livelli**.  
2.  Scegliere l'azione **Nuovo**.  
3.  Compilare i campi come indicato nella tabella seguente.  

    |Campo|Descrizione|  
    |---------------------------------|---------------------------------------|  
    |**Nr.**|Numero del livello del sollecito di consegna. Questo campo viene compilato automaticamente.|  
    |**Calcolo data di scadenza**|Formula per il calcolo della data di scadenza per il sollecito di consegna. È possibile immettere una combinazione di numeri da 0 a 9999 e codici di data (G per giorno, GS per il giorno della settimana, S per settimana, M per mese, T per trimestre o A per anno). I codici di data indicano il calcolo della data di scadenza per il sollecito di consegna. È possibile inserire un massimo di 20 caratteri per la formula di calcolo della data di scadenza.|  

4.  Scegliere il pulsante **OK**.  

Per ciascun livello di sollecito di consegna è possibile definire messaggi di testo che vengono aggiunti al sollecito di consegna. Definire il testo iniziale che viene aggiunto prima della descrizione dell'ordine di acquisto scaduto e il testo finale che viene aggiunto dopo la descrizione dell'ordine di acquisto scaduto.  

La procedura seguente descrive come impostare i messaggi di testo iniziali, ma gli stessi passaggi si applicano per impostare i messaggi di testo finali.  

## <a name="to-set-up-delivery-reminder-text-messages"></a>Per impostare i messaggi di testo di sollecito di consegna  

1.  Nella finestra **Livelli del sollecito di consegna** selezionare un livello e scegliere l'azione **Testo iniziale**.  
2.  Scegliere l'azione **Nuovo**.  
3.  Nel campo **Descrizione** inserire il messaggio di testo iniziale per il sollecito di consegna.  
4.  Scegliere il pulsante **OK**.  

## <a name="see-also"></a>Vedere anche  
 [Solleciti consegna](delivery-reminders.md)   
 [Procedura: Impostare solleciti di consegna](how-to-set-up-delivery-reminders.md)   
 [Procedura: Assegnare codici di solleciti di consegna ai fornitori](how-to-assign-delivery-reminder-codes-to-vendors.md)   
 [Procedura: Creare solleciti di consegna manualmente](how-to-create-delivery-reminders-manually.md)   
 [Procedura: Emettere solleciti di consegna](how-to-issue-delivery-reminders.md)

