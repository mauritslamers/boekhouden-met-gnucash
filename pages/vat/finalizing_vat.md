---
layout: page
title: Verwerking
permalink: /vat/finalizing
parent: Btw-aangifte of aangifte omzetbelasting
nav_order: 3
---

## Voorbereiding van de verwerking

Aan het einde van de btw-aangifte heb je gezien of je per saldo btw moet betalen of dat je omzetbelasting terugkrijgt van de Belastingdienst. Het betalen of terugkrijgen van de omzetbelasting loopt via je zakelijke bankrekening.

Om ervoor te zorgen dat je de bankmutatie (de btw die je moet betalen of die je terugkrijgt) gemakkelijk kan verwerken, maken we een boeking in de boekhouding van de btw-aangifte.

Deze boeking zorgt ervoor dat er per saldo één te betalen of terug te ontvangen bedrag overblijft in de boekhouding voor dat kwartaal.

De boeking maak je aan het einde van de aangifteperiode. De aangifte omzetbelasting was voor het laatste kwartaal 2019, dus de boeking maak je per 31 december 2019.

Wij hebben voor het overzicht een tabel gemaakt van de btw-bedragen in de aangifte en in de boekhouding. De btw-bedragen moeten “op nul” gezet worden. We boeken daarom alle btw-bedragen over naar één omzetbelasting-grootboekrekening. Welke btw-grootboekrekening je gebruikt maakt niet uit als je maar altijd dezelfde gebruikt voor het “wegboeken” en voor de bankmutatie van de aangifte omzetbelasting.

Wij gebruiken “180 Vordering omzetbelasting”. We gaan de bedragen in de creditkolom overboeken naar de debetkolom. De bedragen zijn voorbeelden.

|Naam in de btw-aangifte                         |Naam in de boekhouding          |    Debet (terug te krijgen btw)| Credit (te ontvangen btw)|
|------------------------------------------------|--------------------------------|--------------------------------|--------------------------|
|1a. Leveringen/diensten belast met hoog tarief  | 185 Schuld omzetbelasting 21%  |                                |                  € 138,84|
|1b. Leveringen/diensten belast met laag tarief  | 186 Schuld omzetbelasting 9%   |                                |                  €  48,00|
|1e. Leveringen/diensten belast met 0% of niet bij u belast | nvt.                |                                |                         -|
|2a. Leveringen/diensten waarbij omzetbelasting naar u is verlegd | 189 Schuld omzetbelasting naar mij verlegd |   |                  €  50,00|
|5b. Voorbelasting                               | 180 Vordering omzetbelasting   | €                        289,11|                          |

De overboeking (journaalpost) ziet er dan zo uit. Per saldo boeken we € 236,84 over. De terug te ontvangen € 289,11 uit de tabel hierboven neemt door de overboeking dus af met € 236,84.
Activa
|Grootboekrekening boekhouding              | Debet   | Credit  |
|-------------------------------------------|---------|---------|
|185 Schuld omzetbelasting 21%              | € 138   |         |
|186 Schuld omzetbelasting 9%               | €  98   |         |
|180 Vordering omzetbelasting               |         | € 236,84|

## De verwerking

Er zijn meerdere manieren om de btw-aangifte in de administratie te verwerken.
We beschrijven hier drie manieren: een “quick-and-dirty”-manier, een “zo-kan-het-ook”-manier en de degelijke manier.
We beginnen met de degelijke manier.

### De degelijke manier

Voor de degelijke manier gebruiken we een extra rekening die we eerst gaan aanmaken als je dat al niet gedaan had.
Deze rekening is specifiek bedoeld voor het tijdelijk vasthouden van het eindresultaat van de btw-verwerking.
Als je deze rekening al hebt, kun je deze stap overslaan.

#### Aanmaken Tussenrekening btw

Ga naar het tabblad `Rekeningen` en kies voor Nieuw.

Vul in:
- Rekeningnaam: 190 Tussenrekening btw 
- Rekeningnummer: 190
- Rekeningsoort: Vreemd vermogen
- Hoofdrekening: Nieuwe rekening op hoofdniveau

NB: De Engelse term voor tussenrekening is Suspense Account

#### De boeking zelf

We gaan deze boeking nu invoeren. We doen dit in dit voorbeeld op de rekening `Vordering omzetbelasting` maar feitelijk gezien maakt het niet uit, omdat we een boeking gaan aanmaken waar meerdere rekeningen bij zijn betrokken. GnuCash zal dan automatisch deze boeking plaatsen in de betrokken rekeningen.

Dubbelklik op het tabblad `Rekeningen` op de grootboekrekening “180 Vordering omzetbelasting”. Vul nu als datum de laatste dag in van het kwartaal waarvoor je aangifte hebt gedaan. Vul vervolgens een omschrijving in, bijvoorbeeld “Verwerking btw-aangifte laatste kwartaal 2019”.
Klik nu op de knop `Meer boekregels` in de knoppenbalk bovenin je scherm. Je krijgt nu een nieuwe gele regel. Gebruik de tab-toets of de pijlen op je toetsenbord om naar de volgende regel te gaan.

We gaan nu per regel de bovenstaande tabel verwerken. Doe dit in de volgorde zoals het in de tabel staat, waarbij de rekening Voorbelasting als laatste aan de beurt komt. De getallen zijn afgerond, omdat je bij de opgave in Nederland ook alleen gehele getallen gebruikt.

We klikken daarvoor eerst op de kolom `Rekening` van deze eerste nieuwe regel. We kunnen hier de rekeningnaam typen, maar het is gemakkelijker om het pulldown-menu gebruiken. We kiezen daar de rekening `185 Schuld omzetbelasting 21%` en vullen in de kolom `Toename` het bedrag in dat we ingevuld hebben bij de aangifte, namelijk € 138. We zorgen ervoor dat de kolom `Afname` leeg blijft.

We gaan naar de volgende regel. Je ziet dat GnuCash automatisch de balans van de boeking voor ons uitrekent.
We kiezen de rekening `186 Schuld omzetbelasting 9%` en vullen wederom in de kolom `Toename` het bedrag in dat we opgegeven hebben. Ook hier zorgen we ervoor dat de kolom `Afname` leeg blijft.

We vullen nu de regel in voor de rekening `Vordering omzetbelasting` en we vullen in de kolom `Afname` het bedrag in dat we als voorbelasting hebben opgegeven, namelijk het volledige afgeronde bedrag. Het maakt daarbij niet uit of er nog iets op de rekening blijft staan of niet, en of je naar boven of naar beneden hebt afgerond.

Er blijft nu een verschil over. Dit verschil boeken we naar de rekening `190 Tussenrekening btw` door die rekening te selecteren voor die regel.

We leggen nu de boeking vast door te klikken op `Vastleggen`, of met Enter.

#### Betaling aan of van de Belastingdienst

We openen nu de rekening `190 Tussenrekening btw` door in het Rekeningen-overzicht erop te dubbelklikken.
Het saldo van deze rekening is nu gelijk aan het bedrag dat je nog met de Belastingdienst moet afstemmen. Is het saldo positief, moet je aan de Belastingdienst betalen, en is het saldo negatief, moet de Belastingdienst jou dat bedrag terugbetalen.

Je opent in het menu Acties de optie `Boeken`. Je vult nu het bedrag in dat je moet betalen of moet ontvangen. Dat bedrag is gelijk aan het saldo op de `Tussenrekening btw`, maar dan altijd positief. Dus als het saldo -30 is, vul je 30 in. 
Vul nu de velden Datum en Omschrijving in.

Indien je btw moest betalen aan de Belastingdienst, kies je links voor `110 Bank` en rechts `190 Tussenrekening btw`.
Indien je btw moest ontvangen van de Belastingdienst, kies je links voor `190 Tussenrekening btw` en rechts voor `110 Bank`.

Klik op OK. De betaling is nu verwerkt en het saldo op de Tussenrekening zou weer 0 moeten zijn.

### De zo-kan-het-ook manier

Deze manier lijkt erg op de manier van de tussenrekening, maar gebruikt daarvoor geen aparte rekening maar de rekening `180 Voorbelasting`.
Deze manier is iets minder doorzichtig en daarmee minder correct dan de degelijke manier.

De manier van invoeren is vrijwel hetzelfde als bij de manier hierboven, alleen schrijf je de verschillen niet naar de Tussenrekening, maar naar de rekening Voorbelasting. Indien je btw aan de belastingdienst moet betalen, wordt het saldo op de rekening Voorbelasting negatief. Je verwerkt vervolgens de betaling aan of van de Belastingdienst ook op dezelfde manier, alleen gebruik je ook hier de rekening `180 Voorbelasting` in plaats van de tussenrekening.

### De quick-and-dirty manier

Deze manier is weer iets minder correct dan de zo-kan-het-ook manier. Deze manier is alleen maar bruikbaar als je de betaling aan de Belastingdienst op hetzelfde moment kunt doen als de verwerking van de btw. Meestal is dat niet zo, omdat je dan niet het verschil kunt maken tussen het moment van betaling en het einde van de btw-periode.
De voorgaande methodes zetten de verwerking van de btw op de laatste dag van de btw-periode, maar bij de quick-and-dirty manier kan dat alleen als je btw gaat betalen.

De manier van invullen werkt ook weer vergelijkbaar aan de bovenstaande manieren, maar nu vul je bij het maken van de afsluitingsboeking de rekening `110 Bank` in als je btw aan de Belastingdienst moet betalen. Als datum kies je dan het moment van betalen.

Als je btw terug gaat ontvangen blijft er een bedrag staan op de rekening `Voorbelasting`. Zodra je van de Belastingdienst het bedrag terugkrijgt, boek je via de optie “Boeken” het bedrag van de Voorbelasting-rekening naar de bankrekening.
