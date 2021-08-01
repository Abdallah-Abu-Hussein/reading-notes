
# Functions in JavaScript

 ![javascript](https://miro.medium.com/max/3200/1*i8-u-V8LTTbQwTeUwLI_BQ.gif)

## what's a Function ?

We frequently need to conduct a similar action at several locations throughout the script.
For example, whether a visitor checks in, logs out, or goes someplace else, we need to display a nice-looking message.
The program's basic "building blocks" are functions. They make it possible to call the code several times without having to repeat it.

## Defining functions

Function Declaration
To create a function we can use a function declaration.

It looks like this:

`function showMessage()`
`{`

  `alert( 'Hello everyone!' );`

`}`

The function keyword comes first, followed by the function's name, a list of arguments within parentheses (comma-separated, empty in the example above; we'll see examples later), and lastly the function's code, also known as "the function body," enclosed by curly brackets.

`function name(parameter1, parameter2, ... parameterN) {
  ...body...
}`

Our new function can be called by its name: showMessage().

For instance:

`function showMessage() {`
 `alert( 'Hello everyone!' );`
`}`

`showMessage();`

`showMessage();`

The function's code is executed by the call `showMessage()`. We'll see the message twice in this section. This example exemplifies one of the primary goals of functions: to eliminate code duplication.
If we ever need to alter the message or the way it is shown, we just need to update one piece of code: the function that outputs.

## Function expressions

While the function declaration above is syntactically a statement, functions can also be created by a function expression.
Such a function can be anonymous; it does not have to have a name. For example, the function square could have been defined as:

`const square = function(number)`
`{ return number * number }`
`var x = square(4)`

`// x gets the value 16`

To be continued ......
