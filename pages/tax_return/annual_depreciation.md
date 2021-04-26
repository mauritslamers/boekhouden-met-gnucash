---
layout: page
title: De jaarlijkse afschrijving
permalink: /tax_return/annual_depreciation
parent: Aangifte inkomenstenbelasting
nav_order: 1
---

__Let op: De informatie die hier staat is actueel voor 2021, maar kan wijzigen. Kijk daarom ook altijd op de website van de belastingdienst!__

## De jaarlijkse afschrijving
Allerlei zaken die je hebt aangeschaft voor je bedrijf zullen naar verloop van tijd in waarde dalen. 
Dit betreft vaak apparatuur, zoals computers. Dit zijn kosten voor het bedrijf die (deels) aftrekbaar zijn.
Voor bedrijfsmiddelen met een aanschafwaarde lager dan € 450 mag je de kosten in een keer in mindering brengen op je winst.
Deze hoef je dus niet af te schrijven.

Voor bedrijfsmiddelen die € 450 kosten of meer, mag je de kosten niet ineens in mindering brengen op de winst, 
maar moet je deze afschrijven. De belastingdienst ziet deze namelijk als investering, en het afschrijven op investeringen
is verplicht. 

Het afschrijven is voordelig omdat je door de afschrijving minder belasting betaalt. Hierdoor wordt je investering goedkoper.
Als je dus een computer koopt van € 1000 en je betaalt door het afschrijven uiteindelijk € 200 minder belasting, 
was je voor die computer dus maar € 800 kwijt.

De manier waarop de afschrijvingen hier worden beschreven zijn alleen voor normale situaties. Er zijn namelijk bijzondere 
situaties waarin je meer mag aftrekken (de zogeheten willekeurige afschrijving). Kijk op de [website van de belastingdienst](https://www.belastingdienst.nl/wps/wcm/connect/bldcontentnl/belastingdienst/zakelijk/winst/inkomstenbelasting/inkomstenbelasting_voor_ondernemers/afschrijving/) 
voor meer informatie.

In dit deel van de handleiding laten we zien hoe je die afschrijving verwerkt in je boekhouding en gebruikt bij de 
aangifte inkomstenbelasting.

### Economische afschrijving

Zoals beschreven staat verliezen bedrijfsmiddelen (zoals computers) naar verloop van tijd hun waarde. De waarde van het apparaat
en de kosten die je daardoor maakt, zijn direct gekoppeld aan de levensduur van het apparaat in kwestie en de restwaarde na 
afloop. Bij de aanschaf van een apparaat moeten we dus bedenken hoeveel jaar het apparaat zal meegaan, of na hoeveel jaar we 
het apparaat gaan vervangen, en wat de verwachte waardevermindering zal zijn. 

Stel dat we verwachten dat we de computer die we hebben gekocht na 3 jaar moeten vervangen. Na deze 3 jaar is de waarde van de 
computer € 100. De totale afschrijving voor het bedrijf is dan € 900 (aanschafwaarde min de restwaarde). Deze totale 
afschrijving noemen we ook de _economische afschrijving_.
Per jaar bekeken schrijft het bedrijf € 300 euro af op deze computer. Het maakt daarbij niet uit of deze computer nog in goede staat is of niet. De belastingdienst omschrijft dit als volgt: 

```
De economische levensduur van een bedrijfsmiddel is verstreken als het geen economisch nut meer heeft voor uw onderneming, ook al is het technisch nog in goede staat.
```

(Zie [Bron](https://www.belastingdienst.nl/wps/wcm/connect/bldcontentnl/belastingdienst/zakelijk/winst/inkomstenbelasting/inkomstenbelasting_voor_ondernemers/afschrijving/hoe_berekent_u_het_bedrag_van_de_afschrijving))

Met andere woorden: zodra je de computer vervangen hebt, heeft de oude computer in principe geen economisch nut meer.

### Fiscale afschrijving
Er zijn echter grenzen gesteld aan hoeveel afschrijving je van de winst mag aftrekken. Er zijn een paar categorieën met elk een
verschillende beperking. De meeste middelen vallen onder de 20%-regel: je mag maximaal 20% van de oorspronkelijke 
aanschafwaarde per boekjaar aftrekken. In het hierbovengenoemde geval betekent dat dus, dat je van de € 300 maar € 200 euro 
mag aftrekken. Het is daarom efficiënter om middelen in 5 jaar volledig af te schrijven, zelfs als ze korter meegaan.

Voor de fiscale afschrijving telt bovendien ook nog _wanneer_ je de computer hebt gekocht. We zijn er in het voorbeeld van 
uitgegaan dat de computer aan het begin van het jaar gekocht is. 
Als je de computer halverwege het jaar koopt, mag je bij de eerste afschrijving niet een heel jaar aan afschrijving boeken, maar de helft.

## Invoeren van de afschrijving
We gaan nu de afschrijving invoeren. Daarvoor berekenen we eerst hoeveel we mogen afschrijven.
We gebruiken als bepalingsmoment 31 december. We rekenen vervolgens uit hoeveel dagen we het apparaat hebben.

Als we het apparaat op 1 september gekocht hebben is het 30 + 31 + 30 + 31 = 122 dagen tot aan 31 december.
We berekenen vervolgens uit hoeveel dat is in jaren, en vermenigvuldigen dat met 20%. 122/365 * 20% = 6,68%

Voor de eerste afschrijving van de computer is dat dus 0,0668 * € 1000 = € 66,85, afgerond € 67,-

__Belangrijk: het hoeft niet heel precies! Je moet zowiezo afronden naar hele euro's.__  

Voor alle jaren daarna is het maximaal € 200, met uitzondering van het vijfde jaar, aangezien er dan geen € 200 aan 
waarde meer over is. Je trekt dan af wat er nog aan waarde is.

### Kostenrekening 
Bij het invoeren van een inkoopfactuur van de computer geef je ook altijd een kostenrekening op. 
Nu hebben we een computer gekocht ter waarde van 1000. Bij het invoeren van deze inkoopfactuur kiezen we voor de kostenrekening
`020 Machines en installaties`. Hierdoor wordt de waarde van de computer bijgeschreven bij het vermogen van de onderneming.

### Afschrijvingsrekening
Als je het tabblad Accounts bekijkt, zie je daarin naast de rekening `020 Machines en Installaties` ook een rekening `440 Afschrijvingskosten machines en installaties`. Deze zal in het begin leeg zijn.
Zodra we de jaarlijkste inkomstenbelasting gaan doen, gaan we ook de afschrijvingen verwerken op de computer.
Stel nu dat we de computer gekocht hebben op 10 januari van het vorig jaar. Dit betekent dat we nu een jaar over de computer
beschikken. We mogen dus een afschrijving gaan boeken van 20% van de aanschafwaarde. 
20% van 1000 is 200. We gaan dus deze 200 overboeken van de rekening `020 Machines en Installaties` naar de rekening `440 Afschrijvingskosten machines en installaties`.
Dat doen we door de rekening `440 Afschrijvingskomsten machines en installaties` te openen.

Daar voeren we de volgende zaken in:
- Datum: 31-12-20**: het einde van het jaar waarvoor je de afschrijving doet.
- Omschrijving: Jaarlijkse afschrijving computer
- Overboeken: Kies `020 Machines en Installaties`
- Kosten: Het bedrag dat we hierboven hebben uitgerekend, in dit geval € 67.

Klik op vastleggen.

Als je nu bij Accounts gaat kijken zie je dat er € 67 is bijgeschreven op de rekening 
`440 Afschrijvingskosten machines en installaties` en dat de waarde van de rekening `020 Machines en installaties` 
met € 67 is afgenomen.

Herhaal nu deze actie voor elke afschrijving.