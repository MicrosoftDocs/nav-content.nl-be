---
title: "Domiciliëringsvoorstellen genereren"
description: "Als u domiciliëringen hebt ingesteld, kunt u beginnen met het genereren van domiciliëringsvoorstellen. In [!INCLUDE[navnow](../../includes/navnow_md.md)] kunt u alleen domiciliëringsvoorstellen voor binnenlandse klanten maken."
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
ms.sourcegitcommit: b9b1f062ee6009f34698ea2cf33bc25bdd5b11e4
ms.openlocfilehash: 20006ba794abeffeaecc7d36d1113469a464c3ab
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-generate-domiciliation-suggestions"></a>Procedure: Domiciliëringsvoorstellen genereren
Als u domiciliëringen hebt ingesteld, kunt u beginnen met het genereren van domiciliëringsvoorstellen. In [!INCLUDE[navnow](../../includes/navnow_md.md)] kunt u alleen domiciliëringsvoorstellen voor binnenlandse klanten maken.  

## <a name="to-generate-domiciliation-suggestions"></a>Domiciliëringsvoorstellen genereren  

1.  Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **Domiciliëringsdagboek** in en klik vervolgens op de gerelateerde koppeling.  
2.  Selecteer in het veld **Batchnaam** de vereiste dagboekbatch en kies vervolgens de actie **Domiciliëringen voorstellen**.  
3.  Vul op het sneltabblad **Opties** de velden in zoals in de volgende tabel wordt weergegeven.  

    |Veld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Vervaldatum**|Geef hier de vervaldatum voor de batchverwerking op. Alleen posten met een vervaldatum vóór of op deze datum worden opgenomen.|  
    |**Contantkorting nemen**|Selecteer deze optie als u in de batchverwerking klantposten wilt opnemen waarvoor u een contantkorting kunt krijgen.|  
    |**Kortingsvervaldatum betaling**|Typ de datum die wordt gebruikt om de contantkorting te berekenen.|  
    |**Mogelijke terugbetalingen selecteren**|Selecteer deze optie als in de batchverwerking terugbetalingen moeten worden opgenomen.|  
    |**Boekingsdatum**|Typ de datum die als boekingsdatum verschijnt op de regels die tijdens de batchverwerking in het domiciliëringsdagboek worden ingevoegd.|  

4.  Voer desgewenst extra filtercriteria in op het sneltabblad **Klant**.  
5.  Kies de knop **OK**.  

Wanneer de batchverwerking is uitgevoerd, bevat het domiciliëringsdagboek alle openstaande klantenposten die overeenkomen met de filters.  

> [!NOTE]  
>  De domiciliëringsvoorstellen bevatten alleen klanten waarvoor een domiciliëringsnummer is ingesteld. Zie [Procedure: Domiciliëringen instellen](how-to-set-up-domiciliations.md) voor meer informatie.  

## <a name="see-also"></a>Zie ook  
 [Elektronisch bankieren voor België](belgian-electronic-banking.md)   
 [Incasso via domiciliëring](direct-debit-using-domiciliation.md)   
 [Procedure: Domiciliëringen instellen](how-to-set-up-domiciliations.md)   
 [Procedure: Domiciliëringen testen](how-to-test-domiciliations.md)   
 [Procedure: Domiciliëringsregels bewerken en verwijderen](how-to-edit-and-delete-domiciliation-lines.md)   
 [Procedure: Domiciliëringen exporteren en boeken](how-to-export-and-post-domiciliations.md)

