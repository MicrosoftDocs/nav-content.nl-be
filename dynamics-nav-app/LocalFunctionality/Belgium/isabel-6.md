---
title: Isabel 6
description: "De Isabel-organisatie heeft een CIS-platform (Client Isabel Synchronizer) ontwikkeld waarmee [!INCLUDE[navnow](../../includes/navnow_md.md)] veilig met Isabel kan worden geïntegreerd. CIS verwerkt de uitwisseling van documenten met en van de Isabel-server."
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
ms.openlocfilehash: 38b27c23fc7d9223e2185b087b044bb19bdbd4b4
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="isabel-6"></a><span data-ttu-id="37b0f-104">Isabel 6</span><span class="sxs-lookup"><span data-stu-id="37b0f-104">Isabel 6</span></span>
<span data-ttu-id="37b0f-105">De Isabel-organisatie heeft een CIS-platform (Client Isabel Synchronizer) ontwikkeld waarmee [!INCLUDE[navnow](../../includes/navnow_md.md)] veilig met Isabel kan worden geïntegreerd.</span><span class="sxs-lookup"><span data-stu-id="37b0f-105">The Isabel organization has developed a Client Isabel Synchronizer (CIS) platform that allows [!INCLUDE[navnow](../../includes/navnow_md.md)] to securely integrate with Isabel.</span></span> <span data-ttu-id="37b0f-106">CIS verwerkt de uitwisseling van documenten met en van de Isabel-server.</span><span class="sxs-lookup"><span data-stu-id="37b0f-106">CIS handles document exchange to and from the Isabel server.</span></span>  

<span data-ttu-id="37b0f-107">Als u de bankbestanden wilt uploaden of downloaden, moet u uw omgeving instellen om met Isabel te werken.</span><span class="sxs-lookup"><span data-stu-id="37b0f-107">To upload or download the bank files, you will have to set up your environment to work with Isabel.</span></span> [!INCLUDE[navnow](../../includes/navnow_md.md)]<span data-ttu-id="37b0f-108"> communiceert met de CIS.dll via een COM-wrapper.</span><span class="sxs-lookup"><span data-stu-id="37b0f-108"> communicates to the CIS.dll through a COM wrapper.</span></span>  

<span data-ttu-id="37b0f-109">Ga als volgt te werk om uw systeem geschikt te maken voor samenwerking met Isabel:</span><span class="sxs-lookup"><span data-stu-id="37b0f-109">To set up your system to work with Isabel, complete the following:</span></span>  

- <span data-ttu-id="37b0f-110">Installeer de Isabel-beveiligingsonderdelen.</span><span class="sxs-lookup"><span data-stu-id="37b0f-110">Install the Isabel security components.</span></span> <span data-ttu-id="37b0f-111">Raadpleeg voor meer informatie het downloadgedeelte op de [Isabel-website](http://go.microsoft.com/fwlink/?LinkId=210323).</span><span class="sxs-lookup"><span data-stu-id="37b0f-111">For more information, see the download area on the [Isabel website](http://go.microsoft.com/fwlink/?LinkId=210323).</span></span>  

- <span data-ttu-id="37b0f-112">Installeer de COM-wrapper van de Isabel-organisatie.</span><span class="sxs-lookup"><span data-stu-id="37b0f-112">Install the COM wrapper that is manufactured by the Isabel organization.</span></span> <span data-ttu-id="37b0f-113">Deze wrapper is opgenomen in het Isabel GO 6.20-pakket.</span><span class="sxs-lookup"><span data-stu-id="37b0f-113">This wrapper is included with the Isabel GO 6.20 package.</span></span>  

- <span data-ttu-id="37b0f-114">Registreer de COM-wrapper op uw computer.</span><span class="sxs-lookup"><span data-stu-id="37b0f-114">Register the COM wrapper on your computer.</span></span> <span data-ttu-id="37b0f-115">Zoek de CIS.dll bij de opdrachtprompt en voer vervolgens de opdracht **regsvr32 CISComWrapper.dll** uit.</span><span class="sxs-lookup"><span data-stu-id="37b0f-115">At the command prompt, locate the CIS.dll and then execute the **regsvr32 CISComWrapper.dll** command.</span></span>  

## <a name="see-also"></a><span data-ttu-id="37b0f-116">Zie ook</span><span class="sxs-lookup"><span data-stu-id="37b0f-116">See Also</span></span>  
 <span data-ttu-id="37b0f-117">[Isabel-website](http://go.microsoft.com/fwlink/?LinkId=210323) </span><span class="sxs-lookup"><span data-stu-id="37b0f-117">[Isabel website](http://go.microsoft.com/fwlink/?LinkId=210323) </span></span>  
 <span data-ttu-id="37b0f-118">[Elektronisch bankieren voor België](belgian-electronic-banking.md) </span><span class="sxs-lookup"><span data-stu-id="37b0f-118">[Belgian Electronic Banking](belgian-electronic-banking.md) </span></span>  
 [<span data-ttu-id="37b0f-119">Procedure: Elektronisch bankieren instellen</span><span class="sxs-lookup"><span data-stu-id="37b0f-119">How to: Set Up Electronic Banking</span></span>](how-to-set-up-electronic-banking.md)

