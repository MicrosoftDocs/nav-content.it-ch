---
title: Impostare un bonifico SEPA
description: Informazioni su come impostare bonifico SEPA in Dynamics NAV.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: sepa, credit, transfer, payment,
ms.date: 08/21/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 5dd85579a39fc9bfb3bb362e9573facc0c0a3977
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-sepa-credit-transfer"></a>Procedura: Impostare il bonifico SEPA
Nella finestra **Registrazioni pagamenti** è possibile esportare i pagamenti in un file da caricare nel sito elettronico della banca per elaborare trasferimenti di denaro correlati. [!INCLUDE[d365fin](includes/d365fin_md.md)] supporta il formato di bonifico SEPA, ma nel proprio paese potrebbero essere disponibili anche altri formati di pagamento elettronico.  

Per abilitare l'esportazione di formati di file della banca che non sono supportati come predefiniti in [!INCLUDE[d365fin](includes/d365fin_md.md)], è possibile impostare una definizione di scambio dati utilizzando il framework di scambio dati. Per ulteriori informazioni, vedere [Procedura: Impostare le definizioni di scambio di dati](across-how-to-set-up-data-exchange-definitions.md).  

Prima di elaborare elettronicamente il pagamento esportando i file di pagamento in formato di bonifico SEPA, è necessario effettuare le seguenti operazioni di setup:  

* Impostare il conto corrente bancario in questione per gestire il formato del bonifico SEPA.  
* Impostare le schede fornitori per elaborare i pagamenti esportando i file nel formato di bonifico SEPA.  
* Impostare il batch di registrazioni COGE correlato per abilitare l'esportazione dei pagamenti dalla finestra **Registrazioni pagamenti**.  
* Connettere la definizione di scambio dati per uno o più tipi di pagamento con uno o più metodi di pagamento rilevanti  

### <a name="to-set-up-a-bank-account-for-sepa-credit-transfer"></a>Per impostare un conto bancario per il bonifico SEPA  
1. Nella casella **Cerca** immettere **C/C bancari**, quindi selezionare il collegamento correlato.  
2. Aprire la scheda del conto corrente bancario da cui si esporteranno i file di pagamento nel formato di bonifico SEPA.  
3. Nella Scheda dettaglio **Trasferimento**, nel campo **Formato esportazione pagamento** scegliere **SEPADD**.  
4. Nel campo relativo al **Nr serie ID msg CT SEPA** scegliere una serie numerica da cui i numeri vengono assegnati ai movimenti di bonifici SEPA.  
5. Assicurarsi che il campo **IBAN** sia compilato.  

    > [!NOTE]  
    >  Il campo **Codice valuta** deve essere impostato su **EUR**, perché i bonifici SEPA possono essere eseguiti solo in valuta EURO.  

### <a name="to-set-up-a-vendor-card-for-sepa-credit-transfer"></a>Per impostare una scheda fornitore per il bonifico SEPA  
1. Nella casella **Cerca** immettere **Fornitori**, quindi selezionare il collegamento correlato.  
2. Aprire la scheda del fornitore che si pagherà in via elettronica esportando i file di pagamento nel formato di bonifico SEPA.  
3. Nella Scheda dettaglio **Pagamento**, nel campo **Codice metodo di pagamento** scegliere **BANCA**.  
4. Nel campo **Conto bancario preferito** scegliere la banca a cui sarà trasferito il denaro una volta elaborato in via elettronica dalla banca.  

     Il valore nel campo **Conto bancario preferito** viene copiato nel campo **Conto bancario destinatario** nella finestra **Registrazioni pagamenti**.  

### <a name="to-set-the-payment-journal-up-to-export-payment-files"></a>Per impostare le registrazioni pagamenti fino per esportare i file di pagamento  
1. Nella casella **Cerca** immettere **Registrazioni pagamenti**, quindi selezionare il collegamento correlato.  
2. Aprire le registrazioni pagamenti utilizzate per elaborare i pagamenti esportando i file nel formato di bonifico SEPA.  
3. Nel campo **Nome batch** scegliere il pulsante a discesa.  
4. Nella finestra **Batch registrazioni COGE**, nella scheda **Pagina iniziale**, nel gruppo **Gestisci** scegliere **Modifica lista**.  
5. Nella riga delle registrazioni pagamenti da utilizzare per esportare i pagamenti, selezionare la casella di controllo **Consenti esportazione pagamento**.  

### <a name="to-connect-the-data-exchange-definition-for-one-or-more-payment-types-with-the-relevant-payment-method-or-methods"></a>Per connettere la definizione di scambio dati per uno o più tipi di pagamento con uno o più metodi di pagamento rilevanti  
1. Nella casella **Cerca** immettere **Metodi di pagamento**, quindi selezionare il collegamento correlato.  
2. Nella finestra **Metodi di pagamento** selezionare il metodo di pagamento che viene utilizzato per esportare i pagamenti e quindi scegliere il campo **Definizione righe esport. pagam.**.  
3. Nella finestra **Definizioni righe esportazione pagamento** selezionare il codice che è stato specificato nel campo **Codice** della Scheda dettaglio **Definizioni righe** nel passaggio 4 della sezione "Per descrivere la formattazione di righe e colonne nel file" della [Procedura: Impostare le definizioni di scambio di dati](across-how-to-set-up-data-exchange-definitions.md).  

    Il mandato di addebito diretto viene inserito automaticamente nel campo **ID mandato per addebito diretto** quando si crea una fattura di vendita per il cliente selezionato nel passaggio 2. Per altre informazioni, vedere [Procedura: Creare righe di vendite e acquisti ricorrenti](sales-how-work-standard-lines.md).  

## <a name="see-also"></a>Vedi anche  
[Riscuotere pagamenti con addebito diretto SEPA](finance-collect-payments-with-sepa-direct-debit.md)  
[Procedura: Impostare le definizioni di scambio di dati](across-how-to-set-up-data-exchange-definitions.md)  
[Procedura: Creare righe di vendite e acquisti ricorrenti](sales-how-work-standard-lines.md)  
[Scambio di dati in modalità elettronica](across-data-exchange.md)  

