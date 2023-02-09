# DevelopmentPage
ID DEV BLOG
Wk 1:
1)	Introduction to HTML and CSS
2)	Introduction to Visual Studio Code and repl.it
3)	Learnt what makes a good website
4)	HTML: Defines the content (main codes)
CSS: Assigns the styles (make the website looks better)
5)	HTML has a structure and we name the file as index.html
It begins with:
<!DOCTYPE html>
<html>
<head>
<!-- meta information -->
</head>
<body>
<!-- the content of the page -->
</body>
</html>

<html> <body> and <head> are all required elements.

6)	HTML has tags which includes:
<p> </p>: paragraph element
<h1> </h1>: Main heading (First most important heading)
<h2> </h2>: Second main heading (Second most important heading
<h3> </h3>: Third most important heading 
                     .
                     .
                     .
<b>: bold
<li> </li>: List element (for point forms)
<tr> </tr>: table element
<ul> </ul>: Unordered list (point form)
<o> </o>: ordered list (number form)


To display an image, we use:
<img src="interactive-dev.jpg">
Under the <img> tag, there is 2 attributes:
1)	src: Internal locations on a document
2)	alt: image description in case image not loading 

<a> </a> stands for anchor: To anchor or hyperlink an element 
For example: <a href="https://interactivedev.com" title="JumpStart to 
Interactive Development">Interactive Development</a>

<div> </div>: a container unit which divides the HTML documents into sections
<span> </span>: an inline unit usually used for small chunks of HTML.

7)	Iframe tag ( <iframe> </iframe> ) [usually for media]

The HTML <iframe> tag specifies an inline frame.
An inline frame is used to embed another document within the current 
HTML document.
<iframe src="" width="" height=""></iframe>
Note: 
Iframes are commonly used to embed rich media 
resources. Most commonly Youtube videos

Wk 2:
1)	<header>: eg. H1, h2, h3, h4
2)	<article>: contains 1 or more heading tags ( headers are usally used inside article)
This tag is commonly used for news content or blog post.
3)	<nav>: The location of the munu links most of the time. 

CSS
4)	Responsible for the colour, size, position, etc. 
5)	Rule of CSS: selector{property:value;}  
eg. P{
color:yellow;
}
6)	Inline CSS, we use the tag <style></style> or we can do it in a <p> by writing <p style="text-align: left;">Just a sentence</p>
7)	TO LINK THE CSS TO HTML FILE, we need to link them together. This can be done by saying: <link rel="stylesheet" href="basic.css" type="text/css"> in the <head> tag in the html file.

ID ATTRIBUTES

8)	#(ID Name) for example: #myElement
To call it in the html file, say: 
<body>
<p id="myElement">
A paragraph <em> with emphasis</em>
</p>
</body

CLASS ATTRIBUTE
9)	.myClass

DIFF BETWEEN ID (#) AND CLASS(.)
10)	An element can have only 1 id but multiple classes. ID is unique to that element. 

11)	Fonts in CSS can be retrieved via google fonts or by the built-in fonts.
Wk 3:
HTML Forms:
1)	<form></form> tag
2)	<input></input> tag
3)	<label></label> tag
4)	Validation of the forms can be done by adding the word “required”
5)	<section></section> tag
6)	Grouping selectors in CSS
For example: /* applies to all h1 elements */
h1{...}
/* applies to any element with this class */
.class{...}
/* applies to both h1 and h2 elements (grouping) */
h1, h2{...} /*take note of the spaces when grouping */
/* applies to all of these elements */
h1, h2, .class, #id{...}
7)	Specificity in CSS:
1. Universal (*)
2. type (p)
3. class (.example)
4. id (#example
       8)    More CSS styles for eg. Background pictures, borders, etc.
       CSS BOX MODEL
1)	Content: text, images, etc
2)	Padding: transparent area around the 
3)	content, inside of box
4)	Border: goes around the padding & 
5)	content
6)	Margin: space between boxes
CSS MEDIA QUERIES
1)	@media 
Applies one or more CSS properties based on the result of a media query.
2)	Min-width
If the minimum width of the viewport is at least the specific width or wider, then the media query is true.
3)	Max-width
If the maximum width of the viewport is at no more than the specified width, or it’s narrower, then the media query is true.






For example:

@media screen and (min-width: 576px) 
{ 
/* when the browser viewport is at 
least 576px apply rules here */
}

IMPORTANT NOTES FOR MEDIA QUERIES

h1{color: red;}
/* media query starts here */
/* Small devices (landscape phones, 576px and up) */

@media screen and (min-width: 576px) { 
h1{color: green;}
}

/* Medium devices (tablets, 768px and up) */
@media (min-width: 768px) { 
h1{color: blue;}
}

/* Large devices (desktops, 992px and up) */
@media (min-width: 992px) {
h1{color: purple;}
}

/* Extra large devices (large desktops, 1200px and up) */
@media (min-width: 1200px) {
h1{color: lightpink;
}

4)	Positioning in CSS:  
Relative
For tweaking the position of an element without affecting its 
surrounding boxes
Absolute
Take elements out of the static flow of the page and place 
relative to the browser window
Relative Absolute 
Allows us hook back into the static flow of the page
Fixed
Make elements don't scroll with the rest of the page (sticky)

5)	Z-index: Allows user to control the depth of elements on the page.
-ve z-index go farther into the page
+ve z-index comes out of the page
FLEX-BOX
1)	
Wk 4:
Wk 5:
Wk 6:
Wk 7:
Wk 8:
