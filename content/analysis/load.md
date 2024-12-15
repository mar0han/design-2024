---
Title: Load
Description: This is our loadtime page.
Template: loadtime
---

Laddningstid på olika webbplatser
=======================

Undersökning av tre olika webbplatser och dokumentation på deras laddningstid och prestanda.

Urval
-----------------------

De tre webbplatser som blivit valda är:

- **[Crunchyroll](https://www.crunchyroll.com/):** En streaming hemsida likt Netflix.
- **[W3Schools](https://www.w3schools.com/):** En utbildningssida.
- **[Amazon](https://www.amazon.se/):** En E-handel hemsida.

Jag valde tre webbplatser från helt olika kategorier (underhållning, utbildning och handel) för att kunna jämföra deras laddningstid.

Metod
-----------------------

Med hjälp av PageSpeed Insights kan jag mäta en sidas prestanda på mobil och desktop, sedan använda Inspektor för att se laddningstid, resurser och storlek.

Resultat
-----------------------

*Crunchyroll*
<picture>
        <source media="(min-width: 668px)" srcset="%base_url%/image/crunchyroll.jpg?w=600&q=80">
        <source media="(min-width: 376px)" srcset="%base_url%/image/crunchyroll.jpg?w=400&q=80"">
        <img src="%base_url%/image/crunchyroll.jpg?w=375&h=211&crop-to-fit&q=80" alt="screenshot">
</picture>

- **[Crunchyroll](https://www.crunchyroll.com/):** Home page.
- **[Browse](https://www.crunchyroll.com/videos/popular):** Browse Popular Page.
- **[News](https://www.crunchyroll.com/news):** News Page.

<div class="wavy-line"></div>
*W3Schools*
<picture>
        <source media="(min-width: 668px)" srcset="%base_url%/image/w3schools.jpg?w=600&q=80">
        <source media="(min-width: 376px)" srcset="%base_url%/image/w3schools.jpg?w=400&q=80"">
        <img src="%base_url%/image/w3schools.jpg?w=375&h=211&crop-to-fit&q=80" alt="screenshot">
</picture>

- **[W3Schools](https://www.crunchyroll.com/):** Home page.
- **[Login](https://profile.w3schools.com/login?redirect_url=https%3A%2F%2Fwww.w3schools.com%2F):** Login Page.
- **[Spaces](https://www.w3schools.com/spaces/index.php):** Spaces Page.

<div class="wavy-line"></div>
*Amazon*
<picture>
        <source media="(min-width: 668px)" srcset="%base_url%/image/amazon.jpg?w=600&q=80">
        <source media="(min-width: 376px)" srcset="%base_url%/image/amazon.jpg?w=400&q=80"">
        <img src="%base_url%/image/amazon.jpg?w=375&h=211&crop-to-fit&q=80" alt="screenshot">
</picture>

- **[Amazon](https://www.amazon.se/):** Home page.
- **[Login](https://www.amazon.se/ap/signin?openid.pape.max_auth_age=0&openid.return_to=https%3A%2F%2Fwww.amazon.se%2Fgp%2Fbestsellers%3Fref_%3Dnav_ya_signin&openid.identity=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.assoc_handle=seflex&openid.mode=checkid_setup&openid.claimed_id=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0%2Fidentifier_select&openid.ns=http%3A%2F%2Fspecs.openid.net%2Fauth%2F2.0):** Login Page.
- **[Best Sellers](https://www.amazon.se/gp/bestsellers?ref_=nav_cs_bestsellers):** Best Sellers Page.

<div class="wavy-line"></div>
<div class="table-load">
    <iframe title="myTable" src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQHPon1ZS1a65dopcUg_D1Mj2kwBHq8NBa2t2GUgsJ6kw_Y7_wSutITd_RJQdwAHkSjYce3lsiMva6T/pubhtml?widget=true&amp;headers=false"></iframe>
</div>

Analys
-----------------------

*Crunchyroll*

Crunchyroll visar ganska bra prestanda på desktop på alla sidor. Det finns en tydlig skillnad i prestanda mellan desktop och mobil, där mobilversionen presterar sämre. Deras News sida har den lägsta prestandan av de tre, med ett Performance-betyg på 42 på desktop och 34 på mobil, vilket tyder på att sidan inte är lika optimerad för snabb laddning.

*W3Schools*

W3Schools visar mycket bra prestanda på desktop på alla sidor, med betyg över 90 för både Performance och Accessibility, samt bra resultat för SEO och Best Practices. Prestandan på mobil är lite sämre men inte stor skillnad.

*Amazon*

Amazon visar överlag ganska bra prestanda på alla sidor, men resultaten för mobil Performance och Accessibility är något lägre jämfört med de andra webbplatserna. På Best Sellers är Performance faktiskt bättre på mobil än på desktop, vilket betyder att mobilversionen är bättre optimerad. Generellt sett presterar desktopversionerna bättre än mobilversionerna på de flesta sidor.

Förbättring:

På alla sidor kan man förbättra laddningstiden genom att optimera och komprimera bilder och genom att optimera kod (ta bort onödiga mellanslag, kommentarer och tecken) kan filstorleken reduceras kraftigt, vilket gör att sidan laddas snabbare.

<div class="wavy-line"></div>

**1. W3Schools:** Prestanda: Utmärkt (128 ms - 492 ms)

**2. Crunchyroll:** Prestanda: Mycket bra (612 ms - 623 ms)

**3. Amazon:** Prestanda: Bra (44 ms - 1680 ms)


**Vinnare: W3Schools**

W3Schools vinner testet med snabba laddningstider på desktop. Webbplatsen erbjuder en snabb användarupplevelse, vilket gör den till det bästa alternativet enligt mig.

Jag tycker att en webbplats som laddar på under 2 sekunder är bra, medan en laddningstid på över 5 sekunder kan uppfattas som långsam.
I mitt urval av webbplatser klarar Crunchyroll och W3Schools det här gränsvärdet för de flesta sidor. På Amazon är desktopversionerna av Login och Best Sellers bra. Dock har Home-sidan en längre laddningstid på 1680 ms, vilket kan betraktas som långsamt.