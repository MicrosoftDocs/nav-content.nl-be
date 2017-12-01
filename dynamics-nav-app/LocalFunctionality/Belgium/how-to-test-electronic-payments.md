---
title: Elektronische betalingen testen
description: Nadat u elektronisch bankieren hebt ingesteld en betalingsvoorstellen hebt gegenereerd, kunt u de betalingsdagboekregels op fouten testen voordat u ze boekt.
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
ms.openlocfilehash: 827d1bc67d6a2536f704a63668714a90249de3ae
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-test-electronic-payments"></a>Procedure: Elektronische betalingen testen
Nadat u elektronisch bankieren hebt ingesteld en betalingsvoorstellen hebt gegenereerd, kunt u de betalingsdagboekregels op fouten testen voordat u ze boekt.  

Hierbij wordt onder andere het volgende gevalideerd:  

- Bankrekeningnummers zijn geldig.  
- Positieve betalingsregels zijn aanwezig.  
- Of binnenlandse en internationale betalingen via slechts één rekening worden uitgevoerd.  
- Of slechts één bankrekening kan worden gebruikt voor Isabel.  
- Of betalingsregels in euro's worden weergegeven voor SEPA.  
- Of er een nummerreeks voor SEPA is gedefinieerd.  

U kunt de fouten bekijken in het venster **Logboeken voor controlefouten exporteren**.  

> [!IMPORTANT]  
>  U moet alle fouten corrigeren voordat u de regels kunt boeken.  

## <a name="to-test-payment-journal-lines"></a>Betalingsdagboekregels testen  

1.  Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **Betalingsdagboeken** in en klik vervolgens op de gerelateerde koppeling.  
2.  Selecteer in het veld **Batchnaam** de vereiste dagboekbatch.  
3.  Selecteer in het veld **Exportprotocol** het exportprotocol.  
4.  Voer de betalingsdagboekregelinformatie in en kies vervolgens de actie **Betalingsregels controleren** om de betalingsdagboekregels te valideren. Welke validatie op de dagboekregels wordt uitgevoerd, is afhankelijk van de soort controle die in het venster **Exportprotocollen** is opgegeven.  

## <a name="see-also"></a>Zie ook  
 [Belgische elektronische betalingen](belgian-electronic-payments.md)   
 [Procedure: Leveranciers voor automatische betalingsvoorstellen instellen](how-to-set-up-vendors-for-automatic-payment-suggestions.md)   
 [Procedure: Betalingsvoorstellen genereren](how-to-generate-payment-suggestions.md)   
 [Procedure: Betalingsbestanden afdrukken](how-to-print-payment-files.md)

