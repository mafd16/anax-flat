---
titleBreadcrumb: Designprinciper

views:
    byline:
        region: after-main
        template: default/content
        sort: 1
        data:
            meta:
                type: content
                route: block/byline
    flash:
        region: flash
        template: default/image
        data:
            src: "img/janloof.png"
...

Sida som kort beskriver tre designprinciper, som även kan testas i temaväljaren.

Temaväljaren finner du [här](theme-selector).

Designprinciperna är beskrivna i boken 'The Principles of Beautiful Web Design, 3rd Edition'.

<hr>

1. Volym
========

Denna designprincipen är beskriven i boken 'The Principles of Beautiful Web Design, 3rd Edition', kap 3, Volume and Depth. Tanken bakom principen är att sidan ska få ett djup, eller att elementen ska ha volym.

För att uppnå detta har jag gjort följande saker.

+ Bodyn har fått en skugga bakom sig, och rundade kanter. Simulerar t.ex. ett papper som ligger på ett bord.
+ Utvalda ställen har fått text-skugga, exempelvis site-logo-texten och alla h1-överskrifter.
+ Navigationslänkarna i headern har fått ett utseende lite likt knappar, med skugga under som gör att dom ser ut att hovra en bit ovanför sidan. För man musen över, klickar på eller är på länkens sida, så är knappen nedtryckt.
+ Bilder i main-delen har fått en vit ram, och utanför den en lätt skugga, allt för att simulera att det är ett fysiskt foto som ligger ovanför.

2. Rörelse
==========

Denna princip ska visa på rörelse i sidan. Det kan vara faktisk rörelse på element, eller element som är positionerade på ett sådant sätt att dom ser ut att röra på sig. Designen beskrivs i boken nämnd ovan i kap 3, Line och Shape.

Det jag har gjort här är

+ Länkarna i navbaren roteras när man hovrar över, klickar på dom och när man är på aktuell länks sida.
+ Fotot i main-delen (på första-, about- och gridsidan) är roterade, så det ser ut som om det är fysiska bilder utslängda på ett bord.
+ Bakgrunden har fått en cirkulär repeterande struktur, som kanske drar ögonen mot mitten. I ett skarpt läge skulle jag överväga att ha en bakgrundsbild med centrerande egenskaper istället.


3. Pattern
==========

Principen förklaras i boken nämnd ovan, i kap 3, Pattern. Tanken kan vara att skapa en struktur eller bakgrund som efterliknar t.ex. en tegelvägg eller trä. Att använda en bild som man repeterar för att få ett mönster är även ett bra sätt att spara vikt på sidan.

Det jag har gjort här är

+ Bakgrunden efterliknar ett badrumskakelgolv, genom en bild som repeteras.
+ Navbaren har fått länkar som alla är lika stora, för att de ska hålla sig till ett mönster. Texten i länkarna dols visserligen, men länken får tillräcklig längd vid hovring.
