# "Images” / “Color” / “Text”  in HTML

## First Images in HTML :
A picture is worth a thousand words, and outstanding graphics may help distinguish an average-looking site from one that is truly engaging. 

In less time than it takes to read a description, images may be utilized to define the tone for a website. If you don't have any photos for your website, there are companies that sell stock images, which are images that you pay to use .
Remember that all images are protected by copyright, and merely copying photos from another website might get you in trouble.
If you have a page with numerous images (such as product photos or members of a team), using a simple, consistent background will help them look more cohesive.
## Adding Images

`<img>` images.html
The `<img>` element is used to insert an image into the page. There is no closing tag on this element, therefore it is empty. It must possess the following two characteristics:

## `<Src>`
This instructs the browser on where to look for the image file. This is generally a relative URL to a picture on your own website.

## `<alt>`
This gives you a written explanation of the image, which you may read if you can't see it.

## `<title>`

The title property of the `<img> ` element can also be used to offer more information about the picture. When the user hovers over the picture, most browsers will show the content of this property in a tootip.

![](https://miro.medium.com/max/1400/1*dqmfN8RwTJmvxNsoahJrMg.png)

# Summary
IMAGES
* The <img> element is used to add images to a web page.

* You must always specify a src attribute to indicate the
source of an image and an alt attribute to describe the
content of an image.

* You should save images at the size you will be using
them on the web page and in the appropriate format.

* Photographs are best saved as JPEGs; illustrations orlogos that use flat colors are better saved as GIFs.

## Second color In CSS\

You may use the color property to change the color of text inside an element. CSS allows you to define any color in one of three ways:

## `values in rgb`

These describe colors in terms of the proportions of red, green, and blue utilized to create them. For\sexample: rgb(100,100,90)
## `hexadecimal codes`

These are six-digit numbers preceded by a pound or hash # symbol that reflect the quantity of red, green, and blue in a color. For instance, #ee3e80.

##  color names
There are 147 predefined color
names that are recognized
by browsers

Background color
body {
background-color: rgb(200,200,200);}
h1 {
background-color: DarkCyan;}
h2 {
background-color: #ee3e80;}
p {
background-color: white;}

CSS treats each HTML element as if it appears in a box, and the background-color property sets the color of the background for that box.
You can specify your choice of background color in the same three ways you can specify foreground colors: RGB values, hex codes, and color names (covered on the next page). If you do not specify a background color, then the background is transparent.
Understanding Color
Every color on a computer screen is created by mixing amounts of red, green, and blue. To find the color you want, you can use a color picker.
Computer monitors are made up of thousands of tiny squares called pixels (if you look very closely at your monitor you should be able to see them).
 
When the screen is not turned on, it's black because it's not emitting any light. When it's on, each pixel can be a different color, creating a picture.
The color of every pixel on the screen is expressed in terms of a mix of red, green, and blue — just like on a television screen.
 
# Concepts
 
# Contrast
When picking foreground and background colors, it is important to ensure that there is enough contrast for the text to be legible.
 
# CSS 3 Opacity
CSS3 introduces the opacity property which allows you to specify the opacity of an element and any of its child elements. The value is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity).
The CSS3 rgba property allows you to specify a color, just like you would with an RGB value, but adds a fourth value to indicate opacity. This value is known as an alpha value and is a number between 0.0 and 1.0 (so a value of 0.5 is 50% opacity and 0.15 is 15% opacity). The rgba value will only affect the element on which it is applied (not child elements).
`p.one {`

`background-color: rgb(0,0,0);`

`opacity: 0.5;}`

`p.two {`

`background-color: rgb(0,0,0);`

`background-color: rgba(0,0,0,0.5);}`

## Result:  

# HSL Colors
CSS3 introduces an entirely new and intuitive way to specify colors using hue, saturation, and lightness values.
•	hue
Hue is the colloquial idea of color. In HSL colors, hue is often represented as a color circle where the angle represents the color, although it may also be shown as a slider with values from 0 to 360.
 
• saturation
Saturation is the amount of gray in a color. Saturation is represented as a percentage. 100% is full saturation and 0% is a shade of gray
 
# lightness
Lightness is the amount of white (lightness) or black (darkness) in a color. Lightness is represented as a percentage. 0% lightness is black, 100% lightness is white, and 50% lightness is normal. Lightness is sometimes referred to as luminosity.
 
# Summury
• Color not only brings your site to life, but also helps convey the mood and evokes reactions.

• There are three ways to specify colors imn CSS : RGB values, hex codes, and color names.
• Color picker can help you to find the color you want.

• It is important to ensure that there is enough contrast between any text and the backgroung color.

• CSS3 has in troduced an extra value for RGB colors to indicate opacity. its is known as RGBA.

• CSS3 also allows you to specify colors aas HSL values, with and optional opacity value. it is knon as HSLA.

# Text
* There are properties to control the choice of font, size, weight, style, and spacing.

* There is a limited choice of fonts that you can assume most people will have installed.

* If you want to use a wider range of typefaces there are several options, but you need to have the right license to use them.

* You can control the space between lines of text, individual letters, and words. Text can also be aligned to the left, right, center, or justified. It can also be indented.

* You can use pseudo-classes to change the style of an element when a user hovers over or clicks on text, or when they have visited a link.