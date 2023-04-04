# Class 3 Notes

## Passing Functions as Prop

![](./imgs/functionsprops.png) 

### [React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

1. What does .map() return?

    - The .map() method returns a new array containing the results of calling a provided function on every element in the original array

1. If I want to loop through an array and display each value in JSX, how do I do that in React?

    - You can use the .map() method to loop through an array and render each value in JSX

1. Each list item needs a unique key.

1. What is the purpose of a key?

    - The purpose of a key in React is to help React identify which items have changed, been added, or been removed from a list.

### [The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

1. What is the spread operator?

    - The spread operator is a JavaScript syntax that allows an iterable (like an array or a string) to be expanded into individual elements or properties. It is denoted by the `...` symbol

1. List 4 things that the spread operator can do.

    - Expand elements of an array or string, Merge two or more arrays or objects, Pass arguments as individual elements, Clone an array or object.

1. Give an example of using the spread operator to combine two arrays.

    - ``
        const arr1 = [1, 2, 3];
        const arr2 = [4, 5, 6];
        const arr3 = [...arr1, ...arr2];
        console.log(arr3); // Output: [1, 2, 3, 4, 5, 6]
    ``

1. Give an example of using the spread operator to add a new item to an array.

    - ``
        const arr1 = [1, 2, 3];
        const newItem = 4;
        const arr2 = [...arr1, newItem];
        console.log(arr2); // Output: [1, 2, 3, 4]
    ``


1. Give an example of using the spread operator to combine two objects into one.

    - ``
        const obj1 = { a: 1, b: 2 };
        const obj2 = { c: 3, d: 4 };
        const obj3 = { ...obj1, ...obj2 };
        console.log(obj3); // Output: { a: 1, b: 2, c: 3, d: 4 }
    ``

### [How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

1. In the video, what is the first step that the developer does to pass functions between components?

    - Pass functions between components is to define the function in the parent component and then pass it as a prop to the child component

1. In your own words, what does the `increment` function do?

    - The increment function is used to update a counter value, and it's sent from one component to another component in a React application.

1. How can you pass a method from a parent component into a child component?

    - To pass a method from a parent component into a child component, you can define the method in the parent component and then pass it as a prop to the child component

1. How does the child component invoke a method that was passed to it from a parent component?

    - To invoke a method that was passed to it from a parent component, the child component can simply call the method by using the prop name.

---

Bookmark and Review

1. [React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)

1. [React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)