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
Mätningarna görs genom två verktyg. Google PageSpeed Insights används för att ta fram LCP, FID, CLS, FCP, INP och TTFB på desktop och mobil. DevTools i Mozilla Firefox används för att ta fram inladdningstid, antal resurser som laddas in och total storlek på den data som laddas in.

## Resultat

<iframe src="%base_url%/assets/spreadsheets/design_loads_1.htm" class="excel-loads-1">

<iframe src="%base_url%/assets/spreadsheets/design_loads_2.htm" class="excel-loads-2">

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


## Analys

## Referenser


## Övrigt
Denna rapport är skriven av Viktor Nordenberg.
