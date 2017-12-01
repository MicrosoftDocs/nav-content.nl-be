---
title: Elektronisch bankieren instellen
description: Met elektronisch bankieren kunt u elektronische betalingen naar leveranciers en klanten in binnen- en buitenland, en SEPA-leveranciers en -klanten binnen en buiten de eurozone verzenden.
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
ms.openlocfilehash: 63ddc88627d5c3a9d6692d7e9573617da8aaea30
ms.contentlocale: nl-be
ms.lasthandoff: 10/23/2017

---
# <a name="how-to-set-up-electronic-banking"></a>Procedure: Elektronisch bankieren instellen
Met elektronisch bankieren kunt u elektronische betalingen naar leveranciers en klanten in binnen- en buitenland, en SEPA-leveranciers en -klanten binnen en buiten de eurozone verzenden.  

Uw bedrijf sluit een overeenkomst voor eBanking met de bank om een bepaalde bankrekening of verschillende bankrekeningen te gebruiken. Het bedrijf abonneert zich daarnaast op Isabel om via elektronische weg betalingsbestanden te verzenden naar en bankafschriftbestanden te ontvangen van de bank. Het bedrijf ontvangt smartcards die aan het eBanking-contract zijn gekoppeld. De smartcards zijn met pincodes beveiligd.  

U ontvangt een van deze smartcards om verbinding met IBS te maken, zodat u bent verbonden met eBanking-contract van het bedrijf.  

Als u bestanden wilt uploaden naar of downloaden van het IBS-platform, plaatst u de smartcard in de kaartlezer en gebruikt u een pincode om verbinding met IBS te maken. Wanneer de IBS-sessie is ingesteld, zijn het eBanking-contract en de eBanking-gebruiker bekend bij het systeem. Ook de aan het eBanking-contract en de gebruiker gekoppelde bankrekeningnummers zijn bekend.  

Voordat u met elektronisch bankieren kunt werken, moet u de volgende gegevens instellen:  

- Configuratie van elektronisch bankieren.  
- IBLC/BLWI-codes - Zie [Procedure: IBLC-BLWI-transactiecodes instellen](how-to-set-up-iblc-blwi-transaction-codes.md) voor meer informatie.  
- Bankrekeningen van voorkeur (optioneel).  

## <a name="to-set-up-electronic-banking"></a>Elektronisch bankieren instellen  

1.  Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **Elektronisch bankieren instellen** in en klik op de gerelateerde koppeling.  
2.  Vul in het venster **Elektronisch bankieren instellen** op het sneltabblad **Algemeen** de velden in zoals wordt beschreven in de volgende tabel.   

    |Veld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Alg. dagb.regels samenvatten**|Selecteer deze optie om aan te geven of u de betalingsdagboekregels voor elke leverancier wilt groeperen.|  
    |**Tekst van betaalberichten afbreken**|Selecteer deze optie om lange betaalberichten af te kappen. Berichten worden afgekapt als ze uit meer dan 106 tekens bestaan voor binnenlandse betalingen. Voor internationale betalingen is dit 140 tekens.|  
    |**IBS-versie**|Geef op welke versie van Isabel momenteel voor elektronisch bankieren in uw organisatie wordt gebruikt.|  
    |**E-mailadres voor berichten**|Geef het e-mailadres op dat u voor saldo- en transactieberichten wilt gebruiken voor elektronisch bankieren. Dit is het standaardadres dat wordt gebruikt om contact te maken met de Isabel-server.|  
    |**Taal**|Geef de taal op die u voor saldo- en transactieberichten wilt gebruiken voor elektronisch bankieren.|  
    |**IBS-serviceversie**|Geef de serviceversie op waarmee wordt gecommuniceerd met de Isabel-server.|  

3.  Vul op het sneltabblad **Uploaden** de velden in zoals in de volgende tabel wordt beschreven.   

    |Veld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Uploadintegratiemodus**|Geef de modus op waarin u inhoud naar de Isabel-server wilt uploaden. U kunt kiezen uit de integratiemodusopties **Met toezicht** en **Handmatig**. Als de integratiemodus is ingesteld op **Met toezicht**, moet u het veld **IBS-versie** instellen op **6**. De posten in de tabel **IBS-logboek** worden gemaakt wanneer er betalingsbestanden worden gegenereerd. Als de integratiemodus is ingesteld op **Handmatig**, moet u zich handmatig aanmelden bij de Isabel-server en worden er geen logposten gemaakt.|  
    |**Uploadpad**|Geef het pad op naar de map waarin de bestanden worden opgeslagen tijdens het uploaden.|  

4.  Vul op het sneltabblad **Downloaden** de velden in zoals in de volgende tabel wordt beschreven.   

    |Veld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Downloadintegratiemodus**|Geef de modus op waarin u inhoud naar de Isabel-server wilt downloaden. U kunt kiezen uit de opties **Met toezicht** en **Handmatig**. Als de integratiemodus is ingesteld op **Met toezicht**, moet u het veld **IBS-versie** instellen op **6**. De posten in de tabel **IBS-logboek** worden gemaakt wanneer de download wordt uitgevoerd. Als de integratiemodus is ingesteld op **Handmatig**, moet u zich handmatig aanmelden bij de Isabel-server en worden er geen logposten gemaakt.|  
    |**Downloadpad**|Geef het pad op naar de map waarin de bestanden worden opgeslagen tijdens het downloaden.|  

5.  Vul op het sneltabblad **Nummering** de velden in zoals in de volgende tabel wordt omschreven.   

    |Veld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Uploadnrs. IBS-logboek**|Geef de nummerreeks op die moet worden gebruikt voor Isabel-logposten die worden gemaakt tijdens het uploaden van bestanden.|  
    |**Downloadnrs. IBS-logboek**|Geef de nummerreeks op die moet worden gebruikt voor Isabel-logposten die worden gemaakt tijdens het downloaden van bestanden.|  
    |**Aanvraag-ID IBS**|Geef een nummerreeks op voor een automatische en unieke nummering van de aanvragen.|  

6.  Kies de knop **OK**.  

U kunt ook bankrekeningen aan elke klant en leverancier toewijzen. Zo kunt u elektronische betalingen eenvoudiger maken. In de volgende procedure wordt uitgelegd hoe u gewenste bankrekeningen toewijst aan klanten, maar u kunt dezelfde stappen voor leveranciers gebruiken.  

## <a name="to-add-a-preferred-bank-account-to-a-customer"></a>Een gewenste bankrekening aan een klant toevoegen  

1.  Klik op het pictogram ![Zoeken naar pagina of rapport](../../media/ui-search/search_small.png "Pictogram Zoeken naar pagina of rapport"), voer **Klanten** in en klik vervolgens op de gerelateerde koppeling.  
2.  Selecteer een klant en kies vervolgens de actie **Bewerken**.  
3.  Voer op het sneltabblad **Betalingen** een bankrekening in bij **Bankrekening van voorkeur** en kies de knop **OK**.  

    > [!NOTE]  
    >  Voor alle betalingen gebruikt u één bankrekening voor elke klant of leverancier.  

4.  Kies de knop **OK**.  

## <a name="see-also"></a>Zie ook  
 [Isabel-website](http://go.microsoft.com/fwlink/?LinkId=210323)   
 [Elektronisch bankieren voor België](belgian-electronic-banking.md)   
 [Belgische elektronische betalingen](belgian-electronic-payments.md)   
 [Procedure: IBLC-BLWI-transactiecodes instellen](how-to-set-up-iblc-blwi-transaction-codes.md)   
 [Procedure: Leveranciers voor automatische betalingsvoorstellen instellen](how-to-set-up-vendors-for-automatic-payment-suggestions.md)   
 [Procedure: Betalingsvoorstellen genereren](how-to-generate-payment-suggestions.md)   
 [Procedure: Betalingsdagboeksjablonen en -batches maken](how-to-create-payment-journal-templates-and-batches.md)   
 [Procedure: Elektronische betalingen testen](how-to-test-electronic-payments.md)   
 [Procedure: Regels voor elektronische betalingen beheren](how-to-manage-electronic-payment-lines.md)   
 [Procedure: Betalingsbestanden afdrukken](how-to-print-payment-files.md)

