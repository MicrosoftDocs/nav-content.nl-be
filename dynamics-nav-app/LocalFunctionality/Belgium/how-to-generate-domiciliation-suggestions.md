---
title: "Domiciliëringsvoorstellen genereren"
description: "Als u domiciliëringen hebt ingesteld, kunt u beginnen met het genereren van domiciliëringsvoorstellen. In [!INCLUDE[navnow](../../includes/navnow_md.md)] kunt u alleen domiciliëringsvoorstellen voor binnenlandse klanten maken."
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 20006ba794abeffeaecc7d36d1113469a464c3ab
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-generate-domiciliation-suggestions"></a><span data-ttu-id="ed5ab-104">Procedure: Domiciliëringsvoorstellen genereren</span><span class="sxs-lookup"><span data-stu-id="ed5ab-104">How to: Generate Domiciliation Suggestions</span></span>
<span data-ttu-id="ed5ab-105">Als u domiciliëringen hebt ingesteld, kunt u beginnen met het genereren van domiciliëringsvoorstellen.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-105">After you have set up domiciliations, you can start generating domiciliation suggestions.</span></span> <span data-ttu-id="ed5ab-106">In [!INCLUDE[navnow](../../includes/navnow_md.md)] kunt u alleen domiciliëringsvoorstellen voor binnenlandse klanten maken.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-106">In [!INCLUDE[navnow](../../includes/navnow_md.md)], you can only create domiciliation suggestions for domestic customers.</span></span>  

## <a name="to-generate-domiciliation-suggestions"></a><span data-ttu-id="ed5ab-107">Domiciliëringsvoorstellen genereren</span><span class="sxs-lookup"><span data-stu-id="ed5ab-107">To generate domiciliation suggestions</span></span>  

1.  <span data-ttu-id="ed5ab-108">Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **Domiciliëringsdagboek** in en klik vervolgens op de gerelateerde koppeling.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-108">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Domiciliation Journal**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="ed5ab-109">Selecteer in het veld **Batchnaam** de vereiste dagboekbatch en kies vervolgens de actie **Domiciliëringen voorstellen**.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-109">In the **Batch Name** field, select the required journal batch, and then choose the **Suggest Domiciliations** action.</span></span>  
3.  <span data-ttu-id="ed5ab-110">Vul op het sneltabblad **Opties** de velden in zoals in de volgende tabel wordt weergegeven.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-110">On the **Options** FastTab, fill in the fields as displayed in the following table.</span></span>  

    |<span data-ttu-id="ed5ab-111">Veld</span><span class="sxs-lookup"><span data-stu-id="ed5ab-111">Field</span></span>|<span data-ttu-id="ed5ab-112">Description</span><span class="sxs-lookup"><span data-stu-id="ed5ab-112">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="ed5ab-113">**Vervaldatum**</span><span class="sxs-lookup"><span data-stu-id="ed5ab-113">**Due Date**</span></span>|<span data-ttu-id="ed5ab-114">Geef hier de vervaldatum voor de batchverwerking op.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-114">Enter the due date to be included in the batch job.</span></span> <span data-ttu-id="ed5ab-115">Alleen posten met een vervaldatum vóór of op deze datum worden opgenomen.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-115">Only entries that have a due date before or on this date will be included.</span></span>|  
    |<span data-ttu-id="ed5ab-116">**Contantkorting nemen**</span><span class="sxs-lookup"><span data-stu-id="ed5ab-116">**Take Payment Discounts**</span></span>|<span data-ttu-id="ed5ab-117">Selecteer deze optie als u in de batchverwerking klantposten wilt opnemen waarvoor u een contantkorting kunt krijgen.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-117">Select if you want the batch job to include customer ledger entries for which you can receive a payment discount.</span></span>|  
    |<span data-ttu-id="ed5ab-118">**Kortingsvervaldatum betaling**</span><span class="sxs-lookup"><span data-stu-id="ed5ab-118">**Payment Discount Date**</span></span>|<span data-ttu-id="ed5ab-119">Typ de datum die wordt gebruikt om de contantkorting te berekenen.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-119">Enter the date that will be used to calculate the payment discount.</span></span>|  
    |<span data-ttu-id="ed5ab-120">**Mogelijke terugbetalingen selecteren**</span><span class="sxs-lookup"><span data-stu-id="ed5ab-120">**Select Possible Refunds**</span></span>|<span data-ttu-id="ed5ab-121">Selecteer deze optie als in de batchverwerking terugbetalingen moeten worden opgenomen.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-121">Select if you want the batch job to include refunds.</span></span>|  
    |<span data-ttu-id="ed5ab-122">**Boekingsdatum**</span><span class="sxs-lookup"><span data-stu-id="ed5ab-122">**Posting Date**</span></span>|<span data-ttu-id="ed5ab-123">Typ de datum die als boekingsdatum verschijnt op de regels die tijdens de batchverwerking in het domiciliëringsdagboek worden ingevoegd.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-123">Enter the date that will appear as the posting date on the lines that the batch job inserts in the domiciliation journal.</span></span>|  

4.  <span data-ttu-id="ed5ab-124">Voer desgewenst extra filtercriteria in op het sneltabblad **Klant**.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-124">On the **Customer** FastTab, enter any additional filter criteria.</span></span>  
5.  <span data-ttu-id="ed5ab-125">Kies de knop **OK**.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-125">Choose the **OK** button.</span></span>  

<span data-ttu-id="ed5ab-126">Wanneer de batchverwerking is uitgevoerd, bevat het domiciliëringsdagboek alle openstaande klantenposten die overeenkomen met de filters.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-126">When the batch job is finished, the domiciliation journal contains all open customer ledger entries that match the filters.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="ed5ab-127">De domiciliëringsvoorstellen bevatten alleen klanten waarvoor een domiciliëringsnummer is ingesteld.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-127">The domiciliation suggestions will only include customers who have a Domiciliation number set up.</span></span> <span data-ttu-id="ed5ab-128">Zie [Procedure: Domiciliëringen instellen](how-to-set-up-domiciliations.md) voor meer informatie.</span><span class="sxs-lookup"><span data-stu-id="ed5ab-128">For more information, see [How to: Set Up Domiciliations](how-to-set-up-domiciliations.md).</span></span>  

## <a name="see-also"></a><span data-ttu-id="ed5ab-129">Zie ook</span><span class="sxs-lookup"><span data-stu-id="ed5ab-129">See Also</span></span>  
 <span data-ttu-id="ed5ab-130">[Elektronisch bankieren voor België](belgian-electronic-banking.md) </span><span class="sxs-lookup"><span data-stu-id="ed5ab-130">[Belgian Electronic Banking](belgian-electronic-banking.md) </span></span>  
 <span data-ttu-id="ed5ab-131">[Incasso via domiciliëring](direct-debit-using-domiciliation.md) </span><span class="sxs-lookup"><span data-stu-id="ed5ab-131">[Direct Debit Using Domiciliation](direct-debit-using-domiciliation.md) </span></span>  
 <span data-ttu-id="ed5ab-132">[Procedure: Domiciliëringen instellen](how-to-set-up-domiciliations.md) </span><span class="sxs-lookup"><span data-stu-id="ed5ab-132">[How to: Set Up Domiciliations](how-to-set-up-domiciliations.md) </span></span>  
 <span data-ttu-id="ed5ab-133">[Procedure: Domiciliëringen testen](how-to-test-domiciliations.md) </span><span class="sxs-lookup"><span data-stu-id="ed5ab-133">[How to: Test Domiciliations](how-to-test-domiciliations.md) </span></span>  
 <span data-ttu-id="ed5ab-134">[Procedure: Domiciliëringsregels bewerken en verwijderen](how-to-edit-and-delete-domiciliation-lines.md) </span><span class="sxs-lookup"><span data-stu-id="ed5ab-134">[How to: Edit and Delete Domiciliation Lines](how-to-edit-and-delete-domiciliation-lines.md) </span></span>  
 [<span data-ttu-id="ed5ab-135">Procedure: Domiciliëringen exporteren en boeken</span><span class="sxs-lookup"><span data-stu-id="ed5ab-135">How to: Export and Post Domiciliations</span></span>](how-to-export-and-post-domiciliations.md)

