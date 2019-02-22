Rapport - Mäta sidhastighet
=======================

Uppgiftens syfte är att mäta och jämföra laddningstiden på 3 olika webbsidor. Därefter analysera resultatet och fundera kring laddningstiden.

Urval
-----------------------
För denna övning har jag valt 3 sidor relaterade till film och tv industrin. Valet gjordes då branschen är visuellt framfört. Ofta används video-trailers samt högkvalitets bilder för att presentera produkterna och därifrån kan man se hur sidorna balanserar mellan det visuella och det funktionella.

Sidorna jag valt är:

https://www.lionsgate.com/

https://disney.se/

https://www.universalpictures.com/


Sidorna presenterar sig själva på olika sätt, men alla har en bra del av visuell stimulation.

Metod
-----------------------
För att samla information kring sidornas läsningstid kommer de främst mätas med Google Pagespeed (https://developers.google.com/speed/pagespeed/insights/). Därifrån noteras poängen som anges. Sidorna kommer även jämföras på lokal maskin via devtools där hastighetesurser kommer noteras (Snittet utifrån 3 laddningar per sida).

I efterhand kommer informationen analyseras samt jämföras utifrån resultaten.

Resultat
-----------------------
## Lionsgate:

<img src="image/lionsgate.png" width=90% alt="lionsgate">

Google Pagespeed Insights score (Dator): 99 / 100.

Första innehållsrenderingen: 4.3s.

Första indatafördröjningen: 53ms.

Första uppritningen av innehåll: 1.4s.

Mozilla Devtools Nätverks-analys:

Laddningstid: 11.75666667s.

Nedladdade Resurser: 3.24 mb.

Anmärkning kring sidan:

Sidan har en introduktions-sektion som gör att tiden tills innehållet presenteras är väldigt fördröjd. Med tanke på laddningstiden gentemot resursnedladdnigen känns det som om detta kan bearbetas bättre.



## Disney:

<img src="image/disney.png" width=90% alt="disney">

Google Pagespeed Insights score (Dator): 80 / 100.

Första innehållsrenderingen: 1.9s.

Första indatafördröjningen: 63ms.

Första uppritningen av innehåll: 1.0s.

Mozilla Devtools Nätverks-analys:

Laddningstid: 4.056666667s.

Nedladdade Resurser: 2.65 mb.

Anmärkning kring sidan:

Mycket bildfokus men inget alltför märkvärdigt. Eventuellt kunde en omnavigering av sidans bilder (och storlek) leda till att man kan ladda upp sidans innehåll snabbare (enbart den stora bilden vid första laddning).



## Universal Pictures:

<img src="image/universal_pictures.png" width=90% alt="universal_pictures">

Google Pagespeed Insights score: 50 / 100.

Första innehållsrenderingen: 6s.

Första indatafördröjningen: 305ms.

Första uppritningen av innehåll: 0.5s.


Mozilla Devtools Nätverks-analys:

Laddningstid: 17.96s.

Nedladdade Resurser: 16.59 mb.


Anmärkning kring sidan:

Sidan har en väldigt mycket innehåll som presenteras, detta leder till en segare och mer krävande sidladdning. Samtidigt laddas det in iterativt, sidan blir funktionell väldigt snabbt.

Enligt Pagespeed Insights så kan ett bättre bildformat leda till ca 9 sekunders tidsförminskning.

Allmänt:
Sidorna är inte direkt komparabla med varandra, då exempelvis Lionsgate var till viss del en portal enbart för att navigera till delsidor/innehållet. Universal Pictures (med mycket större nedladdningskrav) har video-embedding m.m. som gör sidan mer funktionellt användbar i och för sig själv.

Lionsgate och Disney är nog mer jämförbara med varandra än Universal Pictures. Alla 3 sidorna rekommenderades att minska antalet steg i viktiga orderkedjor.

Analys
-----------------------
I min åsikt har sidorna inte något som gemensamt är ett större fel. Bilderna och presentation är sidornas identitet och behöver finnas. Det var inget större fel som jag identifierade genom alla 3 sidorna som direkt kunde affektera sidans laddningstid, eventuellt bara orderkedjorna.

Både Disney och Lionsgate klarade sig väl igenom PageInsights analys, varav det tillsynes verkar som om Universal Pictures är i fel, då bildformat indikeras spara flera sekunder i laddningstid.

Ranking enligt Google Insights:

	1. Lionsgate (99 / 100)

	2. Disney (80 / 100)

	3. Universal Pictures (50 / 100)

Snabbast i test:

	1. Disney (4.1s)

	2. Lionsgate (11.8s)

	3. Universal Pictures (18s)

Minst resurskrav i test:

	1. Disney (2.65mb)

	2. Lionsgate (3.24mb)

	3. Universal Pictures (16.59mb)

Allmänt är Disney bäst (2/3 första-platser) och Universal Pictures sämst. Som nämnts ovan i texten är sidorna lite annorlunda i hur dem presenteras och fungerar därav mer testning och en mer komprehensiv analys skulle behövas för att effektivt göra jämförelsen av vilken som skapats på 'bäst sätt'.

I min åsikt är enbart disney en sida som väl utför sin funktion utan att överdriva i andra områden. Den har en klar struktur, laddar snabbt och navigation inom sidan fungerar enkelt. Trots att Lionsgate har bra poäng på Google Insights, liknande resurskrav tycker jag att den artificiella fördröjningen sidan har gör den sämre.

I min åsikt bör inte sidorna kräva mer än  6 sekunder för att presentera allmän information samt vara visuellt tilltalande. Om man tar Lionsgate som exempel, för ett första besök är den intressant, men kan inte tänka mig använda sidan som en resurs för att leta upp deras filmer, då den känns trög och ineffektiv i detta syfte. Samma gäller för universal, att all information, alla trailers och liknande presenteras på framsidan gör sidan så seg, att jag skulle nog hellre använda youtube eller annan media för att komma åt den.

Samtidigt skulle jag nog ha större krav på tid utav sidor såsom youtube och google, där successiv användning leder till accumulerad laddningstid. Exempelsidorna säljer inte produkter direkt och har inget som kräver mitt besök/återbesök.

Referenser
-----------------------
https://www.lionsgate.com/
https://disney.se/
https://www.universalpictures.com/

Övrigt
-----------------------
Oskar Dans
