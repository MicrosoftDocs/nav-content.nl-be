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
# <a name="isabel-6"></a>Isabel 6
De Isabel-organisatie heeft een CIS-platform (Client Isabel Synchronizer) ontwikkeld waarmee [!INCLUDE[navnow](../../includes/navnow_md.md)] veilig met Isabel kan worden geïntegreerd. CIS verwerkt de uitwisseling van documenten met en van de Isabel-server.  

Als u de bankbestanden wilt uploaden of downloaden, moet u uw omgeving instellen om met Isabel te werken. [!INCLUDE[navnow](../../includes/navnow_md.md)] communiceert met de CIS.dll via een COM-wrapper.  

Ga als volgt te werk om uw systeem geschikt te maken voor samenwerking met Isabel:  

- Installeer de Isabel-beveiligingsonderdelen. Raadpleeg voor meer informatie het downloadgedeelte op de [Isabel-website](http://go.microsoft.com/fwlink/?LinkId=210323).  

- Installeer de COM-wrapper van de Isabel-organisatie. Deze wrapper is opgenomen in het Isabel GO 6.20-pakket.  

- Registreer de COM-wrapper op uw computer. Zoek de CIS.dll bij de opdrachtprompt en voer vervolgens de opdracht **regsvr32 CISComWrapper.dll** uit.  

## <a name="see-also"></a>Zie ook  
 [Isabel-website](http://go.microsoft.com/fwlink/?LinkId=210323)   
 [Elektronisch bankieren voor België](belgian-electronic-banking.md)   
 [Procedure: Elektronisch bankieren instellen](how-to-set-up-electronic-banking.md)

