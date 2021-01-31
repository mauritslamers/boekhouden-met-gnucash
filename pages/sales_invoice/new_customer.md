---
layout: page
title: Nieuwe klant
permalink: /new_customer
parent: Verkoopfacturen
nav_order: 1
---

## Klant aanmaken

Als je nog geen klanten in je systeem hebt zitten, maken we eerst een klant aan.
Kies het menu "MKB", de optie "Klant", en vervolgens de optie "Nieuwe klant...".

![Menu nieuwe klant]({{site.baseurl}}/assets/menu_new_customer.png)

Voor je de velden gaat invullen, is het belangrijk dat je weet welk klantnummer
deze klant gaat krijgen.

Als je al facturen hebt verstuurd met klantnummers en
je wilt doornummeren vanaf een bepaald klantnummer, kies dan menu "Bestand", optie "Eigenschappen"
en kies het tabblad "Tellers". Hier vul je het laatste klantnummer in in het veld
"Klantnummer". Als dat nummer 4587 is, zal de eerstvolgende nieuwe klant automatisch klantnummer
4588 krijgen.

Als je nog geen boekhouding hebt, kun je zelf een nummer kiezen. Wanneer je niets invult,
begint GnuCash bij 1. De volgende klant krijgt dan nummer 2 enzovoorts.

Vul nu de volgende velden in:

* **Klantnummer**: Indien dit een bestaande klant is, vul het nummer in. Indien niet, laat het leeg zodat GnuCash zelf het eerstvolgende nummer invult.
* **Bedrijfsnaam**: De bedrijfsnaam van de klant
* **Actief**: Dit staat standaard aangevinkt, en het is belangrijk dat ook zo blijft.
* **Naam**: Naam van de contactpersoon bij deze klant.
* **Adres**: Adres van het bedrijf: straat, huisnummer, postcode en plaats.
* **Telefoon**: Mag leeg gelaten worden
* **Fax**: Mag leeg gelaten worden
* **E-mail**: Mag leeg gelaten worden
* **Toelichting**: Mag leeg gelaten worden.

De velden Klantnummer, Bedrijfsnaam, Naam en Adres komen standaard op de factuur te staan.

![Nieuwe klant]({{site.baseurl}}/assets/new_customer_dialog.png)

Het tweede tabblad van dit dialoogvenster bestaat uit een aantal gegevens rondom facturen aan deze klant.
Het is in het begin (nog) niet nodig deze gegevens te wijzigen.

![Nieuwe klant factuurgegevens]({{site.baseurl}}/assets/new_customer_invoice_properties_dialog.png)

Een kleine uitleg:
* **Voorwaarden**: hier kun je de standaard betalingsvoorwaarden voor deze klant instellen. Bij [Verkoopvoorwaarden instellen]({{site.baseurl}}/sales_invoice/betalingsvoorwaarden) hebben we al laten zien hoe dat gaat.
* **Korting**: Hier kun je de standaard korting invoeren voor deze klant. Je kunt ook per artikel korting opgeven bij het invoeren van de factuur.
* **Kredietlimiet**: Het maximum bedrag dat deze klant aan openstaande facturen mag hebben.
* **Inclusief belasting**: Zijn de verkopen voor deze klant inclusief of exclusief BTW? Je kunt dit ook per artikel invoeren op de factuur.
* **Belastingtarief**: Je kunt hier het standaard belastingtarief voor deze klant kiezen. Je kunt ook eenvoudig per artikel het BTW-tarief opgeven.

Het tabblad "Verzendadres" kun je gebruiken om een verzendadres in te voeren. Dit komt niet op de factuur te staan, en is alleen voor je eigen administratie.

Klik op OK om de klant op te slaan.

Als je nog geen betalingsvoorwaarden hebt aangemaakt, ga je verder naar [Betalingsvoorwaarden aanmaken]({{site.baseurl}}/betalingsvoorwaarden).


