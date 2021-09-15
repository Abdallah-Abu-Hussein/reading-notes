# Forms

## What is a ‘Controlled Component ?

A controlled component is a component that renders form elements and controls them by keeping the form data in the component's state. In a controlled component, the form element's data is handled by the React component (not DOM) and kept in the component's state

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

when we  we update the state with their responses as soon as they enter them, where React is in charge of preserving and setting its state, both of them will function. The state is kept in sync with the value of the input, which means that changing the input changes the state, and changing the state changes the input.

## How do we target what the user is entering if we have an event handler on an input field?

We can target the user input by using the value attribute for the form or the input field.

## Why would we use a ternary operator?

If the condition evaluates to true, the ternary operator allows you to assign one value to a variable, and another value if the condition is false. Because the ternary operand is on a single line rather than an if block, it is simple to observe the assignment of a value to a variable.

## Rewrite the following statement using a ternary statement:

```
if(x===y){

console.log(true);

} else {

console.log(false);

}
```


```
x===y ? console.log(true) : console.log(false)
```