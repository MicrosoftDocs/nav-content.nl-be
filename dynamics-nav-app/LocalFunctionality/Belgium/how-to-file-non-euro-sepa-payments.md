---
title: SEPA-betalingen in andere valuta's dan de euro indienen
description: In [!INCLUDE[navnow](../../includes/navnow_md.md)] kunt u SEPA-betalingen in andere valuta's dan de euro indienen bij de bank. Dit is handig als u betalingen verzendt naar andere landen die SEPA niet gebruiken en voor andere valuta's dan de euro.
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
ms.openlocfilehash: 6fc38866ebc02ef0873e94fc00c2e54c268e840c
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-file-non-euro-sepa-payments"></a>Procedure: SEPA-betalingen in andere valuta's dan de euro indienen
In [!INCLUDE[navnow](../../includes/navnow_md.md)] kunt u SEPA-betalingen in andere valuta's dan de euro indienen bij de bank. Dit is handig als u betalingen verzendt naar andere landen die SEPA niet gebruiken en voor andere valuta's dan de euro.  

Voordat u een dergelijke SEPA-betalingen kunt indienen, moet u de volgende beheertaken uitvoeren:  

- Stel een nieuw exportprotocol voor een niet-euro-SEPA in. Zie Exportprotocol voor meer informatie.  
- Schakel in de tabel **Land/regio** het veld **SEPA toegestaan** uit voor elk land in de EEA-zone.  
- Controleer of de waarde in het veld **Valuta Euro** in de tabel **Boekhoudinstellingen** niet in euro's is.  
- Controleer of het veld **Bankrekening van voorkeur** in de tabel **Leverancier** de IBAN en SWIFT-code bevat.  

## <a name="to-file-a-non-euro-sepa-payment"></a>Een SEPA-betaling in andere valuta's dan de euro indienen  

1.  Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "Pictogram Zoeken naar pagina of rapport"), voer **SEPA-betalingen in andere valuta's dan de euro indienen** in en klik vervolgens op de gerelateerde koppeling.  
2.  Vul de velden in zoals beschreven in de volgende tabel.  

    |Veld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Dagboeksjabloon**|Geef de dagboeksjabloon voor het SEPA-betalingsrapport op.|  
    |**Dagboekbatch**|Geef de dagboekbatch voor het SEPA-betalingsrapport op.|  
    |**Dagboekregels boeken**|Geef op of u de betalingsregels naar het grootboek wilt overbrengen.|  
    |**Dimensies opnemen**|Hier kunt u de dimensies invoeren die u in het SEPA-betalingsrapport wilt opnemen. De optie is alleen beschikbaar als het veld **Alg. dagb.regels samenvatten** in het veld **Elektronisch bankieren instellen** is geselecteerd.|  
    |**Uitvoeringsdatum**|Voer een uitvoeringsdatum in als u op de betalingsregels een datum wilt hebben die afwijkt van de boekingsdatum.|  
    |**Bestandsnaam**|Voer de naam in van het bestand, inclusief station en map, waarin u het rapport wilt afdrukken.|  

3.  Kies de knop **OK**.  

## <a name="see-also"></a>Zie ook  
 [Procedure: SEPA-betalingen indienen](how-to-file-sepa-payments.md)   
 [Procedure: SEPA-betalingen activeren](how-to-activate-sepa-payments.md)   
 [SEPA-betalingen](sepa-payments.md)

