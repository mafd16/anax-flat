Sida som visar att min LESS-struktur fungerar genom att visa upp bilder i olika storlekar.

<!--
Följande shortcodes kan ersätta motsvarande <figure> elementen i blogg-texten. Inkludera hakparanteserna.

    [FIGURE src="image/dbwebbisar.jpg?w=200&h=150&a=0,20,20,50&cf" class="right"]
    [FIGURE src="image/dbwebbisar.jpg?w=700" caption="Här är en liten del av den större planschen."]
    [FIGURE src="https://dbwebb.se/img/dbwebb.jpg?w=700" caption="Den stora planschen."]
-->

<hr>

Images in different sizes
=========================

Width and height for a landscape picture.

[FIGURE src="image/janloof.png?w=120" caption="Width 120."]

[FIGURE src="image/janloof.png?h=120" caption="height 120."]

[FIGURE src="image/janloof.png?w=120&h=120" caption="width 120 and height 120."]

Resize a picture.
================

Stretch. Stretch the image so that the resulting image has the defined width and height.

[FIGURE src="image/janloof.png?w=400&h=400&stretch" caption="width 400 and height 400, stretch."]

Crop to fit. Keep the aspect ratio and crop out the parts of the image that does not fit.

[FIGURE src="image/janloof.png?w=600&h=300&crop-to-fit" caption="width 600 and height 300, crop to fit."]

Fill to fit. Keep the aspect ratio and fill the blank space with a background color.

[FIGURE src="image/janloof.png?w=600&h=300&fill-to-fit=FF0000" caption="width 600 and height 300, fill to fit, backgroundcolor: red."]

Crop to fit, and choose where in picture using percentages. Keep the aspect ratio and crop out the parts of the image that does not fit.

[FIGURE src="image/janloof.png?w=300&h=300&crop-to-fit&area=0,60,0,0" caption="width 300 and height 300, crop to fit, remove 60% to the right."]


Two screenshots
===============

This first picture shows my tools for working!

[FIGURE src="image/screenshot1.png?w=300&h=300&crop-to-fit&area=0,30,40,30" caption="width 300, height 300, crop-to-fit, area 0,30,40,30."]

This second picture shows my colorchooser!

[FIGURE src="image/screenshot2.PNG?w=300&h=300&crop-to-fit&area=10,20,30,30" caption="width 300, height 300, crop-to-fit, area 10,20,30,30."]
















<!-- remove... -->
