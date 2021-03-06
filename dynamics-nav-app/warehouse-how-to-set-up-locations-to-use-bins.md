---
title: Come impostare ubicazioni per l'utilizzo di collocazioni
description: "Le collocazioni rappresentano la struttura di warehouse di base e vengono utilizzate per creare suggerimenti relativi al posizionamento degli articoli. Dopo avere creato le collocazioni desiderate, è possibile definire in modo specifico il contenuto che si desidera includere in ciascuna collocazione. In alternativa, è possibile utilizzare la collocazione come collocazione variabile, ovvero priva di contenuto specifico."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 95b36b6eed79da868c1e41905110788c90f24829
ms.contentlocale: it-ch
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-locations-to-use-bins"></a>Procedura: Impostare ubicazioni per l'utilizzo di collocazioni
Le collocazioni rappresentano la struttura di warehouse di base e vengono utilizzate per creare suggerimenti relativi al posizionamento degli articoli. Dopo avere creato le collocazioni desiderate, è possibile definire in modo specifico il contenuto che si desidera includere in ciascuna collocazione. In alternativa, è possibile utilizzare la collocazione come collocazione variabile, ovvero priva di contenuto specifico.  

Per utilizzare la funzionalità relativa alle collocazioni in un'ubicazione, è necessario prima attivarla nella scheda **Ubicazione**. Si progetterà quindi il flusso degli articoli nell'ubicazione specificando i codici di collocazione nei campi di setup che rappresentano i diversi flussi.  

> [!NOTE]  
>  Prima di poter specificare i codici di collocazione nella scheda Ubicazione, è necessario creare i codici di collocazione. Per ulteriori informazioni, vedere [Procedura: Creare collocazioni](warehouse-how-to-create-individual-bins.md).  

## <a name="to-set-up-a-location-to-use-bins"></a>Per impostare un'ubicazione per l'utilizzo di collocazioni  
1.  Scegliere l'icona ![Cerca pagina o report](media/ui-search/search_small.png "icona Cerca pagina o report"), immettere **Ubicazioni**, quindi scegliere il collegamento correlato.  
2.  Selezionare l'ubicazione in cui si desidera utilizzare le collocazioni.  
3.  Scegliere l'azione **Modifica**.  
4.  Nella Scheda Dettaglio **Warehouse** selezionare la casella di controllo **Collocazione obbligatoria**.  
5.  Se non si utilizzano stoccaggi e prelievi guidati per l'ubicazione, nel campo **Selezione Collocazioni di Default** specificare il metodo che il sistema deve utilizzare per assegnare una collocazione di default a un articolo.  
6.  Aprire la scheda per l'ubicazione per cui si desidera impostare le collocazioni.
7.  Nella Scheda dettaglio **Collocazioni**, selezionare le collocazioni da utilizzare come default per i carichi, le spedizioni e le collocazioni di produzione in entrata, in uscita e aperte.  
8.  I codici delle collocazioni immessi in questa scheda verranno visualizzati automaticamente nelle testate e nelle righe dei vari documenti di warehouse. Le collocazioni di default definiscono le posizioni iniziali e finali degli articoli nella warehouse.  
9.  Se si utilizzano stoccaggi e prelievi guidati, selezionare una collocazione per le rettifiche di warehouse. Il codice di collocazione nel campo **Codice collocazione rettifica** definisce la collocazione virtuale in cui registrare le eventuali discrepanze rilevate nelle giacenze quando si registrano le differenze riscontrate e registrate nelle registrazioni articoli warehouse o le differenze calcolate durante la registrazione di un inventario fisico della warehouse.  
10. Compilare i campi nella Scheda dettaglio **Criteri per collocazione** se appropriati per la warehouse. I campi più importanti sono **Criteri capacità collocazione**, **Permettere breakbulk** e **Codice modello stoccaggio**.  
11. Nella Scheda dettaglio **Warehouse** compilare i campi **Tempo gest. uscita da whse.**, **Tempo gest. entrata in whse.** e **Codice calendario base**. Per ulteriori informazioni, vedere [Procedura: Impostare i calendari di base](across-how-to-assign-base-calendars.md).

## <a name="filling-the-consumption-bin"></a>Rifornimento della collocazione di consumo
Questo diagramma di flusso illustra in che modo il campo **Cod. collocazione** nelle righe del componente dell'ordine di produzione viene compilato in base al setup dell'ubicazione.

![Diagramma di flusso collocazione](media/binflow.png "BinFlow")  

## <a name="see-also"></a>Vedi anche
[Gestione warehouse](warehouse-manage-warehouse.md)  
[Magazzino](inventory-manage-inventory.md)  
[Impostazione gestione warehouse](warehouse-setup-warehouse.md)     
[Gestione assemblaggio](assembly-assemble-items.md)    
[Dettagli di progettazione: Gestione warehouse](design-details-warehouse-management.md)  
[Utilizzo di [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

