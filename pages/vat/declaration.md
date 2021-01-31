---
layout: page
title: De aangifte
permalink: /vat/declaration
parent: BTW aangifte of aangifte omzetbelasting
nav_order: 2
---

## De aangifte

_Let op: De originele handleiding van Accoo klopt niet op dit vlak. Zie de uitleg onderaan als je wilt weten waarom._

Je hebt voor de cijfers twee verschillende overzichten nodig, namelijk het rapport `Proefbalans` en het rapport `Winst- en verliesrekening`.

Open GnuCash en ga naar Rapporten, Opbrengsten en kosten en Proefbalans.

![Menu proefbalans]({{site.baseurl}}/assets/menu_reports_profits_balance.png)

Je krijgt nu het venster proefbalans. De cijfers in het kader gaan we straks gebruiken.

![Weergave proefbalans]({{site.baseurl}}/assets/proefbalans_btw_highlights.png)

We openen nu het rapport "Winst- en verliesrekening". Deze optie staat in de eerste afbeelding onderaan. 

Klik boven in de balk op het pictogram `Opties`, of zoek ernaar in het uitklapmenu mocht de knop niet zichtbaar zijn.
Klik vervolgens op het tabblad Algemeen.

![Algemene opties winst- en verliesrekening]({{site.baseurl}}/assets/profit_loss_report_general_options.png)

Kies hier een datum bij `Begindatum correctie/afsluiting` en bij `Rapportdatum`. Je kunt ervoor kiezen zelf een datum in te vullen,
maar GnuCash heeft bij beide opties een aantal handige snelselectie-opties:

![Smartopties begindatum]({{site.baseurl}}/assets/smart_opties_begindatum.png)

![Smartopties rapportdatum]({{site.baseurl}}/assets/smart_opties_rapportdatum.png)

Meestal zul je kiezen voor `Begin van vorig kwartaal` en `Einde van vorig kwartaal`. 
Na het selecteren van de juiste data klik je op OK en wordt je overzicht bijgewerkt. 

![Winst- en verliesrekening omzet]({{site.baseurl}}/assets/profit_loss_revenue.png)

We gebruiken de cijfers van de rubriek `Omzet`. In dit overzicht staat onder de omzet ook nog een tabel kosten, maar daar hoef je pas naar te kijken bij het invullen van de inkomstenbelasting.

## Vorige aangiftes opzoeken

Deze stap is alleen maar nodig indien er verkoopfacturen zijn ingevoerd in een periode waarvan de BTW-aangifte al heeft plaatsgevonden. 
In dat geval is namelijk de BTW wel bijgeschreven op de bijhorende rekening `Schuld omzetbelasting`, maar de omzet-waarde van de factuur valt nog
altijd onder het originele BTW-tijdvak. Hierdoor kloppen de omzetcijfers niet meer zoals die oorspronkelijk zijn opgegeven.

Als de te ontvangen dan wel te betalen BTW boven de al eerder genoemde € 1000 uitkomt, moet er een suppletie-formulier worden ingevuld, waarmee
de BTW-aangifte voor dat tijdvak wordt gecorrigeerd.

We gaan er nu van uit dat het BTW-bedrag onder de € 1000 euro blijft, en dat we dit kunnen verwerken in de eerstevolgende BTW-aangifte.

Zoek daarom de vorige aangiftes van het jaar op en tel per BTW-tarief de omzet bij elkaar op. Gebruik eventueel het overzicht [Kwartaaloverzicht omzet](../overviews/revenue_per_quarter)

Stel nu bij de opties van de `Winst- en verliesrekening` het begin in op het begin van het jaar, en het einde in op het einde van het kwartaal voorafgaand aan het kwartaal waarvan je de BTW-aangifte doet. Kijk nu of de gezamelijke omzet per BTW-tarief van die periode overeenkomt met de optelsom van de omzet zoals je die hebt opgegeven.

Mocht er een verschil zijn en je hebt te weinig omzet opgegeven, tel dan het verschil bij de nieuwe omzetcijfers op.

## De aangifte invullen

Nu je de benodigde gegevens uit je boekhouding hebt gehaald is het tijd voor het doen van de BTW-aangifte. Ga naar de website van de Belastingdienst en log daar in. Je kiest daar het kwartaal waarvoor je aangifte wil doen. Je krijgt vervolgens een aantal pagina's.

NB: Er is hier gekozen om geen afbeeldingen te gebruiken van de site van de Belastingdienst, omdat deze in principe voor zich zou moeten spreken.

Wij kijken hier specifiek naar de pagina's `Prestaties binnenland`, 

Op de pagina “Prestaties binnenland” vul je de omzet in en de omzetbelasting die je aan je klanten in rekening hebt gebracht.

In de kolom “Bedrag waarover omzetbelasting wordt berekend” vul je de omzet in.
In de kolom “Omzetbelasting” vul je de BTW in die je aan je klanten in rekening hebt gebracht.

- “1a. Leveringen/diensten belast met hoog tarief” is de omzet waarover je 21% btw hebt berekend.
- “1b. Leveringen/diensten belast met laag tarief” is de omzet waarover je 9% btw hebt berekend.
- “1c. Leveringen/diensten belast met overige tarieven, behalve 0%” is een veld dat je bijna nooit in hoeft te vullen. In ons voorbeeld komt dit toevallig wel voor, maar dit slaan we voor 't gemak over. (Opmerking: Mocht je een goed voorbeeld hiervoor weten, laat het even weten via de [GitHub Issues](https://github.com/mauritslamers/boekhouden-met-gnucash/issues))
- “1d. Privégebruik” hier vul je het bedrag en de BTW van privéonttrekkingen in. Bijvoorbeeld als je privé rijdt in een auto van je onderneming vul je dat hier in.
- “1e. Leveringen/diensten belast met 0% of niet bij u belast” is de omzet waarover je geen BTW hebt berekend aan je klant. Bijvoorbeeld als je de BTW verlegt naar je afnemer volgens de “verleggingsregeling”.


### Invullen Prestaties binnenland

1a. Leveringen/diensten belast met hoog tarief
  * Grootboekrekening “800 Omzet 21% omzetbelasting” = “Bedrag waarover omzetbelasting wordt berekend”. In dit voorbeeld € 2702,00. 
    Tel hier eventueel het verschil bij op als er een verschil mocht zijn met de vorige aangifte.
  * Grootboekrekening “185 Schuld omzetbelasting 21%” = “Omzetbelasting”. In dit voorbeeld € 90,42.

1b. Leveringen/diensten belast met laag tarief
  * Grootboekrekening “801 Omzet 9% omzetbelasting” = “Bedrag waarover omzetbelasting wordt berekend”. In dit voorbeeld € 850,00.
    Tel hier eventueel het verschil bij op als er een verschil mocht zijn met de vorige aangifte.
  * Grootboekrekening “186 Schuld omzetbelasting 9%” = “Omzetbelasting”. In dit voorbeeld € 45,00.

1e. Leveringen/diensten belast met 0% of niet bij u belast
  * Grootboekrekening “802 Omzet 0% omzetbelasting” = “Bedrag waarover omzetbelasting wordt berekend”. In dit voorbeeld € 450,00.
    Tel hier eventueel het verschil bij op als er een verschil mocht zijn met de vorige aangifte.
  * Omdat het percentage 0% is kun je geen btw bedrag invullen.

### Invullen Verleggingsregelingen binnenland

Op de pagina “Verleggingsregelingen binnenland” vul je bij “2a. Leveringen/diensten waarbij omzetbelasting naar u is verlegd” de inkopen in waarbij de BTW naar jou is verlegd.

2a. Leveringen/diensten waarbij omzetbelasting naar u is verlegd
  * Grootboekrekening “189 Schuld omzetbelasting naar mij verlegd” = “Omzetbelasting”. In dit voorbeeld € 50.
  * Om te weten wat de inkoopprijs was die hoort bij de € 50 omzetbelasting, is het meestal het gemakkelijkst om de facturen op te zoeken in de boekhouding waar de verlegde btw van € 50,00 bij hoort. In dit voorbeeld hoort hier één factuur bij van € 238,10.

### Invullen Prestaties naar/in het buitenland & Prestaties vanuit het buitenland
De pagina’s “Prestaties naar/in het buitenland” en “Prestaties vanuit het buitenland” zijn voor ondernemers die goederen of diensten exporteren en/of importeren. De BTW bij import en export laten we hier buiten beschouwing.

### Invullen Voorbelasting en kleine ondernemers
De pagina “Voorbelasting en kleine ondernemers“ is de laatste pagina waar je een bedrag uit de boekhouding moet invullen. Hier vul je de BTW in die je aan jouw leveranciers hebt betaald.

5a. Omzetbelasting (rubrieken 1 t/m 4)” is de totale BTW die je hebt ingevuld en die je moet afdragen aan de Belastingdienst.

5b. Voorbelasting
  * Grootboekrekening “180 Vordering omzetbelasting” = “Omzetbelasting”. In dit voorbeeld € 140,21.

Het maakt niet uit of je 21% btw of 9% BTW hebt betaald over je inkopen, je vult hier alleen de door jou aan jouw leveranciers betaalde BTW in één bedrag in.

## Laatste BTW-aangifte van het jaar

Een bijzonder geval is de laatste BTW-aangifte van het jaar, omdat daar ook een aantal afrekeningen in plaats vinden. We gaan daar in deze handleiding niet verder op in, maar het is wel belangrijk om deze informatie goed door te lezen.

[Belastingdienst: Laatste BTW-aangifte van het jaar](https://www.belastingdienst.nl/wps/wcm/connect/bldcontentnl/belastingdienst/zakelijk/btw/btw_aangifte_doen_en_betalen/btw-aangifte-welke-wanneer-en-hoe/laatste_btw_aangifte_van_het_jaar)

## Verschillen met de handleiding van Accoo

De handleiding hierboven is anders dan die van Accoo. In de originele handleiding wordt gesuggereerd alleen het proefbalans-rapport te nemen en altijd als begindatum van dat rapport het begin van het jaar te kiezen. Op deze manier worden verkoopfacturen meegenomen die zijn ingevoerd na het verwerken van de BTW-periode waar die verkoopfactuur betrekking op heeft. 
Er is echter een mismatch: de Belastingdienst wil namelijk graag de omzet hebben over dat kwartaal, maar het proefbalans-rapport geeft alleen maar de totale omzet sinds de laatste boeksluiting. In deze handleiding gebruiken we die optie niet, dus die cijfers zijn onbruikbaar.
Het overzicht Winst- en verliesrekening geeft je wel de mogelijkheid om je omzet per BTW-periode te bekijken. Dit overzicht mist alleen de verkoopfacturen die behoren tot de afgesloten BTW-periode, maar die ingevoerd zijn na het verwerken van de BTW-aangifte.

Let op: dit geldt dus alleen voor verkoopfacturen. Voor inkoopfacturen bestaat dit probleem niet, omdat ze geen onderdeel uitmaken van de omzet.
Het betekent ook alleen dat de omzet-cijfers mogelijk niet kloppen. De BTW-schuld is wel correct, want deze is namelijk cumulatief en niet datum-gevoelig.

Er is daarom voor de simpelste oplossing gekozen, namelijk handmatig de omzetcijfers van de BTW-aangifte en die in GnuCash met elkaar te vergelijken. Mocht er dan een verkoopfactuur later worden ingevoerd, komt deze zowel in de BTW als bij de omzet terug.