---
title: "load"
date: 2024-11-10
---

Load
=======================

Uppgiften handlar om att välja tre olika webbplatser och mäta deras pagespeed samt analyser faktorer som påverkar pagespeed och diskutera hur kan de faktorer förbättras.

Urval
-----------------------

Jag har valt  tre webbplatser för att analysera. 

<li> ul.se </li>
<li> youtube.com </li>
<li> pixabay.com </li>

Jag har försökt att välja webbplatser som är olik varandra eftersom det är ladningstid som ska analyseras. Jag har valt ul.se eftersom jag tror att den sidan använder API och behöver uppdateras helatiden med tågtider och nya tågpositioner på kartan. Pixabay innehåller massvis med bilder och min erfarenhet från kmom05 säger att det blir  lätt tungt för sidan att laddas pga. bilder. Sammaresonemang har lett till även val av youtube.com, där tänker jag också att videos har stort storlek och det bör påverka ladningtider.

Alla tre webbplatser har valts pga. att de är olik varandra och jag tror att det kommer att synnas skillnad i deras ladningstid.

Metod
-----------------------

Jag använder två verktyg för att utföra undersökningen: pageSpeed Insights och devtools. Det används också google kalkylark för att samla in data och presentera.

Devtools används för att mäta laddningstid, antal resurser som laddas ner och totala storleken för webbplatser. Varje värde mäts tre gånger och sedan beräknas meddelvärdet för att hitta en tyngpunkt för värdet för att sedan kunna diskuteras.

PageSpeed Insights används för att mäta prestanada på verja sida. Värdet som samlas in kallas prestanda på hemsidan som blanannat inluderar First Content Paint (FCP) och Time to First Byte (TBT) som parameterar för prestanda.

Resultat
-----------------------

Insamlade resultat kan ses i figuren loadanalys:sheet1 nedan. Det observerades att pagespeed för desktop var alltid bättre än pagespeed för mobilen. Totala storleken på webbplatsen ändrades inte för pixabay och ul medan för youtube ändrades totala storleken varje gång. Antal resurser var konstanta för alla sidor.

När det gäller ladningstid var pixabay snabbast av alla med 259 ms medan ul på nummber två med 638 ms och youtube sist med 2830 ms. Det som kan påpekas är att ladningstid konvergerar med pageSpeed. Exempelvis pageSpeed: desktop var högst för pixabay och sämst för youtube. Dvs. rangordning utifrån pagespeed konvergerar med rangordning utifrån ladningstiden.

Däremot kan det hittas avvikelser mellan storleken och ladningstiden. Minsta storleken hade ul medan största storleken hade youtube. youtube hade sämst ladningstid medan ul var på nummer två trot att den hade mindre storlek än pixabay.

<div class="embed-container">
    <iframe src="https://docs.google.com/spreadsheets/d/e/2PACX-1vQrNhzgE8GqUqdeNl59K3P6q9Q5cjN0RcBMOunp9tJ7AsmZ1wx6MaRk0XqwdDgQdp3rC8ITyzrDKYaU/pubhtml?gid=0&amp;single=true&amp;widget=true&amp;headers=false"></iframe>
</div>

Analys
-----------------------

Jag tycker att det är svårt att bestämma en och samma gräns för varje webbplats för att avgöra vilket som är bättre eftersom det beror självklart på storleken av webbplatsen. Ifall man ska ignoerar det och endast utgå ifrån upplevelsen då vill man ha sin content så snabbt som möjligt så som (Wang & Phan, 2018) påpekar att user experience påverkar använding av webbplatser då skulle jag kunna säga att 3-4 sekunder är en rimlig gräns för webbplatsers ladningstid. Utifrån den gränsen har alla min valda webbplatser klarat sig bra. Detta kan bero på att två av de är ju webbplatser som är kända och används väldigt mycket av männsikor därför antar jag att företagen lägger tillräckligt mycket med resurser och tid för att förbättra sin kod så att det optimeras helatiden.

Enligt mina kunskaper och erfarenhet var alla tre webbplatser bra men pageSpeed Insights la fram några förslag som skulle kunna förbättra dessa webbplatser. Det var några faktorer som var gemensamma för alla tre webbplatser: minska körningstid för js, reducera js och CSS som inte används. Ul skulle kunna förbättras genom att minska påverkan av tredjepartskod och skicka bilder i moderna bildformat. Pixabay ska kunna förbättras genom att använda bilder med rätt storlek och även här genom att använda modernare bildformat.

Referenser
-----------------------
Google. PageSpeed Insights. Hämtad 2024-11-2, fråm https://pagespeed.web.dev/

Wang, Z. & Phan D (2018). Using Page Speed in Mobile Search. Google Developers. Hämtad 2024-11-24, från https://developers.google.com/search/blog/2018/01/using-page-speed-in-mobile-search

Författaren
-----------------------

Daud Nawaz