# Code Refractor
UWA web developement boot camp 2021

## Task:
go through the given html and css to build better semantics and or reform the scructor to read easier and to respond better

## what I managed to do:
first i was given a html and css file. 
![](./assets/screenshots/origonal_code.jpg)
<br>
so i went through looking for better semantics such as section tags,asides,articles and alt tags on all imgs
![](assets\screenshots\semantics1.jpg)
![](assets\screenshots\semantics2.jpg)
<br>

gave the nav its own section
![](assets\screenshots\navsection.jpg)
<br>
put the main text into article tags
![](assets\screenshots\article.jpg)
<br>
put the side bar into aside tags
![](assets\screenshots\aside.jpg)
<br>
also changed the footer h2 to h4 to organise better
![](assets\screenshots\h4.jpg)
<br>
There was also i missing id tag in the nav so i added a new id tag
![](assets\screenshots\newid.jpg)

## What i did to the css:
now the css was abit all over the place there were many double ups of code and elements and the code wasnt organised very well either<br>
so first i seperate the css into two seperate css files headerFooter and body (which included all links and imgs)
<br>
I then grouped up the headers in the headerFooter css file:
![](assets\screenshots\headers.jpg)
<b>
in the origonal there were many headers using the same atrributes that could have been grouped up:
![](assets\screenshots\h3.jpg)
after rearranging the code: 
![](assets\screenshots\h1h2h3.jpg)
<br>

I then found all img elements and grouped then up too under the same code block <BR>
BEFORE:
![](assets\screenshots\before.jpg)<br>
AFTER:
![](assets\screenshots\after.jpg)
I did the same with the aside images as you can see <br>
<br>
Anything i could see in the code that doubled up or didnt do anything i changed
<br>
This is my css after all its rearanging: 
##### HeaderFooter
![](assets\screenshots\headerFooter.jpg)
##### BODY
![](assets\screenshots\body.jpg)