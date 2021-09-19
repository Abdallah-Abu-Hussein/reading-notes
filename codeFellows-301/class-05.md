#  Putting it all together

## **What is the single responsibility principle and how does it apply to components?**

The single-responsibility principle (SRP) is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part.

## **What does it mean to build a ‘static’ version of your application?**

 Static applications and websites render in the user's browser without the need for server side processing, this means that all the rendering of HTML, CSS, and JavaScript is done on the client side, rather then relying on server side technologies.

## **Once you have a static application, what do you need to add?**

Once we have a static application we need to start adding interactivity, but first we need to identify the minimal set of mutable state that the app needs.

## **What are the three questions you can ask to determine if something is state? source (Links to an external site.)**

* Is it passed in from a parent via props? If so, it probably isn’t state.

* Does it remain unchanged over time? If so, it probably isn’t state.

* Can you compute it based on any other state or props in your component? If so, it isn’t state.

## **How can you identify where state needs to live?**

In order to determine where the state needs to live, we need to:

* Identify every component that renders something based on that state.

* Find a common owner component (a single component above all the components that need the state in the hierarchy).

* Either the common owner or another component higher up in the hierarchy should own the state.

* If you can’t find a component where it makes sense to own the state, create a new component solely for holding the state and add it somewhere in the hierarchy above the common owner component.

## **What is a “higher-order function”?**

In mathematics and computer science, a higher-order function is a function that does at least one of the following: takes one or more functions as arguments, returns a function as its result. All other functions are first-order functions. In mathematics higher-order functions are also termed operators or functionals.

## **Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?**

greaterThan function create a new function to check if the value grater than the input one.

line 2 creates a new function that check the current value and the input one.

## **Explain how either map or reduce operates, with regards to higher-order functions.**


It creates a value by mixing a single member from the array with the current value over and over again. When summing numbers, start with zero and add each element to the total. Aside from the array, the arguments to reduce are a combining function and a start value. This function is a little more complicated than filtering and mapping.