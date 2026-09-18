# HTML - Basics to Advanced

Going through basics to advanced of Hypertext Markup Language (HTML) by the help of W3Schools.

# What is HTML?

HTML is the standard markup language for creating Web pages.

HTML stands for Hyper Text Markup Language

HTML is the standard markup language for creating Web pages

HTML describes the structure of a Web page

HTML consists of a series of elements

HTML elements tell the browser how to display the content

# Learn HTML Using Notepad or TextEdit

A simple text editor is all you need to learn HTML.

Web pages can be created and modified by using professional HTML editors.

We believe that using a simple text editor is a good way to learn HTML but I am using visual studio code to save time.

# A simple HTML document

Example:

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

# Basic tag definition

The "!DOCTYPE html" declaration defines that this document is an HTML5 document.

    <!DOCTYPE html>

The "html" element is the root element of an HTML page.

    <html>

The "head" element contains meta information about the HTML page.

    <head>

The "title" element specifies a title for the HTML page (which is shown in the browser's title bar or in the page's tab)

    <title>

The "body" element defines the document's body, and is a container for all the visible contents, such as headings, paragraphs, images, hyperlinks, tables, lists, etc.

    <body>

The "h1" element defines a large heading.

    <h1>

The "p" element defines a paragraph

    <p>

All HTML documents must start with a document type declaration:

     <!DOCTYPE html>.

The HTML document itself begins with

    <html> and ends with </html>.

The visible part of the HTML document is between

    <body> and </body>.

The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

The <!DOCTYPE> declaration is not case sensitive.

The <!DOCTYPE> declaration for HTML5 is: >!DOCTYPE html>

# What is an HTML Element?

An HTML element is defined by a start tag, some content, and an end tag:

    <tagname> Content goes here... </tagname>

The HTML element is everything from the start tag to the end tag:

    <h1>My First Heading</h1>
    <p>My first paragraph.</p>

# Empty HTML Elements

HTML elements with no content are called empty elements.

The "br" tag defines a line break, and is an empty element without a closing tag:

     <br>

Example:

    <p>This is a <br> paragraph with a line break.</p>

# Nested HTML Elements

HTML elements can be nested (this means that elements can contain other elements).
All HTML documents consist of nested HTML elements.
The following example contains four HTML elements

    <html>, <body>, <h1> and <p>

# HTML Headings and Paragraphs

HTML headings are defined with the "h1 to h6" tags.

h1 defines the most important heading.

h6 defines the least important heading:

Example:

    <h1>This is heading 1</h1>

    <h2>This is heading 2</h2>

    <h3>This is heading 3</h3>

    <h4>This is heading 4</h4>

    <h5>This is heading 5</h5>

    <h6>This is heading 6</h6>

HTML paragraphs are defined with the "p" tag:

      <p>

Example:

    <p>This is a paragraph.</p>

    <p>This is another paragraph.</p>

# HTML Text Formatting

    <b> - Bold text
    <strong> - Important text
    <i> - Italic text
    <em> - Emphasized text
    <mark> - Marked text
    <small> - Smaller text
    <del> - Deleted text
    <ins> - Inserted text
    <sub> - Subscript text
    <sup> - Superscript text


# HTML Links

HTML links are defined with the "a" tag:

      <a>

The link's destination is specified in the href attribute.

Attributes are used to provide additional information about HTML elements.

Example:

    <a href="https://www.w3schools.com">This is a link</a>

# HTML Images

HTML images are defined with the "img" tag.

    <img>

The source file (src), alternative text (alt), width, and height are provided as attributes:

Example:

    <img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">

# Different input types used in Forms are as follows:

    <input type="button">
    <input type="checkbox">
    <input type="color">
    <input type="date">
    <input type="datetime-local">
    <input type="email">
    <input type="file">
    <input type="hidden">
    <input type="image">
    <input type="month">
    <input type="number">
    <input type="password">
    <input type="radio">
    <input type="range">
    <input type="reset">
    <input type="search">
    <input type="submit">
    <input type="tel">
    <input type="text"> (default value)
    <input type="time">
    <input type="url">
    <input type="week">

# Web Browsers

The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.

A browser does not display the HTML tags, but uses them to determine how to display the document:

Note:
The content inside the "body" section will be displayed in a browser.

    <body> 

    Example:
    <body>
        <h2>This is heading.</h2>
        <p>This is paragraph.</p>
    </body>

The content inside the "title" element will be shown in the browser's title bar or in the page's tab.

    <title> 

    Example:
    <title> HTML CSS Basics</title>


# HTML History

Since the early days of the World Wide Web, there have been many versions of HTML:

Year ---> Version

1989 ---> Tim Berners-Lee invented www

1991 ---> Tim Berners-Lee invented HTML

1993 ---> Dave Raggett drafted HTML+

1995 ---> HTML Working Group defined HTML 2.0

1997 ---> W3C Recommendation: HTML 3.2

1999 ---> W3C Recommendation: HTML 4.01

2000 ---> W3C Recommendation: XHTML 1.0

2008 ---> WHATWG HTML5 First Public Draft

2012 ---> WHATWG HTML5 Living Standard

2014 ---> W3C Recommendation: HTML5

2016 ---> W3C Candidate Recommendation: HTML 5.1

2017 ---> W3C Recommendation: HTML5.1 2nd Edition

2017 ---> W3C Recommendation: HTML5.2

# HTML is Not Case Sensitive

HTML tags are not case sensitive:

    <P> means the same as <p>.

The HTML standard does not require lowercase tags, but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.