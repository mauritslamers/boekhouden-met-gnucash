---
layout: page
title: Rekeningen aanmaken
permalink: /accounts_setup/
parent: Opzetten
has_children: yes
---

## Rekeningen

Zodra je GnuCash hebt geïnstalleerd en het voor de eerste keer opent,
wordt je gevraagd een rekeningschema te maken. Het is voor een beginner het
beste om dit met de hand te doen. Je hebt dan alle rekeningen een keer gezien
en je kunt je een idee gaan vormen over waar deze rekeningen voor dienen.

Als je al vaker zo'n boekhouding hebt gedaan, of je hebt haast,
kun je dit rekeningschema ook importeren. Ga daarvoor naar [Snel opzetten](/quick_accounts_setup).

Kies annuleren bij de wizard om het invoeren handmatig te kunnen doen.

Je komt nu op het lege tabblad **Rekeningen**. Kies het menu *Acties* en daarna
*Nieuwe rekening...*.

![Menu-actie voor nieuwe rekening](/assets/new_account_nl.png)

Je krijgt dan het volgende dialoogvenster:

![Dialoogvenster voor een nieuwe rekening](/assets/new_account_dialog_nl.png)

### Grootboekrekeningen aanmaken.
Voer de naam in van de rekening, het rekeningnummer, rekeningsoort en hoofdrekening.
Als je wilt kun je de omschrijving ook meenemen, maar dat hoeft niet.
Doe dit voor elke rekening in het onderstaande overzicht. Het kan zijn dat niet
alle rekeningen die hier onder staan voor jouw bedrijf van toepassing zijn.
Dat geeft verder niet, want ze zitten je uiteindelijk ook niet in de weg.
Als er iets mis gaat, kun je de rekening naderhand ook bewerken. Kijk daarvoor
onder het overzicht.

```
NB. De rekeningen in het overzicht zijn goed voor bijna alle zzp-ers en eenmanszaken.
Voor deze indeling is gekozen omdat die het beste aansluit bij de BTW-aangifte
en de aangifte Inkomstenbelasting. Je hoeft dan niet te puzzelen waar je welke
bedragen moet invullen. Dat scheelt tijd en verkleint de kans op fouten.
```

In het rekeningenoverzicht worden 9 verschillende rekeningsoorten gebruikt. Het is handig om te weten wat
deze rekeningsoorten zijn, omdat deze kennis later van pas komt bij het maken van overzichten en rapporten.

* **Activa**: bezittingen die actief gebruikt worden
* **Eigen vermogen**: bezittingen die een waarde bezitten die bij verkoop waarde opleveren
* **Vreemd vermogen**: bezittingen van anderen die onder beheer zijn van het bedrijf, vaak in de vorm van tegoeden
* **Contant**: Rekening voor contant geld
* **Bank**: Rekening bij de bank
* **Debiteuren**: Rekening waarop bijgehouden wordt wat er verkocht is
* **Crediteuren**: Rekening waarop bijgehouden wordt wat er ingekocht is
* **Kosten**: Rekening waarop kosten bijgehouden kunnen worden
* **Opbrengsten**: Rekening waarop de opbrengsten / omzet wordt bijgehouden.

Ga na het aanmaken van de rekeningen verder met het [invoeren van de BTW-tarieven](/vat-tariffs).

##### Rekeningenoverzicht

| Rekeningnaam                                     | Rekeningnummer | Rekeningsoort   | Hoofdrekening                  | Omschrijving                     |
|:-------------------------------------------------|:---------------|:----------------|:-------------------------------|----------------------------------|
| 010 Bedrijfsgebouwen en terreinen                | 010            | Activa          | Nieuwe rekening op hoofdniveau | Waarde van onroerend goed        |
| 020 Machines en installaties                     | 020            | Activa          | Nieuwe rekening op hoofdniveau | Waarde van machines              |
| 040 Eigen vermogen                               | 040            | Eigen vermogen  | Nieuwe rekening op hoofdniveau | Vermogen                         |
| 041 Privéstortingen                              | 041            | Eigen vermogen  | Nieuwe rekening op hoofdniveau | Stortingen als privé             |
| 042 Privéonttrekkingen                           | 042            | Eigen vermogen  | Nieuwe rekening op hoofdniveau | Onttrekkingen als privé          |
| 070 Schulden                                     | 070            | Vreemd vermogen | Nieuwe rekening op hoofdniveau | Tegoeden van investeringen       |
| 100 Kas                                          | 100            | Contant         | Nieuwe rekening op hoofdniveau | Contant geld in kas              |
| 110 Bank                                         | 110            | Bank            | Nieuwe rekening op hoofdniveau | Bankrekening                     |
| 130 Debiteuren                                   | 130            | Debiteuren      | Nieuwe rekening op hoofdniveau | Verkoopfacturen                  |
| 140 Crediteuren                                  | 140            | Crediteuren     | Nieuwe rekening op hoofdniveau | Inkoopfacturen                   |
| 180 Vordering omzetbelasting                     | 180            | Activa          | Nieuwe rekening op hoofdniveau | Betaalde BTW op inkoop           |
| 185 Schuld omzetbelasting 21%                    | 185            | Vreemd vermogen | Nieuwe rekening op hoofdniveau | Ontvangen BTW op verkoop hoog    |
| 186 Schuld omzetbelasting 9%                     | 186            | Vreemd vermogen | Nieuwe rekening op hoofdniveau | Ontvangen BTW op verkoop laag    |
| 187 Schuld omzetbelasting overig (geen 0%)       | 187            | Vreemd vermogen | Nieuwe rekening op hoofdniveau | Ontvangen BTW op verkoop overig  |
| 188 Schuld omzetbelasting 0%                     | 188            | Vreemd vermogen | Nieuwe rekening op hoofdniveau | Ontvangen BTW op verkoop 0%      |
| 189 Schuld omzetbelasting naar mij verlegd       | 189            | Vreemd vermogen | Nieuwe rekening op hoofdniveau | Ontvangen BTW op verkoop verlegd |
| 400 Inkoopprijs materialen en voorraad           | 400            | Kosten          | Nieuwe rekening op hoofdniveau | Inkoopkosten voorraad            |
| 410 Kosten van uitbesteed werk                   | 410            | Kosten          | Nieuwe rekening op hoofdniveau | Inkoopkosten uitbesteed werk     |
| 430 Afschrijvingskosten gebouwen en terreinen    | 430            | Kosten          | Nieuwe rekening op hoofdniveau | Afschrijving onroerend goed      |
| 440 Afschrijvingskosten machines en installaties | 440            | Kosten          | Nieuwe rekening op hoofdniveau | Afschrijving machines            |
| 450 Auto- en transportkosten                     | 450            | Kosten          | Nieuwe rekening op hoofdniveau | Inkoopkosten vervoer en transport|
| 460 Huisvestingskosten                           | 460            | Kosten          | Nieuwe rekening op hoofdniveau | Inkoopkosten huisvesting en huur |
| 470 Onderhoudskosten                             | 470            | Kosten          | Nieuwe rekening op hoofdniveau | Inkoopkosten onderhoud           |
| 480 Verkoopkosten + reclame + marketing          | 480            | Kosten          | Nieuwe rekening op hoofdniveau | Inkoopkosten verkoop / reclame   |
| 490 Andere/overige kosten                        | 490            | Kosten          | Nieuwe rekening op hoofdniveau | Andere inkoopkosten              |
| 495 Rente + bankkosten                           | 495            | Kosten          | Nieuwe rekening op hoofdniveau | Kosten van rente en bankgebruik  |
| 700 Voorraden                                    | 700            | Activa          | Nieuwe rekening op hoofdniveau | Waarde voorraden                 |
| 800 Omzet 21% omzetbelasting                     | 800            | Opbrengsten     | Nieuwe rekening op hoofdniveau | Omzet belast met 21% BTW         |
| 801 Omzet 9% omzetbelasting                      | 801            | Opbrengsten     | Nieuwe rekening op hoofdniveau | Omzet belast met 9% BTW          |
| 802 Omzet 0% omzetbelasting                      | 802            | Opbrengsten     | Nieuwe rekening op hoofdniveau | Omzet niet belast met BTW        |

### Bewerken van grootboekrekeningen

Je kunt de instellingen van een rekening bewerken. Selecteer de rekening die je
wil bewerken en kies in het menu Bewerken de optie Grootboekrekening bewerken.
Je krijgt nu hetzelfde dialoogvenster als waarmee je de rekening hebt aangemaakt.
Breng de gewenste wijzigingen aan en klik op OK.


