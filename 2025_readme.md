HELLO WORLD<br>
*ITALIC* 1*<br>
**STRONG** 2*<br>
***STRONG ITALIC*** 3*<br>
`TEXTCOLOR` **`**<br>
**```** CODE LANGUAGE<br>
~~1000~~ 900 ~tilde <br>
### ### HEADING 3
## ## HEADING 2
# # HEADING 1



```html    
    Hello world <!--comment single & multipleline  Merci Danke und Wunderbar--> HTML stands for hyper text markup language, Created by Tim Berners Lee in 1991, Html used for create web pages. 
```
<br>

```html
<!DOCTYPE html>
    <html>
        <head><!--head of browser -->
            <title>Learn Html</title>
        </head>
        <body>
            <h1><h2><h3><h4><h5></h6> heading tags 
            <p><b>BOLD</b></p> pargraph and bold
            <br> break tag dont need to close
            <i>italics</i>
            <em>emphasize italics</em>
            <mark>highlight in yellow background</mark>
            <small>Small sized letters</small>
            <del>deleted line over letters</del>
            <ins>insert or underlined</ins>
            <sup>superscript slightly above</sup> 
            <sub>subscript slightly below</sub>
            <strong>'i'bold</strong>bold<b></b>
            <blockquote cite="https://en.wikipedia.../Eiffel_Tower">specifies a section that is quoted from another source</blockquote>
            <p><cite>Lettre philosophique</cite> by: Voltaire</p> 
        </body>
    </html>
```
### CSS - Cascading style sheet and html
```html
    
    1. Inline : style attribute inside HTML element
    <h1 style="color: red;">Learn html css</h1>

    2. Internal : <style> element inside <head> tag 
    <head>
        <style>
            h2{color:cornflowerblue;}
            h3{color: blueviolet;}
        </style>
    </head>
    <body>
        <h2>Test</h2>
        <h3>Test</h3>
    </body>

    3. External : <link> element to link an external css file
    <head>
        <link rel="stylesheet" href="styles.css">
    </head>
```
styles.css external file
```css
body{
    background-color: brown;
}
p{
    color: yellow;
    background-color: black;
}
```
HTML colors
```html
Color name = eg: red, tomoto, gold, pink
RGB = red, green, blue values. eg : rgb(200, 100, 115)
HEX = hexadecimal value. eg: #e30b6c
HSL = hue, saturation, lightness values. eg: hsl(10, 90%, 65%)
RGBA = rgb with alpha channel/transparancy value. eg: rgba(200, 100, 115, 0.4)
HSLA = hsl with alpha channel/transparancy. eg: hsla(10, 90%, 65%, 0.5)
```
```CSS

{
    color: blueviolet;/*Colorname*/ 
}
{
    color: rgb(242, 113, 15);/*RGB*/
}
{
    color: #ff3369;/*HEX*/
}
{
    color: hsl(235, 100%, 60%); /* HSL hue ° degree removed)*/ 
}
{
    background-color: rgba(165, 42, 42, 0.1); /* RGBA 0.1 transparency percentage added*/
}
{
    background-color: hsla(205, 98%, 50%, 0.3);/*HSLA 0.3 transparency*/
}
```