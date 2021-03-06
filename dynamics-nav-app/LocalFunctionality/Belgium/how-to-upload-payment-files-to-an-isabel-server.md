---
title: Betalingsbestanden uploaden naar een Isabel-server
description: "Betalingsbestanden kunnen worden geüpload via het venster **IBS-logboeken**. U kunt alleen betalingsbestanden uploaden als de velden **Uploadintegratiemodus** en **Downloadintegratiemodus** in het venster **Elektronisch bankieren instellen** zijn ingesteld op **Met toezicht**."
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
ms.openlocfilehash: fa15bbba7beb1a90df5a6051ab763a802268da79
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-upload-payment-files-to-an-isabel-server"></a>Procedure: Betalingsbestanden uploaden naar een Isabel-server
Betalingsbestanden kunnen worden geüpload via het venster **IBS-logboeken**. U kunt alleen betalingsbestanden uploaden als de velden **Uploadintegratiemodus** en **Downloadintegratiemodus** in het venster **Elektronisch bankieren instellen** zijn ingesteld op **Met toezicht**.  

> [!NOTE]  
>  Voordat u betalingbestanden kunt uploaden, moet u zijn aangemeld bij de Isabel-server.  

## <a name="to-upload-payment-files-in-attended-mode"></a>Betalingsbestanden uploaden in de modus Met toezicht  

1.  Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **IBS-logboeken** in en klik vervolgens op de gerelateerde koppeling.  
2.  Kies de actie **Contract en gebruiker ophalen**.  
3.  Na het verifiëren van de betalingbestanden worden een gebruikers- en contract- id weergegeven in de velden **IBS-gebruikers-id** en **IBS-contract-id**.  

    Het veld **Uploadstatus** wordt ingesteld op **Gereed voor uploaden**. Als op de Isabel-server meerdere contracten voor de bankrekening bestaan, wordt **Uploadstatus** ingesteld op **Conflict bestaat**. Selecteer het juiste contract.  

4.  Kies de actie **Downloaden**. De betalingsbestanden worden geüpload naar de Isabel-server en het veld **Verwerkingsstatus** wordt ingesteld op **Verwerkt**.  
5.  Vervolg het verwerken van de betalingsbestanden door de bestanden op de Isabel-server te ondertekenen en te verzenden.  

## <a name="see-also"></a>Zie ook  
 [Procedure: IBS-logposten archiveren](how-to-archive-ibs-log-entries.md)

