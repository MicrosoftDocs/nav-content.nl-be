---
title: Elektronische betalingen testen
description: Nadat u elektronisch bankieren hebt ingesteld en betalingsvoorstellen hebt gegenereerd, kunt u de betalingsdagboekregels op fouten testen voordat u ze boekt.
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
ms.openlocfilehash: 827d1bc67d6a2536f704a63668714a90249de3ae
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-test-electronic-payments"></a><span data-ttu-id="fcb59-103">Procedure: Elektronische betalingen testen</span><span class="sxs-lookup"><span data-stu-id="fcb59-103">How to: Test Electronic Payments</span></span>
<span data-ttu-id="fcb59-104">Nadat u elektronisch bankieren hebt ingesteld en betalingsvoorstellen hebt gegenereerd, kunt u de betalingsdagboekregels op fouten testen voordat u ze boekt.</span><span class="sxs-lookup"><span data-stu-id="fcb59-104">After you have set up electronic banking and generated payment suggestions, you can test the payment journal lines for errors before posting them.</span></span>  

<span data-ttu-id="fcb59-105">Hierbij wordt onder andere het volgende gevalideerd:</span><span class="sxs-lookup"><span data-stu-id="fcb59-105">Some of the information that is validated includes:</span></span>  

- <span data-ttu-id="fcb59-106">Bankrekeningnummers zijn geldig.</span><span class="sxs-lookup"><span data-stu-id="fcb59-106">Bank accounts numbers are valid.</span></span>  
- <span data-ttu-id="fcb59-107">Positieve betalingsregels zijn aanwezig.</span><span class="sxs-lookup"><span data-stu-id="fcb59-107">Positive payment lines are present.</span></span>  
- <span data-ttu-id="fcb59-108">Of binnenlandse en internationale betalingen via slechts één rekening worden uitgevoerd.</span><span class="sxs-lookup"><span data-stu-id="fcb59-108">If domestic and international payments are made from only one bank account.</span></span>  
- <span data-ttu-id="fcb59-109">Of slechts één bankrekening kan worden gebruikt voor Isabel.</span><span class="sxs-lookup"><span data-stu-id="fcb59-109">If only one bank account can be used for Isabel.</span></span>  
- <span data-ttu-id="fcb59-110">Of betalingsregels in euro's worden weergegeven voor SEPA.</span><span class="sxs-lookup"><span data-stu-id="fcb59-110">If payment lines are in Euro for SEPA.</span></span>  
- <span data-ttu-id="fcb59-111">Of er een nummerreeks voor SEPA is gedefinieerd.</span><span class="sxs-lookup"><span data-stu-id="fcb59-111">If a number series has been defined for SEPA.</span></span>  

<span data-ttu-id="fcb59-112">U kunt de fouten bekijken in het venster **Logboeken voor controlefouten exporteren**.</span><span class="sxs-lookup"><span data-stu-id="fcb59-112">You can view any errors in the **Export Check Error Logs** window.</span></span>  

> [!IMPORTANT]  
>  <span data-ttu-id="fcb59-113">U moet alle fouten corrigeren voordat u de regels kunt boeken.</span><span class="sxs-lookup"><span data-stu-id="fcb59-113">You have to correct all errors before you can post the lines.</span></span>  

## <a name="to-test-payment-journal-lines"></a><span data-ttu-id="fcb59-114">Betalingsdagboekregels testen</span><span class="sxs-lookup"><span data-stu-id="fcb59-114">To test payment journal lines</span></span>  

1.  <span data-ttu-id="fcb59-115">Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **Betalingsdagboeken** in en klik vervolgens op de gerelateerde koppeling.</span><span class="sxs-lookup"><span data-stu-id="fcb59-115">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Payment Journals**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="fcb59-116">Selecteer in het veld **Batchnaam** de vereiste dagboekbatch.</span><span class="sxs-lookup"><span data-stu-id="fcb59-116">In the **Batch Name** field, select the required journal batch.</span></span>  
3.  <span data-ttu-id="fcb59-117">Selecteer in het veld **Exportprotocol** het exportprotocol.</span><span class="sxs-lookup"><span data-stu-id="fcb59-117">In the **Export Protocol** field, select the export protocol.</span></span>  
4.  <span data-ttu-id="fcb59-118">Voer de betalingsdagboekregelinformatie in en kies vervolgens de actie **Betalingsregels controleren** om de betalingsdagboekregels te valideren.</span><span class="sxs-lookup"><span data-stu-id="fcb59-118">Enter the payment journal line information, and then choose the **Check Payment Lines** action to validate the payment journal lines.</span></span> <span data-ttu-id="fcb59-119">Welke validatie op de dagboekregels wordt uitgevoerd, is afhankelijk van de soort controle die in het venster **Exportprotocollen** is opgegeven.</span><span class="sxs-lookup"><span data-stu-id="fcb59-119">The validation that is performed on the journal lines depends on the type of check that is specified in the **Export Protocols** window.</span></span>  

## <a name="see-also"></a><span data-ttu-id="fcb59-120">Zie ook</span><span class="sxs-lookup"><span data-stu-id="fcb59-120">See Also</span></span>  
 <span data-ttu-id="fcb59-121">[Belgische elektronische betalingen](belgian-electronic-payments.md) </span><span class="sxs-lookup"><span data-stu-id="fcb59-121">[Belgian Electronic Payments](belgian-electronic-payments.md) </span></span>  
 <span data-ttu-id="fcb59-122">[Procedure: Leveranciers voor automatische betalingsvoorstellen instellen](how-to-set-up-vendors-for-automatic-payment-suggestions.md) </span><span class="sxs-lookup"><span data-stu-id="fcb59-122">[How to: Set Up Vendors for Automatic Payment Suggestions](how-to-set-up-vendors-for-automatic-payment-suggestions.md) </span></span>  
 <span data-ttu-id="fcb59-123">[Procedure: Betalingsvoorstellen genereren](how-to-generate-payment-suggestions.md) </span><span class="sxs-lookup"><span data-stu-id="fcb59-123">[How to: Generate Payment Suggestions](how-to-generate-payment-suggestions.md) </span></span>  
 [<span data-ttu-id="fcb59-124">Procedure: Betalingsbestanden afdrukken</span><span class="sxs-lookup"><span data-stu-id="fcb59-124">How to: Print Payment Files</span></span>](how-to-print-payment-files.md)

