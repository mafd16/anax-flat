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

Typography
==============================================

På denna sidan visas det typografiska gridet. Det kallas även horisontellt grid, eller baseline grid. Man kan se det som ett papper i ett linjerat kollegieblock, dvs horisontella linjer att förhålla sig till. Detta är det första stycket.

Vi använder oss här av det magiska talet 24, det är alltså 24 pixlar mellan varje horisontell linje i bakgrunden.

Detta är en H1
==============
Ett stycke består av text, dvs en massa ord efter varandra åtskilda av skiljetecken. Ett skiljetecken kan t.ex. vara en punkt (.), ett kommatecken (,), ett utropstecken (!), eller något annat.

Ytterligare ett stycke under samma överskrift. Hur förhåller sig avståndet mellan överskrift och första stycket, jämfört med första och andra stycket?

En H2
-----
Text kan skrivas som *emphasized*. Det är oftast text med font-style italic. **Strong emphazised** verkar vara font-style bold.

### En H3
Mellan denna raden och
<br>
denna raden är det en `<br>`.

En hr (dvs en `<hr>`):
<hr>

###### En H6-överskrift
Vi testar en oordnad lista

+   äpple
+   päron
+   banan

och en numrerad lista

1. juice
2. kaffe
3. te

#### H4-överskrift, bild:

<img class="testbild" src="img/testbild.jpg" alt="svt testbild">

Detta är samma bild som på about-sidan.
