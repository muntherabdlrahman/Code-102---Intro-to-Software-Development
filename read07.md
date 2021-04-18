# CSS & hml/ color
![img](https://www.edlibre.com/wp-content/uploads/apprendre-html-css-pour-les-nuls.jpg)
>CSS allows you to create rules that specify how the content of 
an element should appear. For example, you can specify that 
the background of the page is cream, all paragraphs should 
appear in gray using the Arial typeface, or that all level one 
headings should be in a blue, italic, Times typeface.


###### CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts:
-|-
-|-
 a selector|selector: indicate which  element the rule applies to.  The same rule can apply to more than one element if you  separate the element names  with commas
a declaration|declarations: indicate how  the elements referred to in  the selector should be styled.  Declarations are split into two parts(a property and a value), and are separated by a colon. 



 ### colors, as there are three common ways in which you can indicate your choice of colors (plus extra ways made available in CSS3)

### The color property allows you to specify the color of text inside an element. You can specify any  color in CSS in one of three ways:

*rgb values
These express colors in terms 
of how much red, green and 
blue are used to make it up. For 
example: rgb(100,100,90)*
 
 
 *hex codes
These are six-digit codes that 
represent the amount of red, 
green and blue in a color, 
preceded by a pound or hash # 
sign. For example: #ee3e80*

*color names
There are 147 predefined color 
names that are recognized 
by browsers. For example: 
DarkCyan*




### Background Color
>Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker



*Hue
Hue is near to the colloquial idea 
of color. Technically speaking 
however, a color can also have 
saturation and brightness as 
well as hue.*

*Saturation
Saturation refers to the amount 
of gray in a color. At maximum 
saturation, there would be no 
gray in the color. At minimum 
saturation, the color would be 
mostly gray.*

*Brightness
Brightness (or "value") refers 
to how much black is in a color. 
At maximum brightness, there 
would be no black in the color. 
At minimum brightness, the 
color would be very dark.*




>Computer monitors are made 
up of thousands of tiny squares 
called pixels (if you look very 
closely at your monitor you 
should be able to see them).
When the screen is not turned 
on, it's black because it's not 
emitting any light. When it's 
on, each pixel can be a different 
color, creating a picture 



### *hsl, hsla*

>The hsl color property has 
been introduced in CSS3 as an 
alternative way to specify colors. 
The value of the property starts 
with the letters hsl, followed 
by individual values inside 
parentheses for:

*hue*
This is expressed as an angle 
(between 0 and 360 degrees).
saturation
This is expressed as a 
percentage.

*lightness*
This is expressed as a 
percentage with 0% being white, 
50% being normal, and 100% 
being black.


>The hsla color property allows 
you to specify color properties 
using hue, saturation, and 
lightness as above, and adds a 
fourth value which represents 
transparency (just like the rgba
property). The a stands for:

#### *alpha*
This is expressed as a 
number between 0 and 1.0. 
For example, 0.5 represents 
50% transparency, and 0.75
represents 75% transparency.