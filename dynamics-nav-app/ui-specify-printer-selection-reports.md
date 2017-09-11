---
title: Specificare la selezione della stampante per i report
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 56a5c1428651162293e56d71e2369fe55d291594
ms.contentlocale: it-ch
ms.lasthandoff: 07/19/2017

---
    
# <a name="specify-printer-selection-for-reports"></a><span data-ttu-id="83870-102">Specificare la selezione della stampante per i report</span><span class="sxs-lookup"><span data-stu-id="83870-102">Specify Printer Selection for Reports</span></span>
<span data-ttu-id="83870-103">È possibile impostare i report in modo vengano stampati su una stampante specifica.</span><span class="sxs-lookup"><span data-stu-id="83870-103">You can set up reports so that they must be printed on a specific printer.</span></span> <span data-ttu-id="83870-104">Di seguito sono descritti alcuni utilizzi della selezione stampante:</span><span class="sxs-lookup"><span data-stu-id="83870-104">The following are some uses of printer selection:</span></span> 

- <span data-ttu-id="83870-105">È possibile stampare report sulla carta intestata speciale della società.</span><span class="sxs-lookup"><span data-stu-id="83870-105">You can print reports on special company letterhead.</span></span>
- <span data-ttu-id="83870-106">È possibile stampare i report su formati carta diversi.</span><span class="sxs-lookup"><span data-stu-id="83870-106">You can print reports on different paper sizes.</span></span>
- <span data-ttu-id="83870-107">È possibile stampare report sulla stampante di default di un impiegato specificato.</span><span class="sxs-lookup"><span data-stu-id="83870-107">You can print reports on the default printer of a specified employee.</span></span>

<span data-ttu-id="83870-108">Utilizzare la finestra **Selezioni stampante** per impostare valori differenti al fine di ottenere un output differente.</span><span class="sxs-lookup"><span data-stu-id="83870-108">You use the **Printer Selections** window to set different values to obtain different output.</span></span> <span data-ttu-id="83870-109">Se si imposta una selezione stampante specifica, questa ha la precedenza su una selezione stampante generale.</span><span class="sxs-lookup"><span data-stu-id="83870-109">If you set a specific printer selection, then it takes precedence over a more general printer selection.</span></span> <span data-ttu-id="83870-110">Ad esempio, è possibile impostare una selezione stampante che dispone di valori nei campi **ID utente**, **ID report** e **Nome stampante**.</span><span class="sxs-lookup"><span data-stu-id="83870-110">For example, you can set a printer selection that has values in the **User ID**, **Report ID**, and **Printer Name** fields.</span></span> <span data-ttu-id="83870-111">Questa selezione stampante ha la precedenza su una selezione stampante che ha movimenti vuoti nei campi **ID report** o **ID utente**.</span><span class="sxs-lookup"><span data-stu-id="83870-111">This printer selection takes precedence over a printer selection that has blank entries in the **User ID** or **Report ID** fields.</span></span> 

<span data-ttu-id="83870-112">Nella seguente tabella viene descritta la combinazione dei valori da specificare quando si impostano le selezioni stampante per un report.</span><span class="sxs-lookup"><span data-stu-id="83870-112">The following table describes the combination of values to specify when you set up printer selections for a report.</span></span>

|<span data-ttu-id="83870-113">Per</span><span class="sxs-lookup"><span data-stu-id="83870-113">To</span></span>                                                 |<span data-ttu-id="83870-114">Impostare i seguenti valori</span><span class="sxs-lookup"><span data-stu-id="83870-114">Set the following values</span></span>                                             |
|---------------------------------------------------|---------------------------------------------------------------------|
|<span data-ttu-id="83870-115">Stampare un report su una stampante specifica per tutti gli utenti</span><span class="sxs-lookup"><span data-stu-id="83870-115">Print a report to a specific printer for all users</span></span> |<span data-ttu-id="83870-116">Specificare i valori nei campi **Nome stampante** e **ID report** e lasciare vuoto il campo **ID utente**.</span><span class="sxs-lookup"><span data-stu-id="83870-116">Specify values in the **Report ID** and **Printer Name** fields and leave the **User ID** field blank.</span></span>|
|<span data-ttu-id="83870-117">Stampare tutti i report su una stampante specifica per un utente specifico</span><span class="sxs-lookup"><span data-stu-id="83870-117">Print all reports to a specific printer for a specific user</span></span>|<span data-ttu-id="83870-118">Specificare i valori nei campi **ID utente** e **Nome stampante** e lasciare vuoto il campo **ID utente**.</span><span class="sxs-lookup"><span data-stu-id="83870-118">Specify values in the **User ID** and **Printer Name** fields and leave the **Report ID** field blank.</span></span>|
|<span data-ttu-id="83870-119">Impostare la stampante di default per tutti i report</span><span class="sxs-lookup"><span data-stu-id="83870-119">Set the default printer for all reports</span></span>|<span data-ttu-id="83870-120">Specificare un valore nel campo **Nome stampante** e lasciare vuoti i campi **ID utente** e **ID report**.</span><span class="sxs-lookup"><span data-stu-id="83870-120">Specify a value in the **Printer Name** field and leave the **User ID** and **Report ID** fields blank.</span></span>|
|<span data-ttu-id="83870-121">Stampare un report specifico sulla stampante di default dell'utente</span><span class="sxs-lookup"><span data-stu-id="83870-121">Print a specific report to the user’s default printer</span></span>|<span data-ttu-id="83870-122">Specificare un valore nel campo **ID report** e lasciare vuoti i campi **Nome stampante** e **ID utente**.</span><span class="sxs-lookup"><span data-stu-id="83870-122">Specify a value in the **Report ID** field and leave the **Printer Name** and **User ID** fields blank.</span></span>|
|<span data-ttu-id="83870-123">Stampare un report specifico su una stampante specifica per un utente specifico</span><span class="sxs-lookup"><span data-stu-id="83870-123">Print a specific report to a specific printer for a specific user</span></span>|<span data-ttu-id="83870-124">Specificare i valori in tutti e tre i campi.</span><span class="sxs-lookup"><span data-stu-id="83870-124">Specify values in all three fields.</span></span>|

## <a name="see-also"></a><span data-ttu-id="83870-125">Vedi anche</span><span class="sxs-lookup"><span data-stu-id="83870-125">See Also</span></span>
[<span data-ttu-id="83870-126">Utilizzare Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="83870-126">Work with Dynamics NAV</span></span>](ui-work-product.md)

