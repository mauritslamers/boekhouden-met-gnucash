---
layout: page
title: Nieuwe verkoopfactuur maken
permalink: /sales_invoice/create_sales_invoice
parent: Verkoopfacturen
nav_order: 3
---

## Tellers goedzetten

Als je al facturen hebt gemaakt en je wilt doornummeren vanaf een bepaald nummer, pas dan eerst de tellers aan.
Kies hiervoor de optie "Eigenschappen" uit het menu "Bestand", en ga naar het tabblad "Tellers".
Hier vul je het laatste factuurnummer in in het veld "Verkoopfactuurnummer".
Als je laatste factuur het factuurnummer 20190264 heeft, vul dan 20160264 in. De eerstvolgende factuur
waarvoor je zelf het factuurnummer niet invult krijgt dan automatisch het nummer 20190265.

## Nieuwe verkoopfactuur maken

Klik in de werkbalk op "Nieuwe verkoopfactuur..." of ga naar menu "MKB", optie "Klant" en suboptie "Nieuwe verkooopfactuur...".

![Knop Nieuwe verkoopfactuur op de werkbalk]({{site.baseurl}}/assets/toolbar_new_invoice.png)

![Menu MKB > Klant > Nieuwe verkoopfactuur]({{site.baseurl}}/assets/menu_new_invoice.png)

Je krijgt nu het dialoogvenster "Nieuwe verkoopfactuur".

![Dialoogvenster Nieuwe verkoopfactuur]({{site.baseurl}}/assets/new_sales_invoice_dialog.png)

Vul hier het volgende in:

* **Factuurnummer**: Dit kun je leeg laten als je GnuCash automatisch het eerstvolgende factuurnummer wilt laten kiezen.
* **Documentdatum**: De datum van de factuur. Staat automatisch op de huidige datum.
* **Klant**: Type (een gedeelte van) de naam van de klant.
* **Opdracht**: Hoef je niet in te vullen
* **Kenmerk**: Een veld dat op de factuur komt te staan. Dit kun je leeg laten.
* **Voorwaarden**: Je kunt voor deze factuur een betalingsvoorwaarde kiezen.
* **Toelichting**: Hier kun je een opmerking invullen. Deze tekst komt onderaan de factuur te staan.

Klik op OK.

Je krijgt nu het invoervenster van de items op de factuur te zien.

![Invoervenster nieuwe factuur]({{site.baseurl}}/assets/new_invoice_item_list.png)

Je kunt nu voor elk item op de factuur een regel invoeren.
Je vind hieronder een aantal verschillende mogelijkheden, die je ook kunt combineren.

### Item exclusief BTW
Het item exclusief BTW komt het meest voor. Dit zijn de velden die je invult:

* **Datum**: Hier staat automatisch de datum van de factuur ingevuld. Je kunt deze datum aanpassen indien het item dat je invult betrekking heeft op een andere dag.
* **Omschrijving**: Vul hier de omschrijving in van het product of de dienst die je hebt geleverd.
* **Opbrengstenrekening**: Kies de grootbankrekening die hoort bij het BTW-tarief. Als je een product of dienst levert waar je 21% BTW over berekent, kies dan de grootboekrekening "800 Omzet 21% omzetbelasting". Bij een product of dienst met 9% BTW hoort de grootboekrekening "801 Omzet 9% omzetbelasting" en bij een product met 0% BTW hoort "802 Omzet 0% omzetbelasting".
* **Hoeveelheid**: Het aantal eenheden, bijvoorbeeld 8 (uur) of 1 (stuk).
* **Prijs per eenheid**: De verkoopprijs exclusief BTW
* **Belastbaar**: Zorg dat dit veld staat aangevinkt op het moment dat het een belast product is. Vul je dit niet in, kun je bij het volgende veld geen belastingtarief kiezen!
* **Belastingtarief**: Het BTW-tarief waaronder dit item valt. Kies "Omzetbelasting verkopen 21%" voor producten waarover 21% BTW gerekend moet worden, "Omzetbelasting verkopen 9%" voor de producten waarover 9% BTW gerekend moet worden en bij verkopen met 0% BTW laat je dit veld leeg.

De velden Subtotaal en BTW worden automatisch berekend op basis van het gekozen BTW-tarief en de andere gegevens in deze regel.

### Item inclusief BTW
Het komt soms voor dat je liever een rond bedrag onder aan de streep hebt staan. Vul in dat geval alles in zoals bij het item exclusief BTW, maar vul bij "Prijs per eenheid" het bedrag in inclusief BTW, en selecteer "Inclusief belasting".
Het subtotaal en BTW worden nu automatisch terugberekend uit het "totaalbedrag".

### Item met korting
Als je korting wilt geven op een bepaald item kies je eerst wat voor soort korting je wilt geven, namelijk een percentage (aangegeven met "%") of een geldbedrag
(aangegeven met € of het symbool van de valuta-soort van je factuur). Je kunt tussen deze twee opties schakelen door op de "%" of valuta-symbool te klikken.
Je vult vervolgens een percentage in of een geldbedrag in het veld "Korting".


## Factuurgegevens aanpassen
Je kunt het factuurnummer, documentdatum, klant of voorwaarden niet wijzigen in het invoervenster.
Om deze te wijzigen, kies "Verkoopfactuur bewerken" uit de werkbalk.
Nu krijg je het dialoogvenster te zien dat we hiervoor ook al gezien hebben.
Het veld Toelichting kun je wel in het invoervenster wijzigen.

## Verkoopfactuur controleren

Door op de knop "Verkoopfactuur afdrukken" in de werkbalk te klikken, krijg je een overzichtsvenster van de factuur te zien.
Je kunt dit venster ook openen via het menu "Bestand" en de optie "Verkoopfactuur afdrukken".

![Ongeboekte verkoopfactuur printvoorbeeld]({{ site.baseurl }}/assets/unbooked_sales_invoice_print.png)

Je ziet dat in dit voorbeeld de bedrijfsgegevens nog niet zijn ingevuld. Mocht je dat nog niet gedaan hebben, vul deze gegevens in.
Sluit het tabblad "Belastingfactuur" en volg de instructies bij [Bedrijfsgegevens invoeren]({{site.baseurl}}/company_info).

## Verkoopfactuur verwerken
Als je tevreden bent over de inhoud van de factuur, klik dan op de knop "&#9662;". Dit toont extra opties die niet op de werkbalk passen.

![uitklap-menu verkoopfactuur]({{site.baseurl}}/assets/arrow_menu_invoice.png)

Kies daar voor de optie "Verkoopfactuur boeken". Je krijgt nu een dialoogvenster.

![Bevestiging boeking verkoopfactuur]({{site.baseurl}}/assets/sales_invoice_confirm_dialog.png)

Vul hier het volgende in:

* **Boekdatum**: de datum waarop de factuur in de boekhouding komt te staan
* **Vervaldatum**: deze datum wordt automatisch berekend op basis van de voorwaarden (in dit geval 14 dagen)
* **Omschrijving**: Dit kun je leeg laten
* **Naar rekening boeken**: Laat dit op "130 Debiteuren" staan.

Klik OK om de factuur te boeken.



