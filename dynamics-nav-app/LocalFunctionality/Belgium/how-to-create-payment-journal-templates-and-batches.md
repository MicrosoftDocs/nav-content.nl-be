---
title: Betalingsdagboeksjablonen en -batches maken
description: In [!INCLUDE[navnow](../../includes/navnow_md.md)] worden betalingsvoorstellen gegenereerd en geboekt in betalingsdagboeken. De structuur van het betalingsdagboek lijkt op die van andere dagboeksoorten.
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
ms.openlocfilehash: 2134226936e733f0756249436c5cb77f56a125d4
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-create-payment-journal-templates-and-batches"></a>Procedure: Betalingsdagboeksjablonen en -batches maken
In [!INCLUDE[navnow](../../includes/navnow_md.md)] worden betalingsvoorstellen gegenereerd en geboekt in betalingsdagboeken. De structuur van het betalingsdagboek lijkt op die van andere dagboeksoorten. Het betalingsdagboek bevat echter enkele velden die specifiek betrekking hebben op het verwerken van betalingen. Voordat u betalingsvoorstellen kunt genereren, moet u een betalingsdagboeksjabloon en een betalingsdagboekbatch instellen.  

Als u een bankrekening toewijst aan de betalingsdagboeksjabloon, wordt de bankrekening ingevoegd in alle betalingsdagboekbatches en betalingsdagboekregels die met deze sjabloon worden gemaakt. Door een bankrekening voor de dagboeksjabloon op te geven, kunt u de benodigde tijd voor het controleren van de betalingsvoorstellen beperken.  

## <a name="to-create-a-payment-journal-template"></a>Een betalingsdagboeksjabloon maken  

1.  Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **Betalingsdagboeksjablonen** in en klik vervolgens op de gerelateerde koppeling.  
2.  Kies de actie **Nieuw**.  
3.  Vul in het venster **Betalingsdagboeksjablonen** de velden in zoals wordt beschreven in de volgende tabel.  

    |Veld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Naam**|Voer de unieke naam in van de betalingsdagboeksjabloon die u maakt.|  
    |**Beschrijving**|Voer een omschrijving voor de betalingsdagboeksjabloon in.|  
    |**Bankrekening**|Selecteer de bankrekening die wordt gebruikt als u een betalingsvoorstel maakt.|  
    |**Redencode**|Selecteer de redencode die wordt gebruikt voor alle dagboekbatches en regels die worden gemaakt met de dagboeksjabloon. Als u een andere redencode op een dagboekregel wilt gebruiken, kunt u deze handmatig wijzigen.|  
    |**Broncode**|Selecteer de broncode die wordt gebruikt voor alle dagboekbatches en regels die worden gemaakt met de dagboeksjabloon.|  

4.  Kies de knop **OK**.  

## <a name="to-add-payment-journal-batches-to-the-journal-template"></a>Betalingsdagboekbatches toevoegen aan de dagboeksjabloon  

1.  Kies in het venster **Betalingsdagboeksjablonen** de actie **Batches**.  
2.  Vul in het venster **Betalingsdagboekbatch** de velden in zoals wordt beschreven in de volgende tabel.  

    |Veld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Dagboeksjabloon**|Geef een dagboeksjabloonnaam op voor de betalingsdagboekbatch.|  
    |**Naam**|Voer een unieke naam voor de dagboekbatch in.<br /><br /> **OPMERKING:** als de dagboeknaam numeriek moet wordt bijgewerkt, neemt u een nummer op in de dagboekbatchnaam. Zo wordt de waarde in de batchnaam KBC1 bij elke nieuwe boeking verhoogd (KBC2, KBC3, enzovoort).|  
    |**Beschrijving**|Voer een omschrijving voor de dagboekbatch in.|  
    |**Redencode**|Hiermee wordt de redencode opgegeven die is gekoppeld aan de dagboekbatch.|  
    |**Status**|Hiermee wordt de status van de batch opgegeven.|  

3.  Kies de knop **OK**.  

## <a name="see-also"></a>Zie ook  
 [Belgische elektronische betalingen](belgian-electronic-payments.md)   
 [Procedure: Elektronisch bankieren instellen](how-to-set-up-electronic-banking.md)   
 [Procedure: IBLC-BLWI-transactiecodes instellen](how-to-set-up-iblc-blwi-transaction-codes.md)

