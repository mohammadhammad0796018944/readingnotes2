  # HTML Lists, CSS Boxes, JS Control Flow


Ordered Lists
# ol
The ordered list is created with
the <ol> element

 # li
 Each item in the list is placedbetween an opening <li> tag
and a closing </li> tag. (The listands for list item.)

# Unordered Lists
ul 
The unordered list is created
with the <ul> element

li
Each item in the list is placedbetween an opening <li> tag
and a closing </li> tag. (The listands for list item.)

# Definition Lists
dl
The definition list is created with the <dl> element and usually
consists of a series of terms and their definitions.

dt
This is used to contain the termbeing defined (the definitionterm).

dd
This is used to contain the definition

# Nested Lists
You can put a second list insidean <li> element to create a sublist
or nested list

# Boxes

Box Dimensions 
By default a box is sized just bigenough to hold its contents. To set your own dimensions for a
box you can use the height andwidth properties.The most popular ways to specify the size of a box are
to use pixels, percentages, or ems. Traditionally, pixels have been the most popular method
because they allow designers to accurately control their size.

# Limiting Width
Some page designs expand and shrink to fit the size of the user's screen. In such designs, the
min-width property specifies the smallest size a box can be displayed at when the browser
window is narrow, and the max-width property indicates the maximum width a box can
stretch to when the browser window is wide

# Overflowing Content

overflow
The overflow property tells thebrowser what to do if the content
contained within a box is largerthan the box itself. It can have
one of two values

# Border Margin and Padding

Border
Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border
separates the edge of one box from another

Margin
Margins sit outside the edge of the border. You can set the width of a margin to create a
gap between the borders of two adjacent boxes

Padding
Padding is the space between the border of a box and any
content contained within it. Adding padding can increase the readability of its contents.

White space & Vertical Margin
The padding and margin properties are very helpful
in adding space between various items on the page

# Border Width
The border-width property is used to control the width of a border. The value of this
property can either be given in pixels or using one of the following values

# Border style
You can control the style of a border using the border-style property. This property can take
the following values

# margin
The margin property controls the gap between boxes. Its value is commonly given in pixels,
although you may also use percentages or ems.If one box sits on top of another,
margins are collapsed , which means the larger of the two margins will be used and the
smaller will be disregarded.

# Change Inline/Block
The display property allows you to turn an inline element into a block-level element or vice
versa, and can also be used to hide an element from the page. The values this property can
take are 

# Example
BOXES
<!DOCTYPE html>
<html>
<head>
<title>Boxes</title>
<style type="text/css">
body {
font-size: 80%;
font-family: "Courier New", Courier, monospace;
letter-spacing: 0.15em;
background-color: #efefef;}
#page {
max-width: 940px;
min-width: 720px;
margin: 10px auto 10px auto;
padding: 20px;
border: 4px double #000;
background-color: #ffffff;}
#logo {
width: 150px;
margin: 10px auto 25px auto;}
ul {
width: 570px;
padding: 15px;
margin: 0px auto 0px auto;
border-top: 2px solid #000;
border-bottom: 1px solid #000;
text-align: center;}
li {
display: inline;
margin: 0px 3px;}
p {
text-align: center;
width: 600px;
margin: 20px auto 20px auto;
font-weight: normal;}






# Summary
There are three types of HTML lists: ordered
 unordered, and definition.
 Ordered lists use numbers.
 Unordered lists use bullets.
 Definition lists are used to define terminology.
 Lists can be nested inside one another.
 # Summary
 CSS treats each HTML e XX lement as if it has its own box.
 You can use CSS to control the dimensions of a box.
 You can also control the borders, margin and padding
for each box with CSS.
 It is possible to hide elements using the display and
visibility properties.
 Block-level boxes can be made into inline boxes, and
inline boxes made into block-level boxes.
 Legibility can be improved by controlling the width of
boxes containing text and the leading.
CSS3 has introduced the ability to create image
borders and rounded borders.





# USING QUOTES INSIDE A STRING
Sometimes you will want to use a double or single quote mark within a string.
Because strings can live in single or double quotes, if you just
want to use double quotes in the string, you could surround the 
entire string in single quotes.

# USING A VARIABLE TO STORE A BOOLEAN
A Boolean variable can only have a value of true or fa 1 se, but this
data type is very helpful.In the example on the right, the
values true or fa 1 se are used in the cl ass attributes of HTML
elements. These values trigger different CSS class rules: true
shows a check, fa 1 se shows across

# SHORTHAND FOR CREATING VARIABLES
Programmers sometimes use shorthand to create variables.Here are three variations of how
to declare variables and assign them values

# CHANGING THE VALUE OF A VARIABLE
Once you have assigned a value to a variable, you can then change what is stored in the
variable later in the same script.Once the variable has been created, you do not need to
use the var keyword to assign it a new value. You just use the variable name, the equals sign
(also known as the assignmentoperator), and the new value for that attribute

# COMPARING TWO EXPRESSIONS
In this example, there are two rounds to the test and thecode will check if the user has
achieved a new high score,beating the previous record.The script starts by storing the
user's scores for each round in variables. Then the highest
scores for each round are stored in two more variables.
The comparison operator checks if the user's total score is greater
than the highest score for the test and stores the result in a
variable called comparison
# Ex
var scorel = 90;
var score2 = 95;
var highScorel 75;
var highScore2 = 95;
II Round 1 score
II Round 2 score
II Round 1 high score
II Round 2 high score
II Check if scores are higher than current high scores
var comparison= (score!+ score2) > (highScorel + highScore2);
II Write the message into the page
var el = document.getElementByid( 'answer');
el .textContent ='New high score:'+ comparison;

# logical operators 
In this example, a math test has tworounds.Foreach round
there are two variables: one holds the user's score for that round; the other holds the pass
mark for that round.The logical AND is used to see if the user's score is greater
than or equal to the pass mark in both of the rounds of the test.
The result is stored in a variable called passBoth.
The example fin ishes off by letting the user know whether
or not they have passed both rounds.

# USING LOGICAL OR & LOGICAL NOT
Here is the same test but this time using the logical OR operator to find out if the user has passed
at least one of the two rounds.If they pass just one round, they
do not need to retake the test.JAVASCRIPT
Look at the numbers stored in the four variables at the start of the example. The user has
passed both rounds, so them in Pass variable will hold the Boolean value of true

# EX
var scorel = 8;
var score2 = 8;
var passl 6;
var pass2 = 6;
II Round 1 score
II Round 2 score
II Round 1 pass mark
II Round 2 pass mark
Next, the message is stored
in a variable called msg. At the
end of the message, the logical
NOT will invert the result of the
Boolean variable so it is false.
It is then written into the page.
c04/j s/logi cal -or-logical-not .js
II Check wh ether user passed one of the two rounds. store result in vari able
var minPass = ((scorel >= passl) I I (score2 >= pass2));
II Create message
var msg = 'Resit required: ' + !(minPass);
II Write the message into the page
var el = document.getElementByld('answer');
el .textContent = msg;

