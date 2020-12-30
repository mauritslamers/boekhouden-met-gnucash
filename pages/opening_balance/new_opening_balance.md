---
layout: page
title: Nieuwe openingsbalans
permalink: /opening_balance/new_balance
parent: Openingsbalans
nav_order: 1
---

## Openingsbalans als je nog geen boekhouding hebt
We gaan in een paar stappen de openingsbalans opstellen en invoeren in GnuCash.
Ook ondernemers die al een tijdje actief zijn, maar nog geen boekhouding hebben
adviseren we deze stappen te volgen.

Toen je je bedrijf startte, heb je waarschijnlijk geld en/of goederen vanuit je
privé-bezit naar je bedrijf overgeheveld. Denk hierbij aan:
* Privé-auto op naam van je onderneming gezet.
* Privé-computer overgebracht naar je onderneming.
* Geld overgemaakt van je privé-bankrekening naar je zakelijke rekening.
* Gereedschap dat je privé had, ben je voor je bedrijf gaan gebruiken.

Het overbrengen van privé naar zakelijk heeft als voordeel dat de prijs
afgetrokken wordt van de winst. Over de winst betaal je belasting en als je 
minder winst hebt hoef je minder belasting te betalen.
Goederen met een waarde van meer dan € 450 moet je afschrijven.

Goederen die je van privé naar zakelijk overbrengt hebben de waarde die je er
ook voor zou krijgen bij verkoop. Dit wordt ook wel de "waarde in het economisch
verkeer" genoemd.

Of je de auto het beste zakelijk of privé kunt aanmerken, hangt sterk af van de waarde
(aanschaf en op het moment van overbrengen) van de auto, de onderhoudskosten en vaste
kosten, het verbruik en je verwachte jaarlijkse omzet.
Als je de auto privé houdt en er zakelijk mee rijdt, moet je voor het meeste belastingvoordeel een rittenregistratie bijhouden om de € 0.19 per zakelijke kilometer
te kunnen verrekenen.
De Belastingdienst geeft via de website en de belastingtelefoon veel goede tips en
informatie over de keuze tussen een zakelijke en privé-auto.

Maak een lijst van de goederen en hun waarde die je bij de start van de onderneming
vanuit je privé-bezit over hebt gebracht naar je bedrijf. Bijvoorbeeld:

* Laptop: € 400
* Printer: € 120
* Bestelbus: € 2600
* Mobiele telefoon: € 90
* Gereedschap: € 650
* Storting zakelijke bankrekening € 1000

De privé-inbreng is totaal € 4860.

Van de waarde van de privé-inbreng maak je een beginbalans.
De privé-inbreng van € 4860 is hetzelfde als een privé-storting. Een privé-storting
staat altijd rechts (credit). Alle goederen en de storing op de zakelijke bankrekening
zijn nu een zakelijk bezit. Bezittingen staan altijd links (debet).

De laptop, printer, bestelbus, mobiele telefoon en het gereedschap vallen in de categorie
machines en installaties. De storting op de bankrekening is bank.

Let op dat in een beginbalans debet (links) en credit (rechts) in totaal hetzelfde
moeten zijn. In dit voorbeeld dus € 4860. Voer alleen een beginbalans in waarvan debet
en credit gelijk zijn.

De openingsbalans ziet er dan zo uit:

| Rekeningnaam                                     | Rekeningsoort   | Debet | Credit |
|:-------------------------------------------------|:----------------|------:|-------:|
| 010 Bedrijfsgebouwen en terreinen                | Activa          |       |        |
| 020 Machines en installaties                     | Activa          |  3860 |        |
| 040 Eigen vermogen                               | Eigen vermogen  |       |        |
| 041 Privéstortingen                              | Eigen vermogen  |       |  4860  |
| 042 Privéonttrekkingen                           | Eigen vermogen  |       |        |
| 070 Schulden                                     | Vreemd vermogen |       |        |
| 100 Kas                                          | Contant         |       |        |
| 110 Bank                                         | Bank            |  1000 |        |
| 130 Debiteuren                                   | Debiteuren      |       |        |
| 140 Crediteuren                                  | Crediteuren     |       |        |
| 180 Vordering omzetbelasting                     | Activa          |       |        |
| 185 Schuld omzetbelasting 21%                    | Vreemd vermogen |       |        |
| 186 Schuld omzetbelasting 9%                     | Vreemd vermogen |       |        |
| 187 Schuld omzetbelasting overig (geen 0%)       | Vreemd vermogen |       |        |
| 188 Schuld omzetbelasting 0%                     | Vreemd vermogen |       |        |
| 189 Schuld omzetbelasting naar mij verlegd       | Vreemd vermogen |       |        |
| 400 Inkoopprijs materialen en voorraad           | Kosten          |       |        |
| 410 Kosten van uitbesteed werk                   | Kosten          |       |        |
| 430 Afschrijvingskosten gebouwen en terreinen    | Kosten          |       |        |
| 440 Afschrijvingskosten machines en installaties | Kosten          |       |        |
| 450 Auto- en transportkosten                     | Kosten          |       |        |
| 460 Huisvestingskosten                           | Kosten          |       |        |
| 470 Onderhoudskosten                             | Kosten          |       |        |
| 480 Verkoopkosten + reclame + marketing          | Kosten          |       |        |
| 490 Andere/overige kosten                        | Kosten          |       |        |
| 495 Rente + bankkosten                           | Kosten          |       |        |
| 700 Voorraden                                    | Activa          |       |        |
| 800 Omzet 21% omzetbelasting                     | Opbrengsten     |       |        |
| 801 Omzet 9% omzetbelasting                      | Opbrengsten     |       |        |
| 802 Omzet 0% omzetbelasting                      | Opbrengsten     |       |        |
|--------------------------------------------------|-----------------| ----- | ------ |
|                                                  |                 |  4860 |   4860 |

### Openingsbalans privé-inbreng

Open GnuCash en selecteer in het tabblad Rekeningen de grootboekrekening waarvoor je
het beginsaldo wilt invoeren. In het voorbeeld hierboven is de eerste grootboekrekening
"Machines en installaties" waarop een beginsaldo van € 3860 komt te staan.

Kies als begindatum een datum die eerder is dan de eerste factuur die je hebt gehad of
zelf hebt verstuurd, of de eerste zakelijke kosten die je hebt gemaakt.
Wij gebruiken als voorbeeld hier 1 januari 2019.

Kies uit het menu "Acties" de optie "Afstemmen...".

![Menu Acties, optie Afstemmen]({{ site.baseurl }}/assets/menu_acties_afstemmen.png)

Je krijgt nu het dialoogvenster "Afstemmingsgegevens" te zien. Vul hier bij de "Afschriftdatum"
de gekozen begindatum in en bij het "Eindsaldo" het bedrag.

![Afstemmingsgegevens]({{ site.baseurl }}/assets/acties_afstemmen_dialog.png)

Je krijgt nu het venster "Afstemmen" dat nog leeg is. Rechtsonder zie je het eindsaldo
dat we net ingevoerd hebben. Klik nu op "In balans brengen".

![Afstemmen]({{ site.baseurl }}/assets/afstemmen_empty.png)

De grootboekrekening "Machines en installaties" wordt nu geopend.
Vul bij de datum de gekozen datum in, bij omschrijving "Beginbalans" en gebruik
voor de kolom "Overboeken" de rekening "Privéstortingen".
De rest kan ongewijzigd blijven. Klik vervolgens op "Vastleggen".

![Machines_beginbalans]({{ site.baseurl }}/assets/machines_beginbalans.png)

Ga nu terug naar het venster "Afstemmen" dat nog open staat. Het kan zijn dat
het verborgen zit achter het hoofdscherm. Indien dat niet het geval is, selecteer
de grootboekrekening opnieuw en open het dialoogvenster "Afstemmen" via menu
"Acties", optie "Afstemmen".

Vink de inkomende geldstroom aan. Je ziet nu dat het verschil rechtsonderin het
venster € 0 is geworden.

![Afstemmen met selectie]({{ site.baseurl }}/assets/afstemmen_marked.png)

Nu dit beginsaldo klopt en er geen verschil meer is, kies je "Afronden" via het
menu "Afstemmen" of via het "&#9662;"-menu.

Nu selecteren we de grootboekrekening "Privéstortingen" en kiezen voor "Afstemmen".
Je ziet dat het beginsaldo ook hier nog op € 0 staat, en dat het Eindsaldo al is
ingevuld. Om ook een beginsaldo op de rekening "Privéstortingen" te krijgen, kiezen we OK.

![Privéstortingen afstemmen dialoogvenster]({{site.baseurl}}/assets/privestortingen_afstemmen_dialog.png)

Vink in het venster Afstemmen het beginsaldo aan. Het verschil rechtsonder is nu € 0.

![Privéstortingen afstemmen]({{site.baseurl}}/assets/privestortingen_afstemmen_window.png)

Nu dit beginsaldo klopt en er geen verschil meer is, kiezen we "Afronden" via het menu of het pulldown menu met het pijltje.

Als je nu de grootboekrekening opnieuw selecteert en kiest voor afstemmen, zul je zien dat het beginsaldo klopt
en er niks meer staat in het scherm "Afstemmen".

Herhaal de bovenstaande stappen voor elke privéstorting om een beginsaldo te genereren.
Nadat je de privé-inbreng hebt ingevoerd, zijn de drie bedragen uit dit voorbeeld te zien
in het Rekeningenoverzicht.

![Rekeningoverzicht na afronding beginbalans]({{site.baseurl}}/assets/accounts_after_start_balance_complete.png)
