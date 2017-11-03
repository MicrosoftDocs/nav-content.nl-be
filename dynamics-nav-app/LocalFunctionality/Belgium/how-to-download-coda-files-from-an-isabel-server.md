---
title: CODA-bestanden van een Isabel-server downloaden
description: CODA-bestanden kunnen handmatig of in de modus Met toezicht worden gedownload.
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
ms.openlocfilehash: 28d427fbeb308ba57ee96272cf98ab9d75c06b46
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-download-coda-files-from-an-isabel-server"></a><span data-ttu-id="7cf4f-103">Procedure: CODA-bestanden van een Isabel-server downloaden</span><span class="sxs-lookup"><span data-stu-id="7cf4f-103">How to: Download CODA Files from an Isabel Server</span></span>
<span data-ttu-id="7cf4f-104">CODA-bestanden kunnen handmatig of in de modus Met toezicht worden gedownload.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-104">CODA files can be downloaded manually or in attended mode.</span></span>  

<span data-ttu-id="7cf4f-105">Als u CODA-bestanden handmatig wilt downloaden, meldt u zich aan bij de Isabel-server en selecteert u de bestanden die u wilt downloaden.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-105">To manually download CODA files, log  on to the Isabel server and select the files that you want to download.</span></span> <span data-ttu-id="7cf4f-106">De gedownloade bestanden kunnen vervolgens worden geïmporteerd vanuit de tabel **Bankrekening**.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-106">The downloaded files can then be imported from the **Bank Account** table.</span></span> <span data-ttu-id="7cf4f-107">Zie [Procedure: CODA-afschriften importeren](how-to-import-coda-statements.md) voor meer informatie.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-107">For more information, see [How to: Import CODA Statements](how-to-import-coda-statements.md).</span></span>  

## <a name="to-download-coda-files-in-attended-mode"></a><span data-ttu-id="7cf4f-108">CODA-bestanden downloaden in de modus Met toezicht</span><span class="sxs-lookup"><span data-stu-id="7cf4f-108">To download CODA files in attended mode</span></span>  

1.  <span data-ttu-id="7cf4f-109">Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **IBS-logboeken** in en klik vervolgens op de gerelateerde koppeling.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-109">Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **IBS Logs**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="7cf4f-110">Kies de actie **Downloaden**.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-110">Choose the **Download** action.</span></span>  
3.  <span data-ttu-id="7cf4f-111">Vul in het venster **Opties voor IBS-downloadaanvraag** de velden in zoals wordt beschreven in de volgende tabel.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-111">In the **IBS Download Request Options** window, fill in the fields as described in the following table.</span></span>  

    |<span data-ttu-id="7cf4f-112">Veld</span><span class="sxs-lookup"><span data-stu-id="7cf4f-112">Field</span></span>|<span data-ttu-id="7cf4f-113">Description</span><span class="sxs-lookup"><span data-stu-id="7cf4f-113">Description</span></span>|  
    |---------------------------------|---------------------------------------|  
    |<span data-ttu-id="7cf4f-114">**Van datum**</span><span class="sxs-lookup"><span data-stu-id="7cf4f-114">**From Date**</span></span>|<span data-ttu-id="7cf4f-115">Geef de begindatum van de download op.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-115">Specify the start date of the download.</span></span>|  
    |<span data-ttu-id="7cf4f-116">**T/m datum**</span><span class="sxs-lookup"><span data-stu-id="7cf4f-116">**To Date**</span></span>|<span data-ttu-id="7cf4f-117">Geef de einddatum van de download op.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-117">Specify the end date of the download.</span></span>|  
    |<span data-ttu-id="7cf4f-118">**Bestandsindeling**</span><span class="sxs-lookup"><span data-stu-id="7cf4f-118">**File Format**</span></span>|<span data-ttu-id="7cf4f-119">Selecteer **Coda** als de bestandsindeling.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-119">Select **Coda** as the file format.</span></span>|  
    |<span data-ttu-id="7cf4f-120">**Bestandsstatus**</span><span class="sxs-lookup"><span data-stu-id="7cf4f-120">**File Status**</span></span>|<span data-ttu-id="7cf4f-121">Selecteer de bestandsstatus van de download.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-121">Select the file status of the download.</span></span> <span data-ttu-id="7cf4f-122">U kunt kiezen uit **Niet gedownload**, **Gedownload** en **Alle**.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-122">File statuses include **Not Downloaded**, **Downloaded**, and **All**.</span></span> <span data-ttu-id="7cf4f-123">Doorgaans gebruikt u **Niet gedownload** omdat u de CODA-bestanden downloadt die niet naar uw systeem zijn gedownload.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-123">Typically you will select **Not Downloaded**, because you are downloading the CODA files that have not been downloaded to your system.</span></span>|  

4.  <span data-ttu-id="7cf4f-124">Kies de knop **OK**.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-124">Choose the **OK** button.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="7cf4f-125">U kunt geen bestanden van de Isabel-server verwijderen in het venster **Opties voor IBS-downloadaanvraag**.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-125">You cannot delete any files from the Isabel server by using the **IBS Download Request Options** window.</span></span> <span data-ttu-id="7cf4f-126">U moet de bestanden handmatig verwijderen door u aan te melden bij de Isabel-server.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-126">You must manually delete the files by logging on to the Isabel server.</span></span>  

     <span data-ttu-id="7cf4f-127">Als de CODA-bestanden zijn gedownload, wordt in het veld **Verwerkingsstatus** de waarde **Gemaakt** weergegeven in het venster **IBS-logboeken**.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-127">After the CODA files have been downloaded, the **Process Status** field will display **Created** in the **IBS Logs** window.</span></span> <span data-ttu-id="7cf4f-128">U kunt u aanmelden op de Isabel-server om de bestanden handmatig op te halen.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-128">You can log on to the Isabel server to manually retrieve the files.</span></span> <span data-ttu-id="7cf4f-129">Zie [Procedure: CODA-afschriften importeren](how-to-import-coda-statements.md) voor meer informatie.</span><span class="sxs-lookup"><span data-stu-id="7cf4f-129">For more information, see [How to: Import CODA Statements](how-to-import-coda-statements.md).</span></span>  

## <a name="see-also"></a><span data-ttu-id="7cf4f-130">Zie ook</span><span class="sxs-lookup"><span data-stu-id="7cf4f-130">See Also</span></span>  
[<span data-ttu-id="7cf4f-131">Belgische lokale functionaliteit</span><span class="sxs-lookup"><span data-stu-id="7cf4f-131">Belgium Local Functionality</span></span>](belgium-local-functionality.md)

