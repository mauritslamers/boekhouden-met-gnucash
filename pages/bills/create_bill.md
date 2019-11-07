---
layout: page
title: Nieuwe Inkoopfactuur
permalink: /new_bill
parent: Inkoopfacturen
nav_order: 2
---

**Let op:** In de huidige versies van GnuCash zit een bug waardoor de tekst bij de knoppen in dit venster niet de juiste vertaling krijgen.
Je ziet dus steeds "Verkoopfactuur" staan, maar dit moet "Inkoopfactuur" zijn voor alle knoppen in de werkbalk. De knoppen werken echter correct.
In deze handleiding gaan we uit van de correcte vertaling.

## Inkoopfactuur invoeren
Kies menu "MKB", submenu "Leverancier" en vervolgens de optie "Nieuwe inkoopfactuur".

Je krijgt nu het dialoogvenster "Nieuwe inkoopfactuur".

![Dialoogvenster nieuwe inkoopfactuur]({{site.baseurl}}/assets/create_bill_dialog.png)

Je vult nu de volgende zaken in:

* **Inkoopfactuurnummer**: Het factuurnummer of nummer van de kassabon
* **Documentdatum**: De factuurdatum of datum van de kassabon
* **Leverancier**: De naam van de leverancier. Als je de leverancier al hebt aangemaakt, hoef je alleen de eerste letters van de naam te typen.

Als je veel eenmalige leveranciers hebt, is het een optie om een leverancier "Algemeen" aan te maken. Je hoeft dan niet elke eenmalige leverancier
in te voeren. Hierdoor heb je wel minder inzicht in wat je per leverancier hebt afgenomen.

Klik op OK

Je krijgt nu het scherm waarin je de items op de inkoopfactuur kunt invoeren.

![Invoer items op inkoopfactuur]({{site.baseurl}}/assets/enter_bill_items.png)

We voeren per item het volgende in:

* **Datum**: Factuurdatum
* **Omschrijving**: Een korte omschrijving van de kosten
* **Kostenrekening**: Kies een kostenrekening die de Belastingdienst voorschrijft voor dit type kosten. Omdat in deze handleiding de grootboekrekeningen
  (kostenrekeningen zijn ook grootboekrekeningen) volgens de indeling van de inkomstenbelasting en BTW-aangifte hebben aangemaakt, kunnen we de richtlijnen van de
  Belastingdienst volgen. Zo zorg je ervoor dat je de gegevens uit je boekhouding eenvoudig kunt overnemen in de belastingaangiftes.
  In het aangifteprogramma ondernemers, de aangifte van de omzetbelasting en op de website van de Belastingdienst is voor elk type uitgave een duidelijke toelichting beschikbaar.
* **Hoeveelheid**: Het aantal producten of stuks dat je hebt afgenomen
* **Prijs per eenheid**: Prijs per afgenomen product of dienst
* **Belastbaar**: Dit moet aangevinkt staan indien voor het item BTW is gerekend.
* **Belastingtarief**: Kies voor "Omzetbelasting inkopen 21%" voor de items waarvoor 21% BTW wordt gerekend, "Omzetbelasting inkopen 9%" voor de items waarvoor 9%
  BTW wordt gerekend. Neem deze zaken over van de inkoopfactuur of kassabon.

Onderaan in het venster zie je het Totaal, Subtotaal en BTW van wat je hebt ingevoerd. Check of dit overeenkomt met wat op de inkoopfactuur of kassabon staat.
Kies "Vastleggen" als het klopt.

## Inboeken

Nu de gegevens van de inkoopfactuur zijn ingevoerd, verwerken we de inkoopfactuur in de boekhouding.
Klik op het "&#9662;-menu", en kies daar "Inkoopfactuur boeken".

![Dialoogvenster Inkoopfactuur inboeken]({{site.baseurl}}/assets/book_bill_confirm_dialog.png)

Vul hier het volgende in:

* **Boekdatum**: de factuurdatum
* **Vervaldatum**: De dag waarop de factuur uiterlijk betaald moet zijn. Bij contante betalingen kun je de datum hetzelfde laten.
* **Omschrijving**: Kun je leeg laten
* **Naar rekening boeken**: Inkoopfacturen zijn altijd "140 Crediteuren".

Als alles klopt kies je OK.

