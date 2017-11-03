---
title: Betalingsvoorstellen genereren
description: Als u elektronisch bankieren hebt ingesteld, kunt u beginnen met het genereren van betalingsvoorstellen. U kunt dit doen in het betalingsdagboek.
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
ms.openlocfilehash: 8eff5304474e2ed22ab7d9774d824b13b40cefef
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-generate-payment-suggestions"></a><span data-ttu-id="39be7-104">Procedure: Betalingsvoorstellen genereren</span><span class="sxs-lookup"><span data-stu-id="39be7-104">How to: Generate Payment Suggestions</span></span>
<span data-ttu-id="39be7-105">Als u elektronisch bankieren hebt ingesteld, kunt u beginnen met het genereren van betalingsvoorstellen.</span><span class="sxs-lookup"><span data-stu-id="39be7-105">After you have set up electronic banking, you can start generating payment suggestions.</span></span> <span data-ttu-id="39be7-106">U kunt dit doen in het betalingsdagboek.</span><span class="sxs-lookup"><span data-stu-id="39be7-106">You can do this in the payment journal.</span></span>  

## <a name="to-generate-payment-suggestions"></a><span data-ttu-id="39be7-107">Betalingsvoorstellen genereren</span><span class="sxs-lookup"><span data-stu-id="39be7-107">To generate payment suggestions</span></span>  

1.  <span data-ttu-id="39be7-108">Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **Betalingsdagboeken** in en klik vervolgens op de gerelateerde koppeling.</span><span class="sxs-lookup"><span data-stu-id="39be7-108">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="39be7-109">Selecteer de juiste dagboekbatch en kies vervolgens de actie **Leveranciersbetalingen voorstellen**.</span><span class="sxs-lookup"><span data-stu-id="39be7-109">Select the appropriate journal batch, and then choose the **Suggest Vendor Payments** action.</span></span>  
3.  <span data-ttu-id="39be7-110">Vul in het venter **Leveranciersbetalingen voorstellen** op het tabblad **Opties** de velden in zoals wordt beschreven in de volgende tabel.</span><span class="sxs-lookup"><span data-stu-id="39be7-110">In the **Suggest Vendor Payments EB**  window, on the **Options** FastTab, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="39be7-111">Veld</span><span class="sxs-lookup"><span data-stu-id="39be7-111">Field</span></span>|<span data-ttu-id="39be7-112">Description</span><span class="sxs-lookup"><span data-stu-id="39be7-112">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="39be7-113">**Uiterste vervaldatum**</span><span class="sxs-lookup"><span data-stu-id="39be7-113">**Last Due Date**</span></span>|<span data-ttu-id="39be7-114">Typ de uiterste vervaldatum voor de leveranciersposten in de batchverwerking.</span><span class="sxs-lookup"><span data-stu-id="39be7-114">Enter the last due date that can appear on the vendor ledger entries to be included in the batch job.</span></span>|  
    |<span data-ttu-id="39be7-115">**Creditnota's maken**</span><span class="sxs-lookup"><span data-stu-id="39be7-115">**Take Credit Memos**</span></span>|<span data-ttu-id="39be7-116">Selecteer deze optie om openstaande creditnota's voor leveranciers op te nemen.</span><span class="sxs-lookup"><span data-stu-id="39be7-116">Select to include outstanding credit memos for vendors.</span></span> <span data-ttu-id="39be7-117">De creditnota's worden van het verschuldigde bedrag afgetrokken.</span><span class="sxs-lookup"><span data-stu-id="39be7-117">The credit memos will be subtracted from the amount due.</span></span> <span data-ttu-id="39be7-118">Wanneer u creditnota's selecteert, wordt de vervaldatum niet gebruikt.</span><span class="sxs-lookup"><span data-stu-id="39be7-118">When selecting credit memos, the due date is not used.</span></span>|  
    |<span data-ttu-id="39be7-119">**Contantkorting nemen**</span><span class="sxs-lookup"><span data-stu-id="39be7-119">**Take Payment Discounts**</span></span>|<span data-ttu-id="39be7-120">Selecteer deze optie om op te geven of u in de batchverwerking posten wilt opnemen waarvoor u een contantkorting kunt krijgen.</span><span class="sxs-lookup"><span data-stu-id="39be7-120">Select to include vendor ledger entries for which you can receive a payment discount.</span></span>|  
    |<span data-ttu-id="39be7-121">**Kortingsvervaldatum betaling**</span><span class="sxs-lookup"><span data-stu-id="39be7-121">**Payment Discount Date**</span></span>|<span data-ttu-id="39be7-122">Typ de datum die wordt gebruikt om een contantkorting te berekenen.</span><span class="sxs-lookup"><span data-stu-id="39be7-122">Enter the date that will be used to calculate a payment discount.</span></span>|  
    |<span data-ttu-id="39be7-123">**Beschikbaar bedrag**</span><span class="sxs-lookup"><span data-stu-id="39be7-123">**Available Amount**</span></span>|<span data-ttu-id="39be7-124">Typ hier eventueel een maximumbedrag dat beschikbaar is voor betalingen.</span><span class="sxs-lookup"><span data-stu-id="39be7-124">If there is a maximum amount available for payments, you can enter it here.</span></span> <span data-ttu-id="39be7-125">Tijdens de batchverwerking wordt dan een betalingsvoorstel op basis van dit bedrag en de prioriteit van leveranciers gedaan.</span><span class="sxs-lookup"><span data-stu-id="39be7-125">The batch job will then create a payment suggestion based on this amount and the priority of vendors.</span></span>|  
    |<span data-ttu-id="39be7-126">**Boekingsdatum**</span><span class="sxs-lookup"><span data-stu-id="39be7-126">**Posting Date**</span></span>|<span data-ttu-id="39be7-127">typ hier de datum die als boekingsdatum verschijnt op de regels die tijdens de batchverwerking in het betalingsdagboek worden ingevoegd.</span><span class="sxs-lookup"><span data-stu-id="39be7-127">Enter the date that will appear as the posting date on the lines that the batch job inserts in the payment journal.</span></span>|  

4.  <span data-ttu-id="39be7-128">Voer de filtercriteria op het sneltabblad **Leverancier** in.</span><span class="sxs-lookup"><span data-stu-id="39be7-128">On the **Vendor** FastTab, enter the filter criteria.</span></span>  
5.  <span data-ttu-id="39be7-129">Kies **OK** om de batchverwerking te starten.</span><span class="sxs-lookup"><span data-stu-id="39be7-129">Choose the **OK** button to start the batch job.</span></span>  

<span data-ttu-id="39be7-130">Wanneer de batchverwerking is uitgevoerd, bevat het betalingsdagboek alle leveranciersposten die overeenkomen met de filters.</span><span class="sxs-lookup"><span data-stu-id="39be7-130">When the batch job is finished, the payment journal contains all vendor ledger entries that match the filters.</span></span>  

## <a name="see-also"></a><span data-ttu-id="39be7-131">Zie ook</span><span class="sxs-lookup"><span data-stu-id="39be7-131">See Also</span></span>  
 <span data-ttu-id="39be7-132">[Belgische elektronische betalingen](belgian-electronic-payments.md) </span><span class="sxs-lookup"><span data-stu-id="39be7-132">[Belgian Electronic Payments](belgian-electronic-payments.md) </span></span>  
 <span data-ttu-id="39be7-133">[Procedure: Leveranciers voor automatische betalingsvoorstellen instellen](how-to-set-up-vendors-for-automatic-payment-suggestions.md) </span><span class="sxs-lookup"><span data-stu-id="39be7-133">[How to: Set Up Vendors for Automatic Payment Suggestions](how-to-set-up-vendors-for-automatic-payment-suggestions.md) </span></span>  
 <span data-ttu-id="39be7-134">[Procedure: Betalingsdagboeksjablonen en -batches maken](how-to-create-payment-journal-templates-and-batches.md) </span><span class="sxs-lookup"><span data-stu-id="39be7-134">[How to: Create Payment Journal Templates and Batches](how-to-create-payment-journal-templates-and-batches.md) </span></span>  
 <span data-ttu-id="39be7-135">[Procedure: Elektronische betalingen testen](how-to-test-electronic-payments.md) </span><span class="sxs-lookup"><span data-stu-id="39be7-135">[How to: Test Electronic Payments](how-to-test-electronic-payments.md) </span></span>  
 <span data-ttu-id="39be7-136">[Procedure: Regels voor elektronische betalingen beheren](how-to-manage-electronic-payment-lines.md) </span><span class="sxs-lookup"><span data-stu-id="39be7-136">[How to: Manage Electronic Payment Lines](how-to-manage-electronic-payment-lines.md) </span></span>  
 [<span data-ttu-id="39be7-137">Procedure: Betalingsbestanden afdrukken</span><span class="sxs-lookup"><span data-stu-id="39be7-137">How to: Print Payment Files</span></span>](how-to-print-payment-files.md)

