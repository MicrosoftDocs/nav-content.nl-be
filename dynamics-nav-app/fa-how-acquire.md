---
title: 'Procedure: Vaste activa aanschaffen'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 5b58a6cf0a0c22c8076082328f92725cb7dbc4d1
ms.contentlocale: nl-be
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-acquire-fixed-assets"></a>Procedure: Vaste activa aanschaffen
Voor elk vast activum moet u een kaart maken met informatie over het activum. U kunt gebouwen of productiemateriaal instellen als een hoofdactivum met een onderdelenlijst en u kunt ze op verschillende manieren groeperen, bijvoorbeeld per categorie, afdeling of locatie. Een afschrijvingsboek moeten eerst worden ingesteld en toegewezen aan elk vast activum voordat u het kunt aanschaffen.

Wanneer een vast activum is ingesteld en een afschrijvingsboek is toegewezen, moet u het vaste activum aanschaffen. Als u een vast activum wilt aanschaffen, registreert u de bijbehorende aanschafkosten in de betreffende grootboekrekening, bankrekening of leverancier door een aanschaftransactie te boeken in het venster **Financieel dagboek voor vaste activa**. U kunt het venster **voor begeleide aanschaf van vaste activa** gebruiken om de vereiste dagboekregels automatisch te maken en te boeken.

De restwaarde is de resterende waarde van een vast activum als dit niet langer meer kan worden gebruikt. U kunt de restwaarde tegelijk met het boeken van de aanschafkosten boeken. Zie [Procedure: Vaste activa afschrijven of aflossen](fa-how-depreciate-amortize.md) voor meer informatie.

Indexering wordt gebruikt om waarden aan te passen voor algemene prijswijzigingen. De batchverwerking **Vast activum indexeren** kan worden gebruikt om de aanschafkosten te berekenen bij vervangingskosten.

## <a name="to-create-a-fixed-asset-and-acquire-it-automatically"></a>Een vast activum maken en automatisch aanschaffen
In de volgende procedure wordt beschreven hoe u een vast activum kunt maken en vervolgens kunt aanschaffen met het venster **voor begeleide aanschaf van vaste activa** om de vereiste dagboekregels voor vaste activa te maken en te boeken. U kunt de dagboekregels ook handmatig maken en boeken. Zie het gedeelte "De aanschaf van een vast activum handmatig boeken met het financieel dagboek voor vaste activa" voor meer informatie.

1. Kies in de rechterbovenhoek het pictogram **Zoeken naar pagina of rapport**, voer **Vaste activa** in en kies vervolgens de gerelateerde koppeling.  
2. Kies de actie **Nieuw** en vul vervolgens indien nodig de velden op het sneltabblad **Algemeen** in. Kies een veld om een korte omschrijving van het veld of een koppeling naar meer informatie te lezen.
3. Vul op het sneltabblad **Afschrijvingsboek** indien nodig de velden in. Met deze stap wordt een afschrijvingsboek aan het vaste activum toegewezen.  
4. Als u meer dan één afschrijvingsboek aan het vaste activum moet toewijzen, kiest u de actie **Meer afschrijvingsboeken toevoegen**. Zie het gedeelte "Een afschrijvingsboek aan een vast activum toewijzen" in [Procedure: Afschrijving van vaste activa instellen](fa-how-setup-depreciation.md) voor meer informatie.

    Wanneer alle velden die nodig zijn om een vast activum aan te schaffen zijn ingevuld, verschijnt boven aan de pagina de melding dat **u het vaste activum nu kunt aanschaffen**.
5. Kies de actie **Aanschaffen** in de melding.
6. Voer de stappen in het venster **voor begeleid aanschaffen van vaste activa** uit om de automatische aanschaffing van het vaste activum te voltooien.

**Opmerking**: u kunt aanschafkosten ook als creditbedragen boeken. In dat geval moet u er rekening mee houden dat de waarde in het veld **Aanschafkosten inclusief BTW** met een minteken moet worden ingevuld om een creditbedrag aan te geven.

Wanneer u **Voltooien** kiest, wordt het veld **Boekwaarde** in het venster **Vast activum** ingevuld waarmee wordt aangegeven dat het vaste activum met de opgegeven aanschafkosten is aangeschaft.  

## <a name="to-set-up-a-component-list-for-a-main-asset"></a>Een onderdelenlijst instellen voor een hoofdactivum  
U kunt vaste activa groeperen in hoofdactiva en hun onderdelen. U kunt bijvoorbeeld een productiemachine hebben die uit vele onderdelen bestaat die u op deze manier wilt groeperen.  

Zowel het hoofdactivum als alle onderdelen moeten als individueel vast activum worden ingesteld. Nadat u een onderdelenlijst hebt ingesteld, worden in Dynamics NAV automatisch de velden **Hoofdactivum/onderdeel** en **Onderdeel van hoofdactivum** voor het vaste activum ingevuld.

1. Kies in de rechterbovenhoek het pictogram **Zoeken naar pagina of rapport**, voer **Vaste activa** in en kies vervolgens de gerelateerde koppeling.
2. Selecteer het vaste activum dat het hoofdactivum is en kies vervolgens de actie **Onderdelen van hoofdactivum**.
3. Kies in het venster **Onderdelen van hoofdactivum** het veld **VA-nr.** en selecteer vervolgens het vaste activum dat u als onderdeel van het hoofdactivum wilt toevoegen.
4. Sluit het venster.
5. Herhaal stap 3 en 4 voor elk onderdeelactivum dat u wilt toevoegen.
6. Kies in de rechterbovenhoek het pictogram **Zoeken naar pagina of rapport**, voer **VA-instellingen** in en kies vervolgens de gerelateerde koppeling.
7. Schakel het selectievakje **Boeken op hoofdactivum toegestaan** in.

## <a name="to-post-a-fixed-asset-acquisition-manually-with-the-fixed-asset-gl-journal"></a>Een aanschaf voor vaste activa handmatig boeken met het financieel dagboek voor vaste activa
In de volgende procedure wordt beschreven hoe u een vast activum handmatig kunt aanschaffen door regels te maken en te boeken het venster **Financieel dagboek voor vaste activa**. U kunt een vast activum ook automatisch aanschaffen door het venster **voor begeleide aanschaf van vaste activa** te gebruiken. Zie stap 5 in het gedeelte "Een vast activum maken en het automatisch aanschaffen" voor meer informatie.

**Opmerking**: u kunt aanschafkosten ook als creditbedragen boeken. In dat geval moet u er rekening mee houden dat de waarde in het veld **Bedrag** met een minteken moet worden ingevuld om een creditbedrag aan te geven.

1. Kies in de rechterbovenhoek het pictogram **Zoeken naar pagina of rapport**, voer **Financieel dagboek voor vaste activa** in en kies vervolgens de gerelateerde koppeling.
2. Selecteer in het venster **Financieel dagboek voor vaste activa** in het veld **VA-boekingssoort** **Aanschafkosten**.
3. Vul indien nodig de resterende velden in.
4. Kies de actie **Boeken**.  

**Tip**: als u tijdens het boeken van de aanschafkosten het veld **Verzekeringsnr.** invult in het financieel dagboek voor vaste activa, worden de aanschafkosten van het vaste activum in Dynamics NAV ook naar de dekkingsposten geboekt. Zie [Procedure: Vaste activa verzekeren](fa-how-insure.md) voor meer informatie.

## <a name="to-cancel-an-acquisition-cost-posting-for-one-fixed-asset"></a>De boeking van aanschafkosten voor één vast activum annuleren
Als u een fout maakt wanneer u aanschafkosten boekt, kunt u de post verwijderen met de batchverwerking **VA-posten annuleren** en vervolgens de juiste aanschafpost boeken. De foutieve posten worden overgebracht naar het venster **Foutieve VA-posten**.

Als u bijvoorbeeld een aanschaf met een onjuiste datum boekt, moet u dit zo snel mogelijk corrigeren omdat de boekingsdatum van een vast activum in vele belangrijke berekeningen wordt gebruikt.

**Belangrijk**: u kunt de functie **Transacties tegenboeken** niet voor VA-posten gebruiken.

1. Kies in de rechterbovenhoek het pictogram **Zoeken naar pagina of rapport**, voer **VA-posten annuleren** in en kies vervolgens de gerelateerde koppeling.
2. Vul indien nodig de velden in. Kies een veld om een korte omschrijving van het veld of een koppeling naar meer informatie te lezen.
3. Kies **OK** om de batchverwerking te starten.
4. Als de foutieve post of posten zijn geannuleerd, gaat u verder met het boeken van de juiste aanschafkosten.

Als u posten voor meerdere vaste activa tegelijk wilt annuleren, gebruikt u de batchverwerking **VA-posten annuleren**.

## <a name="to-post-the-salvage-value-together-with-the-acquisition-cost"></a>De restwaarde samen met de aanschafkosten boeken  
Het is mogelijk om de restwaarde samen met de aanschafkosten te boeken via een financieel dagboek voor vaste activa.    

1. Kies in de rechterbovenhoek het pictogram **Zoeken naar pagina of rapport**, voer **VA-posten annuleren** in en kies vervolgens de gerelateerde koppeling.
2. Maak de dagboekregel van de aanschaf. Zie het gedeelte "De aanschaf van een vast activum handmatig boeken met het financieel dagboek voor vaste activa" voor meer informatie.
3. Voer de restwaarde in als een creditbedrag (met een minteken) in het veld **Restwaarde** op de dagboekregel.
4. Kies de actie **Boeken**.

**Opmerking**: Het boekingssoort **Restwaarde** is uitsluitend een optie in het **Financieel dagboek voor vaste activa**. Het is niet beschikbaar in het venster **Financieel dagboek voor vaste activa** omdat de restwaarde nooit naar het grootboek wordt geboekt.

## <a name="see-also"></a>Zie ook
[Vaste activa beheren](fa-manage.md)  
[Vaste activa instellen](fa-setup.md)  
[Financiën](finance-setup.md)  
[Welkom bij Dynamics NAV](across-get-started.md)
