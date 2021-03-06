---
title: Utilizzare Excel per importare i dati in Dynamics NAV
description: Utilizzare il pacchetto di configurazione di default per aggiungere i dati del cliente in Excel e importare nuovamente i dati in Dynamics NAV.
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: migration, Excel
ms.date: 07/05/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: eb9b7137ee31824ba845ff336c00c6f0e59f6f5c
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="importing-data-from-legacy-accounting-software-using-a-configuration-package"></a>Importazione di dati del software di contabilizzazione legacy utilizzando un pacchetto di configurazione
È possibile importare dati master e alcuni dati transazionali da altri sistemi finanziari in base al pacchetto di configurazione standard disponibile in [!INCLUDE[d365fin](includes/d365fin_md.md)]. Nella finestra **Pacchetti di configurazione** è possibile utilizzare il pacchetto per importare e convalidare i dati prima di applicare il pacchetto.  

Se si ha familiarità con i Servizi di RapidStart per Microsoft Dynamics, si conoscono anche i pacchetti di configurazione. Il pacchetto di configurazione di default supporta i più comuni tipi di dati che si desidera importare da un sistema legacy. In Excel è possibile aggiungere i dati del sistema legacy e configurarli in base alla logica di business di [!INCLUDE[d365fin](includes/d365fin_md.md)].  

> [!TIP]  
>   In alternativa, usare le procedure guidate di migrazione dati per importare i dati da QuickBooks o Dynamics GP. Per ulteriori informazioni, vedere [Migrazione dei dati di QuickBooks](ui-extensions-quickbooks-data-migration.md) o [Migrazione dei dati di Dynamics GP](ui-extensions-dynamicsgp-data-migration.md).  

## <a name="working-with-data-in-excel"></a>Utilizzo di dati in Excel
Quando si esporta il pacchetto di configurazione di default in Excel, la cartella di lavoro generata contiene un prospetto per ogni tabella del pacchetto. Per semplificare i task, è possibile avvantaggiarsi degli strumenti di modifica XML incorporati in Excel. È inoltre possibile utilizzare le funzioni incorporate di Excel per agevolare la formattazione dei dati e inserire i dati nella cella appropriata. Ad esempio, aggiungere un prospetto vuoto e copiarvi i dati legacy. Creare quindi una formula Excel per mappare i dati nel prospetto di trasformazione tra i campi del prospetto esportato e i dati legacy del cliente. Dopo aver eseguito la mappatura di tutti i dati, copiare l'intervallo dei dati nel prospetto della tabella.  

> [!IMPORTANT]  
>  Non modificare le colonne nei prospetti. Se vengono spostate, modificate o eliminate, il prospetto non può essere importato in [!INCLUDE[d365fin](includes/d365fin_md.md)].

## <a name="tables-in-the-default-configuration-package"></a>Tabelle nel pacchetto di configurazione di default
Il pacchetto di configurazione di default supporta le seguenti tabelle:

-   Condizioni pagamento
-   Gruppo prezzi cliente
-   Metodo di spedizione
-   Agenti/Addetti acq.
-   Località
-   Conto C/G
-   Cliente
-   Fornitore
-   Articolo
-   Testate vendita
-   Righe vendite
-   Testate acquisti
-   Righe Acquisto
-   Righe registrazioni COGE
-   Righe reg. magazzino
-   Cat. reg. cliente
-   Cat. reg. fornitore
-   Cat. reg. magazzino
-   Unità di misura
-   Cat. reg. business
-   Cat. reg. articoli/servizi
-   Setup registrazioni COGE
-   Regioni
-   Categorie articolo
-   Prezzo vendita
-   Prezzo acquisto

## <a name="importing-customer-data"></a>Importazione di dati dei clienti
Dopo che i dati dei clienti sono stati importati in Excel, vengono importati in [!INCLUDE[d365fin](includes/d365fin_md.md)]. Nella finestra **Pacchetti di configurazione** importare i dati del file Excel. È possibile verificare che i dati siano coerenti con [!INCLUDE[d365fin](includes/d365fin_md.md)] prima di applicare il pacchetto.

## <a name="see-also"></a>Vedi anche
[Importazione dei dati aziendali da altri sistemi contabili](upload-data.md)  
[Migrazione dei dati QuickBooks](ui-extensions-quickbooks-data-migration.md)  
[Migrazione dei dati Dynamics GP](ui-extensions-dynamicsgp-data-migration.md)

