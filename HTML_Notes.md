## HTML Introduction

## What is HTML?
* HTML stands for Hypertext Markup Language
* Hypertext is Text which contain links to other texts
* markup language it's a way to give instruction to the computer about how content should be organized and displayed.
* Hypertext --> Hyperlink
* HTML is the standard markup language for creating Web pages
* HTML describes the structure of a Web page

## syntax
```html
<opening tag> content <closing tag>
<h1>Content</h1>
```
* HTML file is saved in .html extension.
* Default home page should be index.html

## HTML Document/Structure

```html
<!DOCTYPE html> // let browser know it's an HTML5 Document.
<html> // Root of an HTML Document
<head> // contains the information of HTML Document.
<title>Page Title</title>
</head>
<body> // Contain everything you want to display on the web page.

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

## Lets Understand above html code
```html
* The **<!DOCTYPE html>** declaration defines that this document is an HTML5 document
* The **<html>** element is the root element of an HTML page
* The **<head>** element contains meta information about the HTML page

* The <title> element specifies a title for the HTML page which is shown in the browser's title bar or in the page's tab
* The **<body>** element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
* The **<h1>** element defines a large heading
* The **<p>** element defines a paragraph
```

## What is an HTML Element?

* An HTML element is defined by a start tag, some content, and an end tag

## Syntax:
```html
<tagname> Content goes here... </tagname>
```
* The HTML element is everything from the start tag to the end tag
```html
<h1>My First Heading</h1>
<p>My first paragraph.</p>
```
## Some HTML elements have no content (like the <br> element). These elements are called empty elements. Empty elements do not have an end tag!

## HTML Page Structure

* Below is a visualization of an HTML page structure:
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
## The content inside the ```<body> ```section will be displayed in a browser. The content inside the ```<title>``` element will be shown in the browser's title bar or in the page's tab.

## HTML BASIC

```html
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

## The ```<!DOCTYPE>``` Declaration
* The ```<!DOCTYPE>``` declaration represents the document type, and helps browsers to display web pages correctly.
* It must only appear once, at the top of the page ```(before any HTML tags)```.

* The ```<!DOCTYPE>```declaration is not case sensitive.

* The ```<!DOCTYPE>``` declaration for HTML5 is``` <!DOCTYPE html>``` .

## HTML Attributes

* HTML attributes provide additional information about HTML elements.
* Attributes are always specified in the start tag
* Attributes usually come in name/value pairs like: name="value"
* Name: Specifies the property for that element.
* Value: Sets the value of that property for the element


```html
<html lang="en">
```
## ID Attribute
* The ID attribute is used to assign a unique identifier to an HTML element. Each element with an ID has its own unique identity
```html
  <p id="html">This is an HTML<p>
  <p id="python">This is a Python</p>
```

## Class Attribute
* The class attribute is used to associate an HTML element with a particular class, typically for styling or JavaScript manipulation. Unlike the ID attribute, the class attribute is not unique, and multiple elements can share the same class.

```html
<p class="html">This is an HTML</p>
<p class="html ">This is a HTML</p>
```
## Other useful HTML attributes
## href Attribute
* The href attribute is used to link to another page or another web address. It is used in  a tag
```html
<a href="https://devjunctionpoint.blogspot.com/"> Home </a>
```
## src Attribute
* src attribute is used to define file location. It accepts the URL of the resource.

```html
<img>,<iframe>,<audio>, <video>
<img src="../images/E3CCA633-C689-4DD9-8B20-79E7C5A88487.jpg" 
alt="Clickable World Map"/>
```

## alt Attribute
* The alt attribute is added as an alternate text in a <img> tag. It holds a description of the image.

## HTML Attribute List
```
Attribute	Used in	Description
alt	<img>	Description of the image
src	<img>	URL of the image
width	<img>	Width of the image
height	<img>	Height of the image
href	<a>	URL of the link
target	<a>	Target of the link
rel	<a>	Relation of the link
lang	html	Language of the text
style	Almost all elements	Style of the element
class	Almost all elements	Class of the element
id	Almost all elements	Id of the element
title	Almost all elements	Title of the element
dir	Almost all elements	Direction of the text
colspan	<td>	Number of columns to span
rowspan	<td>	Number of rows to span
for	<label>	For which element the label is
placeholder	<input>	Placeholder of the input
autofocus	<input>	Focus the input
required	<input>	Input is required
checked	<input>	Input is checked
disabled	<input>	Input is disabled
readonly	<input>	Input is readonly
max	<input>	Maximum value of the input
min	<input>	Minimum value of the input
action	<form>	Action of the form
method	<form>	Method of the form
```

## HTML COMMENTS
* It is used to understand the code written by someone.
* Browser will ignore the comments.
```html
<!-- comment -->
 ```
## Types of Comments in HTML
* HTML primarily supports two types of comments:
Single-line Comments
* Single-line comments are contained within one line. They are useful for short annotations.
## Example:
```html
<!-- This is a single-line comment -->
```
## Multi-line Comments
* Multi-line comments span across multiple lines, making them ideal for detailed explanations or temporarily disabling blocks of code.
Example:
```html
  <!-- 
  This is a multi-line comment.
  It spans multiple lines.
  -->
```


## HTML Headings

* The ```<h1>``` to ```<h6>``` tags create headings in HTML.

* where ```<h1>``` is the biggest and most important, and ```<h6>``` is the smallest and least important

```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Headings and Paragraphs</title>
</head>

<body>
    <h1>Headingh1</h1>
    <h2>Headingh2</h2>
    <h3>Headingh3</h3>
    <h4>Headingh3</h4>
    <h5>Headingh3</h5>
    <h6>Headingh3</h6>
</body>

</html>
```
* The tag's element name is case-insensitive.
* A single H1 is typically used per page
* Follow the hierarchy from H1 to H6 consistently.


## HTML Paragraphs

* The ```<p>``` tag defines a paragraph.
* Browsers automatically add a single blank line before and after each ```<p>``` element.
```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```
## br tag (line break)

```html
<p>
  Lorem, ipsum dolor sit amet consectetur adipisicing elit.
  <br> <!-- line break-->
  Lorem ipsum, dolor sit amet consectetur adipisicing elit.
</p>
```
## hr Tag(Horizontal rule)

```html
<hr> <!-- Horizontal rule-->
```

## Anchor Link

* The ```<a>``` tag defines a hyperlink, which is used to link from one page to another.

## Key Characteristics of HTML Anchor Links

* Specified by the ```<a>``` tag.
*	Also known as hyperlinks.
*	Used to link one document to another.
*	Includes a closing tag ```<a>```.

```html
<a href="https://www.instagram.com/junctioncodebase/" target="_blank"

title="Instagram id">Follow In Instagram</a>
```

## Essential Attributes of the Anchor Tag

## HTML links primarily use two attributes:

*	href attribute: Specifies the URL or destination the link points to.
*	target attribute: Specifies where to open the linked document.

## Target Attribute Values

*	_blank: Opens the linked document in a new window or tab.
*	_top: Opens document in the full body of the window.
*	_self: Opens document in the same window or tab (default behavior).
*	_parent: Opens the linked document in the parent frame.

## Linking to Specific Page Sections
* To link to a specific section of a webpage, you can:
*	Use the name or id attribute of the target section.
*	Use a hyperlink with a hash (##) followed by the target id or name.

## Example
*	Let's say you have a long webpage with multiple sections, and you want to create a link at the top that, when clicked, takes the user directly to a specific section further down the page. You can do this using HTML Anchor link that target specific sections.

```html
<!DOCTYPE html>
<html>
<head>
  <title>My Webpage</title>
</head>
<body>

  <!-- Link at the top -->
  <a href="##gardening-tips">Go to Gardening Tips</a>

  <!-- Some content -->
  <p>Here is some other content...</p>

  <!-- Gardening Tips Section -->
  <h2 id="gardening-tips">Gardening Tips</h2>
  <p>This section provides tips on how to garden...</p>

</body>
</html>

</body>

</html>
```

## Link colors
> Links typically appear in different colors based on their state:
*	Active: Displayed in red and underlined like this sentence
*	Visited: Appears purple and underlined like this sentence
*	Unvisited: Shown as blue and underlined like this sentence

## HTML Entities

* HTML entities are codes used to represent special characters and symbols that have reserved meanings in HTML.
* These entities are especially important when you  want to display characters that might conflict with HTML syntax or when you want to display characters that aren't directly available on your keyboard.
*HTML entities are represented using an ampersand (&) followed by a code and a semicolon (;).


&lt; 👉 Less than sign (<)
&gt; 👉 Greater than sign (>)
&amp; 👉 Ampersand (&)
&quot; 👉 Double quotation mark (")
&apos; 👉 Single quotation mark or apostrophe (')
&nbsp; 👉 Non-breaking space ( )
&copy; 👉 Copyright symbol (©)
&reg; 👉 Registered trademark symbol (®)
&trade; 👉 Trademark symbol (™)
&hearts; 👉 Heart symbol (♥)


```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>HTML Entities Example</title>
    <style>
        @import url("https://fonts.googleapis.com/css2?family=Poppins:
wght@300;400;600&family=Urbanist:wght@300;400;600;700;800;900&display=swap");

        html {
            font-family: "Poppins", sans-serif;
        }
    </style>
</head>

<body>
    <p>
        &lt;: Less than sign (<br />
        &gt;: Greater than sign (>)<br />
        &amp;: Ampersand (&amp;)<br />
        &quot;: Double quotation mark (")<br />
        &apos;: Single quotation mark or apostrophe (')<br />
        &nbsp;: Non-breaking &nbsp; &nbsp; &nbsp; &nbsp; 
&nbsp;space ( )<br />
        &dollar;: Dollar Sign ($) <br />
        &copy;: Copyright symbol (©)<br />
        &reg;: Registered trademark symbol (®)<br />
        &trade;: Trademark symbol (™)<br />
        &hearts;: Heart symbol (♥, 💖)
    </p>
</body>

</html>

```

## INTERVIEW QUESTIONS: HTML ENTITIES

* 1: When might you use the &nbsp; entity?
* The &nbsp; entity is used to insert a non-breaking space, which prevents the browser from collapsing consecutive spaces into one

* 2: How would you display a trademark symbol using an HTML entity?
* ou can display a trademark symbol using the &trade; entity: &trade;.

* 3: Why is it important to use HTML entities for special characters?
* Using HTML entities ensures proper rendering of characters and symbols and helps avoid conflicts with HTML syntax.

* 4: Represent the dollar sign symbol using different HTML entity methods
* Using Named Entity: &dollar; 

## HTML Image Tag

* ```<img>``` tag is used to embed(ADD) an image in an HTML page.

```html
 <img src="/image.png" alt="altext"/>
```
## Key Features of the <img> Tag
* It's a self-closing tag, meaning it doesn't require a corresponding closing tag
* Commonly used attributes include the "alt" attribute for image descriptions and the "src" attribute for specifying the image location.
* Supports various image formats including PNG, JPEG, JPG, GIF, etc.

## Setting Mandatory Attributes

* src attribute: Specifies the path to the image file.
* alt attribute: Provides a text description for the image.
```html
 <img src="images/profile_picture.jpg" alt="Profile Picture" />
```
## Setting Image Dimensions

```html
<img src="image.png" alt="Description" 
width="300" height="100" />
```

## Lazy Loading Attribute
* You can use the loading attribute to completely defer the loading of offscreen images that are reached by scrolling:

```html
<a href="https://devjunctionpoint.blogspot.com/" target="_blank">
  <img src="../images/E3CCA633-C689-4DD9-8B20-79E7C5A88487.jpg" 
  alt="my Image" width="250" height="150"
  title="My Image" loading="lazy" />
</a>

```
## Use an Image as a Link
* To use an image as a link,put the ```<img>``` tag inside the ```<a>``` tag.
```
<a href="default.asp">
<img src="smiley.gif" alt="HTML tutorial" style="width:42px;height:42px;">
</a>
```

## INTERVIEW QUESTIONS: HTML IMAGE TAG 


* 1: How would you make an image responsive using the width attribute?

* You can set the width attribute to a percentage value (e.g., width="100%") to make the image adjust its width based on the available space.

* 2: How do you create an image link using the ```<img>``` tag?

* You wrap the ```<img>``` tag with an anchor ```<a>``` tag and provide the href attribute in the ```<a>```tag.

* 3: What's the difference between relative and absolute URLs in the href attribute?

* Relative URLs are URLs that are relative to the current page's URL. Absolute

* URLs are complete URLs, including the protocol (http/https) and domain.

* 4: Why is providing descriptive alt text for images important? 

* It improves accessibility for users with visual impairments and helps search engines understand image content.

## picture tag

* The ```<picture>``` element in HTML is used to provide multiple sources of an image, allowing the   browser to choose the most appropriate source based on the user's device,   screen size, and other factors. This is particularly useful for responsive  design and ensuring the best quality images are displayed. ```</picture>```

## SHARING IS CARING 💖  https://pixelied.com/, https://squoosh.app/

```html
<picture>
        <source srcset="./images/html.webp" type="image/webp" />
        <source srcset="./images/html.jpg" type="image/jpg" />
        <source srcset="./images/html.jpeg" type="image/jpeg" />
        <source srcset="./images/html.svg" type="image/svg" />
        <img src="./images/html.png" alt="Images" width="500" />
</picture>
```
## figure tag

* The figure element is particularly useful for images, illustrations, diagrams, videos, audio clips, and other types of media.
* Use the alt attribute for images within the figure element to provide alternative text for accessibility.
* The figure element helps improve accessibility and search engine optimization by indicating the content and its context.

```html
 <!-- add figure tag here  -->
    <figure>
        <img src="../images/E3CCA633-C689-4DD9-8B20-79E7C5A88487.jpg" 
        
        alt="my image" width="500" height="auto" />
        <figcaption>This is my image</figcaption>
    </figure>
```

## INLINE & BLOCK ELEMENTS
* HTML elements are generally divided into two categories: Block-level and Inline elements
* Inline Elements don't start on a new line. It only takes the width required to cover the content
* Block-level elements take complete width and start on a new line and take up the entire width of their container by default.

## Common Inline Elements
```html
<span>: A generic inline container for text
<a>: Defines a hyperlink
<strong>: Defines important text
<em>: Defines emphasized text
<img>: Embeds an image
<input>: Defines an input control
```

## Characteristics of Block-level Elements:
*	Always start on a new line.
*	Take up the full width available.
*	Width and height can be controlled via CSS.
*	Can contain other block-level as well as inline elements.

## Common Block-level Elements:
```html
•	<h1>,<h2>,<h3>,<h4>,<h5>,<h6> - Headings
•	<p> - Paragraphs
•	<hr> - Horizontal rule
•	<address> - Address information
```

## HTML LIST:

HTML lists allow web developers to group a set of related items in lists


## Types of HTML Lists
* **Unordered List**: Displays items using bullets.
* **Ordered List**: Displays items in a numerical sequence, and supports various numbering styles like Arabic numerals, Roman numerals, and so on.
* **Definition List**: Organizes items in a format similar to a dictionary, with terms and their corresponding definitions.


## Unordered HTML List
* An unordered list starts with the ```<ul> ```tag. Each list item starts with the ```<li> ```tag.

## Key Characteristics of Unordered Lists
*	No specific sequence is required.
*	Typically displayed as bullet points.
*	Defined using the ```<ul>``` tag.
*	Individual items use the ```<li>``` tag.

```html
<ul>
  <li>Pen</li>
  <li>Pencil</li>
  <li>Eraser</li>
</ul>
```
## Customizing Bullet Points with 'type' Attribute

* You can specify the style of bullet points using the type attribute. It supports three values:
* disc - default bullet style
* square
* circle

## Ordered HTML List

* An ordered list starts with the ```<ol>``` tag. Each list item starts with the``` <li>``` tag.

* An Ordered list is used to create a list of item in a specific order typically indicated by numbers

## Key Points
*	Ordered lists are used for items that follow a sequence.
*	They are created using the ```<ol>``` (Ordered List) tag.
*	List items are enclosed within ```<li>``` (List Item) tags.


* The list items will be marked with numbers by default:
```html
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
```
## Setting the 'type' Attribute
* The type attribute specifies the style of numbering. You have several options:
*	Uppercase Roman Numerals: Use type="I"
*	Lowercase Roman Numerals: Use type="i"
*	Arabic Numerals: Use type="1" (This is the default if the type attribute is not specified)
*	Lowercase Alphabetical Letters: Use type="a"
*	Uppercase Alphabetical Letters: Use type="A"


## HTML Description Lists

* It is used to represent elements in definition form like a dictionary.
```<dl>``` tag defines the description list, ```<dt>``` tag defines the term, and the ```<dd>``` tag describes each term in
```html
<dl>
    <dt> HTML Simplified </dt>
        <dd> This is complete series of HTML </dd>
    <dt> CSS Master </dt>
        <dd> This will help you to master CSS </dd>
</dl>
```
## INTERVIEW QUESTIONS: HTML List 
* 1: What is the significance of the type attribute in ordered lists?
* Decimal Numbers (type="1"): This is the default style. It uses regular decimal numbers. 
* Uppercase Letters (type="A"): It uses uppercase letters (A, B, C) as list item numbers.
* Lowercase Letters (type="a"): It uses lowercase letters (a, b, c) as list item numbers.
* Uppercase Roman Numerals (type="I"): It uses uppercase Roman numerals (I, II, III) as list item numbers.
* Lowercase Roman Numerals (type="i"): It uses lowercase Roman numerals (i, ii, iii) as list item numbers. 

* 2: What is the use of the start attribute in ordered lists? 

* 3: Explain the concept of nested lists 

* 4: How do you create a horizontal navigation menu using an unordered list? 


## HTML Tables:
* HTML tables allow web developers to arrange data into rows and columns.
* we must write everything inside the table tag.

* ```<table></table>``` This element defines an HTML table which is used to organize data into row and column, -->
* ```<tbody>``` element Groups the main content(data rows).
* ```<thead>``` element Groups the header content (table heading).
* ```<th>``` Defines a header cell (table heading) with in a table.
* ```<td>``` Represent a data cell within an HTML table.
* ```<tr>``` Defines a row within an html table

* A table in HTML consists of table cells inside rows and columns.

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

* Each table cell is defined by a ``` <td>``` and a ```</td>``` tag.

* td stands for table data.

## Table Rows
* Each table row starts with a ``` <tr> and ends with a </tr>``` tag

tr stands for table row.

## Table Headers
*Sometimes you want your cells to be table header cells, In those cases use the ```<th> tag instead of the <td>```

## th stands for table header.

## INTERVIEW Q: HTML TABLES

*  1: What is the purpose of the ```<thead>```, ```<tbody>```, and ```<tfoot>``` elements within a table? -->
* 2: How can you create table headers using the ```<th>``` element? How is it different from using ```<td>``` for data cells? -->
* 3: What is the significance of the colspan and rowspan attributes in table cells? Provide an example. -->

## The HTML <pre> Element
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
## HTML Style Attribute
* Setting the style of an HTML element, can be done with the style attribute
* HTML style attribute has the following syntax
```
<tagname style="property:value;">
```
* The property is a CSS property. The value is a CSS value.

## Background Color
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
## HTML Formatting Elements
 
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

## HTML Quotation and Citation Elements

## <blockquote> for Quotations

* HTML ```<blockquote>``` element defines a section that is quoted from another source

## <q> for Short Quotations
```
<p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
```
## <abbr> for Abbreviations

* The HTML ```<abbr>``` tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr."
```
<p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
```
## HTML <address> for Contact Information
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

## Link to an Email Address
* Use mailto: inside the href attribute to create a link that opens the user's email program (to let them send a new email).
```
<a href="mailto:someone@example.com">Send email</a>
```
## HTML Form

* The form is a collection of input tags in an HTML document.
* Forms are mainly used to take the data from the user to serve on the server.
* Forms are created using ```<form>``` tag.

## Form Tag Attributes

* action: This attribute specifies what action will be taken after submitting the form.
* target: This specifies on which browser tab the response will be displayed after form submission.
* method: This attribute is used to define the HTTP method used to submit the form.

#### What a normal HTML Form Contains?
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

## Input Tag in HTML 

* The input tag specifies an input field where the user can enter data.
* Input filed is created using ```<input> ```tag.
* Input tags don't need any closing tags.

#### Types of Input Tag

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

## Input Tag Attributes

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

## Semantic HTML5 Elements

* The elements in HTML which define their meaning are semantic elements.
And also these elements describe their content.

#### Semantic Elements:

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

## Non-Semantic HTML5 Elements

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

## HTML Styles - CSS
* CSS stands for Cascading Style Sheets.
* CSS saves a lot of work. It can control the layout of multiple web pages all at once.

## CSS can be added to HTML documents in 3 ways:

* Inline - by using the style attribute inside HTML elements
* Internal - by using a ```<style> element in the <head>``` section
* External - by using a ```<link>``` element to link to an external CSS file

## Inline CSS
* An inline CSS is used to apply a unique style to a single HTML element.
* An inline CSS uses the style attribute of an HTML element.

```html
<h1 style="color:blue;">A Blue Heading</h1>

<p style="color:red;">A red paragraph.</p>
```

## Internal CSS

* An internal CSS is used to define a style for a single HTML page.
* An internal CSS is defined in the ```<head>``` section of an HTML page, within a ```<style>``` element.

```html
<!DOCTYPE html>
<html>
<head>
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

## External CSS
* An external style sheet is used to define the style for many HTML pages.
* To use an external style sheet, add a link to it in the ```<head>``` section of each HTML page

```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" href="styles.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```
styles.css
```
body {
  background-color: powderblue;
}
h1 {
  color: blue;
}
p {
  color: red;
}
```