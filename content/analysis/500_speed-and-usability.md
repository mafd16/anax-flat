---
views:
    byline:
        region: after-main
        template: default/content
        sort: 1
        data:
            meta:
                type: content
                route: block/byline
...
Speed and usability
===============================

Här ska jag utvärdera webbplatsers laddningstid och användbarhet.

När jag gjort mitt urval så har jag letat efter en sida med väldigt lite innehåll, som bör kunna laddas snabbt. Jag har även letat efter en sida med stort innehåll, som då kan ta lång tid att ladda. Jag ville även ta med en sida med mycket innehåll, som jag även har en föreställning om att inte vara så särskilt användarvänlig.

De webbplatser jag har valt att analysera är:

+ vecka.nu (lite innehåll.)
+ youtube.com (eventuellt stort innehåll?)
+ smhi.se (mycket info och krångligt innehåll?)
+ turfgame.com


Hur jag har mätt de olika delarna
=================================

Jag har använt google pagespeed för ena delen av analysen. Sen har jag använt mig av webbläsarens utvecklarverktyg, och där nätverks-fliken för att mäta laddningstid, förfrågningar och storlek på webbsidans laddade innehåll.

Rådatan för min analys går att finna i ett [Google kalkylark](https://docs.google.com/spreadsheets/d/1W6-cuXgtjTKOK_ymiyEVGOb7AFUdNQqadtDI6bODJXI/edit?usp=sharing).



<hr>

1. vecka.nu
--------------------------

#### Snapshot på webbplatsen.

<img src="img/analysis/vecka1.JPG" alt="vecka.nu">

#### Välj ut tre sidor (bifoga länkarna) som skall mätas med Google Pagespeed. Mät på både Mobile och Desktop. Notera de betyg som ges.

På vecka.nu finns bara en sida. Den får följande betyg på Google Pagespeed.

Mobile:  
Användarupplevelse: 87/100.  
Hastighet: 98/100.

Desktop:  
Förslagsöversikt: 98/100.

#### För varje sida, mät med devtools flik networks och notera sidans laddningstid tillsammans med antalet resurser som laddas samt sidans totala storlek. För varje sida gör mätningen tre gånger och ta snittet av mätvärdena.

Sidan som är väldigt enkel i sin natur använder bara fyra resurser, och laddas väldigt fort. Genomsnittsvärdena är

+ Laddningstid, 0,54 s
+ Antalet resurser, 4
+ Total storlek, 34 kb

#### Diskutera och skriv två meningar om hur webbplatsen kan förbättra sig.

Då sidan innehåller väldigt lite så finns det inte mycket att jobba med. Det som kan göras och som pagespeed även klagar på är att sidan inte är mobilanpassad. Sidan återges på precis samma sätt i mobilen som på desktop.


2. youtube.com
--------------------------

#### Snapshot på webbplatsen.

<img src="img/analysis/youtube1.JPG" alt="youtube.nu">

#### Välj ut tre sidor (bifoga länkarna) som skall mätas med Google Pagespeed. Mät på både Mobile och Desktop. Notera de betyg som ges.

[youtube.com](https://www.youtube.com)

Mobile:  
Användarupplevelse: 99/100.  
Hastighet: 63/100.

Desktop:  
Förslagsöversikt: 73/100.

[youtube.com/feed/trending](https://www.youtube.com/feed/trending)

Mobile:  
Användarupplevelse: 100/100.  
Hastighet: 57/100.

Desktop:  
Förslagsöversikt: 80/100.

[youtube.com/channels](https://www.youtube.com/channels)

Mobile:  
Användarupplevelse: 65/100.  
Hastighet: 61/100.

Desktop:  
Förslagsöversikt: 76/100.


#### För varje sida, mät med devtools flik networks och notera sidans laddningstid tillsammans med antalet resurser som laddas samt sidans totala storlek. För varje sida gör mätningen tre gånger och ta snittet av mätvärdena.

För de tre sidorna har jag noterat följande genomsnittsvärden

youtube.com

+ Laddningstid, 61,83 s
+ Antalet resurser, 132
+ Total storlek, 12 204 kb

youtube.com/feed/trending

+ Laddningstid, 16,17 s
+ Antalet resurser, 44
+ Total storlek, 2 693 kb

youtube.com/channels

+ Laddningstid, 16,33 s
+ Antalet resurser, 241
+ Total storlek, 3 406 kb

#### Diskutera och skriv två meningar om hur webbplatsen kan förbättra sig.

Det är intressant att notera att två av sidorna får väldigt bra betyg på användarupplevelse i mobil (99 och 100), medans den tredje sidan bara får värdet 65 på motsvarande test. Det som är dåligt på alla tre är hastigheten. Det tar väldigt lång tid att ladda klart sidan. Där kan dom definitivt förbättra sig. Några sätt att göra detta är att se till att innehåll ovanför mitten (fold) renderas snabbare, eller att undvika omdirigering. Dom kan också bli bättre på att utnyttja cachelagring i webbläsaren.




3. smhi.se
--------------------------

#### Snapshot på webbplatsen.

<img src="img/analysis/smhi1.JPG" alt="smhi.se">

#### Välj ut tre sidor (bifoga länkarna) som skall mätas med Google Pagespeed. Mät på både Mobile och Desktop. Notera de betyg som ges.

[smhi.se](http://www.smhi.se)

Mobile:  
Användarupplevelse: 92/100.  
Hastighet: 53/100.

Desktop:  
Förslagsöversikt: 70/100.

[smhi.se/bloggar/vaderleken-2-3336](http://www.smhi.se/bloggar/vaderleken-2-3336)

Mobile:  
Användarupplevelse: 97/100.  
Hastighet: 67/100.

Desktop:  
Förslagsöversikt: 84/100.

[smhi.se/kunskapsbanken-2-3251](http://www.smhi.se/kunskapsbanken-2-3251)

Mobile:  
Användarupplevelse: 94/100.  
Hastighet: 67/100.

Desktop:  
Förslagsöversikt: 83/100.


#### För varje sida, mät med devtools flik networks och notera sidans laddningstid tillsammans med antalet resurser som laddas samt sidans totala storlek. För varje sida gör mätningen tre gånger och ta snittet av mätvärdena.

För de tre sidorna har jag noterat följande genomsnittsvärden

smhi.se

+ Laddningstid, 7,57 s
+ Antalet resurser, 111
+ Total storlek, 3191 kb

smhi.se/bloggar/vaderleken-2-3336

+ Laddningstid, 3,43 s
+ Antalet resurser, 36
+ Total storlek, 1145 kb

smhi.se/kunskapsbanken-2-3251

+ Laddningstid, 3,61 s
+ Antalet resurser, 42
+ Total storlek, 1501 kb

#### Diskutera och skriv två meningar om hur webbplatsen kan förbättra sig.

Smhi bör snabba upp sin sida, då en relativt snabb inläsning ändå uppfattas som långsam. Några förslag som pagespeed rekommenderar är att komprimera bilder, utnyttja cachelagring, och snabba upp rendering av innehåll ovanför folden. När det gäller mobil visning så bör smhi förstora tryckytor, dvs se till att länkar inte sitter för nära varandra.



4. turfgame.com
--------------------------

#### Snapshot på webbplatsen.

<img src="img/analysis/turfgame1.JPG" alt="turfgame.com">

#### Välj ut tre sidor (bifoga länkarna) som skall mätas med Google Pagespeed. Mät på både Mobile och Desktop. Notera de betyg som ges.

[turfgame.com/](https://turfgame.com/)

Mobile:  
Användarupplevelse: 56/100.  
Hastighet: 42/100.

Desktop:  
Förslagsöversikt: 49/100.

[turfgame.com/toplist](https://turfgame.com/toplist)

Mobile:  
Användarupplevelse: 54/100.  
Hastighet: 51/100.

Desktop:  
Förslagsöversikt: 68/100.

[turfgame.com/map](https://turfgame.com/map)

Mobile:  
Användarupplevelse: 56/100.  
Hastighet: 50/100.

Desktop:  
Förslagsöversikt: 62/100.


#### För varje sida, mät med devtools flik networks och notera sidans laddningstid tillsammans med antalet resurser som laddas samt sidans totala storlek. För varje sida gör mätningen tre gånger och ta snittet av mätvärdena.

OBS! För dessa sidor så skickas hela tiden nya requests mot ett api, för att t.ex. uppdatera listor på hemsidan såsom t.ex. 'senaste zontagningarna', 'top today takeovers' och 'latest medals'. Det är därför svårt att sätta ett stop på när sidan har laddat klart. Jag tog därför tidpunkten då laddikonen under favikonen slutat snurra. För de tre sidorna har jag noterat följande genomsnittsvärden.

turfgame.com

+ Laddningstid, 16,99 s
+ Antalet resurser, 162
+ Total storlek, 7534 kb

turfgame.com/toplist

+ Laddningstid, 3,80 s
+ Antalet resurser, 66
+ Total storlek, 1067 kb

turfgame.com/map

+ Laddningstid, 6,00 s
+ Antalet resurser, 87
+ Total storlek, 2368 kb

#### Diskutera och skriv två meningar om hur webbplatsen kan förbättra sig.

Webbplatsen fick med råge sämst betyg på pagespeed av de fyra analyserade sidorna. Till att börja med så är sidan inte mobilanpassad, även om man har haft det tänket i den senast tillagda fliken. Vidare så får hastigheten dåligt betyg, och där kan dom arbeta med att utnyttja cachelagring, optimera bilder, minifiera kod och minska svarstid från server.



Sammanfattning
==============

Det som sidorna genomgående har fått nedslag på, och som kan förbättras är rendering av innehåll ovanför fold, förstora tryckytor (hålla isär länkar i mobil vy), utnyttja cachelagring bättre och optimera bilder.  

Rangordning av webbplatserna
============================

Om man tar snittvärdena av värdena från pagespeed så får jag följande lista:

1. 94 / 100 vecka.nu
2. 78 / 100 smhi.se
3. 75 / 100 youtube.com
4. 54 / 100 turfgame.com

Dock så lägger jag gärna in mina personliga åsikter här, och jag tycker att vecka.nu som innehåller så lite borde vara bättre, åtminstone på mobil vy. Därför rankar jag sidorna enligt följande:

1. smhi.se
2. youtube.com
3. vecka.nu
4. turfgame.com

Smhi blir vinnare, med youtube tätt efter. Turfgame kommer sist, trots att min personliga upplevelse av den sidan i många fall är bättre än t.ex. smhi.



Gräns för absolut laddningstid
==============================

Detta var inte helt självklart för mig, så jag var tvungen att testa några ytterligare webbplatser och mäta deras laddningstid. Jag kom fram till att en laddningstid under 3 sekunder kan räknas som snabb. För mitt urval innebär det att enbart vecka.nu kan räknas som snabb. Jag tycker smhi och turfgame har acceptabel laddningstid, medan youtube borde förbättra sig på denna punkten.


Deltagare i analysen
====================

Denna analysen har jag arbetat fram själv.
