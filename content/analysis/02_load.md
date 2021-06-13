---
Title: Load
Description: Analysis of page speed ("kmom05")
---

# Analys av laddningstid och användbarhet

Denna uppgift handlar om att välja ut tre webbplatser och utvärdera laddningstid och användbarhet.

## Urval

Jag har valt ut samma tre webbplatser som i färganalysen, dvs:

[Team Nordic Trail](https://teamnordictrail.se)

[Runacademy](https://runacademy.se)

[Trailrunning Sweden](https://trailrunningsweden.se)

Jag valde dessa hemsidor eftersom det kändes relevant att fortsätta analysera de hemsidor jag gjorde färganalys på i förra kursmomentet.
#

## Metod
Jag använde mig av [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights) för att se vilka betyg hemsidorna fick gällande prestanda och hur de kan förbättra laddningstiden samt Chrome DevTools för analys av laddingstid m.m.
#

## Resultat

[Här finns länken](https://docs.google.com/spreadsheets/d/e/2PACX-1vT_B0_fFl06I0u5B99ksfBQZB26GAA2MQgMGFfkh0j4dIieYxxI8OqlSrCbKCdmHMlHXS2RSq6oUgv-/pubhtml) till mitt mätresultat från DevTools och PageSpeed.


**Hemsida 1: Team Nordic Trail**

[Team Nordic Trail](https://teamnordictrail.se) hade en genomsnittlig laddningstid på 5.49 sekunder vilket jag ändå tycker är acceptabelt. Genomsnittlig resurs är 10.53MB och sidans storlek är 6.50MB. Sidan får lågt betyg på PageSpeed Insight där betyget blev 8 (dator) och 10 (mobil). För att sidan ska kunna laddas snabbare kan de aktivera textkomprimering, ta bort resurser som blockerar renderingen samt ta bort CSS som inte används.

<img src=../assets/img/tnt.png alt="Team Nordic Trail">  
#

**Hemsida 2: Runacademy**

[Runacademys](https://runacademy.se) hade en genomsnittlig laddningstid på 2.82 sekunder vilket jag tycker är bra. Snittvärdet för resurser är 5.30MB och storleken 3.20MB. De klarar dock inte PageSpeed Insight så väl där betyget blev 27 (dator) och 20 (mobil). Tidsbesparing kan framför allt göras genom att skicka bilder i ett modernare bildformat.

<img src=../assets/img/runacademy.png alt="Runacademy">  
#

**Hemsida 3: Trailrunning Sweden**

[Trailrunning Swedens](https://trailrunningsweden.se) hemsida laddades på i genomsnitt 9,09 sekunder vilket är mycket långsamt. Snittvärdet för resurser var 17.13MB och storleken 9.97MB. I PageSpeed Insights prestandatest fick de betyget 7 (dator) och 6 (mobil). Åtgärder som de kan vidta för att snabba på laddningen är att skjuta upp inläsning av bilder som inte visas på skärmen, ta bort JavaScript som inte används och skicka bilder i modernare bildformat.

<img src=../assets/img/trailrunningsweden.png alt="Trailrunning Sweden">  
#

## Analys

Ingen av hemsidorna kan skryta med sin prestanda enligt PageSpeed Insight utan kan vidta flera åtgärder för att förbättra laddningstiden. En förbättringsåtgärd alla har gemensamt är att bilder inte hanteras optimalt. De kan t ex använda ett modernare bildformat.

Utifrån de mätvärden som blev resultatet i undersökningen rangordar jag hemsidorna enligt följande:

1. Runacademy
2. TeamNordicTrail
3. TrailRunningSweden

Runacademy laddar nästan direkt. När man laddar Team Nordic Trails hemsida  får man sitta och vänta på att bilderna laddas in men det går ändå ganska snabbt. TrailRunning Sweden är bedrövligt långsam och sidan är grå i flera sekunder (känns det som) innan bilder och text börjar laddas. De 9 sekunder det tar för hemsidan på jumboplats är inte acceptabelt enligt mina mått mätt, men de två andra klarar sig bra. Med andra ord går nog min gräns runt 5 sekunder.

## Övrigt

Analysen är gjord av Bettina Kron.
