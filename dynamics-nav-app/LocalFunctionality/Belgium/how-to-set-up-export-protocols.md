---
title: Exportprotocollen instellen
description: "Voordat u met elektronisch bankieren aan de slag kunt, moet u de exportprotocollen instellen. Exportprotocollen bepalen welke bestandsindeling wordt gegenereerd wanneer u de betaalrun exporteert die door de bank moet worden verwerkt. Elke regel bevat een exportprotocol dat door een code en een beschrijving wordt geïdentificeerd. U kunt zoveel exportprotocollen instellen als nodig is. U moet een exportprotocol voor binnenlandse betalingen, internationale betalingen en SEPA-betalingen binnen en buiten de eurozone instellen."
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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: a098c397ac5df5501c4c2d7d12cb2f74b2b50d63
ms.contentlocale: nl-be
ms.lasthandoff: 10/16/2017

---
# Procedure: Exportprotocollen instellen
Voordat u met elektronisch bankieren aan de slag kunt, moet u de exportprotocollen instellen. Exportprotocollen bepalen welke bestandsindeling wordt gegenereerd wanneer u de betaalrun exporteert die door de bank moet worden verwerkt. Elke regel bevat een exportprotocol dat door een code en een beschrijving wordt geïdentificeerd. U kunt zoveel exportprotocollen instellen als nodig is. U moet een exportprotocol voor binnenlandse betalingen, internationale betalingen en SEPA-betalingen binnen en buiten de eurozone instellen.  
  
 Met exportprotocollen kunt u de codeunit toewijzen waarmee de controle wordt gedefinieerd die moet worden uitgevoerd voordat de betalingsregels naar een bestand worden geëxporteerd. Daarnaast kunt u het rapport toewijzen waarmee de betalingsindeling wordt gedefinieerd. U kunt bijvoorbeeld een exportprotocol met de naam **DOM1** hebben. Dit exportprotocol bevat de codeunit voor de controle **Binnenlandse betalingen controleren** en het rapport **Binnenlandse betalingen indienen**. Elk exportprotocol omvat zowel een controlecodeunit als een bijbehorend rapport, zoals in de volgende tabel wordt weergegeven.  
  
|**Id controleobject**|**Id exportobject**|  
|-------------------------|--------------------------|  
|2000002 Binnenlandse betalingen controleren|Rapport 2000001 Binnenlandse betalingen indienen|  
|2000003 Internationale betalingen controleren|Rapport 2000002 Internationale betalingen indienen|  
|2000004 SEPA-betalingen controleren|Rapport 2000005 SEPA-betalingen indienen|  
|2000005 SEPA-betalingen in andere valuta's dan de euro controleren|Rapport 2000006 SEPA-betalingen in andere valuta's dan de euro indienen|  
|Als u deze optie niet wilt gebruiken, stelt u deze in op nul of gebruikt u een andere optie.|XMLport 1000 (SEPA pain.001.001.03-betalingen)|  
  
 Als u exportprotocollen hebt ingesteld, kunt u deze gebruiken in uw betalingsdagboeken voor elektronisch bankieren.  
  
### Een exportprotocol instellen  
  
1.  Kies het pictogram ![Zoeken naar pagina of rapport](media/ui-search/search_small.png "pictogram Zoeken naar pagina of rapport"), voer **Exportprotocollen** in en kies vervolgens de gerelateerde koppeling.  
  
2.  Kies op het tabblad **Start** in de groep **Nieuw** de optie **Nieuw**.  
  
3.  Vul in het venster **Exportprotocollen** de velden in zoals wordt beschreven in de volgende tabel.  
  
    |Veld|Description|  
    |---------------------------------|---------------------------------------|  
    |**Code**|Geef een code op om het exportprotocol uniek mee aan te duiden.|  
    |**Beschrijving**|Geef een omschrijving op voor de exportprotocolpost. U kunt maximaal 50 tekens invoeren (cijfers en/of letters).|  
    |**Codeonkosten**|Geef de code op om het onkostentype voor de exportprotocolpost te omschrijven. Tot de onkostencodes behoren **leeg**, **DEL**, **BEG** en **ONS**. Voor internationale betalingen is **DEL** de standaard.|  
    |**Id controleobject**|Geef het identificatienummer op van de codeunit die u wilt gebruiken om een controle op het object uit te voeren voordat het betalingsbestand wordt geëxporteerd.|  
    |**Naam controleobject**|Geef de naam op van een verificatieproces dat wordt gebruikt om een controle op het object uit te voeren voordat het betalingsbestand wordt geëxporteerd. Wanneer u **Id controleobject** selecteert, wordt in dit veld de **naam van het controleobject** weergegeven.|  
    |**Exportobjecttype**|Geef het objecttype op waarmee de exportindeling van de export van het betalingsbestand wordt bepaald. Wanneer u **Id exportobject** selecteert, wordt in dit veld het **type van het exportobject** weergegeven.<br /><br /> **OPMERKING:** als u het exportprotocol voor SEPA pain.001.001.03 wilt instellen, selecteert u **XMLPort**.|  
    |**Id exportobject**|Geef het identificatienummer op waarmee de exportindeling van de export van het betalingsbestand wordt bepaald. Als u **2000002** selecteert, is de exportindeling voor het betalingsbestand bijvoorbeeld **Internationale betalingen archiveren**.<br /><br /> **OPMERKING:** als u het exportprotocol voor SEPA pain.001.001.03 wilt instellen, selecteert u XMLport **1000**.|  
    |**Exportnr.-reeks**|Hiermee geeft u de nummerreekscode op die wordt gebruikt om id-nummers toe te wijzen aan de export van het betalingsbestand.|  
  
4.  Kies de knop **OK**.  
  
## Zie ook  
 [Belgische elektronische betalingen](belgian-electronic-payments.md)   
 Exportprotocollen   
 Exportprotocol   
 [Procedure: Betalingsdagboeksjablonen en -batches maken](how-to-create-payment-journal-templates-and-batches.md)   
 [Procedure: Elektronische betalingen testen](how-to-test-electronic-payments.md)
