**HTML CSS JS VUE - CHEATSHEET**

# HTML
**Basic Tags**
<html> </html>
Creates an HTML document

<head> </head>
Sets off the title & other info that isn't displayed

<body> </body>
Sets off the visible portion of the document

<title> </title>
Puts name of the document in the title bar; when
bookmarking pages, this is what is bookmarked
Body attributes (only used in email newsletters)

<body bgcolor=?>
Sets background color, using name or hex value

<body text=?>
Sets text color, using name or hex value

<body link=?>
Sets color of links, using name or hex value

<body vlink=?>
Sets color of visited links, using name or hex value

<body alink=?>
Sets color of active links (while mouse-clicking)

**Text Tags**
<pre> </pre>
Creates preformatted text

<h1> </h1> --> <h6> </h6>
Creates headlines -- H1=largest, H6=smallest

<b> </b>
Creates bold text (should use <strong> instead)

<i> </i>
Creates italicized text (should use <em> instead)

<tt> </tt>
Creates typewriter-style text

<code> </code>
Used to define source code, usually monospace

<cite> </cite>
Creates a citation, usually processed in italics

<address> </address>
Creates address section, usually processed in italics

<em> </em>
Emphasizes a word (usually processed in italics)

<strong> </strong>
Emphasizes a word (usually processed in bold)

<font size=?> </font>
Sets size of font - 1 to 7 (should use CSS instead)

<font color=?> </font>
Sets font color (should use CSS instead)

<font face=?> </font>
Defines the font used (should use CSS instead)

**Links**
<a href="URL">clickable text</a>
Creates a hyperlink to a Uniform Resource Locator

<a href="mailto:EMAIL_ADDRESS">clickable text</a>
Creates a hyperlink to an email address

<a name="NAME">
Creates a target location within a document

<a href="#NAME">clickable text</a>
Creates a link to that target location

**Formatting
<p> </p>
Creates a new paragraph

<br>
AInserts a line break (carriage return)

<blockquote> </blockquote>
Puts content in a quote - indents text from both sides

<div> </div>
Used to format block content with CSS

<span> </span>
Used to format inline content with CSS

**Lists**
<ul> </ul>
Creates an unordered list

<ol start=?> </ol>
Creates an ordered list (start=xx,
where xx is a counting number)

<li> </li>
Encompasses each list item

<dl> </dl>
Creates a definition list

<dt>
 Precedes eachdefintion term
 
<dd>
 Precedes eachdefintion
 
**Graphical elements**
<hr>
Inserts a horizontal rule

<hr size=?>
Sets size (height) of horizontal rule

<hr width=?>
Sets width of rule (as a % or absolute pixel length)

<hr noshade>
Creates a horizontal rule without a shadow

<img src="URL" />
Adds image; it is a separate file located at the URL

<img src="URL" align=?>
Aligns image left/right/center/bottom/top/middle (use CSS)

<img src="URL" border=?>
Sets size of border surrounding image (use CSS)

<img src="URL" height=?>
Sets height of image, in pixels

<img src="URL" width=?>
Sets width of image, in pixels

<img src="URL" alt=?>
Sets the alternate text for browsers that can't
process images (required by the ADA)

**Forms**
<form> </form>
Defines a form

<select multiple name=? size=?> </select>
Creates a scrolling menu. Size sets the number of
menu items visible before user needs to scroll.

<select name=?> </select>
Creates a pulldown menu

<option>
Sets off each menu item
<textarea name=? cols="x" rows="y"></textarea>
Creates a text box area. Columns set the width;
rows set the height.

<input type="checkbox" name=? value=?>
Creates a checkbox.

<input type="checkbox" name=? value=? checked>
Creates a checkbox which is pre-checked.

<input type="radio" name=? value=?>
Creates a radio button.

<input type="radio" name=? value=? checked>
Creates a radio button which is pre-checked.

<input type="text" name=? size=?>
Creates a one-line text area. Size sets length, in
characters.

<input type="submit" value=?>
Creates a submit button. Value sets the text in the
submit button.

<input type="image" name=? src=? border=? alt=?>
Creates a submit button using an image.

<input type="reset">
Creates a reset button

**Tables (use only for data layout - use CSS for page layout) Table attributes (only use for email newsletters)**
<table> </table>
Creates a table

<tr> </tr>
Sets off each row in a table

<td> </td>
Sets off each cell in a row

<th> </th>
Sets off the table header (a normal cell with bold,
centered text)

**Table attributes (only use for email newsletters)**
<table border=?>
Sets the width of the border around table cells

<table cellspacing=?>
Sets amount of space between table cells

<table cellpadding=?>
Sets amount of space between a cell's border and
its contents

<table width=?>
Sets width of the table in pixels or as a percentage

<tr align=?>
Sets alignment for cells within the row
(left/center/right)

<td align=?>
Sets alignment for cells (left/center/right)

<tr valign=?>
Sets vertical alignment for cells within the row
(top/middle/bottom)

<td valign=?>
Sets vertical alignment for cell (top/middle/bottom)

<td rowspan=?>
Sets number of rows a cell should span (default=1)

<td colspan=?>
Sets number of columns a cell should span

<td nowrap>
Prevents lines within a cell from being broken to fit

**HTML5 input tag attributes**
(not all browsers support; visit http://caniuse.com
 for details)
 
<input type="email" name=?>
 Sets a single-line textbox for email addresses
 
<input type="url" name=?>
 Sets a single-line textbox for URLs
 
<input type="number" name=?>
 Sets a single-line textbox for a number
 
<input type="range" name=?>
 Sets a single-line text box for a range of numbers
 
<input type="date/month/week/time" name=?>
 Sets a single-line text box with a calendar


<input type="search" name=?>
 Sets a single-line text box for searching
 
<input type="color" name=?>
 Sets a single-line text box for picking a color 
 
# CSS

## Font Properties
**Font-Family**
Changes the font family of certain words, sentences,
paragraphs, etc.
P { font-family: "New Century Schoolbook", Times, serif; }

**Font-Style**
Changes text: normal, oblique, and italics.
H1 { font-style: oblique; }
P { font-style: normal; }

**Font-Variant**
Used to display font in normal or small-caps.
SPAN { font-variant: small-caps; }

**Font-Weight**
Used to specify the weight of the font.
H1 { font-weight: 800; } or P { font-weight: normal; }

**Font-Size**
Used to modify the size of the displayed font.
H1 { font-size: large; } or P { font-size: 12pt; }
LI { font-size: 90%; }
STRONG { font-size: larger; }

**Font**
Used to combine all properties of fonts.
P { font: italic bold 12pt/14pt Times, serif; }
## Color and Background Properties
**Color**
Changes the color of text.
H1 { color: blue; } or H2 { color: #000080; }

**Background-Color**
Sets the background color of an element.
BODY { background-color: white; }
H1 { background-color: #000080; }

**Background-Image**
Sets the background image of an element.
BODY { background-image: url(/images/foo.gif); }
P { background-image: url(http://www.htmlhelp.com/bg.png); }

**Background-Repeat**
Determines how a specified background image is repeated.
The repeat-x value will repeat the image horizontally while the
repeat-y value will repeat the image vertically.
BODY { background: white url(candybar.gif);
background-repeat: repeat-x; }

**Background-Attachment**
Determines if a specified background image will scroll with the
content or be fixed with regard to the canvas.
BODY { background: white url(candybar.gif);
background-attachment: fixed; }

**Background**
Used to combine all properties of background.
BODY { background: white url(http://www.htmlhelp.com/foo.gif); }
BLOCKQUOTE { background: #7fffd4; }
P { background: url(../backgrounds/pawn.png) #f0f8ff fixed; }
TABLE { background: red url(leaves.jpg) no-repeat bottom right; }
## Text Properties
**Word-Spacing**
Defines an additional amount of space between words.
P EM { word-spacing: 0.4em; }
P.note { word-spacing: -0.2em; }

**Letter-Spacing**
Defines an additional amount of space between characters.
H1 { letter-spacing: 0.1em; }
P.note { letter-spacing: -0.1em; }

**Text-Decoration**
Allows text to be decorated through one of five properties:
underline, overline, line-through, blink, none.
A:link, A:visited, A:active { text-decoration: none; }

**Vertical-Align**
Used to alter the vertical positioning of an inline element,
relative to its parent element or to the element's line.
IMG.middle { vertical-align: middle; }
IMG { vertical-align: 50%; }
.exponent { vertical-align: super; }

**Text-Transform**
Allows for capitalizing the first letter of each word (capitalize),
capitalizing all letters of a word (uppercase), using all small
letters in each word(lowercase), and the inital value(none).
H1 { text-transform: uppercase; }
H2 { text-transform: capitalize; }

**Text-Align**
Used to justify text left, center, right, and justify.
H1 { text-align: center; }
P.newspaper { text-align: justify; }

**Text-Indent**
Used to specify the amount of indentation prior to the first line
of text.
P { text-indent: 5em; }

**Line-Height**
Used to control the spacing between baselines of text.
P { line-height: 200%; }

## Classification Properties
**List-Style-Type**
Specifies the type of list-item marker, and is used if list-styleimage is none or if image loading is turned off.
LI.square { list-style-type: square; }
UL.plain { list-style-type: none; }
OL { list-style-type: upper-alpha; } /* A B C D E etc. */
OL OL { list-style-type: decimal; } /* 1 2 3 4 5 etc. */
OL OL OL { list-style-type: lower-roman; } /* i ii iii iv v etc. */

**List-Style-Image**
Specifies the image that will be used as list-item marker when
image loading is turned on, replacing the marker specified in
the list-style-type property.
UL.check { list-style-image: url(/LI-markers/checkmark.gif); }
UL LI.x { list-style-image: url(x.png); }

**List-Style-Position**
Determines where the marker is placed in regard to the list
item. If the value inside is used, the lines will wrap under the
marker instead of being indented. outside is default.
UL { list-style-position: inside; } 


## Box Properties 
**Margin-Top**
Sets the top margin of an element by specifying a length or a
percentage.
BODY { margin-top: 5pt; }

**Margin-Right**
Sets the right margin of an element by specifying a length or a
percentage.
P.narrow { margin-right: 50%; }

**Margin-Bottom**
sets the bottom margin of an element by specifying a length or
a percentage.
DT { margin-bottom: 3em; }

**Margin-Left**
sets the left margin of an element by specifying a length or a
percentage.
ADDRESS { margin-left: 50%; }

**Margin**
Sets the margins of an element by specifying top, bottom, left
and right margins -- all either specifying length or percentage.
BODY { margin: 5em; } /* all margins 5em */
P { margin: 2em 4em; } /* top & bottom 2em, left & right 4em */
DIV { margin: 1em 2em 3em 4em; }
/* top margin 1em, right 2em, bottom 3em, left 4em */

**Padding-Top**
Describes the amount of space between the top border and
the content of the selector.
P { padding-top: 20%; }

**Padding-Right**
Describes the amount of space between the right border and
the content of the selector.
P { padding-right: 20 px; }

**Padding-Bottom**
Describes the amount of space between the bottom border
and the content of the selector.
P { padding-bottom: 5 em; }

**Padding-Left**
Describes the amount of space between the left border and
the content of the selector.
P { padding-left: 15 pt; }

**Padding**
Shorthand for the padding-top, padding-right, padding-bottom,
and padding-left properties.
BLOCKQUOTE { padding: 2em 4em 5em 4em; }

**Border-Top-Width**
Used to specify the width of an element's top border.
P { border-top: 20%; }

**Border-Right-Width**
Used to specify the width of an element's right border.
P { border-right: 20%; }

**Border-Bottom-Width**
Used to specify the width of an element's bottom border.
P { border-bottom: 20%; }

**Border-Left-Width**
Used to specify the width of an element's left border.
P { border-left: 20%; }

**Border-Width**
Used to set the width of an element's border (either all
borders, or specifying top border, right border, bottom border,
left border).
P { border-width: 20%; }
P { border-width: 10px 5px 10px 5px; }

**Border-Color**
Used to set the color of an element's border.
P { border-color: #00000; }

**Border-Style**
Sets style of a border - none, dotted, dashed, solid, double.
P { border-style: dotted; }

**Border-Top**
Sets the width, style, and color of an element's top border.
P { border-top: 10px, red, double; }

**Border-Right**
Sets the width, style, and color of an element's right border.
P { border-right: 10px, red, double; }

**Border-Bottom**
Sets the width, style, and color of an element's bottom border.
P { border-bottom: 10px, red, double; }

**Border-Left**
Sets the width, style, and color of an element's left border.
P { border-left: 10px, red, double; }

**Border**
Sets the width, style, and color of an element's border.
P { border: 10px, red, double; }

**Width**
Each block-level or replaced element can be given a width,
specified as a length, a percentage, or as auto.
P { width: 15px; }
H1 { width: 35%; }
.foo { width: auto; }

**Height**
Each block-level or replaced element can be given a height,
specified as a length or as auto.
P { height: 15px; }
H1 { height: 35%; }
.foo { height: auto; }

**Float**
Allows text to wrap around an element (left, right, none).
P { float: left; }
H1 { float: right; }
.foo { float: none; }

**Clear**
Specifies whether an element allows floating elements to its
sides (left, right, none).
P { clear: left; }
H1 { clear: right; }
.foo { clear: none; }

# JS
## Basics

**On page script**
<script type="text/javascript"> ...
</script>

**Include external JS file**
<script src="filename.js"></script>
Delay - 1 second timeout
setTimeout(function () {
}, 1000);

**Functions**
function addNumbers(a, b) {
 return a + b; ;
}
x = addNumbers(1, 2);

**Edit DOM element**
document.getElementById("elementID").innerHTML = "

**Output**
console.log(a); // write to the browse
document.write(a); // write to the HTML
alert(a); // output in an alert
confirm("Really?"); // yes/no dialog, retu
prompt("Your age?","0"); // input dialog. Secon

**Comments**
/* Multi line
 comment */
// One line


## Loops
**For Loop**
for (var i = 0; i < 10; i++) {
 document.write(i + ": " + i*3 + "<br />");
}

var sum = 0;

for (var i = 0; i < a.length; i++) {
 sum + = a[i];
} // parsing an array

html = "";

for (var i of custOrder) {
 html += "<li>" + i + "</li>";
}

**While Loop**
var i = 1; // initialize
while (i < 100) { // enters the cycle
 i *= 2; // increment to avo
 document.write(i + ", "); // output
}

**Do While Loop**
var i = 1; // initialize

do { // enters cycle at
 i *= 2; // increment to avo
 document.write(i + ", "); // output
} while (i < 100) // repeats cycle if

**Break**
for (var i = 0; i < 10; i++) {
 if (i == 5) { break; } // stops and ex
 document.write(i + ", "); // last output
}

**Continue**
for (var i = 0; i < 10; i++) {
 if (i == 5) { continue; } // skips the re
 document.write(i + ", "); // skips 5
}

## If - Else

if ((age >= 14) && (age < 19)) { // logical
 status = "Eligible."; // execute
} else { // else bl
 status = "Not eligible."; // execute
}

**Switch Statement**
switch (new Date().getDay()) { // input is cu
 case 6: // if (day ==
 text = "Saturday";
 break;
 case 0: // if (day ==
 text = "Sunday";
 break;
 default: // else...
 text = "Whatever";
} 


## Variables

var a; // variable
var b = "init"; // string
var c = "Hi" + " " + "Joe"; // = "Hi Joe"
var d = 1 + 2 + "3"; // = "33"
var e = [2,3,5,8]; // array
var f = false; // boolean
var g = /()/; // RegEx
var h = function(){}; // function object
const PI = 3.14; // constant
var a = 1, b = 2, c = a + b; // one line
let z = 'zzz'; // block scope loca

**Strict mode**
"use strict"; // Use strict mode to write secure
x = 1; // Throws an error because variable

## Data Types

var age = 18; // number
var name = "Jane"; // string
var name = {first:"Jane", last:"Doe"}; // object
var truth = false; // boolean
var sheets = ["HTML","CSS","JS"]; // array
var a; typeof a; // undefin
var a = null; // value n

**Objects**
var student = { // object name
 firstName:"Jane", // list of propert
 lastName:"Doe",
 age:18,
 height:170,
 fullName : function() { // object function
 return this.firstName + " " + this.lastName
 }
};
student.age = 19; // setting value
student[age]++; // incrementing
name = student.fullName(); // call object functio

**Values**
false, true // boolean
18, 3.14, 0b10011, 0xF6, NaN // number
"flower", 'John' // string
undefined, null , Infinity // special

**Operators**
a = b + c - d; // addition, substraction
a = b * (c / d); // multiplication, division
x = 100 % 48; // modulo. 100 / 48 remainder =
a++; b--; // postfix increment and decrem

**Bitwise operators**
& AND 5 & 1 (0101 &
0001) 1 (1)
| OR 5 | 1 (0101 | 0001) 5 (101)
~ NOT ~ 5 (~0101) 10
(1010)
^ XOR 5 ^ 1 (0101 ^ 0001) 4 (100)
<< left shift 5 << 1 (0101 << 1) 10
(1010)
>> right shift 5 >> 1 (0101 >> 1) 2 (10)
>>> zero fill right
shift
 5 >>> 1 (0101 >>>
1) 2 (10)

**Arithmetic**
a * (b + c) // grouping
person.age // member
person[age] // member
!(a == b) // logical not
a != b // not equal
typeof a // type (number, object, functi
x << 2 x >> 3 // minary shifting
a = b // assignment
a == b // equals
a != b // unequal
a === b // strict equal
a !== b // strict unequal
a < b a > b // less and greater than
a <= b a >= b // less or equal, greater or eq
a += b // a = a + b (works with - * %.
a && b // logical and
a || b // logical or

## Strings
var abc = "abcdefghijklmnopqrstuvwxyz";
var esc = 'I don\'t \n know'; // \n new line
var len = abc.length; // string length
abc.indexOf("lmno"); // find substring,
abc.lastIndexOf("lmno"); // last occurance
abc.slice(3, 6); // cuts out "def",
abc.replace("abc","123"); // find and replac
abc.toUpperCase(); // convert to uppe
abc.toLowerCase(); // convert to lowe
abc.concat(" ", str2); // abc + " " + str
abc.charAt(2); // character at in
abc[2]; // unsafe, abc[2]
abc.charCodeAt(2); // character code
abc.split(","); // splitting a str
abc.split(""); // splitting on ch
128.toString(16); // number to hex(1

## Numbers and Math
var pi = 3.141;
pi.toFixed(0); // returns 3
pi.toFixed(2); // returns 3.14 - for worki
pi.toPrecision(2) // returns 3.1
pi.valueOf(); // returns number
Number(true); // converts to number
Number(new Date()) // number of milliseconds s
parseInt("3 months"); // returns the first number
parseFloat("3.5 days"); // returns 3.5
Number.MAX_VALUE // largest possible JS numb
Number.MIN_VALUE // smallest possible JS num
Number.NEGATIVE_INFINITY// -Infinity
Number.POSITIVE_INFINITY// Infinity

**Math.**
var pi = Math.PI; // 3.141592653589793
Math.round(4.4); // = 4 - rounded
Math.round(4.5); // = 5
Math.pow(2,8); // = 256 - 2 to the power o
Math.sqrt(49); // = 7 - square root
Math.abs(-3.14); // = 3.14 - absolute, posit
Math.ceil(3.14); // = 4 - rounded up
Math.floor(3.99); // = 3 - rounded down
Math.sin(0); // = 0 - sine
Math.cos(Math.PI); // OTHERS: tan,atan,asin,ac
Math.min(0, 3, -2, 2); // = -2 - the lowest value
Math.max(0, 3, -2, 2); // = 3 - the highest value
Math.log(1); // = 0 natural logarithm
Math.exp(1); // = 2.7182pow(E,x)
Math.random(); // random number between 0
Math.floor(Math.random() * 5) + 1; // random integ

**Constants like Math.PI:**
E, PI, SQRT2, SQRT1_2, LN2, LN10, LOG2E, Log10E

## Dates
Mon Feb 17 2020 13:42:03 GMT+0200 (Eastern European
Standard Time)
var d = new Date();
1581939723047 miliseconds passed since 1970
Number(d)
Date("2017-06-23"); // date declara
Date("2017"); // is set to Ja
Date("2017-06-23T12:00:00-09:45"); // date - time
Date("June 23 2017"); // long date fo
Date("Jun 23 2017 07:45:00 GMT+0100 (Tokyo Time)");

**Get Times**
var d = new Date();
a = d.getDay(); // getting the weekday
getDate(); // day as a number (1-31)
getDay(); // weekday as a number (0-6)
getFullYear(); // four digit year (yyyy)
getHours(); // hour (0-23)
getMilliseconds(); // milliseconds (0-999)
getMinutes(); // minutes (0-59)
getMonth(); // month (0-11)
getSeconds(); // seconds (0-59)
getTime(); // milliseconds since 1970

**Setting part of a date**
var d = new Date();
d.setDate(d.getDate() + 7); // adds a week to a dat
setDate(); // day as a number (1-31)
setFullYear(); // year (optionally month and d
setHours(); // hour (0-23)
setMilliseconds(); // milliseconds (0-999)
setMinutes(); // minutes (0-59)
setMonth(); // month (0-11)
setSeconds(); // seconds (0-59)
setTime(); // milliseconds since 1970)

## Global Functions
eval(); // executes a string as
String(23); // return string from n
(23).toString(); // return string from n
Number("23"); // return number from s
decodeURI(enc); // decode URI. Result:
encodeURI(uri); // encode URI. Result:
decodeURIComponent(enc); // decode a URI compone
encodeURIComponent(uri); // encode a URI compone
isFinite(); // is variable a finite
isNaN(); // is variable an illeg
parseFloat(); // returns floating poi
parseInt(); // parses a string and

## Arrays
var dogs = ["Bulldog", "Beagle", "Labrador"];
var dogs = new Array("Bulldog", "Beagle", "Labrado
dogs[0] = "Bull Terier"; // change the first it
alert(dogs[1]); // access value at ind
for (var i = 0; i < dogs.length; i++) { // par
 console.log(dogs[i]);
}

**Methods**
dogs.toString(); // convert
dogs.join(" * "); // join: "
dogs.pop(); // remove
dogs.push("Chihuahua"); // add new
dogs[dogs.length] = "Chihuahua"; // the sam
dogs.shift(); // remove
dogs.unshift("Chihuahua"); // add new
delete dogs[0]; // change
dogs.splice(2, 0, "Pug", "Boxer"); // add ele
var animals = dogs.concat(cats,birds); // join tw
dogs.slice(1,4); // element
dogs.sort(); // sort st
dogs.reverse(); // sort st
x.sort(function(a, b){return a - b}); // numeric
x.sort(function(a, b){return b - a}); // numeric
highest = x[0]; // first i
x.sort(function(a, b){return 0.5 - Math.random()})

**---**
concat, copyWithin, every, fill, filter, find, findIndex,
forEach, indexOf, isArray, join, lastIndexOf, map, pop,
push, reduce, reduceRight, reverse, shift, slice, some,
sort, splice, toString, unshift, valueOf

## Regular Expressions
var a = str.search(/CheatSheet/i);
**Modifiers**
perform case-insensitive matching
perform a global match
perform multiline matching

**Patterns**
\
\d
\s
\b
Escape character
find a digit
find a whitespace character
find match at beginning or end of a word
n+
n*
n?
^
contains at least one n
contains zero or more occurrences of n
contains zero or one occurrences of n
Start of string

## JSON
var str = '{"names":[' + // cra
'{"first":"Hakuna","lastN":"Matata" },' +
'{"first":"Jane","lastN":"Doe" },' +
'{"first":"Air","last":"Jordan" }]}';
obj = JSON.parse(str); // par
document.write(obj.names[1].first); // acc

**Send**
var myObj = { "name":"Jane", "age":18, "city":"Chi
var myJSON = JSON.stringify(myObj);
window.location = "demo.php?x=" + myJSON;

**Storing and retrieving**
myObj = { "name":"Jane", "age":18, "city":"Chicago
myJSON = JSON.stringify(myObj); //
localStorage.setItem("testJSON", myJSON);
text = localStorage.getItem("testJSON"); //
obj = JSON.parse(text);
document.write(obj.name);

## Promises
function sum (a, b) {
 return Promise(function (resolve, reject) {
 setTimeout(function () {
 if (typeof a !== "number" || typeof b !== "
 return reject(new TypeError("Inputs must
 }
 resolve(a + b);
 }, 1000);
 });
}
var myPromise = sum(10, 5);
myPromsise.then(function (result) {
 document.write(" 10 + 5: ", result);
 return sum(null, "foo"); // Invalid
}).then(function () { // Won't b
}).catch(function (err) { // The cat
 console.error(err); // => Plea
});
**States**
pending, fulfilled, rejected

**Properties**
Promise.length, Promise.prototype

**Methods**
Promise.all(iterable), Promise.race(iterable),
Promise.reject(reason), Promise.resolve(value)

## Events
<button onclick="myFunction();">
 Click here
</button>

**Mouse**
onclick, oncontextmenu, ondblclick, onmousedown,
onmouseenter, onmouseleave, onmousemove,
onmouseover, onmouseout, onmouseup

**Keyboard**
onkeydown, onkeypress, onkeyup

**Frame**
onabort, onbeforeunload, onerror, onhashchange, onload
onpageshow, onpagehide, onresize, onscroll, onunload

**Form**
onblur, onchange, onfocus, onfocusin, onfocusout,
oninput, oninvalid, onreset, onsearch, onselect, onsubmit

**Drag**
ondrag, ondragend, ondragenter, ondragleave,
ondragover, ondragstart, ondrop

**Clipboard**
oncopy, oncut, onpaste

**Media**
onabort, oncanplay, oncanplaythrough, ondurationchange
onended, onerror, onloadeddata, onloadedmetadata,
onloadstart, onpause, onplay, onplaying, onprogress,
onratechange, onseeked, onseeking, onstalled,
onsuspend, ontimeupdate, onvolumechange, onwaiting

**Animation**
animationend, animationiteration, animationstart

**Miscellaneous**
transitionend, onmessage, onmousewheel, ononline,
onoffline, onpopstate, onshow, onstorage, ontoggle,
onwheel, ontouchcancel, ontouchend, ontouchmove,
ontouchstart

## Errors
try { // block of code to
 undefinedFunction();
}
catch(err) { // block to handle
 console.log(err.message);
}

**Throw error**
throw "My error message"; // throw a text

**Input validation**
var x = document.getElementById("mynum").value; //
try {
 if(x == "") throw "empty"; //
 if(isNaN(x)) throw "not a number";
 x = Number(x);
 if(x > 10) throw "too high";
}
catch(err) { //
 document.write("Input is " + err); //
 console.error(err); //
}
finally {
 document.write("</br />Done"); //
}

**Error name values**
RangeError - A number is "out of range"
ReferenceError - An illegal reference has occurred
SyntaxError - A syntax error has occurred
TypeError - A type error has occurred
URIError - An encodeURI() error has occurred
