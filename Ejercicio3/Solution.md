# Ejercicio 3

## ___```<p id="mission>```___
>There are a few selectors trying to apply a style to this tag wich are **p**, **.text** and **#mission**, this last one is above the other two selectors due to higher specificity, so the color of the font will be Dark Orange.

## ___```<p id="team">```___
>The styles trying to change the color are the **style="color : darkblue"** inline style and the **p**, **.text** and **#team** selectors. The dark blue color of the inline style will be applied thanks to the hierarchy rulings.

## ___```<p id="experience">```___
>In the conflict between the rules of **p**, **#experience**, **.text** and **#about p:last-child**, this last one is applied for having a scpecifity of ```(1,1,1)```, higher than the rest. THe color applied is **Green**.

## ___```<p id="services-intro">```___
>This one has a conflict in the **class** property, where both **.intro** and **text** are trying to change its color. The one who stablishes the color in the end is **.intro** due to being written later in the css thus overriding the **.text** color change. The color of the font will be **blue**

## ___``` <p id="offer">```___
> Despite having different conflicting rules such as **p**, **.text** and the **inline style**, the style **#offer** is the one who changes the color thanks to the **!important** tag on the color property that ignores any other attempts of changing it. The color will be **darkgreen**.