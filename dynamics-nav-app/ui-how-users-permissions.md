---
title: Assegnare autorizzazioni utente e creare o modificare i set di autorizzazioni
description: Descrive come aggiungere utenti di Office 365 a Dynamics NAV e quindi assegnare le autorizzazioni, i diritti di accesso e le impostazioni di protezione.
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: access, right, security
ms.date: 07/12/2018
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 9bd92e91f614963125756aceb2e6942f91e0e5e2
ms.openlocfilehash: a05ef07a512cfe5ba9a9113dbc846c89e0493f63
ms.contentlocale: it-ch
ms.lasthandoff: 07/13/2018

---
# <a name="how-to-manage-users-and-permissions"></a>Procedura: Gestire gli utenti e le autorizzazioni
Se nella società arriva un nuovo dipendente, l'amministratore di sistema o un responsabile IT deve aggiungerlo in [!INCLUDE[d365fin](includes/d365fin_md.md)]. Successivamente è possibile assegnare al dipendente l'accesso alle parti pertinenti del prodotto in base alla sua area di competenza, assegnandolo a gruppi utenti e concedendogli autorizzazioni.

I set di autorizzazioni definiscono a quali oggetti di database, e quindi quali elementi dell'interfaccia utente, hanno accesso gli utenti e in quali società.

Un set di permessi è un raccolta di permessi per oggetti specifici del database. A tutti gli utenti devono essere assegnati uno o più set di autorizzazioni prima di poter accedere a [!INCLUDE[d365fin](includes/d365fin_md.md)]. Alcuni set di autorizzazioni di default vengono forniti per default. È possibile utilizzare questi set di permessi già definiti, modificarli o creare ulteriori set di permessi.

È possibile aggiungere gli utenti ai gruppi utente. Ciò facilita l'assegnazione degli stessi set di autorizzazioni a più utenti.

Gli amministratori possono utilizzare la finestra **Setup utente** per definire i periodi di tempo in cui utenti specificati possono effettuare registrazioni e anche specificare se il sistema registra il periodo di tempo per cui gli utenti si sono connessi.

## <a name="to-assign-permissions-to-a-user"></a>Assegnare autorizzazioni a un utente
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Utenti**, quindi scegliere il collegamento correlato.
2. Selezionare l'utente a cui si intende assegnare l'autorizzazione.
Tutti i set di autorizzazioni già assegnati all'utente vengono visualizzati nel Dettaglio informazioni **Set di autorizzazioni**.
3. Scegliere l'azione **Modifica** per aprire la finestra **Scheda utente**.
4. Nella Scheda dettaglio **Set di autorizzazioni utente** compilare i campi secondo le necessità su una nuova riga. [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-group-users-in-user-groups"></a>Per raggruppare gli utenti in gruppi di utenti
È possibile impostare i gruppi di utenti per gestire facilmente i set di autorizzazioni per i gruppi di utenti della società. È possibile utilizzare una funzione che consente di copiare tutti i set di autorizzazioni da un gruppo di utenti esistenti al nuovo gruppo di utenti. I membri del gruppo di utenti non vengono copiati.

1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Gruppi di utenti**, quindi scegliere il collegamento correlato.
2. In alternativa, nella finestra **Utenti** scegliere l'azione **Gruppi di utenti**.
3. Nella finestra **Gruppi di utenti** selezionare un gruppo di utenti esistenti che si desidera copiare quindi scegliere l'azione **Copia gruppo di utenti**.
4. Nel campo **Nuovo codice gruppo di utenti** specificare il nome del nuovo gruppo di utenti quindi scegliere il pulsante **OK**.

    Come alternativa alla copia, è possibile scegliere l'azione Nuovo per creare una nuova riga per un gruppo di utenti vuoto, che quindi viene compilato manualmente.
5. Per aggiungere nuovi o ulteriori utenti, nella finestra **Gruppo di utenti** selezionare l'azione **Membri gruppo di utenti**.
6. Nella finestra **Membri gruppo di utenti**, in una nuova riga, compilare tutti i campi come necessario selezionando dagli utenti esistenti.
7. Per aggiungere nuove o ulteriori autorizzazioni, nella finestra **Gruppo di utenti** selezionare l'azione **Set di autorizzazioni gruppo di utenti**.
8. Nella finestra **Set di autorizzazioni gruppo di utenti**, in una nuova riga, compilare tutti campi come necessario selezionando dai set di autorizzazioni.

## <a name="to-create-or-modify-permission-sets"></a>Per creare o modificare i set di autorizzazioni
Se i set di autorizzazioni di default forniti con [!INCLUDE[d365fin](includes/d365fin_md.md)] non sono sufficienti o non appropriati per la propria organizzazione, è possibile creare nuovi set di autorizzazioni. Se le singole autorizzazioni oggetto che definiscono un set di autorizzazioni non sono appropriate, è possibile modificare un set di autorizzazioni. È possibile creare manualmente un set di autorizzazioni oppure utilizzare una funzione di registrazione per le azioni mentre gli utenti effettuano spostamenti in uno scenario e quindi generare il set di autorizzazioni richiesto.

### <a name="to-create-or-modify-permission-sets-manually"></a>Per creare o modificare i set di autorizzazioni manualmente
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Utenti**, quindi scegliere il collegamento correlato.
2. Nella finestra **Utenti** scegliere l'azione **Set di autorizzazioni**.
3. Nella finestra **Set di autorizzazioni** scegliere l'azione **Nuovo**.
4. In una nuova riga, compilare i campi in base alle esigenze.
5. Scegliere l'azione **Autorizzazioni**.
6. Nella finestra **Autorizzazioni** compilare i campi nell'intestazione in base alle esigenze.
7. In una nuova riga, compilare i cinque campi per i vari tipi di autorizzazione come descritto nella tabella seguente.

    |Opzione|Descrizione|
    |------|-----------|
    |Vuoto|Specifica che il tipo di autorizzazione non è concesso per l'oggetto.|
    |**Sì**|Specifica che il tipo di autorizzazione è concesso con accesso diretto all'oggetto.|
    |**Indiretto**|Specifica che il tipo di autorizzazione è concesso con accesso indiretto all'oggetto.|

    L'autorizzazione indiretta per una tabella significa che non è possibile aprire la tabella e leggere da essa, ma è possibile visualizzare i dati della tabella mediante un altro oggetto, ad esempio una pagina, con autorizzazione diretta all'accesso. Per ulteriori informazioni, vedere la sezione "Esempio - Autorizzazione indiretta" in questo argomento.

8. Nel campo **Filtro protezione** immettere un filtro da applicare all'autorizzazione selezionando il campo per cui si desidera limitare l'accesso dell'utente.

    Ad esempio, se si desidera creare un filtro di protezione in modo che l'utente visualizzi solo le vendite con uno specifico codice agente, si può scegliere il numero di campo per il campo **Codice agente**. Quindi, nel campo **Filtro campo**, immettere il valore di che si desidera utilizzare per limitare l'accesso. Ad esempio, per limitare l'accesso di un utente solo alle vendite di Annette Hill, immettere AH.
9. Ripetere i passaggi 7 e 8 per aggiungere le autorizzazioni per gli oggetti aggiuntivi al set di autorizzazioni.

### <a name="to-create-or-modify-permission-sets-by-recording-your-actions"></a>Per creare o modificare i set di autorizzazioni registrando le azioni
1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Utenti**, quindi scegliere il collegamento correlato.
2. Nella finestra **Utenti** scegliere l'azione **Set di autorizzazioni**.
3. Nella finestra **Set di autorizzazioni** scegliere l'azione **Nuovo**.
4. In una nuova riga, compilare i campi in base alle esigenze.
5. Scegliere l'azione **Autorizzazioni**.
6. Nella finestra **Autorizzazioni** scegliere l'azione **Avvia**.

    Un processo di registrazione inizia ad acquisire tutte le azioni nell'interfaccia utente.
7. Passare alle diverse finestre e attività di [!INCLUDE[d365fin](includes/d365fin_md.md)] a cui si desidera che gli utenti con questo set di autorizzazioni possano accedere. È necessario eseguire i task per cui si desidera registrare le autorizzazioni.
8. Quando si desidera terminare la registrazione, tornare alla finestra **Autorizzazioni** e scegliere l'azione **Arresta**.
9. Scegliere il pulsante **Sì** per aggiungere le autorizzazioni registrate nel nuovo set di autorizzazioni.
10. Per ogni oggetto nella lista registrata, specificare se gli utenti possono immettere, modificare o eliminare, i record nelle tabelle registrate. Vedere il passaggio 7 della sezione "Per creare o modificare i set di autorizzazioni manualmente".

### <a name="example---indirect-permission"></a>Esempio - Autorizzazione indiretta
È possibile assegnare un'autorizzazione indiretta per utilizzare un oggetto solo attraverso un altro oggetto.
Ad esempio, un utente può disporre dell'autorizzazione per eseguire la codeunit 80, **Vendite-Registra**. La codeunit **Vendite-Registra** esegue molti task, tra cui la modifica della tabella 37, **Riga vendite**. Quando l'utente registra un documento di vendita, la codeunit **Vendite-Registra**, [!INCLUDE[d365fin](includes/d365fin_md.md)] verifica se l'utente dispone delle autorizzazioni per modificare la tabella **Righe vendite**. In caso di risposta negativa, la codeunit non può completare i relativi task e l'utente riceve un messaggio di errore. In caso di risposta affermativa, la codeunit viene eseguita correttamente.

Tuttavia, per l'utente non è necessario avere accesso completo alla tabella **Righe vendite** per eseguire la codeunit. Se l'utente possiede un'autorizzazione indiretta per la tabella **Righe vendite**, la codeunit **Vendite-Registra** viene eseguita correttamente. Quando un utente possiede un'autorizzazione indiretta, tale utente può solo modificare la tabella **Riga vendite** eseguendo la codeunit di **Vendite-Registra** o un altro oggetto per cui possiede l'autorizzazione per modificare la tabella **Righe vendite**. L'utente può solo modificare la tabella **Righe vendite** quando esegue questa operazione da aree di applicazione supportate. L'utente non può eseguire inavvertitamente o intenzionalmente la funzionalità con altri metodi.

## <a name="to-set-up-user-time-constraints"></a>Per impostare i vincoli connessioni utenti
Gli amministratori possono definire i periodi di tempo in cui utenti specificati possono effettuare registrazioni e anche specificare se il sistema registra il periodo di tempo per cui gli utenti si sono connessi. Gli amministratori possono anche assegnare centri di responsabilità agli utenti.

1. Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "Cerca pagina o report"), immettere **Setup utente**, quindi scegliere il collegamento correlato.
2. Nella finestra **Setup utenti** scegliere l'azione **Nuovo**.
3. Nel campo **ID utente**, immettere l'ID di un utente o scegliere il campo per visualizzare tutti gli utenti correnti di Windows nel sistema.
4. Compilare i campi come necessario.

## <a name="see-also"></a>Vedi anche
[Preparazione al business](ui-get-ready-business.md)  
[Impostazione e amministrazione in Dynamics NAV](admin-setup-and-administration.md)  
[Benvenuto in [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  
[Creazione di utenti di Microsoft Dynamics NAV](/dynamics-nav/How-to--Create-Microsoft-Dynamics-NAV-Users)  

