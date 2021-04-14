# THE DOCUMENT OBJECT REPRESENTS AN HTML PAGE 

![img](https://upload.wikimedia.org/wikipedia/commons/thumb/5/5a/DOM-model.svg/1200px-DOM-model.svg.png)

>Using the document object, you can access and change what content
users see on the page and respond to how they interact with it. 



##### Like other objects that represent real-world things, the document object has: 
No|Title
-|-
1|PROPERTIES
2|METHODS 
3|EVENTS

***HOW A BROWSER SEES A WEB PAGE*** 
> you need to know how a browser interprets the HTML code and applies styling to it. 



- [x] RECEIVE A PAGE AS HTML CODE
- [x] CREATE A MODEL OF THE PAGE AND STORE IT IN MEMORY
- [x] USE A RENDERING ENGINE TO SHOW THE PAGE ON SCREEN

>If there is no CSS, the rendering engine will apply default styles to HTML elements. However, the HTML code for this example links to a CSS style sheet, so the browser requests that file and displays the page accordingly.



***HOW HTML, CSS, & JAVASCRIPT FIT  TOGETHER***
![img](https://cpng.pikpng.com/pngl/s/266-2660463_mayank-grover-consultant-html-css-javascript-icons-clipart.png)


>Each language forms a separate
layer with a different purpose.
Each layer, from left to right.
builds on the previous one. 


ob|discribtions
-|-
html | CONTENT LAYER html files This is where the content of the page lives. The HTML gives the page structure and adds semantics. 
css|  PRESENTATION LAYER css files The CSS enhances the HTML page with rules that state how the HTML content is presented (backgrounds, borders, box dimensions, colors, fonts, etc.).
javascript|BEHAVIOR LAYER js files This is where we can change how the page behaves, adding interactivity. We will aim to keep as much of our JavaScript as ossible in separate files. 


>CREATING A BASIC
JAVASCRIPT

~
1.Create a folder to put the
example in called cOl, then start
up your favorite code editor, and
enter the text to the right.
A JavaScript file is just a
text file (like HTML and CSS
files are) but it has a . j s file
extension, so save this file with
the name add-content . j s 

2.Get the CSS and images for
this example from the website
that accompanies the book:
www.javascriptbook. com
To keep the files organized, in
the same way that CSS files
often live in a folder called
styles or css, your JavaScript
files can live in a folder called
scripts,javascript,orjs.
In this case, save your file in a
folder called j s 

3.n your code editor, enter the
HTML shown on the left. Save
this file with the name
add-content.html
The HTML <script> element is
used to load the JavaScript file
into the page. It has an attribute
called src, whose value is the
path to the script you created.
This tells the browser to find and
load the script file (just like the
src attribute on an <i mg> tag). 

4. Open the HTML file in your
browser. You should see that the
JavaScript has added a greeting
(in this case, Good Afternoon!) to
the page. (These greetings are
coming from the JavaScript file;
they are not in the HTML file.) 
~



