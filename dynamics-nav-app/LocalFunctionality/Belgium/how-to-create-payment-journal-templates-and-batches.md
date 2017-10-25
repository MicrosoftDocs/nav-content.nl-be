---
title: Betalingsdagboeksjablonen en -batches maken
description: In [!INCLUDE[navnow](../../includes/navnow_md.md)] worden betalingsvoorstellen gegenereerd en geboekt in betalingsdagboeken. De structuur van het betalingsdagboek lijkt op die van andere dagboeksoorten. Het betalingsdagboek bevat echter enkele velden die specifiek betrekking hebben op het verwerken van betalingen. Voordat u betalingsvoorstellen kunt genereren, moet u een betalingsdagboeksjabloon en een betalingsdagboekbatch instellen.
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 67b116fd8b5fa5b63e8855922c793ca7d94b870f
ms.contentlocale: nl-be
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-payment-journal-templates-and-batches"></a><span data-ttu-id="59eca-106">Procedure: Betalingsdagboeksjablonen en -batches maken</span><span class="sxs-lookup"><span data-stu-id="59eca-106">How to: Create Payment Journal Templates and Batches</span></span>
<span data-ttu-id="59eca-107">In [!INCLUDE[navnow](../../includes/navnow_md.md)] worden betalingsvoorstellen gegenereerd en geboekt in betalingsdagboeken.</span><span class="sxs-lookup"><span data-stu-id="59eca-107">In [!INCLUDE[navnow](../../includes/navnow_md.md)], payment suggestions are generated and posted in payment journals.</span></span> <span data-ttu-id="59eca-108">De structuur van het betalingsdagboek lijkt op die van andere dagboeksoorten.</span><span class="sxs-lookup"><span data-stu-id="59eca-108">The structure of the payment journal is similar to the structure of other journal types.</span></span> <span data-ttu-id="59eca-109">Het betalingsdagboek bevat echter enkele velden die specifiek betrekking hebben op het verwerken van betalingen.</span><span class="sxs-lookup"><span data-stu-id="59eca-109">However, the payment journal contains some fields that are specific for processing payments.</span></span> <span data-ttu-id="59eca-110">Voordat u betalingsvoorstellen kunt genereren, moet u een betalingsdagboeksjabloon en een betalingsdagboekbatch instellen.</span><span class="sxs-lookup"><span data-stu-id="59eca-110">Before you can start generating payment suggestions, you have to set up a payment journal template and a payment journal batch.</span></span>  
  
 <span data-ttu-id="59eca-111">Als u een bankrekening toewijst aan de betalingsdagboeksjabloon, wordt de bankrekening ingevoegd in alle betalingsdagboekbatches en betalingsdagboekregels die met deze sjabloon worden gemaakt.</span><span class="sxs-lookup"><span data-stu-id="59eca-111">If you assign a bank account to the payment journal template, the bank account will be inserted on all payment journal batches and payment journal lines that are created by using this template.</span></span> <span data-ttu-id="59eca-112">Door een bankrekening voor de dagboeksjabloon op te geven, kunt u de benodigde tijd voor het controleren van de betalingsvoorstellen beperken.</span><span class="sxs-lookup"><span data-stu-id="59eca-112">By specifying a bank account for the journal template, you can reduce the time that is required for checking the payment suggestions.</span></span>  
  
### <a name="to-create-a-payment-journal-template"></a><span data-ttu-id="59eca-113">Een betalingsdagboeksjabloon maken</span><span class="sxs-lookup"><span data-stu-id="59eca-113">To create a payment journal template</span></span>  
  
1.  <span data-ttu-id="59eca-114">Klik op het pictogram ![Zoeken naar pagina of rapport](media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **Betalingsdagboeksjablonen** in en klik vervolgens op de gerelateerde koppeling.</span><span class="sxs-lookup"><span data-stu-id="59eca-114">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journal Templates**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="59eca-115">Kies op het tabblad **Start** in de groep **Nieuw** de optie **Nieuw**.</span><span class="sxs-lookup"><span data-stu-id="59eca-115">On the **Home** tab, in the **New** group, choose **New**.</span></span>  
  
3.  <span data-ttu-id="59eca-116">Vul in het venster **Betalingsdagboeksjablonen** de velden in zoals wordt beschreven in de volgende tabel.</span><span class="sxs-lookup"><span data-stu-id="59eca-116">In the **EB Payment Journal Templates** window, fill in the fields as described in the following table.</span></span>  
  
    |<span data-ttu-id="59eca-117">Veld</span><span class="sxs-lookup"><span data-stu-id="59eca-117">Field</span></span>|<span data-ttu-id="59eca-118">Description</span><span class="sxs-lookup"><span data-stu-id="59eca-118">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="59eca-119">**Naam**</span><span class="sxs-lookup"><span data-stu-id="59eca-119">**Name**</span></span>|<span data-ttu-id="59eca-120">Voer de unieke naam in van de betalingsdagboeksjabloon die u maakt.</span><span class="sxs-lookup"><span data-stu-id="59eca-120">Enter the unique name for the payment journal template that you are creating.</span></span>|  
    |<span data-ttu-id="59eca-121">**Beschrijving**</span><span class="sxs-lookup"><span data-stu-id="59eca-121">**Description**</span></span>|<span data-ttu-id="59eca-122">Voer een omschrijving voor de betalingsdagboeksjabloon in.</span><span class="sxs-lookup"><span data-stu-id="59eca-122">Enter a description of the payment journal template.</span></span>|  
    |<span data-ttu-id="59eca-123">**Bankrekening**</span><span class="sxs-lookup"><span data-stu-id="59eca-123">**Bank Account**</span></span>|<span data-ttu-id="59eca-124">Selecteer de bankrekening die wordt gebruikt als u een betalingsvoorstel maakt.</span><span class="sxs-lookup"><span data-stu-id="59eca-124">Select the bank account that will be used when you create a payment suggestion.</span></span>|  
    |<span data-ttu-id="59eca-125">**Redencode**</span><span class="sxs-lookup"><span data-stu-id="59eca-125">**Reason Code**</span></span>|<span data-ttu-id="59eca-126">Selecteer de redencode die wordt gebruikt voor alle dagboekbatches en regels die worden gemaakt met de dagboeksjabloon.</span><span class="sxs-lookup"><span data-stu-id="59eca-126">Select the reason code that will be used on all the journal batches and lines that are created by using the journal template.</span></span> <span data-ttu-id="59eca-127">Als u een andere redencode op een dagboekregel wilt gebruiken, kunt u deze handmatig wijzigen.</span><span class="sxs-lookup"><span data-stu-id="59eca-127">If you want to use a different reason code on a journal line, you can manually change it.</span></span>|  
    |<span data-ttu-id="59eca-128">**Broncode**</span><span class="sxs-lookup"><span data-stu-id="59eca-128">**Source Code**</span></span>|<span data-ttu-id="59eca-129">Selecteer de broncode die wordt gebruikt voor alle dagboekbatches en regels die worden gemaakt met de dagboeksjabloon.</span><span class="sxs-lookup"><span data-stu-id="59eca-129">Select the source code that will be used on all the journal batches and lines that are created by using the journal template.</span></span>|  
  
4.  <span data-ttu-id="59eca-130">Kies de knop **OK**.</span><span class="sxs-lookup"><span data-stu-id="59eca-130">Choose the **OK** button.</span></span>  
  
### <a name="to-add-payment-journal-batches-to-the-journal-template"></a><span data-ttu-id="59eca-131">Betalingsdagboekbatches toevoegen aan de dagboeksjabloon</span><span class="sxs-lookup"><span data-stu-id="59eca-131">To add payment journal batches to the journal template</span></span>  
  
1.  <span data-ttu-id="59eca-132">Kies in het venster **Betalingsdagboeksjablonen** op het tabblad **Navigeren** in de groep **Sjabloon** de optie **Batches**.</span><span class="sxs-lookup"><span data-stu-id="59eca-132">In the **Payment Journal Templates** window, on the **Navigate** tab, in the **Template** group, choose **Batches**.</span></span>  
  
2.  <span data-ttu-id="59eca-133">Vul in het venster **Betalingsdagboekbatch** de velden in zoals wordt beschreven in de volgende tabel.</span><span class="sxs-lookup"><span data-stu-id="59eca-133">In the **Paym. Journal Batch** window, fill in the fields as described in the following table.</span></span>  
  
    |<span data-ttu-id="59eca-134">Veld</span><span class="sxs-lookup"><span data-stu-id="59eca-134">Field</span></span>|<span data-ttu-id="59eca-135">Description</span><span class="sxs-lookup"><span data-stu-id="59eca-135">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="59eca-136">**Dagboeksjabloon**</span><span class="sxs-lookup"><span data-stu-id="59eca-136">**Journal Template Name**</span></span>|<span data-ttu-id="59eca-137">Geef een dagboeksjabloonnaam op voor de betalingsdagboekbatch.</span><span class="sxs-lookup"><span data-stu-id="59eca-137">Specify a journal template name for the payment journal batch.</span></span>|  
    |<span data-ttu-id="59eca-138">**Naam**</span><span class="sxs-lookup"><span data-stu-id="59eca-138">**Name**</span></span>|<span data-ttu-id="59eca-139">Voer een unieke naam voor de dagboekbatch in.</span><span class="sxs-lookup"><span data-stu-id="59eca-139">Enter a unique name for the journal batch.</span></span><br /><br /> <span data-ttu-id="59eca-140">**OPMERKING:** als de dagboeknaam numeriek moet wordt bijgewerkt, neemt u een nummer op in de dagboekbatchnaam.</span><span class="sxs-lookup"><span data-stu-id="59eca-140">**NOTE:** To have the journal name update numerically, include a number in the journal batch name.</span></span> <span data-ttu-id="59eca-141">Zo wordt de waarde in de batchnaam KBC1 bij elke nieuwe boeking verhoogd (KBC2, KBC3, enzovoort).</span><span class="sxs-lookup"><span data-stu-id="59eca-141">For example, the name KBC1 will increment by one number with every posting to KBC2, KBC3, and so on.</span></span>|  
    |<span data-ttu-id="59eca-142">**Beschrijving**</span><span class="sxs-lookup"><span data-stu-id="59eca-142">**Description**</span></span>|<span data-ttu-id="59eca-143">Voer een omschrijving voor de dagboekbatch in.</span><span class="sxs-lookup"><span data-stu-id="59eca-143">Enter a description for the journal batch.</span></span>|  
    |<span data-ttu-id="59eca-144">**Redencode**</span><span class="sxs-lookup"><span data-stu-id="59eca-144">**Reason Code**</span></span>|<span data-ttu-id="59eca-145">Hiermee wordt de redencode opgegeven die is gekoppeld aan de dagboekbatch.</span><span class="sxs-lookup"><span data-stu-id="59eca-145">Specifies the reason code that is linked to this journal batch.</span></span>|  
    |<span data-ttu-id="59eca-146">**Status**</span><span class="sxs-lookup"><span data-stu-id="59eca-146">**Status**</span></span>|<span data-ttu-id="59eca-147">Hiermee wordt de status van de batch opgegeven.</span><span class="sxs-lookup"><span data-stu-id="59eca-147">Specifies the status of the batch.</span></span>|  
  
3.  <span data-ttu-id="59eca-148">Kies de knop **OK**.</span><span class="sxs-lookup"><span data-stu-id="59eca-148">Choose the **OK** button.</span></span>  
  
## <a name="see-also"></a><span data-ttu-id="59eca-149">Zie ook</span><span class="sxs-lookup"><span data-stu-id="59eca-149">See Also</span></span>  
 <span data-ttu-id="59eca-150">[Belgische elektronische betalingen](belgian-electronic-payments.md) </span><span class="sxs-lookup"><span data-stu-id="59eca-150">[Belgian Electronic Payments](belgian-electronic-payments.md) </span></span>  
 <span data-ttu-id="59eca-151">[Procedure: Elektronisch bankieren instellen](how-to-set-up-electronic-banking.md) </span><span class="sxs-lookup"><span data-stu-id="59eca-151">[How to: Set Up Electronic Banking](how-to-set-up-electronic-banking.md) </span></span>  
 [<span data-ttu-id="59eca-152">Procedure: IBLC-BLWI-transactiecodes instellen</span><span class="sxs-lookup"><span data-stu-id="59eca-152">How to: Set Up IBLC-BLWI Transaction Codes</span></span>](how-to-set-up-iblc-blwi-transaction-codes.md)
