---
layout: page
title: Betalingsgegevens importeren
permalink: /paying/import_mutations
parent: Betalingen verwerken
nav_order: 2
---

**NB: Helaas is dit deel van de handleiding nog niet volledig.**

## Betalingsgegevens importeren

De meeste Nederlandse banken ondersteunen het downloaden van transacties in CSV of SWIFT (MT940/MT942) formaat.
GnuCash kan transacties vanuit diverse bestandsformaten importeren zodat je niet elke transactie handmatig hoeft in te boeken.
Echter, voor SWIFT is er een externe interface nodig dus is deze handleiding gebaseerd op het CSV formaat.

## Downloaden

Dit proces verschilt per bank maar is in het algemeen hetzelfde.
Log in bij de bank en download alle bij- en afschrijvingen, bijvoorbeeld nieuwe transacties sinds de laatste download, of in een bepaalde periode (afgelopen maand), en kies voor het CSV formaat. Sommige banken bieden de download in zip formaat aan, pak deze eerst uit voordat je gaat importeren.

## Importeren

Je importeert een CSV bestand door in het menu "Bestand" te kiezen voor het submenu "Importeren" en daarin voor "Boekingen uit een CSV-bestand importeren".
Je krijgt dan een zogeheten wizard, die je helpt om de gegevens correct te importeren.
De eerste stap is het kiezen van het CSV-bestand.
De volgende stap geeft een voorvertoning van de geïmporteerde gegevens en de mogelijkheid om instellingen te wijzigen, bijvoorbeeld in welk formaat de datum notatie is.
Kies onder rekening "110 Bank".
Onderin het venster staat de inhoud van het bestand zoals het door GnuCash begrepen wordt aan de hand van de instellingen die je erboven aangeeft.

Let hierbij op dat het bedrag formaat in de kolom overeenkomt met de valuta-opmaak.
Een andere tip is om naast de omschrijving ook een notitie kolom aan te wijzen.
Soms is de omschrijving wat cryptisch en helpt het om een andere kolom als notitie aan te wijzen aangezien beide kolommen getoond worden tijdens het boeken van de transacties.

Onderin de wizard staat aangegeven welke type gegevenskolom je minimaal moet selecteren.

### Meer dan 1 rekening importeren

Indien je naast een betaalrekening bijvoorbeeld ook een spaarrekening hebt, dan kan je transacties van beide rekeningen gecombineerd in 1 bestand downloaden.
Bij het import voorbeeld laat je de algemene instelling Rekening leeg, en geef je aan welke kolom de Rekening gegevens (IBAN nummer) bevat. Zorg ervoor dat je vooraf voor elke rekening een grootboekrekening heb aangemaakt, bijvoorbeeld:

- 110 SNS Bank
- 111 SNS Bank - Spaarrekening

### Profiel opslaan

Het is aan te raden om als je deze import-optie vaker gaat gebruiken de instellingen op te slaan in een profiel.
Je kunt een nieuw profiel aanmaken, door een naam te typen onder "Instellingen inlezen of opslaan" en vervolgens te klikken op de pijl naar beneden (Instellingen opslaan).
Bij de volgende import kan je dan dit profiel selecteren en worden de juiste instellingen toegepast.

### Rekening koppelen

Indien je niet Rekening "110 Bank" als algemene instelling hebt gekozen, maar een kolom Rekening hebt aangegeven, bijvoorbeeld als je gecombineerd bestand inleest, dan kan je in de volgende stap het IBAN nummer koppelen aan de juiste grootboekrekening.

## Boekingen koppelen

De volgende stap is het testen of de import zal slagen.
Vervolgens kan je de boekingen gaan koppelen.

Klik op de knop Help om uitleg te krijgen over de kleur en keuze per boeking.

Bijvoorbeeld een boeking met bankkosten heeft de kleur geel en is niet in balans.
Dubbelklik op deze regel en selecteer "495 Rente + bankkosten".
De boeking wordt nu in groen weergegeven.

Een ander voorbeeld, een klant heeft een factuur betaald.
In dit geval kan je de boeking niet koppelen aan een factuur tijdens het import proces.
Laat in dit geval de regel ongemoeid en koppel de factuur na het importeren van de boeking.
Dit doe je door na de import de grootboekrekening van de bank te openen, vervolgens zie je in de kolom Overboeken "Niet in balans" staan.
Klik met de rechtermuisknop op deze boeking en selecteer "Toewijzen als betaling..." en volg de wizard waarna "Niet in balans" wordt vervangen.

Kijk goed in de kolom "Aanvullende opmerkingen", het kan namelijk zijn dat GnuCash een verkeerde tegenrekening kiest.
In dit geval dubbelklik je op de regel en selecteer je de juiste grootboek rekening.
Bestaat de grootboekrekening nog niet, dan kan je gelijk een nieuwe grootboekrekening aanmaken door op "Nieuwe rekening.." te klikken.

## Afstemmen

Als de import geslaagd is, open je de grootboekrekening "110 Bank" en controleer je of er nog transacties zijn die niet in balans zijn.
Zodra alles in balans is, klik dan op "Afstemmen" en controleer het eindsaldo van de bankrekening.
Vergeet niet in het geval van een gecombineerde import om ook de andere bankrekening af te stemmen.

## Import associaties bewerken

Bij elke import leert GnuCash hoe een transactie waarschijnlijk geboekt moeten worden.
Merk je dat een bepaalde boeking steeds gekoppeld wordt aan de verkeerde grootboekrekening, bekijk dan de gecorreleerde tekst en rekeningnaam in "Import associaties bewerken".
Deze vind je in het menu Hulpmiddelen. Helaas kan je hier niet zelf teksten toevoegen, alleen verwijderen.