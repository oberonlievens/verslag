# verslag

Dit is basically onze .docx in een .md formaat

## Abstract

## Voorwoord

## Inhoudsopgave

## Figurenlijst

## Codefragmentenlijst

## Begrippenlijst

## Inleiding

In dit rapport wordt onderzocht hoe een zelfrijdende smart-frigobox gerealiseerd kan worden aan de hand van Arduino en een smartphone app. De tijdspanne van dit onderzoek is twaalf weken met als begindatum 9 februari 2020.

De bedoeling van dit project is om de klassieke frigobox te vernieuwen. Het project start vanaf nul. De eerste stap is het ontwerpen van de smart-frigobox. Deze bevat enkele functies waaronder een verbinding tussen een app en Arduino, een volgfunctie, temperatuurmeting en een inventaris. Vervolgens wordt de manier waarop de functionaliteiten tot stand kunnen komen onderzocht. Als laatste stap wordt een prototype gebouwd.

In dit rapport is de belangrijkste onderzoeksmethode een literatuurstudie. De voornaamste bronnen zijn handleidingen om de technische aspecten te begrijpen en te implementeren. Tijdens de opbouw van de frigobox wordt de werking geoptimaliseerd door diverse testen.

Het eerste hoofdstuk beschrijft de opbouw van de frigobox. Vervolgens wordt toegelicht hoe de app werkt. De volgfunctie wordt beschreven in hoofdstuk drie. In een vierde hoofdstuk wordt de temperatuurmeting beschreven. Daarna volgt een hoofdstuk over de inventaris. Als laatste wordt de verbinding tussen de app en de frigobox uitgelegd. In de conclusie wordt verteld of de vooropgestelde doelstellingen behaald zijn en wat de mogelijke verbeterpunten zijn.

## Opbouw

## App

### Features van de App

 - checken of bluetooth en GPS aanstaan -> zoniet, deze aanzetten.
 - connecteren met arduino via GSM / App
 - doosturen van geolocatie gegevens naar arduino via bluetooth.
 - vergrendelen & ontgrendelen van de frigobox (via bluetooth of NFC).

### Design van de app

Hier vind je de originele Figma file waarin het ontwerp van de app gebouwd werd: [Figma file](<https://www.figma.com/file/eEKTlIOeK6VJ5IYxP0VTZK/FrigoboxApp?node-id=0%3A1>)

### sources gebruikt voor app

 - <https://javatutorial.net/connect-android-device-android-studio>
 - <https://www.youtube.com/watch?v=nAcTO1LELN0>

## Volgfunctie

### onderzoek naar motoren

### Onderzoek naar power voor arduino / motoren:

Arduino Mega en Uno kunnen beide gepowered worden met een spanning tussen 7V en 12V (liefst, ze kunnen opzich ook draaien tussen 6 en 20V), een 9V output batterij is dus ideaal. Er bestaan ook laptop powerbanks, die deze spanning kunnen leveren, maar dan heb je snel een kost boven de €100. Een heroplaadbare 9V batterij zou in principe ook kunnen werken, maar 6AA batterijen zouden langer mee moeten gaan.

De gemiddelde runtime op batterij is rond de 10uur, maar daar zijn geen motoren ingerekend.

Ik heb op [AliExpress](<https://www.aliexpress.com>) wel wat mogelijke powerbanks voor redelijke prijzen gevonden (let wel op dat het output voltage tussen 6 en 20V moet blijven.

- [ROCK QC3 powerbank 10ah](<https://www.aliexpress.com/item/4000040465626.html?spm=a2g0o.productlist.0.0.5aa4fc138d7akw&algo_pvid=52b30fad-e2b2-48bc-9deb-97f8a324fa0a&algo_expid=52b30fad-e2b2-48bc-9deb-97f8a324fa0a-0&btsid=0be3743615818484143618356e8a4f&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_>)
- [Xiaomi MI Powerbank 10ah](<https://www.aliexpress.com/item/4000043404704.html?spm=a2g0o.productlist.0.0.5aa4fc138d7akw&algo_pvid=52b30fad-e2b2-48bc-9deb-97f8a324fa0a&algo_expid=52b30fad-e2b2-48bc-9deb-97f8a324fa0a-2&btsid=0be3743615818484143618356e8a4f&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_>)
- [Baseus 10ah plug-in](<https://www.aliexpress.com/item/33051393901.html?spm=a2g0o.productlist.0.0.5aa4fc138d7akw&algo_pvid=52b30fad-e2b2-48bc-9deb-97f8a324fa0a&algo_expid=52b30fad-e2b2-48bc-9deb-97f8a324fa0a-7&btsid=0be3743615818484143618356e8a4f&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_>)
- [Xiaomi redmi 20ah](<https://www.aliexpress.com/item/32850936433.html?spm=a2g0o.productlist.0.0.5aa4fc138d7akw&algo_pvid=52b30fad-e2b2-48bc-9deb-97f8a324fa0a&algo_expid=52b30fad-e2b2-48bc-9deb-97f8a324fa0a-11&btsid=0be3743615818484143618356e8a4f&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603_>)

Kunnen we powerbanks stacken / serieel gebruiken?

### Bronnen

- <https://forum.arduino.cc/index.php?topic=2067.0>
- <https://www.techradar.com/news/best-portable-laptop-battery-chargers-and-power-banks>
- <https://forum.arduino.cc/index.php?topic=305175.0>

## Temperatuurmeting

## Inventaris

## Verbinding

## Conclusie

## Literatuurlijst

## Bijlagenoverzicht

## Bijlagen

