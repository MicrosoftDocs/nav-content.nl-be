---
title: CODA-afschriften vereffenen
description: "Nadat een CODA-afschrift is geïmporteerd, kunnen de afschriftregels worden geopend vanuit het venster **Bankrekeningkaart**. De vereffeningsstatus is op elke regel leeg omdat de afschriftbedragen niet zijn vereffend met openstaande posten."
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
ms.openlocfilehash: 9c22f28cf9693bc0fec118d4783d496ac38f8187
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-apply-coda-statements"></a><span data-ttu-id="d0d57-104">Procedure: CODA-afschriften vereffenen</span><span class="sxs-lookup"><span data-stu-id="d0d57-104">How to: Apply CODA Statements</span></span>
<span data-ttu-id="d0d57-105">Nadat een CODA-afschrift is geïmporteerd, kunnen de afschriftregels worden geopend vanuit het venster **Bankrekeningkaart**.</span><span class="sxs-lookup"><span data-stu-id="d0d57-105">After a CODA statement has been imported, the statement lines can be accessed from the **Bank Account Card** window.</span></span> <span data-ttu-id="d0d57-106">De vereffeningsstatus is op elke regel leeg omdat de afschriftbedragen niet zijn vereffend met openstaande posten.</span><span class="sxs-lookup"><span data-stu-id="d0d57-106">The application status on each line will be blank because the statement amounts have not been applied to outstanding ledger entries.</span></span>  

<span data-ttu-id="d0d57-107">Afschriftbedragen kunnen als volgt worden vereffend met openstaande posten:</span><span class="sxs-lookup"><span data-stu-id="d0d57-107">Statement amounts can be applied to outstanding ledger entries by:</span></span>  

-   <span data-ttu-id="d0d57-108">Door CODA-afschriftregels handmatig te vereffenen.</span><span class="sxs-lookup"><span data-stu-id="d0d57-108">Manually applying CODA statement lines.</span></span>  
-   <span data-ttu-id="d0d57-109">Door CODA-afschriftbedragen automatisch te vereffenen met de betreffende posten en rekeningen.</span><span class="sxs-lookup"><span data-stu-id="d0d57-109">Automatically applying CODA statement amounts to the appropriate ledger entries and accounts.</span></span> <span data-ttu-id="d0d57-110">De automatische verwerking van CODA-afschriftregels wordt aanbevolen.</span><span class="sxs-lookup"><span data-stu-id="d0d57-110">Automatic processing of CODA statement lines is recommended.</span></span>  

## <a name="to-manually-apply-the-coda-statement-lines"></a><span data-ttu-id="d0d57-111">De CODA-afschriftregels handmatig vereffenen</span><span class="sxs-lookup"><span data-stu-id="d0d57-111">To manually apply the CODA statement lines</span></span>  

1.  <span data-ttu-id="d0d57-112">Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **Bankrekeningen** in en klik vervolgens op de gerelateerde koppeling.</span><span class="sxs-lookup"><span data-stu-id="d0d57-112">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Accounts**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="d0d57-113">Selecteer de bankrekening en kies de actie **CODA-afschriften**.</span><span class="sxs-lookup"><span data-stu-id="d0d57-113">Select the bank account, and then choose the **CODA Statements** action.</span></span>  
3.  <span data-ttu-id="d0d57-114">Selecteer het CODA-afschrift en kies vervolgens de actie **Bewerken**.</span><span class="sxs-lookup"><span data-stu-id="d0d57-114">Select the CODA statement, and then choose the **Edit** action.</span></span>  
4.  <span data-ttu-id="d0d57-115">Vul op het sneltabblad **CODA-afschriftregels** voor elke afschriftregel de velden in zoals wordt beschreven in de volgende tabel.</span><span class="sxs-lookup"><span data-stu-id="d0d57-115">In the **CODA Statement Lines** FastTab, for each statement line, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="d0d57-116">Veld</span><span class="sxs-lookup"><span data-stu-id="d0d57-116">Field</span></span>|<span data-ttu-id="d0d57-117">Description</span><span class="sxs-lookup"><span data-stu-id="d0d57-117">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="d0d57-118">**Rekeningnr.**</span><span class="sxs-lookup"><span data-stu-id="d0d57-118">**Account No.**</span></span>|<span data-ttu-id="d0d57-119">Voer het nummer van de grootboekrekening, de bank, de klant, de leverancier of een vast activum in waaraan de afschriftregel van de bankrekening is gekoppeld.</span><span class="sxs-lookup"><span data-stu-id="d0d57-119">Enter the number of the general ledger account, bank, customer, vendor, or fixed asset, which the bank account statement line is linked to.</span></span>|  
    |<span data-ttu-id="d0d57-120">**Beschrijving**</span><span class="sxs-lookup"><span data-stu-id="d0d57-120">**Description**</span></span>|<span data-ttu-id="d0d57-121">In [!INCLUDE[navnow](../../includes/navnow_md.md)] wordt automatisch de omschrijving van het geïmporteerde CODA-bestand opgehaald, maar u kunt de inhoud van dit veld wijzigen.</span><span class="sxs-lookup"><span data-stu-id="d0d57-121">[!INCLUDE[navnow](../../includes/navnow_md.md)] automatically retrieves the description from the imported CODA file, but you can modify the contents of this field.</span></span>|  

5.  <span data-ttu-id="d0d57-122">Kies de knop **OK**.</span><span class="sxs-lookup"><span data-stu-id="d0d57-122">Choose the **OK** button.</span></span>  

## <a name="to-automatically-apply-the-coda-statement-lines"></a><span data-ttu-id="d0d57-123">De CODA-afschriftregels automatisch vereffenen</span><span class="sxs-lookup"><span data-stu-id="d0d57-123">To automatically apply the CODA statement lines</span></span>  

1.  <span data-ttu-id="d0d57-124">Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **Bankrekeningen** in en klik vervolgens op de gerelateerde koppeling.</span><span class="sxs-lookup"><span data-stu-id="d0d57-124">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Bank Accounts**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="d0d57-125">Selecteer de bankrekening en kies de actie **CODA-afschriften**.</span><span class="sxs-lookup"><span data-stu-id="d0d57-125">Select the bank account, and then choose the **CODA Statements** action.</span></span>  
3.  <span data-ttu-id="d0d57-126">Selecteer het CODA-afschrift en kies vervolgens de actie **Bewerken**.</span><span class="sxs-lookup"><span data-stu-id="d0d57-126">Select the CODA statement, and then choose the **Edit** action.</span></span>  
4.  <span data-ttu-id="d0d57-127">Kies de actie **CODA-afschriftregels**.</span><span class="sxs-lookup"><span data-stu-id="d0d57-127">Choose the **Process CODA Statement Lines** action.</span></span>  
5.  <span data-ttu-id="d0d57-128">Vul de velden in zoals beschreven in de volgende tabel.</span><span class="sxs-lookup"><span data-stu-id="d0d57-128">Fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="d0d57-129">Veld</span><span class="sxs-lookup"><span data-stu-id="d0d57-129">Field</span></span>|<span data-ttu-id="d0d57-130">Description</span><span class="sxs-lookup"><span data-stu-id="d0d57-130">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="d0d57-131">**Standaardboeking**</span><span class="sxs-lookup"><span data-stu-id="d0d57-131">**Default Posting**</span></span>|<span data-ttu-id="d0d57-132">Selecteer deze optie als u wilt dat met de batchverwerking afschriftbedragen worden geboekt die niet aan bestaande posten kunnen worden gekoppeld.</span><span class="sxs-lookup"><span data-stu-id="d0d57-132">Select if you want the batch job to post statement amounts that cannot be linked to existing ledger entries.</span></span> <span data-ttu-id="d0d57-133">Zie Transactiecodering voor meer informatie.</span><span class="sxs-lookup"><span data-stu-id="d0d57-133">For more information, see Transaction Coding.</span></span>|  
    |<span data-ttu-id="d0d57-134">**Lijst afdrukken**</span><span class="sxs-lookup"><span data-stu-id="d0d57-134">**Print List**</span></span>|<span data-ttu-id="d0d57-135">Selecteer deze optie om een overzicht van afschriftbedragen af te drukken die niet automatisch kunnen worden gekoppeld.</span><span class="sxs-lookup"><span data-stu-id="d0d57-135">Select to print a list of statement amounts that cannot be linked automatically.</span></span>|  

6.  <span data-ttu-id="d0d57-136">Kies de knop **OK**.</span><span class="sxs-lookup"><span data-stu-id="d0d57-136">Choose the **OK** button.</span></span>  

    <span data-ttu-id="d0d57-137">Wanneer u de batchverwerking start, worden de afschriftbedragen vereffend met bestaande posten op basis van de transactiecodes.</span><span class="sxs-lookup"><span data-stu-id="d0d57-137">When you start the batch job, statement amounts will be applied to existing ledger entries based on the transaction codes.</span></span> <span data-ttu-id="d0d57-138">Zie voor meer informatie [Procedure: Bankrekeningen voor CODA instellen](how-to-set-up-bank-accounts-for-coda.md).</span><span class="sxs-lookup"><span data-stu-id="d0d57-138">For more information, see [How to: Set Up Bank Accounts for CODA](how-to-set-up-bank-accounts-for-coda.md).</span></span>  

## <a name="see-also"></a><span data-ttu-id="d0d57-139">Zie ook</span><span class="sxs-lookup"><span data-stu-id="d0d57-139">See Also</span></span>  
 <span data-ttu-id="d0d57-140">[CODA-bankafschriften](coda-bank-statements.md) </span><span class="sxs-lookup"><span data-stu-id="d0d57-140">[CODA Bank Statements](coda-bank-statements.md) </span></span>  
 <span data-ttu-id="d0d57-141">[Procedure: Bankrekeningen instellen voor CODA](how-to-set-up-bank-accounts-for-coda.md) </span><span class="sxs-lookup"><span data-stu-id="d0d57-141">[How to: Set Up Bank Accounts for CODA](how-to-set-up-bank-accounts-for-coda.md) </span></span>  
 <span data-ttu-id="d0d57-142">[Procedure: IBLC-BLWI-transactiecodes instellen](how-to-set-up-iblc-blwi-transaction-codes.md) </span><span class="sxs-lookup"><span data-stu-id="d0d57-142">[How to: Set Up IBLC-BLWI Transaction Codes](how-to-set-up-iblc-blwi-transaction-codes.md) </span></span>  
 <span data-ttu-id="d0d57-143">[Procedure: CODA-afschriften importeren](how-to-import-coda-statements.md) </span><span class="sxs-lookup"><span data-stu-id="d0d57-143">[How to: Import CODA Statements](how-to-import-coda-statements.md) </span></span>  
 <span data-ttu-id="d0d57-144">[Procedure: Financiële dagboeken maken](how-to-create-financial-journals.md) </span><span class="sxs-lookup"><span data-stu-id="d0d57-144">[How to: Create Financial Journals](how-to-create-financial-journals.md) </span></span>  
 <span data-ttu-id="d0d57-145">[Procedure: CODA-afschriften automatisch overbrengen en boeken](how-to-automatically-transfer-and-post-coda-statements.md) </span><span class="sxs-lookup"><span data-stu-id="d0d57-145">[How to: Automatically Transfer and Post CODA Statements](how-to-automatically-transfer-and-post-coda-statements.md) </span></span>  
 [<span data-ttu-id="d0d57-146">Procedure: CODA-afschriften handmatig overbrengen en boeken</span><span class="sxs-lookup"><span data-stu-id="d0d57-146">How to: Manually Transfer and Post CODA Statements</span></span>](how-to-manually-transfer-and-post-coda-statements.md)

