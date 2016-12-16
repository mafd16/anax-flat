---
titleBreadcrumb: Om teman

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



Om teman på denna sidan
==============================================

[Temaväljare](theme-selector)

På denna sidan beskriver jag varje anpassat tema som jag nu har skapat. Jag beskriver och visar den färgpalett jag använt.

Base
----
Minimal style, bara den enkla basen.
Detta tema är egentligen inte mycket att säga om. Nästan ingen styling är gjord. Det som ändå är gjort är att sidorna grid och typography visar sina grids, och jag har justerat ner storleken på någon bild som annars tog upp hela sidan.

Default
-------
Som default använder jag den stylingen som jag har haft på sidan tidigare i kursen. Bakgrundsfärgen är ljusblå-aktig, och footern är grå. I övrigt är det inte mycket styling gjord, förutom att få allt på rätt plats och storlek, och att få allt att fungera bra responsivt.

<table>
    <tr>
        <td style="height: 50px; width: 50px; background-color: #d0fafa"> </td>
        <td style="height: 50px; width: 50px; background-color: #576969"> </td>
        <td style="height: 50px; width: 50px; background-color: #3F4C4C"> </td>
        <td style="height: 50px; width: 50px; background-color: #bebebe"> </td>
    </tr>
    <tr>
        <td>#d0fafa</td>
        <td>#576969</td>
        <td>#3F4C4C</td>
        <td>#bebebe</td>
    </tr>
</table>

Light
-----
Till light-temat har jag använt helt vit bakgrund, en ljus grå färg till footern, och något mörkare grå till borders i footern. Målet var att hålla det mycket enkelt. I övrigt så är sidan funktionellt stylad (ex responsivitet) precis som default-temat.

<table>
    <tr>
        <td style="height: 50px; width: 50px; background-color: #FFF"> </td>
        <td style="height: 50px; width: 50px; background-color: #e0e0e0"> </td>
        <td style="height: 50px; width: 50px; background-color: #3F4C4C"> </td>
    </tr>
    <tr>
        <td>#FFF</td>
        <td>#e0e0e0</td>
        <td>#3F4C4C</td>
    </tr>
</table>

Color
-----
Detta färgtemat skulle innehålla lite mer färg än light-temat. Jag har lagt en mörkare lila-grå färg på footern, och gjort borders rosa-aktiga.

<table>
    <tr>
        <td style="height: 50px; width: 50px; background-color: #FFF"> </td>
        <td style="height: 50px; width: 50px; background-color: #FF7876"> </td>
        <td style="height: 50px; width: 50px; background-color: #7F6261"> </td>
    </tr>
    <tr>
        <td>#FFF</td>
        <td>#FF7876</td>
        <td>#7F6261</td>
    </tr>
</table>

Dark
----
Till detta färgtema har jag lagt en mörkblå färg som bakgrund, och en lite ljusare blå som borders. Footern blev grön-brun-aktig, och fick mörk-gula borders. Texten fick en ljusare gul färg. Jag har även stylat länkarna i navbaren, och även den responsiva navbaren.

<table>
    <tr>
        <td style="height: 50px; width: 50px; background-color: #030033"> </td>
        <td style="height: 50px; width: 50px; background-color: #0B0557"> </td>
        <td style="height: 50px; width: 50px; background-color: #473D07"> </td>
        <td style="height: 50px; width: 50px; background-color: #7E6A01"> </td>
        <td style="height: 50px; width: 50px; background-color: #ECC700"> </td>
    </tr>
    <tr>
        <td>#030033</td>
        <td>#0B0557</td>
        <td>#473D07</td>
        <td>#7E6A01</td>
        <td>#ECC700</td>
    </tr>
</table>

Colorful
--------
Till detta färgtemat ville jag skapa samma känsla som hos br.se, som jag analyserade i sidan analysis. Det skulle kännas lite lekfullt. Eftersom det skulle vara ett triadiskt färgschema så valde jag rött, blått och gult. Det blåa fick bli bakgrundsfärg, och det röda bakgrundsfärg på footern. Sen satte jag en mörkare röd på typsnitten.

<table>
    <tr>
        <td style="height: 50px; width: 50px; background-color: #0094FF"> </td>
        <td style="height: 50px; width: 50px; background-color: #FFFF00"> </td>
        <td style="height: 50px; width: 50px; background-color: #FF1914"> </td>
        <td style="height: 50px; width: 50px; background-color: #B2B228"> </td>
        <td style="height: 50px; width: 50px; background-color: #B20C09"> </td>
    </tr>
    <tr>
        <td>#0094FF</td>
        <td>#FFFF00</td>
        <td>#FF1914</td>
        <td>#B2B228</td>
        <td>#B20C09</td>
    </tr>
</table>


Typography
----------
Här använde jag mig färgmässigt av samma style som mitt default-tema. Sen har jag lagt på lite olika typsnitt på olika ställen. Jag började med site-logo-texten som fick fonten Permanent Marker. Den efterliknar en bred tuschpenna. Navbaren fick en egen font vid namn Exo. Alla headers fick en serif-font vid namn Alegreya, och all annan text fick fonten Amaranth som är sans-serif.
