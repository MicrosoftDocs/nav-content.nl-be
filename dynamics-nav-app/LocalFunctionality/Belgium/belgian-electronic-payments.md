---
title: Belgische elektronische betalingen
description: In de module voor elektronisch bankieren in [!INCLUDE[navnow](../../includes/navnow_md.md)] kunt u elektronische betalingen naar binnen- en buitenland, en SEPA en niet-Euro SEPA verzenden.
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
ms.openlocfilehash: f9c57e308c07fea0a7dfac37889eff8ec4c84c5b
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="belgian-electronic-payments"></a>Belgische elektronische betalingen
In de module voor elektronisch bankieren in [!INCLUDE[navnow](../../includes/navnow_md.md)] kunt u elektronische betalingen naar binnen- en buitenland, en SEPA en niet-Euro SEPA verzenden.  

|Elektronische betaling|Description|  
|------------------------|---------------------------------------|  
|Binnenlands|Deze betalingen worden uitgevoerd in de lokale valuta (LV) en worden verwerkt door een lokale financiële instelling voor begunstigden die rekeningen hebben bij een lokale financiële instelling. De geldigheid van de bankrekeningnummers wordt door [!INCLUDE[navnow](../../includes/navnow_md.md)] gecontroleerd.|  
|Internationaal|Deze betalingen worden uitgevoerd in een vreemde valuta of de lokale valuta (LV) en worden verwerkt door een lokale financiële instelling voor begunstigden die rekeningen hebben bij een buitenlandse financiële instelling. De geldigheid van de bankrekeningnummers wordt niet door [!INCLUDE[navnow](../../includes/navnow_md.md)] gecontroleerd.|  
|SEPA|Deze betalingen worden uitgevoerd in euro's en verwerkt in landen/regio's waar SEPA-betalingen zijn toegestaan. De geldigheid van de bankrekeningnummers wordt door [!INCLUDE[navnow](../../includes/navnow_md.md)] gecontroleerd.|  
|SEPA-betalingen in andere valuta's|Deze betalingen worden uitgevoerd in andere valuta's dan de euro en naar een land of regio buiten de EEA (European Economic Association). De geldigheid van de bankrekeningnummers wordt door [!INCLUDE[navnow](../../includes/navnow_md.md)] gecontroleerd.|  

 Omdat de standaard voor elektronische betalingen per land/regio verschilt, kunnen elektronische betalingen gemaakt in [!INCLUDE[navnow](../../includes/navnow_md.md)] alleen worden verwerkt door financiële instellingen in België. Voor internationale betalingen moeten de lokale financiële instellingen de betaling verwerken met de buitenlandse instellingen.  

> [!NOTE]  
>  Creditnota's kunnen niet afzonderlijk worden verwerkt omdat betalingen geen negatief saldo mogen hebben. Als u een creditnota wilt verwerken, moet u deze aan een of meer facturen toevoegen door betalingen te totaliseren.  

Voordat u een elektronische betaling kunt uitvoeren, moet u het gebruik van elektronisch bankieren instellen in [!INCLUDE[navnow](../../includes/navnow_md.md)].  

## <a name="correcting-payment-lines"></a>Betalingsregels corrigeren  
U moet alle fouten corrigeren voordat u de regels met elektronische betalingen kunt boeken. U kunt betalingsregels op de volgende manieren corrigeren.  

|Storno|Description|  
|----------------|---------------------------------------|  
|Een betalingsdagboekregel toevoegen|Als het betalingsdagboek al veel regels bevat en u nog een regel wilt toevoegen, kunt u de dagboekregel handmatig invoeren. U kunt dit bijvoorbeeld doen als u een creditnota wilt terugbetalen aan een klant. Dergelijke klantbetalingen worden niet automatisch voorgesteld door de batchverwerking **Leveranciersbetalingen voorstellen**.|  
|Een betalingsdagboekregel bewerken|Als u geen bankrekening aan het betalingsdagboek hebt toegewezen of als u geen bankrekening van voorkeur op de leverancierskaart hebt opgegeven, moet u deze gegevens handmatig op elke dagboekregel invoeren voordat u het dagboek boekt. Als u een bankrekening voor een leverancier opgeeft, wordt de bankrekening gekopieerd naar alle betalingsdagboekregels voor die leverancier. Zie [Procedure: Elektronisch bankieren instellen](how-to-set-up-electronic-banking.md) voor meer informatie.|  
|Een betalingsdagboekregel verwijderen|Met de batchverwerking **Leveranciersbetalingen voorstellen** maakt u betalingsvoorstellen voor alle leveranciers die overeenkomen met de opgegeven criteria. Als u de betaling voor een bepaalde leverancierspost of leverancier wilt voorkomen, kunt u de betreffende dagboekregels verwijderen.|  

Zie [Procedure: Regels voor elektronische betalingen beheren](how-to-manage-electronic-payment-lines.md) voor meer informatie.  

## <a name="see-also"></a>Zie ook  
 [Elektronisch bankieren voor België](belgian-electronic-banking.md)   
 [Procedure: Elektronisch bankieren instellen](how-to-set-up-electronic-banking.md)   
 [Procedure: IBLC-BLWI-transactiecodes instellen](how-to-set-up-iblc-blwi-transaction-codes.md)   
 [Procedure: Leveranciers voor automatische betalingsvoorstellen instellen](how-to-set-up-vendors-for-automatic-payment-suggestions.md)   
 [Procedure: Betalingsvoorstellen genereren](how-to-generate-payment-suggestions.md)   
 [Procedure: Betalingsdagboeksjablonen en -batches maken](how-to-create-payment-journal-templates-and-batches.md)   
 [Procedure: Elektronische betalingen testen](how-to-test-electronic-payments.md)   
 [Procedure: Regels voor elektronische betalingen beheren](how-to-manage-electronic-payment-lines.md)   
 [Procedure: Betalingsbestanden afdrukken](how-to-print-payment-files.md)

