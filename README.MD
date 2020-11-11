![HTML5 Logo](assets/HTML5.png)
<h1 style="text-align: center;"> HTML </h1>
<h4 style="text-align: center;"> Hyper Text Markup Language </h4>
 Hypertext Markup Language is the standard markup language for documents designed to be displayed in a web browser. It can be assisted by technologies such as Cascading Style Sheets and scripting languages such as JavaScript.
 </br></br>

 **HTML Basic Syntax**

    <!DOCTYPE html>
    <html lang="en">
    <head>
        <title>Page Title</title>
    </head>
    <body>
        <h1>My First Heading</h1>
        <p>My first paragraph.</p>
    </body>
    </html> 

***Explanation of Code***

    The <!DOCTYPE html> declaration defines that this document is an HTML5 document
    The <html> element is the root element of an HTML page
    The <head> element contains meta information about the HTML page
    The <title> element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)
    The <body> element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.
    The <h1> element defines a large heading
    The <p> element defines a paragraph
</br>

***The <!DOCTYPE> Declaration***

The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.
The HTML5 syntax for doctype is : ```<!DOCTYPE html>```

***HTML Elements***
An HTML element is defined by a start tag, some content, and an end tag:
    `<tagname>Content goes here...</tagname>`

***HTML Attributes***
* All HTML elements can have attributes
* Attributes provide additional information about elements
* Attributes are always specified in the start tag
* Attributes usually come in name/value pairs like: name="value"            
---
<br>

## HTML Headings

HTML headings are defined with the `<h1>` to `<h6>` tags.   
<ul>  
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
</ul>

Heading 1 is  `<h1>` and so on ... Heading 6 is `<h6>`.
>Syntax : `<h1>. . . . .</h1>`  


## HTML Paragraphs

The HTML `<p>` element defines a paragraph.

A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.

>Syntax : `<p>. . . . .</p>`

***HTML Line Breaks***
The HTML `<br>` element defines a line break.
Use `<br>` if you want a line break (a new line) without starting a new paragraph


## HTML Styles
The HTML style attribute is used to add styles to an element, such as color, font, size, and more.
>Syntax is : `<tagname style="property:value;">`


## HTML Text Formatting
HTML contains several elements for defining text with a special meaning.

***HTML Formatting Elements***
Formatting elements were designed to display special types of text:

    <b> Bold text </b>
    <strong> Important text </strong>
    <i> Italic text </i>
    <em> Emphasized text </em>
    <mark> Marked text </mark>
    <small> Smaller text </small>
    <del> Deleted text </del>
    <ins> Inserted text </ins>
    S<sub> Subscript text </sub>
    S<sup> Superscript text </sup>
>The Above syntax results in the output shown below :<br>
<b> Bold text </b>
<strong> Important text </strong>
<i> Italic text </i>
<em> Emphasized text </em>
<mark> Marked text </mark>
<small> Smaller text </small>
<del> Deleted text </del>
<ins> Inserted text </ins>
S<sub> Subscript text </sub>
S<sup> Superscript text </sup>

## HTML Quotation and Citation Elements
Some of HTML Quotation and Citation Elements are `<blockquote>,<q>, <abbr>, <address>, <cite>, and <bdo> .`

* The HTML `<blockquote>` element defines a section that is quoted from another source.
* The HTML `<q>` tag defines a short quotation.
* The HTML `<abbr>` tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".
* The HTML `<address>` tag defines the contact information for the author/owner of a document or an article.
* The HTML `<cite>` tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).
* The HTML `<bdo>` tag is used to override the current text direction *(BDO stands for Bi-Directional Override)*.

## HTML Comments
HTML comments are not displayed in the browser, but they can help document your HTML source code.

>Syntax :`<!-- Write your comments here -->`

## HTML Styles - CSS
Cascading Style Sheets (CSS) is used to format the layout of a webpage.

With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!

**CSS can be added to HTML documents in 3 ways:**

* Inline - by using the style attribute inside HTML elements.
* Internal - by using a `<style>` element in the `<head>` section.
* External - by using a `<link>` element to link to an external CSS file.

**Inline CSS**
An inline CSS is used to apply a unique style to a single HTML element.
>Syntax :`<h1 style="color:blue;">A Blue Heading</h1>`

**Internal CSS**
An internal CSS is used to define a style for a single HTML page.
```
<style>
body {background-color: powderblue;}
h1   {color: blue;}
p    {color: red;}
</style>
```

**External CSS**
An external style sheet is used to define the style for many HTML pages.
To use an external style sheet, add a link to it in the `<head>` section of each HTML page:
>Syntax :```<link rel="stylesheet" href="styles.css">```

## HTML Links
The HTML `<a>` tag defines a hyperlink.
>Syntax :`<a href="url">link text</a>`

The most important attribute of the `<a>` element is the href attribute, which indicates the link's destination.
***HTML Links - The target Attribute***
By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The target attribute specifies where to open the linked document.

The target attribute can have one of the following values:
* _self - Default. Opens the document in the same window/tab as it was clicked
* _blank - Opens the document in a new window or tab
* _parent - Opens the document in the parent frame
* _top - Opens the document in the full body of the window

***HTML Links - Use an Image as a Link***
To use an image as a link, just put the `<img>` tag inside the `<a>` tag:
>Syntax : `<img src="image.png" alt="error loading" >`

***Link to an Email Address***
Use mailto: inside the href attribute to create a link that opens the user's email program (to let them send a new email)
>Syntax : `<a href="mailto:someone@example.com">Send email</a>`

***Button as a Link***
To use an HTML button as a link, you have to add some JavaScript code.
>Syntax : `<button onclick="document.location='default.asp'">HTML Tutorial</button>`


## HTML Images
The HTML `<img>` tag is used to embed an image in a web page.

Images are not technically inserted into a web page; images are linked to web pages.
The `<img>` tag has two required attributes:
- src - Specifies the path to the image
- alt - Specifies an alternate text for the image
>Syntax : `<img src="url" alt="alternatetext">`

***Image Maps***
The HTML <map> tag defines an image map. An image map is an image with clickable areas. The areas are defined with one or more <area> tags.

```
<img src="workplace.jpg" alt="Workplace" usemap="#workmap">

<map name="workmap">
  <area shape="rect" coords="34,44,270,350" alt="Computer" href="computer.htm">
</map>
```
    You must define the shape of the clickable area, and you can choose one of these values:

- rect - defines a rectangular region
- circle - defines a circular region
- poly - defines a polygonal region
- default - defines the entire region

## HTML Tables
HTML tables allow web developers to arrange data into rows and columns.

The `<table>` tag defines an HTML table.
Each table row is defined with a `<tr>` tag. Each table header is defined with a `<th>` tag. Each table data/cell is defined with a `<td>` tag.

    <table style="width:100%">
    <tr>
        <th>Firstname</th>
        <th>Lastname</th>
        <th>Age</th>
    </tr>
    <tr>
        <td>Rahul</td>
        <td>Mishra</td>
        <td>22</td>
    </tr>
    <tr>
        <td>Abhishek</td>
        <td>Mishra</td>
        <td>18</td>
    </tr>
    </table>

The Above Code will output is shown below :

<table style="width:100%">
  <tr>
    <th>Firstname</th>
    <th>Lastname</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Rahul</td>
    <td>Mishra</td>
    <td>22</td>
  </tr>
  <tr>
    <td>Abhishek</td>
    <td>Mishra</td>
    <td>18</td>
  </tr>
</table>

>Some important tag and their descriptions :

    <table>	        Defines a table
    <th>	        Defines a header cell in a table
    <tr>	        Defines a row in a table
    <td>	        Defines a cell in a table
    <caption>	Defines a table caption
    <colgroup>	Specifies a group of one or more columns in a table for formatting
    <col>	        Specifies column properties for each column within a <colgroup> element
    <thead>	        Groups the header content in a table
    <tbody>	        Groups the body content in a table
    <tfoot>	        Groups the footer content in a table

## HTML Lists
HTML lists allow web developers to group a set of related items in lists.

**Unordered HTML List**
An unordered list starts with the `<ul>` tag. Each list item starts with the `<li>` tag.

    <ul>
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
    </ul>
The above code will produce following output :
<ul>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>

**Ordered HTML List**
An ordered list starts with the `<ol>` tag. Each list item starts with the `<li>` tag.

    <ol>
    <li>Coffee</li>
    <li>Tea</li>
    <li>Milk</li>
    </ol>
The above code will produce following output :
<ol>
<li>Coffee</li>
<li>Tea</li>
<li>Milk</li>
</ol>

## HTML Block and Inline Elements
Every HTML element has a default display value, depending on what type of element it is.

There are two display values: block and inline.
**1. Block-level Elements**
A block-level element always starts on a new line and takes up the full width available (stretches out to the left and right as far as it can).

The `<div>` element is a block-level element.
>Syntax : `<div>Hello World</div>`    

The block-level elements in HTML:

    <address> <article> <aside> <blockquote> <canvas> <dd> <div> <dl> 
    <dt> <fieldset> <figcaption> <figure> <footer> <form> <h1>-<h6> 
    <header> <hr> <li> <main> <nav> <noscript> <ol> <p> <pre> <section> 
    <table> <tfoot> <ul> <video>

**2. Inline Elements**
An inline element does not start on a new line and it only takes up as much width as necessary.

This is a `<span>` element inside a paragraph.
>Syntax : <span>Hello World</span>

The inline elements in HTML:
    `<a> <abbr> <acronym> <b> <bdo> <big> <br> <button> <cite> <code>` 
    `<dfn> <em> <i> <img> <input> <kbd> <label> <map> <object> <output>` 
    `<q> <samp> <script> <select> <small> <span> <strong> <sub> <sup>` 
    `<textarea> <time> <tt> <var>`
    
## HTML Iframes
An HTML iframe is used to display a web page within a web page.
The HTML `<iframe>` tag specifies an inline frame.
An inline frame is used to embed another document within the current HTML document.

>Syntax : `<iframe src="url" title="description">`

## HTML File Paths
A file path describes the location of a file in a web site's folder structure.

**Absolute File Paths**
An absolute file path is the full URL to a file:
>Syntax : `<img src="https://www.wikipedia.com/images/picture.jpg" alt="Hills">`

**Relative File Paths**
A relative file path points to a file relative to the current page.
>Syntax : `<img src="/images/picture.jpg" alt="Mountain">`

>*It is best practice to use relative file paths (if possible).*

## HTML Head
Websites often display content in multiple columns (like a magazine or a newspaper).

**HTML Layout Elements**
* `<header>` - Defines a header for a document or a section
* `<nav>` - Defines a set of navigation links
* `<section>` - Defines a section in a document
* `<article>` - Defines an independent, self-contained content
* `<aside>` - Defines content aside from the content (like a sidebar)
* `<footer>` - Defines a footer for a document or a section
* `<details>` - Defines additional details that the user can open and close on demand
* `<summary>` - Defines a heading for the `<details>` element

## HTML Computer Code Elements
HTML contains several elements for defining user input and computer code.

    Syntax :
    <code>
    x = 5;<br>
    y = 6;<br>
    z = x + y;
    </code>

**`<kbd>` For Keyboard Input**
The HTML `<kbd>` element is used to define keyboard input. The content inside is displayed in the browser's default monospace font.

**`<samp>` For Program Output**
The HTML `<samp>` element is used to define sample output from a computer program. The content inside is displayed in the browser's default monospace font.

## HTML Entities
Some characters are reserved in HTML.

If you use the less than (<) or greater than (>) signs in your text, the browser might mix them with tags.

Character entities are used to display reserved characters in HTML.

**HTML Character Entities :**
| Result	| Description	| Entity Name	| Entity Number |
| :---      |    :----:     | :----:        |          ---: |
|	| non-breaking space	| `&nbsp;`	    | `&#160`;      |
|<	| less than	            | `&lt;`	    | `&#60`;       |
|>	| greater than	        | `&gt;`	    | `&#62;`       |
|&	| ampersand	            | `&amp;`	    | `&#38;`       |
|"	| double quotation mark	| `&quot;`	    | `&#34;`       |
|'	| single quotation mark	| `&apos;`	    | `&#39;`       |
|¢	| cent	                | `&cent;`	    | `&#162;`      |
|£	| pound	                | `&pound;`	    | `&#163;`      |
|¥	| yen	                | `&yen;`	    | `&#165;`      |
|€	| euro	                | `&euro;`	    | `&#8364;`     |
|©	| copyright	            | `&copy;`	    | `&#169;`      |
|®	| registered trademark	| `&reg;`	    | `&#174;`      |


## HTML Symbols
Symbols that are not present on your keyboard can also be added by using entities.

**Some Mathematical Symbols :**
| Char	| Number	| Entity	| Description |
| :---  | :---:     | :---:     | :---:        |
| ∀	    | `&#8704;`	| `&forall;`| FOR ALL | 
| ∂	    | `&#8706;`	| `&part;`	| PARTIAL DIFFERENTIAL | 
| ∃	    | `&#8707;`	| `&exist;`	| THERE EXISTS |
| ∅	    | `&#8709;`	| `&empty;`	| EMPTY SETS |
| ∇	    | `&#8711;`	| `&nabla;`	| NABLA |
| ∈	    | `&#8712;`	| `&isin;`	| ELEMENT OF |
| ∉	    | `&#8713;`	| `&notin;`	| NOT AN ELEMENT OF |
| ∋	    | `&#8715;`	| `&ni;`	| CONTAINS AS MEMBER |
| ∏	    | `&#8719;`	| `&prod;`	| N-ARY PRODUCT |
| ∑	    | `&#8721;`	| `&sum;`	| N-ARY SUMMATION |

**Some Geek Symbols :**
| Char	| Number	| Entity	 |            Description       |
| :---  | :---:     | :---:      |            :---:              |
| Α	    | `&#913;`	| `&Alpha;`	 | GREEK CAPITAL LETTER ALPHA   |
| Β	    | `&#914;`	| `&Beta;`	 | GREEK CAPITAL LETTER BETA    |
| Γ	    | `&#915;`	| `&Gamma;`	 | GREEK CAPITAL LETTER GAMMA   |
| Δ	    | `&#916;`	| `&Delta;`	 | GREEK CAPITAL LETTER DELTA   |
| Ε	    | `&#917;`	| `&Epsilon;`| GREEK CAPITAL LETTER EPSILON |
| Ζ	    | `&#918;`	| `&Zeta;`	 | GREEK CAPITAL LETTER ZETA    |


## Using Emojis in HTML
Emojis are characters from the UTF-8 character set: 😄 😍

**What are Emojis?**
Emojis look like images, or icons, but they are not.

They are letters (characters) from the UTF-8 (Unicode) character set.

**Some Emoji Symbols in UTF-8 :**

| Emoji	| Value   |
| :---  | ---:    |
| 🗻	| #128507;|
| 🗼	| #128508;|
| 🗽	| #128509;|
| 🗾	| #128510;|
| 🗿	| #128511;|
| 😀	| #128512;|
| 😁	| #128513;|
| 😂	| #128514;|
| 😃	| #128515;|
| 😄	| #128516;|
| 😅	| #128517;|

>For Full Emojis List : [Click Here👈](https://www.w3schools.com/charsets/ref_emoji.asp)


##HTML Encoding (Character Sets)
To display an HTML page correctly, a web browser must know which character set to use.

>Want to more about Character Sets : [Click Here👈](https://www.w3schools.com/html/html_charset.asp)

---

## HTML Forms
An HTML form is used to collect user input. The user input is most often sent to a server for processing.

**The `<form>` Element**
The HTML `<form>` element is used to create an HTML form for user input:

    <form>
    .
    form elements
    .
    </form>

**The `<input>` Element**
The HTML `<input>` element is the most used form element.
An `<input>` element can be displayed in many ways, depending on the type attribute.

|       Type	        |       Description         |
|       :---            |           :---            |
|`<input type="text">`	| Displays a single-line text input field
|`<input type="radio">`	| Displays a radio button (for selecting one of many choices)
|`<input type="checkbox">`|	Displays a checkbox (for selecting zero or more of many choices)
|`<input type="submit">`| Displays a submit button (for submitting the form)
|`<input type="button">`| Displays a clickable button

**Text Fields**
The `<input type="text">` defines a single-line input field for text input.

**The <label> Element**
The `<label>` tag defines a label for many form elements.
The `<label>` element is useful for screen-reader users, because the screen-reader will read out loud the label when the user focus on the input element.

**Radio Buttons**
The `<input type="radio">` defines a radio button.
Radio buttons let a user select ONE of a limited number of choices.

**Checkboxes**
The `<input type="checkbox">` defines a checkbox.
Checkboxes let a user select ZERO or MORE options of a limited number of choices.

**The Submit Button**
The `<input type="submit">` defines a button for submitting the form data to a form-handler.

**HTML Input Types**
* `<input type="button">`
* `<input type="checkbox">`
* `<input type="color">`
* `<input type="date">`
* `<input type="datetime-local">`
* `<input type="email">`
* `<input type="file">`
* `<input type="hidden">`
* `<input type="image">`
* `<input type="month">`
* `<input type="number">`
* `<input type="password">`
* `<input type="radio">`
* `<input type="range">`
* `<input type="reset">`
* `<input type="search">`
* `<input type="submit">`
* `<input type="tel">`
* `<input type="text">`
* `<input type="time">`
* `<input type="url">`
* `<input type="week">`

**Input Restrictions**
Here is a list of some common input restrictions:

| Attribute	| Description |
| :---      |  :---     |
| checked	|Specifies that an input field should be pre-selected when the page loads (for type="checkbox" or type="radio")
| disabled	| Specifies that an input field should be disabled
| max	    | Specifies the maximum value for an input field
| maxlength	| Specifies the maximum number of character for an input field
| min	    | Specifies the minimum value for an input field
| pattern	| Specifies a regular expression to check the input value against
| readonly	| Specifies that an input field is read only (cannot be changed)
| required	| Specifies that an input field is required (must be filled out)
| size	    | Specifies the width (in characters) of an input field
| step	    | Specifies the legal number intervals for an input field
| value	    | Specifies the default value for an input field


## HTML Graphics

**HTML Canva Graphics**
The HTML `<canvas>` element is used to draw graphics on a web page.

The graphic to the left is created with `<canvas>`.
It shows four elements: a red rectangle, a gradient rectangle, a multicolor rectangle, and a multicolor text.
* **What is HTML Canvas?**
The HTML `<canvas>` element is used to draw graphics, on the fly, via JavaScript.
The `<canvas>` element is only a container for graphics. You must use JavaScript to actually draw the graphics.

>Syntax : `<canvas id="myCanvas" width="200" height="100"></canvas>`

>For Full Canva tutorial : [Click Here👈](https://www.w3schools.com/graphics/canvas_intro.asp)

**HTML SVG Graphics**
SVG defines vector-based graphics in XML format.

* **What is SVG?**
* SVG stands for Scalable Vector Graphics
* SVG is used to define graphics for the Web

The HTML `<svg>` element is a container for SVG graphics.

    <svg width="100" height="100">
    <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
    </svg>

The above code  will create :

<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="green" stroke-width="4" fill="yellow" />
</svg>

>For Full SVG tutorial : [Click Here👈](https://www.w3schools.com/graphics/svg_intro.asp)

## HTML Multimedia
Multimedia on the web is sound, music, videos, movies, and animations.
Multimedia comes in many different formats. It can be almost anything you can hear or see, like images, music, sound, videos, records, films, animations, and more.
Web pages often contain multimedia elements of different types and formats.

**HTML Video**
The HTML `<video>` element is used to show a video on a web page.
The controls attribute adds video controls, like play, pause, and volume.

**HTML Audio**
The HTML `<audio>` element is used to play an audio file on a web page.
The controls attribute adds audio controls, like play, pause, and volume.

**HTML YouTube Videos**
The easiest way to play videos in HTML, is to use YouTube.

To play your video on a web page, do the following:

* Upload the video to YouTube
* Take a note of the video id
* Define an `<iframe>` element in your web page
* Let the src attribute point to the video URL
* Use the width and height attributes to specify the dimension of the player
* Add any other parameters to the URL (see below)

<br>
<br>
<br>
<br>
<br>
<h1 style="text-align: center;">
 <span style="color:GREEN">THANK YOU</span>
 </h1>

 For detailed HTML5 tutorial visit : [w3schools.com](https://www.w3schools.com/html/)
 Created by :[TheCyberAtom](https://github.com/TheCyberAtom)
![Happy Coding](https://media.giphy.com/media/pLgom5kv8PLnG/giphy.gif)
