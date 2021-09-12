# js Debugging

![](https://firebearstudio.com/blog/wp-content/uploads/2015/10/Node.JS-Debugging-Tools.png)

## **Code Debugging**

Programming code might contain syntax errors, or logical errors.
Many of these errors are difficult to diagnose.
Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get no indications where to search for errors.
Searching for (and fixing) errors in programming code is called code debugging.


## **JavaScript Debuggers**

Debugging is not easy. But fortunately, all modern browsers have a built-in JavaScript debugger.
Built-in debuggers can be turned on and off, forcing errors to be reported to the user.
With a debugger, you can also set breakpoints (places where code execution can be stopped), and examine variables while the code is executing.
Normally, otherwise follow the steps at the bottom of this page, you activate debugging in your browser with the F12 key, and select "Console" in the debugger menu.

##  The console.log() Method

If your browser supports debugging, you can use console.log() to display JavaScript values in the debugger window:

### Example

`<!DOCTYPE html>`

`<html>`

`<body>`

`<h1>My First Web Page</h1>`

`<script>`

`a = 5;`

`b = 6;`

`c = a + b;`

`console.log(c);`

`</script>`

`</body>`

`</html>`

## **Setting Breakpoints**

In the debugger window, you can set breakpoints in the JavaScript code.

At each breakpoint, JavaScript will stop executing, and let you examine JavaScript values.

After examining values, you can resume the execution of code (typically with a play button).


## **Summary** 

* If you understand execution contexts (which have two stages) and stacks, you are more likely to find the error in your code.

* Debugging is the process of finding errors. It involves a process of deduction.

* The console helps narrow down the area in which the error is located, so you can try to find the exact error.

* JavaScript has 7 different types of errors. Each createsits own error object, which can tell you its line number and gives a description of the error.

* If you know that you may get an error, you can handleit gracefully using the try, catch, finally statements. Use them to give your users helpful feedback.
