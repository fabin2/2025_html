HELLO WORLD<br>
*ITALIC* 1*<br>
**STRONG** 2*<br>
***STRONG ITALIC*** 3*<br>
**`TEXTCOLOR`** **`** BACKTICK<br>
**```** PROGRAMMING LANGUAGE<br>
~~1000~~ 900 **~tilde** <br>

[visit youtube](https://www.youtube.com/ "just right") **``[ alt text ]( url "hoover")``**<br>
MDimage<br>
![image](images/icon_markdown.png "mmm...") **``![ alt text ]( url "hoover")``**<br>

html img tag<br>
<img src="images/icon_markdown.png" alt="icon_markdown" width="50" height="50"><br>

TABLES<br>
TABLE | GOES | HERE
| --- | --- | --- |
| ONE | TWO | THREE |<br>
QUOTE >
> KEEP WORK HARDER <br> 

- **- hyphen to bullet point**<br><br>
Horizontal lines **`--- *** <hr>`**<br>


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
## TABLES
![image](images/table_image.png "tabels")

```html
<table style="width: 100%;" border="1";><!-- Table -->
        <caption>TABLE</caption>
        <tr>
            <th>Seriel N</th>
            <th>Item name</th>
            <th>Unit</th>
            <th>Quantity</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Note book</td>
            <td>Nos</td>
            <td>10</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Ball pen</td>
            <td>Nos</td>
            <td>15</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Pencils</td>
            <td>Nos</td>
            <td>25</td>
        </tr>
    </table>
    <table style="width: 100%;" border="1"><!-- Table COLSPAN -->
        <caption>COLSPAN</caption>
        <tr>
            <th>Name</th>
            <th colspan="3">Contact</th>
        </tr>
        <tr>
            <td>John</td>
            <td>1234567</td>
            <td>4821541</td>
            <td>5554214</td>
        </tr>
    </table>

    <table style="width: 100%;" border="1"><!-- Table ROWSPAN -->
        <caption>ROWSPAN</caption>
        <tr>
            <th>Name</th>
            <td>John</td>
        </tr>
        <tr>
            <th rowspan="3">Contact</th>
            <td>1234567</td>
        </tr>
        <tr>
            <td>4821541</td>
        </tr>
        <tr>
            <td>5554214</td>
        </tr>
    </table>

    <table style="width: 100%;" border="1"><!-- Table ROWSPAN AND COLSPAN -->
        <caption>ROWSPAN AND COLSPAN</caption>
        <thead>
            <tr>
                <th colspan="2">Name</th>
                <th>Class</th>
                <th>School</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td rowspan="2">Mahima</td>
                <td rowspan="2">Gupta</td>
                <td>11</td>
                <td rowspan="2">MVM School</td>
            </tr>
            <tr>
                <td>A</td>
            </tr>
            <tr>
                <td rowspan="2">Sri</td>
                <td rowspan="2">Krishn</td>
                <td>3</td>
                <td rowspan="2">LMS School</td>
            </tr>
            <tr>
                <td>B</td>
            </tr>
            <tr>
                <td rowspan="2">Shivika</td>
                <td rowspan="2">Goyal</td>
                <td>5</td>
                <td rowspan="2">SCPM School</td>
            </tr>
            <tr>
                <td>A</td>
            </tr>
        </tbody>
    </table>
```
CSS tabels
```css
table{
    border: 1px solid red;
    border-collapse: collapse;
    background-color: rosybrown;
}
th,td{
    text-align: center;
    padding: 10px;
}
th{
    background-color: seagreen;
    color: white;
}
caption{
    font-weight: bold;
}
```
## Links / Image
```html css
<a href="https://www.google.fr/" target="_blank" title="clickme">Google</a> <!--external link-->
<a href="contact.html" target="_blank">Contact</a> <!--internal-->

<img src="/images/dog.jpeg" alt="dog_image" width="200" height="200"> <!--internal imagie-->
<img src="......site......" alt="cat_image" width="200" height="200"> <!--external-->
```
```css
a:link{
    text-decoration: none; /*removed underline link*/
}
a:hover{
    color: red; /*hoover color link*/
}

body{
    background-image: url('/images/cat.jpg');           /*background CSS single img*/
    background-repeat: no-repeat;
    background-size: 100% 100%;
    background-attachment: fixed;
}
```
Clickable img & image Mapping
```html
<a href="https://www.google.fr/" target="_blank" title="clickme"><!--clickable image-->
    <img src="/images/google.png" alt="google_image" width="150" height="200">
</a>

<!-- usemap #name <map name> <area shape= "rect,circle, poly, default" coords -->
<img src="/images/social.png" alt="socialnetwork_sites" usemap="#social"><!--image map: pixel defined 200*200-->
    <map name="social">
        <area shape="rect" coords="0,0,100,100" href="https://www.google.fr/" target="_blank">
        <area shape="rect" coords="100,0,200,100" href="https://www.facebook.com/" target="_blank">
        <area shape="rect" coords="0,100,100,200" href="https://x.com/?lang=fr/" target="_blank">
        <area shape="rect" coords="100,100,200,200" href="https://www.instagram.com/" target="_blank">
    </map>
```
**DIV :** The div tag defines a section, a container for HTML elements, styled with CSS/JavaScript. It creates line breaks by default.
```html
<div style="background-color: red; float: left; width: 33%;">
        <span>HTML</span>
        <p>Hypertext Markup Language HTML is the standard markup language for documents designed to be displayed in a web browser. It defines the content and structure of web content.</p>
    </div>
    <div style="background-color: green; float: left; width: 33%;">
        <span>CSS</span>
        <p>Cascading Style Sheets CSS is a style sheet language used for specifying the presentation and styling of a document written in a markup language such as HTML or XML including XML dialects such as SVG, MathML or XHTML. </p>
    </div>
    <div style="background-color: blue; float: left; width: 33%;">
        <span>JAVASCRIPT</span>
        <p>JavaScript, often abbreviated as JS, is a programming language and core technology of the World Wide Web, alongside HTML and CSS.</p>
    </div>
```
**CLASSES, multiple class names** . class tag point to a class name in a style sheet. It can also be used by a JavaScript to access and manipulate elements with the specific class name.
```html
<h3 class="vegetable organic">Carrot</h3> <!--multiple class names-->
<h3 class="vegetable">Onion</h3>
<h3 class="fruit">Orange</h3>
<h3 class="fruit">Apple</h3>
```
```css
.vegetable{
    background-color: green;
}
.fruit{
    background-color: blue;
}
.organic{               /* multiple class names*/
    color: white;
    text-align: center;
}
```
**ID attribute** IDs uniquely identify one HTML element; classes apply to multiple. JavaScript uses IDs for specific element manipulation.IDs: case-sensitive, no leading numbers, no spaces.
```html
<h2>ID</h2>
   <h3 id="veg1">Carrot</h3>
    <h3 id="veg2">Onion</h3>
    <h3 id="fruit1">Orange</h3>
    <h3 id="fruit2">Apple</h3>
```
```css
#veg1{
    background-color: gray;
}
#fruit1{
    background: blueviolet;
}
#veg2{
    color: gray;
}
#fruit2{
    color: blueviolet;
}
```
**LIST unorderd ordered nested** A list item can contain a new list, and other HTML elements, like images and links, etc.
```html
<h3>Unordered</h3>
    <ul style="list-style-type: disc;">
        <li>Tomato</li>
            <ul>
                <li>Organic</li>
            </ul>
        <li>Carrot</li>
    </ul>
    <h3>Ordered</h3>
    <ol start="10">
        <li>Banana</li>
        <li>Apple</li>
    </ol>
```
**LIST ``MENU`` navigation**
```html
 <h2>Menu navigation list</h2>
    <ul class="ul_classMenu">
        <li class="li_classMenu">HOME</li>
        <li class="li_classMenu">ABOUT</li>
        <li class="li_classMenu">SERVICE</li>
        <li class="li_classMenu">CONTACT</li>
    </ul>
```
```css
.ul_classMenu{
    list-style-type: none;
    overflow: hidden;
    background-color: blueviolet;
    color: white;
    font-size: 20px;
}
.li_classMenu{
    float: left;
    padding: 15px;
}
.li_classMenu:hover{
    background-color: blue;
}
```
**Iframe** embeds another html document within the current one, a nested browsing context.
```html
<iframe src="https://www.google.com/maps/embed?" width="100%" height="250"></iframe> <!--google map embed-->
<iframe src="contact.html" width="100%" height="250"></iframe>
```
**FORM** 
```html
<form >
    <label for="username">User Name: </label>
    <input type="text" name="username" id="username">
    <label>Password</label>
    <input type="password" name="password" id="password">
    <input type="submit" value="Submit">
</form>
```
```html
<div style="background-color: grey;">
    <form>
        <h2>Registration Form</h2>
        <label for="firstname">First Name: </label>
        <input type="text" name="firstname" id="firstname"><br>
        <label for="secondname">Second Name: </label>
        <input type="text" name="secondname" id="secondname"><br>
        <label for="email">Email: </label>
        <input type="email" name="email" id="email"><br>
        <label for="pass">Password: </label>
        <input type="password" name="pass" id="pass"><br>
        
        <div style="background-color: rgb(112, 112, 194);">
            <h3>Gender</h3>
            <input type="radio" name="gender" id="male">
            <label for="male">Male</label>
            <input type="radio" name="gender" id="female">
            <label for="female">Female</label>
            <input type="radio" name="gender" id="other">
            <label for="other">Other</label>
        </div>
        <div>
            <h3>Hobbies</h3>
            <input type="checkbox" name="game" id="football">
            <label for="football">Football</label>
            <input type="checkbox" name="game" id="rugby">
            <label for="rugby">Rugby</label>
            <input type="checkbox" name="game" id="tennis">
            <label for="tennis">Tennis</label>
        </div>
        <div style="background-color: rgb(112, 112, 194);">
            <h3>Regions</h3>
            <label for="regions">Regions</label>
            <select name="regions" id="regions"> 
                <option value="grandest">Grand-Est</option>
                <option value="iledefrance">Île-de-France</option>
                <option value="auvergnerhonealpes">Auvergne Rhône-Alpes</option>
            </select>
        </div>
        <div>
            <h3>Adresse</h3>
            <label for="adresse">Adresse</label><br>
            <textarea name="adresse" id="adresse" cols="30" rows="4"></textarea>
        </div>
        <h3>Upload Photo</h3>
        <label for="photo">Upload:</label>
        <input type="file" name="photo" id="photo"><br><br>

        <input type="button" value="Register">
    </form>
</div>
<br>
<h3>Button normal and image</h3>
<button type="button" class="button">Sign Up</button>
<br><br>

<button type="button" class="button2">
    <img src="/images/button_signup_image.png" alt="signup" width="100" height="40">
</button>
```
```css
.button{
    background-color: red;
    border: none;
    padding: 15px 30px;
    color: white;
    font-size: 20px;
}
```
**Video Adio**
```html
<video width="320" height="240" controls autoplay muted>
    <source src="/video_audio/ Jackson - They Don’t Care About Us.mp4" type="video/mp4">
</video>

<!--youtube embed iframe-->

<audio controls>
    <source src="/video_audio/It's My Life - Bon Jovi.mp3">
</audio>
```
**JScript in html**
```html
<script>
    alert("Hell World");
</script>

<script src="/jshtml.js"></script> <!--js external file-->
```
```js
alert("Hello world");
```
js function call onclick-event html button Hello world message pop up
```html
<p id="messageId"></p>
<button type="button" onclick="message()">Click</button>
```
```js
function message(){
    document.getElementById("messageId").innerHTML = "Hello world";
}
```
**Metadata** Meta data is information about information, Metadata is data (information) about data.



