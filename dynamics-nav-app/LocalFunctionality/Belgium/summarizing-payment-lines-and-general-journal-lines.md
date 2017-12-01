---
title: Betalingsregels en dagboekregels samenvatten
description: In [!INCLUDE[navnow](../../includes/navnow_md.md)] worden verschillende soorten transacties op dezelfde manier afgehandeld.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 80baa8f0f21cfac16fe522ea3a4ba606fb872cf1
ms.contentlocale: nl-be
ms.lasthandoff: 12/01/2017

---
# <a name="summarizing-payment-lines-and-general-journal-lines"></a><span data-ttu-id="c1853-103">Betalingsregels en dagboekregels samenvatten</span><span class="sxs-lookup"><span data-stu-id="c1853-103">Summarizing Payment Lines and General Journal Lines</span></span>
<span data-ttu-id="c1853-104">In [!INCLUDE[navnow](../../includes/navnow_md.md)] worden de volgende soorten transacties op dezelfde manier afgehandeld:</span><span class="sxs-lookup"><span data-stu-id="c1853-104">In [!INCLUDE[navnow](../../includes/navnow_md.md)] handles the following types of transactions in the same way:</span></span>  

- <span data-ttu-id="c1853-105">Binnenlandse betalingen</span><span class="sxs-lookup"><span data-stu-id="c1853-105">Domestic payments</span></span>  
- <span data-ttu-id="c1853-106">Internationale betalingen</span><span class="sxs-lookup"><span data-stu-id="c1853-106">International payments</span></span>  
- <span data-ttu-id="c1853-107">SEPA-betalingen</span><span class="sxs-lookup"><span data-stu-id="c1853-107">SEPA payments</span></span>  
- <span data-ttu-id="c1853-108">Niet-euro SEPA-betalingen</span><span class="sxs-lookup"><span data-stu-id="c1853-108">Non-euro SEPA payments</span></span>  

## <a name="how-payment-journal-lines-are-transferred-to-the-general-journal"></a><span data-ttu-id="c1853-109">Hoe betalingsdagboekregels naar het grootboek worden overgebracht</span><span class="sxs-lookup"><span data-stu-id="c1853-109">How Payment Journal Lines are Transferred to the General Journal</span></span>  
<span data-ttu-id="c1853-110">Wanneer u de betalingsdagboekregels naar een bestand exporteert, brengt [!INCLUDE[navnow](../../includes/navnow_md.md)] de betalingsdagboekregels naar het opgegeven dagboek over.</span><span class="sxs-lookup"><span data-stu-id="c1853-110">When you export the payment journal lines to a file, [!INCLUDE[navnow](../../includes/navnow_md.md)] transfers the payment journal lines to the specified general journal.</span></span> <span data-ttu-id="c1853-111">Standaard wordt een dagboekregel gemaakt voor elke betalingsdagboekregel.</span><span class="sxs-lookup"><span data-stu-id="c1853-111">By default, a general journal line is created for each payment journal line.</span></span>  

<span data-ttu-id="c1853-112">De volgende twee velden in het venster **Elektronisch bankieren instellen** bepalen hoe de betalingsregels worden samengevat:</span><span class="sxs-lookup"><span data-stu-id="c1853-112">The following two fields in the **Electronic Banking Setup** window affect how the payment lines are summarized:</span></span>  

- <span data-ttu-id="c1853-113">**Alg. dagb.regels samenvatten**</span><span class="sxs-lookup"><span data-stu-id="c1853-113">**Summarize Gen. Jnl. Lines**</span></span>  
- <span data-ttu-id="c1853-114">**Tekst van betaalberichten afbreken**</span><span class="sxs-lookup"><span data-stu-id="c1853-114">**Cut off Payment Message Texts**</span></span>  

<span data-ttu-id="c1853-115">Als u het selectievakje **Alg. dagb.regels samenvatten** in het venster **Elektronisch bankieren instellen** hebt geselecteerd, vat [!INCLUDE[navnow](../../includes/navnow_md.md)] alle betalingsdagboekregels voor een bepaalde leverancier in één dagboekregel samen.</span><span class="sxs-lookup"><span data-stu-id="c1853-115">If you have selected the **Summarize Gen. Jnl. Lines** check box in the **Electronic Banking Setup** window, [!INCLUDE[navnow](../../includes/navnow_md.md)] summarizes all payment journal lines for a specific vendor into one general journal line.</span></span> <span data-ttu-id="c1853-116">De algemene omschrijving 'Betaling %1', waarbij %1 het leveranciersnummer is, wordt gebruikt voor de samengevatte dagboekregelomschrijving.</span><span class="sxs-lookup"><span data-stu-id="c1853-116">The general description "Payment %1," where %1 is the vendor number, is used for the summarized journal line description.</span></span> <span data-ttu-id="c1853-117">Er worden een afzonderlijke betalingsregel en een aparte dagboekregel gemaakt om het volgende af te handelen:</span><span class="sxs-lookup"><span data-stu-id="c1853-117">A separate payment line and a separate general journal line are created to handle:</span></span>  

- <span data-ttu-id="c1853-118">Betalingsdagboekregels die gedeeltelijke betalingen bevatten, met zowel het veld **Gedeeltelijke betaling** als het veld **Afzonderlijke regel** ingeschakeld.</span><span class="sxs-lookup"><span data-stu-id="c1853-118">Payment journal lines that contain partial payments, with both the **Partial Payment** and the **Separate Line** fields selected.</span></span>  

- <span data-ttu-id="c1853-119">Betalingsdagboekregels die een bericht met een standaardindeling bevatten (dus slagen voor de MOD97-test), waarmee **Bericht met standaardindeling** op Waar wordt ingesteld in het dagboek voor elektronisch bankieren.</span><span class="sxs-lookup"><span data-stu-id="c1853-119">Payment journal lines that contain a standard format message (that is, passes the MOD97 test), which sets **Standard Format Message** to True in the electronic banking journal.</span></span>  

## <a name="example-1"></a><span data-ttu-id="c1853-120">Voorbeeld 1</span><span class="sxs-lookup"><span data-stu-id="c1853-120">Example 1</span></span>  
<span data-ttu-id="c1853-121">In dit voorbeeld exporteert u betalingsregels en is het selectievakje **Alg. dagb.regels samenvatten** ingeschakeld.</span><span class="sxs-lookup"><span data-stu-id="c1853-121">In this example, you export payment lines, and the **Summarize Gen. Jnl. Lines** check box is selected.</span></span> [!INCLUDE[navnow](../../includes/navnow_md.md)]<span data-ttu-id="c1853-122"> maakt:</span><span class="sxs-lookup"><span data-stu-id="c1853-122"> creates:</span></span>  

- <span data-ttu-id="c1853-123">Een gecombineerde betalingsregel in een XML-bestand met een samengevoegd betalingsbericht.</span><span class="sxs-lookup"><span data-stu-id="c1853-123">One combined payment line in a XML file that has a concatenated payment message.</span></span> <span data-ttu-id="c1853-124">Spaties zijn het scheidingsteken.</span><span class="sxs-lookup"><span data-stu-id="c1853-124">White space is the delimiter.</span></span>  
- <span data-ttu-id="c1853-125">Eén betaling in het grootboek met een algemene beschrijving die ../../de leveranciersnaam bevat.</span><span class="sxs-lookup"><span data-stu-id="c1853-125">One payment line in the general journal with a generic description that ../../includes the vendor name.</span></span>  

## <a name="example-2"></a><span data-ttu-id="c1853-126">Voorbeeld 2</span><span class="sxs-lookup"><span data-stu-id="c1853-126">Example 2</span></span>  
<span data-ttu-id="c1853-127">In dit voorbeeld exporteert u betalingsregels en is het selectievakje **Alg. dagb.regels samenvatten** ingeschakeld.</span><span class="sxs-lookup"><span data-stu-id="c1853-127">In this example, you export payment lines, and the **Summarize Gen. Jnl. Lines** check box is selected.</span></span> <span data-ttu-id="c1853-128">Het selectievakje **Tekst van betaalberichten afbreken** wordt gewist en gecombineerde SEPA- en niet-auto SEPA-betalingsregels overschrijden 140 tekens in het betalingsbericht.</span><span class="sxs-lookup"><span data-stu-id="c1853-128">The **Cut off Payment Message Texts** check box is cleared, and combined SEPA and non-euro SEPA payment lines exceed 140 characters in payment message.</span></span> [!INCLUDE[navnow](../../includes/navnow_md.md)]<span data-ttu-id="c1853-129"> maakt:</span><span class="sxs-lookup"><span data-stu-id="c1853-129"> creates:</span></span>  

- <span data-ttu-id="c1853-130">Twee gecombineerde betalingsregels in een XML-bestand.</span><span class="sxs-lookup"><span data-stu-id="c1853-130">Two combined payment lines in a XML file.</span></span> <span data-ttu-id="c1853-131">De eerste betalingsregel bevat de eerste samengevoegde betalingsberichten.</span><span class="sxs-lookup"><span data-stu-id="c1853-131">The first payment line contains the first concatenated payment messages.</span></span> <span data-ttu-id="c1853-132">De tweede betalingsregel bevat het betalingsbericht vanaf de derde regel.</span><span class="sxs-lookup"><span data-stu-id="c1853-132">The second payment line contains the payment message from the third line.</span></span>  

- <span data-ttu-id="c1853-133">Eén betaling in het grootboek met een algemene beschrijving die ../../de leveranciersnaam bevat.</span><span class="sxs-lookup"><span data-stu-id="c1853-133">One payment line in the general journal with a generic description that ../../includes the vendor name.</span></span>  

## <a name="example-3"></a><span data-ttu-id="c1853-134">Voorbeeld 3</span><span class="sxs-lookup"><span data-stu-id="c1853-134">Example 3</span></span>  
<span data-ttu-id="c1853-135">In dit voorbeeld exporteert u betalingsregels en is het selectievakje **Alg. dagb.regels samenvatten** ingeschakeld.</span><span class="sxs-lookup"><span data-stu-id="c1853-135">In this example, you export payment lines, and the **Summarize Gen. Jnl. Lines** check box is selected.</span></span> <span data-ttu-id="c1853-136">Het selectievakje **Tekst van betaalberichten afbreken** wordt ook ingeschakeld en gecombineerde SEPA- en niet-SEPA betalingsregels overschrijden 140 tekens in het betalingsbericht.</span><span class="sxs-lookup"><span data-stu-id="c1853-136">The **Cut off Payment Message Texts** check box is also selected and combined SEPA and non-SEPA payment lines exceed 140 characters in payment message.</span></span> [!INCLUDE[navnow](../../includes/navnow_md.md)]<span data-ttu-id="c1853-137"> maakt:</span><span class="sxs-lookup"><span data-stu-id="c1853-137"> creates:</span></span>  

- <span data-ttu-id="c1853-138">Eén gecombineerde betalingsregel in een XML-bestand met twee samengevoegde betalingsberichten.</span><span class="sxs-lookup"><span data-stu-id="c1853-138">One combined payment line in a XML file that has two concatenated payment messages.</span></span> <span data-ttu-id="c1853-139">Een beletselteken (…) wordt gebruikt om aan te geven dat het bericht afgekapt is.</span><span class="sxs-lookup"><span data-stu-id="c1853-139">An ellipsis (…) is used to indicate that the message is truncated.</span></span>  

- <span data-ttu-id="c1853-140">Eén betalingsregel in het grootboek met een algemene beschrijving die de leveranciersnaam bevat.</span><span class="sxs-lookup"><span data-stu-id="c1853-140">One payment line in the general journal with a generic description that includes the vendor name.</span></span>  

<span data-ttu-id="c1853-141">Op basis van de XML-structuur worden betalingen samengevat per rekeningnummer en bankrekeningnummer van de begunstigde en bankrekening. Het bankrekeningfilter mag leeg zijn.</span><span class="sxs-lookup"><span data-stu-id="c1853-141">Based on the XML structure, the payments are summarized per account number and beneficiary bank account no and bank account no. The bank account filter can be empty.</span></span>  

<span data-ttu-id="c1853-142">De EndToEndId in het SEPA-bericht wordt gehaald uit het betalingsbericht en kan worden afgekapt tot de maximumlengte van 45 tekens.</span><span class="sxs-lookup"><span data-stu-id="c1853-142">The EndToEndId in the SEPA message is taken from the payment message and can be truncated to the maximum length of 45 characters.</span></span>  

## <a name="see-also"></a><span data-ttu-id="c1853-143">Zie ook</span><span class="sxs-lookup"><span data-stu-id="c1853-143">See Also</span></span>  
 <span data-ttu-id="c1853-144">[Procedure: Elektronisch bankieren instellen](how-to-set-up-electronic-banking.md) </span><span class="sxs-lookup"><span data-stu-id="c1853-144">[How to: Set Up Electronic Banking](how-to-set-up-electronic-banking.md) </span></span>  
 [<span data-ttu-id="c1853-145">Financiën instellen</span><span class="sxs-lookup"><span data-stu-id="c1853-145">Setting Up Finance</span></span>](../../finance-setup-finance.md)  
 [<span data-ttu-id="c1853-146">Procedure: Inkopen vastleggen</span><span class="sxs-lookup"><span data-stu-id="c1853-146">How to: Record Purchases</span></span>](../../purchasing-how-record-purchases.md) 

