---
Title: Rapport kmom05
Description: Report in kmom05 ?.
Template: report
---

Laddningstid och användbarhet på hemsidor för TV-kanalers streamningstjänster
==========================

## Inledning
Denna rapport undersöker och jämför inladdningar av hemsidor för TV-kanalers streamningstjänser i bland annat inladdningstider och användbarhet.

## Urval
De tre hemsidor som undersöks:
    * tv4play.se - https://www.tv4play.se/
    * svtplay.se - https://www.svtplay.se/
    * discoveryplus.com/se - https://www.discoveryplus.com/se

<br>
Jag valde hemsidor för tre stora svenska TV-kanalers streamningstjänser då de har en ett liknande syfte och konkurrerar med varandra.

## Metod
Mätningarna görs genom två olika verktyg. Google PageSpeed Insights används för att ta fram LCP, FID, CLS, FCP, INP och TTFB på desktop och mobil. DevTools i Mozilla Firefox används för att ta fram inladdningstid, antal resurser som laddas in och total storlek på den data som laddas in.

## Resultat

<iframe src="%base_url%/assets/spreadsheets/design_loads_1.htm" class="excel-loads-1"></iframe>
<i>Tabell 1</i>

<br>

<iframe src="%base_url%/assets/spreadsheets/design_loads_2.htm" class="excel-loads-2"></iframe>
<i>Tabell 2</i>

### tv4play.se

<div class="play-screenshot">
    <a href="%base_url%/image/tv4play.png" target="_blank">
        <picture>
            <source media="(min-width: 600px)" srcset="%base_url%/image/tv4play.png?w=550">
            <source media="(min-width: 400px)" srcset="%base_url%/image/tv4play.png?w=400">
            <source media="(min-width: 300px)" srcset="%base_url%/image/tv4play.png?w=300">
            <img src="%base_url%/image/tv4play.png?w=200" alt="tvplay.se screenshot">
        </picture>
    </a>
</div>

I Tabell 1 kan vi se att laddningstiden på tv4.play är i snitt 3,16 sekunder vilket är rätt lång tid för den dator och internetanslutning som testarna i Tabell 1 är gjorda på. Detta kan till stor del bero på den video som laddas och börjar spelas upp i bakgrunded så fort den har laddads ned. Sidan laddas dock in med en bakgrundsbild istället och fungerar bra långt innan bakgrundsvideon har laddads ned. Sidan betyg från testerna med Googles PageSpeed på desktop är bra. Testerna på mobil är något sämre men det finns ingen speciellt att anmärka på.

För att minska inladdningstiden och den data som användaren behöver ladda ned så kan se över den bakgrundsvideo man använder.

### svtplay.se

<div class="play-screenshot">
    <a href="%base_url%/image/svtplay.png" target="_blank">
        <picture>
            <source media="(min-width: 600px)" srcset="%base_url%/image/svtplay.png?w=550">
            <source media="(min-width: 400px)" srcset="%base_url%/image/svtplay.png?w=400">
            <source media="(min-width: 300px)" srcset="%base_url%/image/svtplay.png?w=300">
            <img src="%base_url%/image/svtplay.png?w=200" alt="tvplay.se screenshot">
        </picture>
    </a>
</div>

svtplay har den klart snabbaste inladdningstiden av de tre hemsidorna. Detta beror till viss del att man laddar ned klart mindre data än för tv4play och discoveryplus, ca 40% så mycket. svtplay använder sig av en ladningsskärm tills man laddad ned all data så när man kommer fram till hemsidans innehåll så har allting laddads färdigt.

Värdena i Tabell 2 från Google PageSpeed är generellt bra, framför allt på desktop. På mobil så finns det förbättringspotential, hemsidan har rätt så svaga värdet på INP (den längsta tid från flera mätningar över hur lång tid det tar från en förfrågan tills att innehåll börjar renderas) och CLS (oväntad förflyttning av layout).

Det som svtplay kan förbättra är att minska hur mycket oväntat förflyttning av layout som sker när man besöker hemsidan på mobilen.

### discoveryplus.com/se

<div class="play-screenshot">
    <a href="%base_url%/image/discoveryplus.png" target="_blank">
        <picture>
            <source media="(min-width: 600px)" srcset="%base_url%/image/discoveryplus.png?w=550">
            <source media="(min-width: 400px)" srcset="%base_url%/image/discoveryplus.png?w=400">
            <source media="(min-width: 300px)" srcset="%base_url%/image/discoveryplus.png?w=300">
            <img src="%base_url%/image/discoveryplus.png?w=200" alt="tvplay.se screenshot">
        </picture>
    </a>
</div>

discoveryplus har totalt sett kanske de sämsta värderna av de tre hemsidorna. De har långsammast laddningstid, trots att man laddar in mindre data än tv4play. Testerna med Google PageSpeed är kasnke inte kritiska men lämnar mer att önska. På mobilen är det likt svtplay är svaga värden på INP och CLS men det som sticker ut är det svaga värdet på INP även på desktop.

Det man kan förbättra är att minska tiden det tar från att man gör en förfrågan tills att innehåll börjar renderas genom att optimera eller skjut upp de skript som körs, minska renderingsblockerande resurser eller optimera bilder.

## Analys
De tre sidorna har generellt sett liknande värdet och fungerar rätt så bra. Det är INP (den längsta tid från flera mätningar över hur lång tid det tar från en förfrågan tills att innehåll börjar renderas) och CLS (oväntad förflyttning av layout) som sidorna får lite svagare väden på och framför allt på mobil. Jag tycker inte det finns något särskilt anmärkningsvärt resultat från de tester som utförds.

## Övrigt

### Ranking

1. svtplay.se
2. tv4play.se
3. discoveryplus.se

<br>
svtplay har den snabbase inladdningstiden och har generell sett bäst värden från testerna. Det är inte heller något som sticker ut som särskild dåligt jämfört med de andra två hemsidorna. tv4play och discoveryplus har liknande värden från testerna men tv4play har totalt sett lite bättre värden och kammar därmed hem andraplatsen.


### Övre gräns för inladdningstid
Jag tänker mig att med en bra dator och internetuppkoppling så vill jag inte att inladdningstiden för en hemsidan ska vara mer än ca 2-3 sekunder. Sätt gränsen för en snabb hemsida till 2 sekunder. Isåfall klarar svtplay gränsen men ej tv4play och discoveryplus. Det ska dock sägas att tv4play uppleves som fördiginladdad vid ca 1,5-2 sekunder och det är gissningsvis bakgrundsvideon som skjuter upp inladdningstiden.

### Upphovsperson
Denna rapport är skriven av Viktor Nordenberg.
