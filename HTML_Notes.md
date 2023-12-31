# HTML Introduction

## HTML is the standard markup language for creating Web pages.

* What is HTML?
* HTML stands for Hyper Text Markup Language
* HTML is the standard markup language for creating Web pages
* HTML describes the structure of a Web page
* HTML consists of a series of elements
* HTML elements tell the browser how to display the content
* HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.

```
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>

```

> Lets Understand above html code.

* The ```<!DOCTYPE html> ``` declaration defines that this document is an HTML5 document
* The ```<html>``` element is the root element of an HTML page
* The ``` <head>``` element contains meta information about the HTML page
* The ```<title>``` element specifies a title for the HTML page which is shown in the browser's title bar or in the page's tab
* The ```<body>``` element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
* The ```<h1>``` element defines a large heading
* The ```<p>``` element defines a paragraph

# What is an HTML Element?

An HTML element is defined by a start tag, some content, and an end tag:

Syntax:

```<tagname> Content goes here... </tagname>```

The HTML element is everything from the start tag to the end tag:
```
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```

>> Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag!

# HTML Page Structure

Below is a visualization of an HTML page structure:
```
<html>
    <head>
        <title>Page title</title>
    </head>
    <body>
        <h1>This is a heading</h1>
        <p>This is a paragraph.</p>
        <p>This is another paragraph.</p>
    </body>
</html>

```
>> The content inside the ```<body> ```section will be displayed in a browser. The content inside the ```<title>``` element will be shown in the browser's title bar or in the page's tab.

# HTML BASIC:

```
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```
* All HTML documents must start with a document type declaration: ```<!DOCTYPE html>```.
* The HTML document itself begins with ```<html>``` and ends with ```</html>```.
* The visible part of the HTML document is between ```<body>``` and ```</body>```.

# The ```<!DOCTYPE>``` Declaration
* The ```<!DOCTYPE>``` declaration represents the document type, and helps browsers to display web pages correctly.
* It must only appear once, at the top of the page ```(before any HTML tags)```.

* The ```<!DOCTYPE>```declaration is not case sensitive.

* The ```<!DOCTYPE>``` declaration for HTML5 is``` <!DOCTYPE html>``` .

# HTML Headings

* HTML headings are defined with the ```<h1> to <h6>``` tags.

* ```<h1>``` defines the most important heading.``` <h6> ```defines the least important heading

```
Example:

<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>

```

# HTML Paragraphs

* HTML paragraphs are defined with the ```<p>``` tag:

```
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>

```

# HTML Links

* HTML links are defined with the ```<a>``` tag

```
Example:

<a href="https://www.w3schools.com">This is a link</a>

The link's destination is specified in the href attribute. 

Attributes are used to provide additional information about HTML elements

```
# HTML Images

* HTML images are defined with the ```<img>``` tag.
* The source file (src), alternative text (alt), width, and height are provided as attributes.

```
Example:

<img src="image.jpg" alt="image" width="104" height="142">
```

# HTML Elements

* An HTML element is defined by a start tag, some content, and an end tag.

``` <tagname>Content goes here...</tagname>```

# Nested HTML Elements

* HTML elements can be nested (this means that elements can contain other elements).

* All HTML documents consist of nested HTML elements.

``` 
Example

<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>

```
* The ```<html> ``` element is the root element and it defines the whole HTML document
* It has a start tag ```<html>``` and an end tag ```</html>```.
* Then, inside the ```<html>``` element there is a``` <body>``` element.
* The ```<body>``` element defines the document's body.
* It has a start tag``` <body> ```and an end tag``` </body>```.
* Then, inside the ```<body> ```element there are two other elements: ```<h1> and <p>```
* The ```<h1>``` element defines a heading.
* It has a start tag ```<h1> ```and an end tag ```</h1>```.
* The ```<p>``` element defines a paragraph
* It has a start tag ```<p> and an end tag </p>```.

> Never Skip the End Tag
> Unexpected results and errors may occur if you forget the end tag!

# Empty HTML Elements.

* HTML elements with no content are called empty elements.
* The ```<br> ```tag defines a line break, and is an empty element without a closing tag
```<p>This is a <br> paragraph with a line break.</p> ```.


# HTML Attributes

* HTML attributes provide additional information about HTML elements.

* All HTML elements can have attributes.
* Attributes provide additional information about elements
* Attributes are always specified in the start tag
* Attributes usually come in name/value pairs like: name="value".

# The href Attribute.

* The ```<a>``` tag defines a hyperlink. The href attribute specifies the URL of the page the link goes to.

```
<a href="https://www.google.com">Visit Google</a>
```

# The src Attribute.

* The ```<img>``` tag is used to embed an image in an HTML page. The src attribute specifies the path to the image to be displayed.

```
<img src="imgage.jpg">
```

## There are two ways to specify the URL in the src attribute:

1. Absolute URL - Links to an external image that is hosted on another website.

Example: src="https://www.google.com/images/image.jpg".

2. Relative URL - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page
Example: src="image.jpg"

* If the URL begins with a slash, it will be relative to the domain. Example: src="/images/image.jpg".

> Tip: It is almost always best to use relative URLs. They will not break if you change domain.

# The width and height Attributes:

* The ```<img> ```tag should also contain the width and height attributes, which specify the width and height of the image (in pixels)

```
<img src="image.jpg" width="500" height="600">
```
# The alt Attribute.
* The required alt attribute for the <img> tag specifies an alternate text for an image,if the image for some reason cannot be displayed. This can be due to a slow connection, or an error in the src attribute, or if the user uses a screen reader.

```
<img src="image.jpg" alt="image with jacket">
```

# The style Attribute

* The style attribute is used to add styles to an element, such as color, font, size, and more.

```
<p style="color:red;">This is a red paragraph.</p>
```
# The lang Attribute

* You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers.

```
<!DOCTYPE html>
<html lang="en">
<body>
...
</body>
</html>
```
* Country codes can also be added to the language code in the lang attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.

```
<!DOCTYPE html>
<html lang="en-US">
<body>
...
</body>
</html>
```

# The title Attribute

* The title attribute defines some extra information about an element.

> The value of the title attribute will be displayed as a tooltip when you mouse over the element

```
<p title="I'm a tooltip">This is a paragraph.</p>
```

# HTML Headings

* HTML headings are titles or subtitles that you want to display on a webpage.
* HTML headings are defined with the ``` <h1> to <h6> tags```.
* ```<h1>``` defines the most important heading. ```<h6>``` defines the least important heading.
```
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```
# HTML Paragraphs

* The HTML ```<p> ```element defines a paragraph.
* A paragraph always starts on a new line
```
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```
>> The browser will automatically remove any extra spaces and lines

# HTML Horizontal Rules
* The ```<hr>``` tag defines a thematic break in an HTML page
* The ```<hr> ```tag is an empty tag, which means that it has no end tag.
```
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
```
# HTML Line Breaks
* The HTML ```<br>``` element defines a line break.
* Use ```<br>``` if you want a line break (a new line) without starting a new paragraph
* The ```<br>``` tag is an empty tag, which means that it has no end tag
```
<p>This is<br>a paragraph<br>with line breaks.</p>
```
# The HTML <pre> Element
* The HTML ```<pre> ```element defines preformatted text
* The text inside a ```<pre>``` element is displayed in a fixed-width font

```
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
```
# HTML Style Attribute
* Setting the style of an HTML element, can be done with the style attribute
* HTML style attribute has the following syntax
```
<tagname style="property:value;">
```
* The property is a CSS property. The value is a CSS value.

# Background Color
```
<body style="background-color:powderblue;">

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
```
* Set background color for two different elements
```
<body>

<h1 style="background-color:powderblue;">This is a heading</h1>
<p style="background-color:tomato;">This is a paragraph.</p>

</body>
```
# HTML Formatting Elements
 
1. ```<b> ```- Bold text - element defines bold text, without any extra importance
2. ```<strong>``` - Important text - element defines text with strong importance
3. ```<i> ```- Italic text 
4. ```<em>``` - Emphasized text - element defines emphasized text, The content inside is typically displayed in italic
5. ```<mark>``` - Marked text - element defines text that should be marked or highlighted
6. ```<small>``` - Smaller text - element defines smaller text
6. ```<del>``` - Deleted text - element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text
7. ```<ins>``` - Inserted text - element defines a text that has been inserted into a document. Browsers will usually underline inserted text
8. ```<sub>``` - Subscript text - element defines subscript text. Subscript text appears half a character below the normal line like H2O
```
<p>This is <sub>subscripted</sub> text.</p>
```
9. ```<sup>``` - Superscript text - element defines superscript text. Superscript text appears half a character above the normal line  WWW[1]
```
<p>This is <sup>superscripted</sup> text.</p>
```

# HTML Quotation and Citation Elements

# <blockquote> for Quotations

* HTML ```<blockquote>``` element defines a section that is quoted from another source

# <q> for Short Quotations
```
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```
# <abbr> for Abbreviations

* The HTML ```<abbr>``` tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr."
```
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```
# HTML <address> for Contact Information
* The HTML``` <address>``` tag defines the contact information for the author/owner of a document or an article
```
<address>
Written by John Doe.<br>
Visit us at:<br>
Example.com<br>
Box 564, Disneyland<br>
USA
</address>
```
# HTML Comment Tag

```
<!-- Write your comments here -->
```

# HTML Links

* HTML links are hyperlinks.

* You can click on a link and jump to another document.

* When you move the mouse over a link, the mouse arrow will turn into a little hand.

> Note: A link does not have to be text. A link can be an image or any other HTML element!

## HTML Links - Syntax

```
<a href="url">link text</a>
```
* a is an element and href is an attribute which indicate the link destination.

```
<a href="https://www.google.com/">Visit Google.com!</a>

```
* By default, links will appear as follows in all browsers:

1. An unvisited link is underlined and blue
2. A visited link is underlined and purple
3. An active link is underlined and red

# HTML Links - The target Attribute

* The target attribute specifies where to open the linked document
> The target attribute can have one of the following values:

1.  _self - Default. Opens the document in the same window/tab as it was clicked
2.  _blank - Opens the document in a new window or tab
3.  _parent - Opens the document in the parent frame
4.  _top - Opens the document in the full body of the window

# Use an Image as a Link
* To use an image as a link,put the ```<img>``` tag inside the ```<a>``` tag.
```
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
```

# Link to an Email Address
* Use mailto: inside the href attribute to create a link that opens the user's email program (to let them send a new email).
```
<a href="mailto:someone@example.com">Send email</a>
```

# HTML Image 

```
<img src="url" alt="alternatetext">
```
# Background Images
* Background Image on a HTML element
* To add a background image on an HTML element, use the HTML style attribute and the CSS background-image property:
```
<p style="background-image: url('img_girl.jpg');">
```
```
<style>
p {
  background-image: url('img_girl.jpg');
}
</style>
```

# HTML Tables:
HTML tables allow web developers to arrange data into rows and columns.

A table in HTML consists of table cells inside rows and columns.

```
<table>
  <tr>
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
</table>
```
##  Table Cells

Each table cell is defined by a ``` <td>``` and a ```</td>``` tag.

td stands for table data.

## Table Rows
Each table row starts with a ``` <tr> and ends with a </tr>``` tag

tr stands for table row.

## Table Headers
Sometimes you want your cells to be table header cells, In those cases use the ```<th> tag instead of the <td>```

th stands for table header.

# HTML LIST:

HTML lists allow web developers to group a set of related items in lists

## Unordered HTML List

An unordered list starts with the ```<ul> ```tag. Each list item starts with the ```<li> ```tag.

The list items will be marked with bullets (small black circles) by default:

```
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```
## Ordered HTML List

An ordered list starts with the ```<ol>``` tag. Each list item starts with the``` <li>``` tag.

The list items will be marked with numbers by default:
```
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```
## HTML Description Lists

It is used to represent elements in definition form like a dictionary.
```<dl>``` tag defines the description list, ```<dt>``` tag defines the term, and the ```<dd>``` tag describes each term in
```
<dl>
    <dt> HTML Simplified </dt>
        <dd> This is complete series of HTML </dd>
    <dt> CSS Master </dt>
        <dd> This will help you to master CSS </dd>
</dl>
```

## HTML Unordered Lists

Unordered HTML List - Choose List Item Marker

The CSS list-style-type property is used to define the style of the list item marker. It can have one of the following values:

1. disc -	Sets the list item marker to a bullet (default)
2. circle - Sets the list item marker to a circle
3. square - 	Sets the list item marker to a square
4. none	- The list items will not be marked

# HTML Block and Inline Elements
## Block-level Elements
A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.

A block-level element always takes up the full width available (stretches out to the left and right as far as it can).

Two commonly used block elements are: ```<p> and <div>```.

The ```<p>``` element defines a paragraph in an HTML document.

The ```<div>``` element defines a division or a section in an HTML document.

## Inline Elements

An inline element does not start on a new line.

An inline element only takes up as much width as necessary.

This is a ```<span>``` element inside a paragraph.

# HTML class Attribute

The class attribute is often used to point to a class name in a style sheet. It can also be used by a JavaScript to access and manipulate elements with the specific class name.

```
<!DOCTYPE html>
<html>
<head>
<style>
.city {
  background-color: tomato;
  color: white;
  border: 2px solid black;
  margin: 20px;
  padding: 20px;
}
</style>
</head>
<body>

<div class="city">
  <h2>London</h2>
  <p>London is the capital of England.</p>
</div>

<div class="city">
  <h2>Paris</h2>
  <p>Paris is the capital of France.</p>
</div>

<div class="city">
  <h2>Tokyo</h2>
  <p>Tokyo is the capital of Japan.</p>
</div>

</body>
</html>
```

> Note: To Access the class name in style we use . symbol.

# HTML id Attribute

id attribute is used to specify a unique id for an HTML element.

You cannot have more than one element with the same id in an HTML document

> Note: To Access id we use # symbol.
```
<!DOCTYPE html>
<html>
<head>
<style>
#myHeader {
  background-color: lightblue;
  color: black;
  padding: 40px;
  text-align: center;
}
</style>
</head>
<body>

<h1 id="myHeader">My Header</h1>

</body>
</html>
```
> Note: The id name is case sensitive!

> Note: The id name must contain at least one character, cannot start with a number, and must not contain whitespaces (spaces, tabs, etc.).

## Difference Between Class and ID

A class name can be used by multiple HTML elements, while an id name must only be used by one HTML element within the page

# HTML Form

* The form is a collection of input tags in an HTML document.
* Forms are mainly used to take the data from the user to serve on the server.
* Forms are created using ```<form>``` tag.

# Form Tag Attributes

* action: This attribute specifies what action will be taken after submitting the form.
* target: This specifies on which browser tab the response will be displayed after form submission.
* method: This attribute is used to define the HTTP method used to submit the form.

## What a normal HTML Form Contains?
```
<input>
<label>
<select>
<option>
<textarea>
<button>
```
Example:

```
<form action="/index.php" target="_blank" method="get">
    Name: <input type="text"/>
    Last Name: <input type="text">
    <button type="submit"> Submit </button>
</form>
```

# Input Tag in HTML 

* The input tag specifies an input field where the user can enter data.
* Input filed is created using ```<input> ```tag.
* Input tags don't need any closing tags.

## Types of Input Tag

1. Text: It is used to create a text input field.

```
<input type="text">
```
2. Color: It is used for input fields that contain color.
```
<input type="color">
```
3. DateTime: It specifies an input field which contains the date and time.
```
<input type="datetime"
```
4. DateTime Local: It specifies t the data and time input with no time zone.
```
<input type="datetime-local">
```
5. Email: It is used for the input field which contains e-mail address.
```
<input type="email">
```
6. File: It is used for the input field which takes a file as input form the user
```
<input type="file">
```
7. Image: It is used to define an image as a submit button.
```
<input type="image">
```
8. Number: It is used to define an input field which contains a numeric value.
```
<input type="number">
```
9. Password: It is used to create an input field which contains input data as password.
```
<input type="password">
```
10. Phone: It defines an input field which contains telephone number.
```
<input type="tel">
```
11.  Range: It is used to define a control for entering a numeric value. The default range is from 0 to 100
```
<input type="range">
```
12. Radio: It is used to create radio button.
```
<input type="radio">
```
13. Time: It is used to create an input field which allows the user to select a time.
```
<input type="time">
```
14. Reset: It is used to create a reset button.
```
<input type="reset" value="reset">
```
15. URL: It is used for input fields that contain a URL address.
```
<input type="url">
```
16. Week: It is used to create an input field which allows the user to select a week and year
```
<input type="week">
```
17. Checkbox: It is used to create a checkbox.
```
<input type="checkbox">
```
18.  Button: It is used to define a button
```
<input type="button" value="Button">
```

# Input Tag Attributes

Attribute Provide the additional information.

1. name: This attribute is used to specify the name of the element.
```
<input type="text" name="text">
```
2.  placeholder: It represents, what type of value you can insert in the input field
```
<input type="text" placeholder="Enter your name...">
```
3.  disabled: It is used to disable the input field from the user side
```
<input type="text" disabled value="raju">
```
4.  value: This attribute is used to set the initial value to the input field.
```
<input type="text" value="raju">
```
5. readonly: This attribute is used to make readonly input field.
```
<input type="text" readonly value="raju">
```
6. required: This specifies that the input field must be filled.
```
<input type="text" required>
```
7. min-max: These are used to set the min and max values.
```
<input type="range" name="" id="" min="0" max="100">
```

# Semantic HTML5 Elements

* The elements in HTML which define their meaning are semantic elements.
And also these elements describe their content.

## Semantic Elements:

1.  form: Used to take the data from the user to process on the server.

```
<form action="">
    Name: <input type="text" name="name" id=""> <br>
    Last Name: <input type="text" name="lastName" id=""> <br>
    <input type="submit" value="Submit">
</form>
```
2. table: Used to represent the data in tabular form
```
<table>
    <tr>
        <th> Name </th>
        <th> Role </th>
    </tr>
    <tr>
        <td> Raju </td>
        <td> Frontend Developer </td>
    </tr>
    <tr>
        <td> Jassi </td>
        <td> Youtuber </td>
    </tr>
</table>
```
3.  article: Used to contain, blog posts, articles, comments, etc.
```
<article>
    <h3> HTML Simplified Series</h3>
    <p> This is HTML series by raju_webdev. In this series I covered most of the topics of HTML to learn it in an easy way with PDF.</p>
</article>

<article>
    <h3> CSS Master</h3>
    <p> This is another series of raju_webdev at geekshelp in this series I covered the most of the basic concepts of CSS.</p>
</article>
<article>
    <h3> JavaScript Doctory Series </h3>
    <p> This series is on JavaScript in which I covered most of the basic concepts to learn JavaScript </p>
</article>
```
4.  header: It is used to create the header part on the web page.
```
<header>
    <h1> HTML Simplified Series </h1>
    <p> This is HTML series by raju_webdev. In this series I covered most of the topics of HTML to learn it in an easy way with PDF. </p>
</header>
```
5. nav: It is used to create a navigation bar. And it contains many navigation links
```
<nav>
    <a href="https://html.com/"> HTML </a>
    <a href="https://css-tricks.com"> CSS </a>
    <a href="https://javascript.info"> JavaScript </a>
</nav>
```
6. main: This specifies the main content on the web page.
```
<main>
    <h3> HTML Simplified Series</h3>
    <p> This is HTML series by raju_webdev. In this series I covered most of the topics of HTML to learn it in an easy way with PDF.</p>
</main>
```
7. footer: Used to create the footer of the web page.
```
<footer>
    <p> @ Copyright All rights resered -  Help</p>
</footer>
```
8. section: It is used to create section on the web page
```
<section>
    <h3> Section 1 </h3>
    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo sapiente odit mollitia laborum consectetur quisquam totam perferendis, similique dolorum quos! </p>
</section>
<section>
    <h3> Section 2 </h3>
    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo sapiente odit mollitia laborum consectetur quisquam totam perferendis, similique dolorum quos! </p>
</section>
```
9. details: It is used to define additional details that a user can view or hide
```
<details>
    <summary> HTML Simplified Series </summary>
    <p>This is HTML series by raju_webdev. In this series I covered most of the topics of HTML to learn it in an easy way with PDF</p>
</details>
```
10. aside: It is used to create a sidebar on the webpage.
```
<aside>
    <h4> JavaScript Doctory Series </h4>
    <p> This series is on JavaScript in which I covered most of the basic concepts to learn JavaScrip </p>
</aside>
```

# Non-Semantic HTML5 Elements

* The elements in HTML which don't represent any meaning.
And these elements don't describe anything about their content

1. div: It is used to create the division of content on the web pages

```
<div>
    <section>
        <h3> HTML Simplified Series</h3>
        <p> This is HTML series by raju_webdev. In this series I covered most of the topics of HTML to learn it in an easy way with PDF.</p>
    </section>
    <aside>
        <h4> JavaScript Doctory Series </h4>
        <p>This series is on JavaScript in which I covered most of the basic concepts to learn JavaScrip</p>
    </aside>
</div>
```
2.  span: It is used to mark up a part of the text.
```
<span> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ipsam commodi a sapiente vel adipisci id odit nam eveniet ea necessitatibus. </span>
```