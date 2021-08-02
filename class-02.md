# Basics of HTML, CSS & JS


# What's content management system (CMS)
A content management system (CMS) is a program that allows many contributors to generate, modify, and publish web content. In a CMS, content is generally saved in a database and presented using a collection of templates in a presentation layer.

# HTML(Tags/ Structural / Semantic Markup) :

## Structural vs Semantic Markup :
![st vs sm](https://www.jungledisk.com/blog/content/images/blog/div-soup-vs-semantic-html.png)

A **semantic element** clearly describes its meaning to both the browser and the developer.

Examples of **non-semantic elements**: `<div>` and `<span>`- Tells nothing about its content.

Examples of semantic elements: `<form>`, `<table>`, and `<article>` - Clearly defines its content.

# More Semantic Elements in HTML
Many web sites contain HTML code like: <div id="nav"> <div class="header"> <div id="footer"> to indicate navigation, header, and footer.

In HTML there are some semantic elements that can be used to define different parts of a web page:  

`<article>`

`<aside>`

`<details>`

`<figcaption>`

`<figure>`

`<footer>`

`<header>`

`<main>`

`<mark>`

`<nav>`

`<section>`    

`<summary>`    

`<time>`

# HTML Headings
![](https://www.schudio.com/wp-content/uploads/2016/10/html-headings-title.png)
HTML headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. `<h6>` defines the least important heading.

![](https://karoku.com/wp-content/uploads/2019/02/heading-tags.jpg)


# HTML Paragraphs
The HTML `<p>` element defines a paragraph.

A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.

**Example** :

`<p>`This is a paragraph.`</p>`

`<p>`This is another paragraph.`</p>`

# Superscript & Subscript
`<sup>`
The `<sup>` element is used
to contain characters that
should be superscript such
as the suffixes of dates or
mathematical concepts like
raising a number to a power such
as 22.
`<sub>`

The `<sub>` element is used to
contain characters that should
be subscript. It is commonly
used with foot notes or chemical
formulas such as H20.

# Summary
* TEXT HTML elements are used t XX o describe the structure of
the page ( headings, subheadings, paragraphs).

* They also provide semantic information ( where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).


# Introducing-CSS
we will look at how to make your web pages more attractive, controlling the design of them using CSS.

# Understanding-CSS
The key to understanding how CSS works is to imagine that there is an invisible box around every HTML element.

# CSS-Style-Rules
CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration. 

This rule indicates that all <p> elements should be shown in the Arial typeface.

Selectors indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.

Declarations indicate how the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a colon.

CSS Properties Affect How Elements Are Displayed
CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify several properties in one declaration, each separated by a semi-colon.


# Using-Externel-CSS
`<link>` The `<link>` element can be used in an HTML document to tell the browser where to find the CSS file used to style the page. It is an empty element (meaning it does not need a closing tag), and it lives inside the `<head>` element. It should use three attributes:

`href`

This specifies the path to the CSS file (which is often placed in a folder called css or styles).

`type`

This attribute specifies the type of document being linked to. The value should be text/css.

`rel`

This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when linking to a CSS file.

Using-Internal-CSS

`<style>`


You can also include CSS rules within an HTML page by placing them inside a `<style>` element, which usually sits inside the `<head>` element of the page.

The `<style>` element should use the type attribute to indicate that the styles are specified in CSS. The value should be text/ css.

# CSS-Selector

There are many different types
of CSS selector that allow you to
target rules to specific elements
in an HTML document.

The table on the opposite page
introduces the most commonly
used CSS selectors.

On this page, there is an HTML
file to demonstrate which
elements these CSS selectors
would apply to.

CSS selectors are case sensitive,
so they must match element
names and attribute values
exactly.

There are some more advanced
selectors which allow you
to select elements based on
attributes and their values,
which you will see on page 292.
IE 7 was the first version of IE to
support the last two selectors in
the table (the sibling selectors),
so their use is less common than
the other selectors shown here.

<!DOCTYPE html>
<html>
<head>
<title>CSS Selectors</title>
</head>
<body>
<h1 id="top">Kitchen Garden Calendar</h1>
<p id="introduction">Here you can read our
handy guide about what to do when.</p>
<h2>Spring</h2>
<ul>
<li><a href="mulch.html">
Spring mulch vegetable beds</a></li>
<li><a href="potato.html">
Plant out early potatoes</a></li>
<li><a href="tomato.html">
Sow tomato seeds</a></li>
<li><a href="beet.html">
Sow beet seeds</a></li>
<li><a href="zucchini.html">
Sow zucchini seeds</a></li>
<li><a href="rhubarb.html">
Deadhead rhubarb flowers</a></li>
</ul>
<p>
</p>
</body>
<html>

#

# Summary-CSS

* CSS treats each HTML element as if it appears inside its own box and uses rules to indicate how that element should look.

* Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).

* Different types of selectors allow you to target your rules at different elements.

* Declarations are made up of two parts: the properties of the element that you want to change, and the values of those properties. For example, the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.

* CSS rules usually appear in a separate document, although they may appear within an HTML page.


# Javascript 

Javascript is what makes a web page interactive ,The structure of your online document, as well as the content within it, is defined by HTML. CSS specifies different styles for the contents of a web document. JavaScript, on the other hand, is a dynamic programming language that allows you to do things like do math computations, generate dynamic style declarations, and fetch content from other websites.
we can use Javascript in HTML in many ways like :

* Internal JavaScript with the script tag
Just like the style tag for style declarations within an HTML page, the script tag exists for JavaScript. Here's how it's used:

`<script>`

 `function(){`

     `alert("I am inside a script tag")`
 `}`
`</script>`

* External JavaScript
You may want to have your JavaScript code in a different file. External JavaScript allows this. For such uses-cases, here's how it's done:

`<script src="./script.js">
</script>
alert("I am inside an external file");`

The src attribute of the script tag allows you to apply a source for the JavaScript code. That reference is important because it notifies the browser to also fetch the content of script.js.

## 3) How to talk to the user

The alert() method displays an alert box with a specified message and an OK button.

An alert box is often used if you want to make sure information comes through to the user.

`alert("Hello\nHow are you?");`

# Operators and Loops in JavaScript

![JavaScript loops](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/07/JavaScript-Loops-1200x720.jpg)

![operators](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/03/JavaScript-Operators-1200x720.jpg)

## First **Loops**

### Here we are gonig to cover only `for` and `while` loops

## For Loops

`for ([initialization]); [condition]; [final-expression])`

`{`

  `// code`

`}`

### Description

* __initialization__ - Performed before the loop's first iteration. Counters are frequently created using this expression. Variables generated in this section are limited to the loop. They are deleted once the loop has completed its iteration.

* __condition__ - An expression that is tested before each repetition begins. If this expression is left blank, it translates to true. The loop's statement is executed if it evaluates to true. The loop ends if it evaluates to false.

* __final-expression__ - After each iteration, this expression is run. Typically used to increase the value of a counter. However, it can also be used to decrement a counter.

* __statement__ - The code that will be repeated in a loop.

## Example

![example](https://res.cloudinary.com/practicaldev/image/fetch/s--RD5sE5BL--/c_limit%2Cf_auto%2Cfl_progressive%2Cq_66%2Cw_880/https://thepracticaldev.s3.amazonaws.com/i/ciwuuuxvt9ew1sxd45hl.gif)

## While loops

The condition is evaluated first in the while loop. The statement(s) is/are performed if the condition is true. The statement(s) is/are not performed if the condition is false, and the while loop terminates. While loops are worth paying attention to since if the false condition is never satisfied, you'll end up with an endless loop. An infinite loop might cause your program or browser to break.

`while (condition)`

`{`

  `code;`

`}`

## Example

![while loops ](https://www.toolsqa.com/wp-content/gallery/javascript/doWhile-loop.png)

## -------------------------------------------------------

## Second __Operators__

Operators are included in JavaScript, just as they are in other languages. An operator provides a result by performing an action on a single or more operands (data value). For example, 1 + 2 is an operator with 1 as the left operand and 2 as the right operand. The + operator adds two numeric numbers, yielding a result of 3, in this example.

### Some famous ones

`== equal to`

`=== equal value and equal type`

`!= not equal`

`!== not equal value or not equal type`

`> greater than`

`< less than`

`>= greater than or equal to`

`<= less than or equal to`

`? ternary operator`
# Arrays: 

This is a structure that allows you to store multiple values in a single reference.	
Creating an Array:

`let colors = [blue, pink, black, orange, red, yellow]`