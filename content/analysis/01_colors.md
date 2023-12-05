---
Title: Rapport kmom04
Description: Report in kmom04 on color schemes on wep pages.
Template: report
---

Analys av färgschema och typografi
==========================

## Inledning
Denna rapport analyserar val av färgschema och typografi på tre olika typer av hemsidor.

## Urval
De tre hemsidor som kommer att analyseras:
    * wikipedia.org - https://www.wikipedia.org/
    * netonnet.se - https://www.netonnet.se/
    * bvb.de - https://www.bvb.de/eng


<p style="line-height: 2; margin-top: 1em;">
wikipedia.org är en online encyklopedi där alla användare kan bidra med och redigera information.<br>
netonnet.se är webbutiken för företaget NetOnNet som är en återförsäljare av hemelektronik.<br>
bvb.de är den officiella hemsidan för det tyska fotbollslaget Borussia Dortmund.
</p>

Jag har valt att analysera tre olika typer av hemsidor med helt olika syfte. Jag valde just dessa tre hemsidor då det är hemsidor och företag jag är väl bekant med och de är stora och välkända företag vilket gör att deras färgschema och typografi bör vara professionellt och väl genomtänkt.

## Metod
För att ta fram färgschemat för respektive hemsida så används verktygen Color Contrast Accessibility Validator<sup>1</sup>, Color Combos<sup>2</sup>, ColorZilla<sup>3</sup> samt Web development tools.

För att ta fram vilka teckensnitt som används på hemsidorna används WhatFont<sup>4</sup>.

## Resultat

### wikipedia.org
<div class="webpage-screenshot">
    <img src="../assets/img/weppages/wikipedia.png" class="weppage-screenshot">
</div>

<table class="color-scheme-table">
    <tr>
        <td style="background-color: #ffffff">
        <td style="background-color: #f8f9fa">
        <td style="background-color: #ededed">
        <td style="background-color: #373737">
        <td style="background-color: #202122">
        <td style="background-color: #54595d">
        <td style="background-color: #447ff5">
        <td style="background-color: #3366cc">
    </tr>
</table>

Färgschemat som används på wikipedia.org kan bäst beskrivas som monokromatiskt och består av olika nyanser av vit, grå, svart och blå.

Wikipedia sätter generellt sätt inget typsnitt eller teckensnitt på sin hemsida<sup>5</sup>. Detta gäller för både för rubrikelement och brödtext. När man skriver en artikel på Wikipedia kan man dock välja att skriva viss text i ett specifikt typsnitt eller teckensnitt. font-family sätts därmed till sans-serif vilket resulterar i att det teckensnitt som visas är det teckensnitt som är satt som standardteckensnitt i ditt operativsystem. Till exempel så är standardteckensnitt om man inte själv bytt Segoe UI i Windows och San Francisco i MAC OS<sup>6</sup>.

Jag tycker att wikipedias minimalistiska och enkla val av färger och typsnitt speglar rätt bra vad jag ser som deras avsikt, att tillhandahålla informaton utan något krimskrams.

### netonnet.se
<div class="webpage-screenshot">
    <img src="../assets/img/weppages/netonnet.png">
</div>

<table class="color-scheme-table">
    <tr>
        <td style="background-color: #f2f2f2">
        <td style="background-color: #ffffff">
        <td style="background-color: #000000">
        <td style="background-image: radial-gradient(#cf2a24, #750e0a);">
        <td style="background-color: #ed1c24">
        <td style="background-color: #015582">
        <td style="background-color: #0078af">
        <td style="background-color: #ffa300">
    </tr>
</table>

Färgschemat för netonnet.se utgår från loggan som är blå och röd. Man använder ett triadiskt färgschema med den blåa och mörkröda färgen som utgångspunkt. Den tredje färgen ska dock vara gul på väg mot grön. Denna verkar isåfall vara ersatt med orange.

NetOnNet använder sig av typsnittet Open Sans på både rubrikelement och brödtext.

Jag tänker att både val av färger och typsnitt är vad jag förväntar mig av netonnet.se.

### bvb.de
<div class="webpage-screenshot">
    <img src="../assets/img/weppages/bvb.png">
</div>

<table class="color-scheme-table">
    <tr>
        <td style="background-color: #ffd900">
        <td style="background-color: #000000">
        <td style="background-color: #ffffff">
        <td style="background-color: #909090">
    </tr>
</table>

bvb.de använder sig av av sina egna typsnitt. För rubrikelement används BVBCopy-Bold eller BVBCopy-ExtraBold och för brödtext används BVBCopy-Regular.

Det används inte riktigt något färgschema på bvb.de. Färgerna som används är i stort sett bara gult och svart och vitt eller grått när det behövs. Det är färger med hög kontrast.

Gult och svart är färgerna på loggan och klubbfärgerna som används i alla delar av verksamheten. Jag tänker att dom vill få in en i klubbkänslan när man besöker hemsidan och det tycker jag verkligen att dom lyckas med.

## Analys
Jag är något förvånad över att man använder sig av flera nyanser av till exempel vit, grå och svart. Jag hade tänkt att man föredrar att bara se en nyans oav till exempel grå och att man därmed bestämmer sig för en nyans och försöker använda sig av den så mycket som möjligt istället för att börja använda ytterligare nyanser. Men det är inget som jag direkt noterar och stör mig på när jag besöker de olika hemsidoran så det fungerar tydligen bra att använda sig av flera oliak nyanser.

Både Wikipedia och NetOnNet använder sig av gråa och vita bakgrunder vilket känns lite tråkigt. Borussia Dortmund kör helt på sitt svartgula vilket jag kan uppskatta men jag kan inte säga att jag tycker den är direkt snyggare. Liknande så sticker deras teckensnitt ut lite grann vilket jag också uppskattar. Men ska jag läsa mycket text så väljer jag hellre Wikipedias val av ett väldigt simpelt teckensnitt, eller något man valt själv. Borussia Dortmunds texter är lite jobbiga att läsa då det är fullt vit på fullt svart vilket blir en för hög kontrast.

Jag tykcer det är intressant med det låga antalet olika teckensnitt som används på hemsidorna. Jag hade tänkt att man vill använda sig av åtminstone några stycken olika totalt sett.
## Referenser

<sup>1</sup> https://color.a11y.com/Contrast/ <br>
<sup>2</sup> https://www.colorcombos.com/grabcolors.html <br>
<sup>3</sup> https://addons.mozilla.org/en-US/firefox/addon/colorzilla/ <br>
<sup>4</sup> https://addons.mozilla.org/en-US/firefox/addon/zjm-whatfont/ <br>
<sup>5</sup> https://en.wikipedia.org/wiki/Wikipedia:Typography <br>
<sup>6</sup> https://granneman.com/webdev/coding/css/fonts-and-formatting/default-fonts <br>

## Övrigt
Denna rapport är skriven av Viktor Nordenberg.
