# What I learnd About CSS

![CSS logo](https://cdn.pixabay.com/photo/2017/08/05/11/16/logo-2582747_1280.png)

"Cascading Style Sheet" is an acronym for "Cascading Style Sheet." The layout of Web pages is formatted using Cascading Style Sheets. They can be used to define text styles, table sizes, and other characteristics of Web pages that were previously solely defined in the HTML of the page.

CSS allows website designers to provide a uniform look across numerous pages. Rather of detailing the style of each table and block of text within the HTML of a page, commonly used styles only need to be declared once in a CSS document. Once a style is defined in a cascading style sheet, it can be used by any page that references the CSS file. CSS also makes updating the style of numerous pages at once a breeze. A Web developer could want to increase the default font size from 10pt to 12pt for fifty pages of a website. If all of the pages utilize the same style sheet, all that is required is to change the text size on the style sheet, and the larger text will display on all of them.

## CSS in Action

When a browser reads a style sheet, it will format the HTML document according to the information in the style sheet.
hree Ways to Insert CSS
There are three ways of inserting a style sheet:

* External CSS
* Internal CSS
* Inline CSS

**External CSS**
With an external style sheet, you can change the look of an entire website by changing just one file!

Each HTML page must include a reference to the external style sheet file inside the `<link>` element, inside the head section.

Example
**External styles** are defined within the <link> element, inside the <head> section of an HTML page:

<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
An external style sheet can be written in any text editor, and must be saved with a .css extension.

The external .css file should not contain any HTML tags.
Here is how the `"mystyle.css"` file looks:

`"mystyle.css"`
`body {`
  `background-color: lightblue;
}`

`h1 {
  color: navy;
  margin-left: 20px;
}`

Internal CSS
An internal style sheet may be used if one single HTML page has a unique style.

**The internal** style is defined inside the `<style> element`, inside the head section.

Example
Internal styles are defined within the <style> element, inside the `<head>` section of an HTML page:

`<!DOCTYPE html>`
`<html>`
`<head>`
`<style>`
`body {
  background-color: linen;
}`

`h1 {
  color: maroon;
  margin-left: 40px;
}`
`</style>
`</head>
`<body>`

`<h1>This is a heading</h1>`
  `<p>This is a paragraph.</p>`

`</body>`
`</html>`

**Inline CSS**
An inline style may be used to apply a unique style for a single element.

To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

Example
Inline styles are defined within the "style" attribute of the relevant element:

`<!DOCTYPE html>`
`<html>`
`<body>`

`<h1 style="color:blue;text-align:center;">This is a heading</h1>`
`<p style="color:red;">This is a paragraph.</p>`

`</body>`
`</html>`

## And I'm still learinig
