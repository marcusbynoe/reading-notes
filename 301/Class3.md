# Readings: Passing Functions as Props

## React Docs - lists and keys [^1]

[^1] Reference: <https://reactjs.org/docs/lists-and-keys.html>

1. **What does .map() return?:** A new array with doubled or more values.

2. **If I want to loop through an array and display each value in JSX, how do I do that in React?:** Using curly braces `{}`.

3. **Each list item needs a unique ____.** Key

4. **What is the purpose of a key?:** Keys help React identify which items have changed, are added, or are removed.

## The Spread Operator [^2]

[^2] Reference: <https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab>

1. **What is the spread operator?:** It takes in an iterable (e.g an array) and expands it into individual elements.

2. **List 4 things that the spread operator can do.:** Copying an array, Concatenating or combining arrays, Using Math functions, Adding to state in React.

3. **Give an example of using the spread operator to combine two arrays.:**  

```
const marvel = ['Iron Man', 'Captain America'];
const dc = ['Batman', 'Superman'];

const all = [...marvel, ...dc];

all; // ['Iron Man', 'Captain America', 'Batman', 'Superman'];
```

4. **Give an example of using the spread operator to add a new item to an array.:**

```
const fewFruit = ['🍏','🍊','🍌']
const fewMoreFruit = ['🍉', '🍍', ...fewFruit]
console.log(fewMoreFruit) //  Array(5) [ "🍉", "🍍", "🍏", "🍊", "🍌" ]
```

5. **Give an example of using the spread operator to combine two objects into one.:**

```
const objectOne = {hello: "🤪"}
const objectTwo = {world: "🐻"}
const objectThree = {...objectOne, ...objectTwo, laugh: "😂"}
console.log(objectThree) // Object { hello: "🤪", world: "🐻", laugh: "😂" }
const objectFour = {...objectOne, ...objectTwo, laugh: () => {console.log("😂".repeat(5))}}
objectFour.laugh() // 😂😂😂😂😂
```

## How to Pass Functions Between Components

1. **In the video, what is the first step that the developer does to pass functions between components?:** Pass in an object.

2. **In your own words, what does the `increment` function do?:** it adds to the quantity by 1 and returns the vaule.

3. **How can you pass a method from a parent component into a child component?:** By passing the method as a prop into the child component.

4. **How does the child component invoke a method that was passed to it from a parent component?:**


## Things I want to know more about

- N/A

