---
layout: page
title: Bestaande openingsbalans
permalink: /opening_balance/existing_balance
parent: Openingsbalans
nav_order: 2
---

## Openingsbalans als je al wel boekhouding hebt

Op het moment dat je je boekhouding overbrengt naar GnuCash is het belangrijk dat
je vanaf de eerder gekozen datum alleen maar zaken invoert in GnuCash en niet in
meer de andere systemen die je tot nu toe gebruikt hebt.
Dat geldt voor alle facturen, alle bankmutaties en betalingen vanaf die datum.

Alle zaken voor die datum voer je nog wel in in je oude systeem.

### Proefbalans of saldibalans
Genereer in je oude boekhouding een proefbalans (of saldibalans, dat is hetzelfde) per de gekozen datum.
Die proefbalans ga je gebruiken voor het invoeren van de openingsbalans in GnuCash.
Voor dit voorbeeld gebruiken we de onderstaande proefbalans.

| Rekeningnaam                                     | Rekeningsoort   | Debet | Credit |
|:-------------------------------------------------|:----------------|------:|-------:|
| 010 Bedrijfsgebouwen en terreinen                | Activa          |   220 |        |
| 020 Machines en installaties                     | Activa          |   180 |        |
| 040 Eigen vermogen                               | Eigen vermogen  |       |  1550  |
| 041 Privéstortingen                              | Eigen vermogen  |       |   150  |
| 042 Privéonttrekkingen                           | Eigen vermogen  |    50 |        |
| 070 Schulden                                     | Vreemd vermogen |       |   160  |
| 100 Kas                                          | Contant         |    60 |        |
| 110 Bank                                         | Bank            |   200 |        |
| 130 Debiteuren                                   | Debiteuren      |   800 |        |
| 140 Crediteuren                                  | Crediteuren     |       |    440 |
| 180 Vordering omzetbelasting                     | Activa          |   140 |        |
| 185 Schuld omzetbelasting 21%                    | Vreemd vermogen |       |     90 |
| 186 Schuld omzetbelasting 9%                     | Vreemd vermogen |       |     45 |
| 187 Schuld omzetbelasting overig (geen 0%)       | Vreemd vermogen |       |     15 |
| 188 Schuld omzetbelasting 0%                     | Vreemd vermogen |       |      0 |
| 189 Schuld omzetbelasting naar mij verlegd       | Vreemd vermogen |       |     50 |
| 400 Inkoopprijs materialen en voorraad           | Kosten          |  1800 |        |
| 410 Kosten van uitbesteed werk                   | Kosten          |  1200 |        |
| 430 Afschrijvingskosten gebouwen en terreinen    | Kosten          |    10 |        |
| 440 Afschrijvingskosten machines en installaties | Kosten          |    25 |        |
| 450 Auto- en transportkosten                     | Kosten          |   170 |        |
| 460 Huisvestingskosten                           | Kosten          |    60 |        |
| 470 Onderhoudskosten                             | Kosten          |    85 |        |
| 480 Verkoopkosten + reclame + marketing          | Kosten          |   125 |        |
| 490 Andere/overige kosten                        | Kosten          |   145 |        |
| 495 Rente + bankkosten                           | Kosten          |    30 |        |
| 700 Voorraden                                    | Activa          |  1200 |        |
| 800 Omzet 21% omzetbelasting                     | Opbrengsten     |       |   2700 |
| 801 Omzet 9% omzetbelasting                      | Opbrengsten     |       |    850 |
| 802 Omzet 0% omzetbelasting                      | Opbrengsten     |       |    450 |
|--------------------------------------------------|-----------------| ----- | ------ |
|                                                  |                 |  6500 |   6500 |

Open GnuCash en selecteer op het tabblad Rekeningen de grootboekrekening waarvoor je het
beginsaldo wilt invoeren. We kiezen nu de eerste grootboekrekening "Bedrijfsgebouwen en terreinen".
Hierop moet een beginsaldo van € 220 komen te staan.

Kies uit het menu "Acties" de optie "Afstemmen".

![menu Acties, optie Afstemmen]({{site.baseurl}}/assets/menu_acties_afstemmen.png)

Vul nu in het dialoogvenster bij Eindsaldo € 220 in.

![Afstemmen bedrijfsgebouwen dialoogvenster]({{site.baseurl}}/assets/bedrijfsgebouwen_afstemmen_dialog.png)

Het venster Afstemmen is nog leeg. Rechtsonder zie je bij het eindsaldo dat je hiervoor hebt ingevoerd.
Klik op "In balans brengen".

![Bedrijfsgebouwen afstemmen]({{site.baseurl}}/assets/bedrijfsgebouwen_afstemmen.png)

De grootboekrekening "Bedrijfsgebouwen en terreinen" wordt nu geopend. Vul hier in de datum van de beginbalans,
als omschrijving "Beginbalans" en kies onder Overboeken de rekening "Eigen vermogen". Gebruik hiervoor altijd
de grootboekrekening "Eigen vermogen"!

De rest kun je ongewijzigd laten.

Kies nu "Vastleggen".

![Bedrijfsgebouwen beginbalans]({{site.baseurl}}/assets/bedrijfsgebouwen_beginbalans.png)

Ga weer terug naar het scherm "Afstemmen". Dit staat zeer waarschijnlijk nog open, mogelijk achter het hoofdvenster van GnuCash.
Indien dat niet het geval is, selecteer onder "Rekeningen" opnieuw de grootboekrekening, en kies opnieuw de optie "Afstemmen" in het
menu "Acties".

Vink nu de inkomende geldstroom aan. Je ziet nu dat het verschil rechtsonder € 0 geworden is.

![Bedrijfsgebouwen afstemmen met geldstroom]({{site.baseurl}}/assets/bedrijfsgebouwen_geldstroom.png)

Nu dit beginsaldo klopt en er geen verschil meer is, kies je "Afronden" via het
menu "Afstemmen" of via het "&#9662;"-menu.

Selecteer nu de grootboekrekening "Eigen vermogen" en kies ook hiervoor de optie "Afstemmen" uit het "Acties" menu.
Je zult zien dat het beginsaldo hier ook nog op € 0 staat en het eindsaldo al ingevuld is. Kies OK.

![Dialoogvenster afstemmen Eigen vermogen]({{site.baseurl}}/assets/eigenvermogen_afstemmen_dialog.png)

Markeer in het scherm Afstemmen het beginsaldo. Het verschil rechtsonder wordt nu € 0.

![Eigenvermogen afstemmen]({{site.baseurl}}/assets/eigenvermogen_afstemmen.png)

Nu dit beginsaldo klopt en er geen verschil meer is, kies je "Afronden" via het
menu "Afstemmen" of via het "&#9662;"-menu.

Als je nu de grootboekrekening opnieuw selecteert en kiest voor afstemmen, zul je zien dat het beginsaldo klopt
en er niets meer staat in het venster "Afstemmen".

Herhaal de bovenstaande stappen voor elk bedrag van de openingsbalans om een beginsaldo te
genereren. Alleen "Eigen vermogen" met het bedrag van € 1550 voer je niet in. Dit is namelijk het totaal
van alle andere invoeren samen (debet en credit).
Let er bij de rekening "Privé-onttrekkingen" op dat je het bedrag negatief invult, zodat het aan de debet-kant valt
van de balans.

### Debiteuren
De debiteuren van totaal € 800 bestaat uit twee openstaande verkoopfacturen, namelijk klant Hopman voor € 450 en
klant Petersen voor € 350.

Open nu de grootboekrekening "Debiteuren" en voer voor elke factuur het volgende in:

* **Datum**: de datum van de beginbalans
* **Klant**: de naam van de klant
* **Overboeken**: de grootboekrekening "Eigen vermogen"
* **Verkoopfactuur**: Het bedrag van de factuur.

Je kunt hier het veld Vervaldatum niet invullen en ook de rest van de velden vul je niet in.
Klik op "Vastleggen".

![Invullen van openstaande facturen in Debiteuren]({{site.baseurl}}/assets/debiteuren_openstaande_facturen.png)

#### Betaling facturen uit beginsaldo debiteuren
Als de openstaande verkoopfacturen zijn betaald door de klant, ga je in het tabblad "Rekeningen" naar de grootboekrekening "Bank".
Dubbelklik op de grootboekrekening "Bank" en voer de ontvangen bedragen in.

![Bank debiteuren betaling]({{site.baseurl}}/assets/bank_debiteuren_betaling.png)

Verder kun je voor deze ontvangst de stappen volgen van de pagina ["Bankafschriften verwerken"]({{site.baseurl}}/bankafschriften_verwerken).


### Crediteuren
De waarde op de grootboekrekening Crediteuren van € 440 bestaat uit twee openstaande inkoopfacturen,
namelijk leverancier Groothandel De Lamp ter waarde van € 180 en leverancier Tuincentrum Tuin, Dier en Vijver ter waarde van
€ 260.

Open de grootboekrekening Crediteuren en vul daarin voor elke openstaande inkoopfactuur het volgende in:
* **Datum**: De datum van de beginbalans
* **Leverancier**: de naam van de leverancier
* **Overboeken**: rekening "Eigen vermogen"
* **Inkoopfactuur**: de waarde van de inkoopfactuur

Je kunt hier het veld Vervaldatum niet invullen en ook de rest van de velden vul je niet in.
Klik op "Vastleggen".

![Invoeren openstaande facturen in Crediteuren]({{site.baseurl}}/assets/crediteuren_invoeren_openstaande_inkoopfacturen.png)

#### Betaling facturen uit beginsaldo crediteuren
Als de openstaande facturen zijn betaald per bank aan de leverancier, ga je in het tabblad "Rekeningen" naar de rekening "Bank".
Dubbelklik op de rekening en voer de betaalde bedragen in.

TODO: Verificatie: Op accoo.nl staat een afbeelding waarbij de betalingen als storting zijn doorgevoerd op de bankrekening.
Ik ga er van uit dat dat een vergissing moet zijn, dus in de onderstaande afbeelding zijn ze als opname doorgevoerd.

![Invoeren betaling openstaande facturen in Bank]({{site.baseurl}}/assets/bank_verwerking_crediteuren_betaling.png)

Verder kun je voor deze betaling de stappen volgen van de pagina ["Bankafschriften verwerken"]({{site.baseurl}}/bankafschriften_verwerken).

## Proefbalans
Nadat je de openingsbalans hebt ingevoerd, zijn alle bedragen uit het voorbeeld in de proefbalans te zien.
Open de proefbalans via het menu "Rapporten", de optie "Opbrengsten en kosten" en de suboptie "Proefbalans".

![Weergave proefbalans]({{site.baseurl}}/assets/proefbalans_prefilled.png)

De rapportdatum van de proefbalans kun je aanpassen via "Opties" in de werkbalk onder het tabblad Algemeen.

![Algemene opties van het rapport proefbalans]({{site.baseurl}}/assets/proefbalans_options_general.png)

## Ter afsluiting
De openingsbalans invoeren is een stap waarvan je veel plezier zulthebben tijdens het gebruik van een boekhoudprogramma.
Je kent nu de details en de stappen die komen kijken bij het invoeren van de openingsbalans. Bovendien weet je hoe je
deze beginbalans zelf kunt opstellen.