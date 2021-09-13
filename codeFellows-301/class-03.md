# Passing Functions as Props

From [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

## **What does .map() return do ?**

The `map()` method creates a new array populated with the results of calling a provided function on every element in the calling array.

## **If I want to loop through an array and display each value in JSX, how do I do that in React ?**

In React, transforming arrays into lists of elements is nearly identical with regular javascript as we can see here : 

### In Javascript

`const numbers = [1, 2, 3, 4, 5];`

`const doubled = numbers.map((number) => number * 2);`

`console.log(doubled);`

.............................................................

### In JSX

`const numbers = [1, 2, 3, 4, 5];`

`const listItems = numbers.map((number) =>`

 `<li>{number} </li> );`

## Each list item needs a unique **`key`**.


## **What is the purpose of a key?**

Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.


From [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)


## **What is the spread operator?**
Spread operator allows an iterable to expand in places where 0+ arguments are expected. It is mostly used in the variable array where there is more than 1 values are expected. It allows us the privilege to obtain a list of parameters from an array. 

## **List 4 things that the spread operator can do.**

1. **Copy an array**
```
let arr = [1, 2, 3];
let arr2 = [...arr]; // like arr.slice()

arr2.push(4);
//  arr2 becomes [1, 2, 3, 4]
//  arr remains unaffected
````

2. **Concatenate arrays**

```
let arr1 = [0, 1, 2];
let arr2 = [3, 4, 5];

arr1 = [...arr1, ...arr2];
//  arr1 is now [0, 1, 2, 3, 4, 5]
```
3. **Add a new item to an array**
```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
```

4. **Combine two objects into one**

```
 let a = {
    a: 1,
    b: true
}
let b = {
	y: 093,
	z: 'This is an object'
}
const c = {...a, ...b}

```
