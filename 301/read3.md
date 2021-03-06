# Passing Functions as Props

## React Docs - lists and keys

**What does .map() return?**

A new different array

**If I want to loop through an array and display each value in JSX, how do I do that in React?**

**Each list item needs a unique \_\_\_\_.**

**What is the purpose of a key?**

Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity

[References](https://reactjs.org/docs/lists-and-keys.html)

---

## The Spread Operator

**What is the spread operator?**

In JavaScript, spread syntax refers to the use of an ellipsis of three dots (âĶ) to expand an iterable object into the list of arguments.

**List 4 things that the spread operator can do.**

- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments
- Adding an item to a list
- Adding to state in React
- Combining objects
- Converting NodeList to an array

**Give an example of using the spread operator to combine two arrays.**

`[...["ððððĪŠð"]] // Array [ "ððððĪŠð" ]`
`[..."ððððððĨ°ððĪĐ!"] // Array(9) [ "ð", "ð", "ð", "ð", "ð", "ðĨ°", "ð", "ðĪĐ", "!" ]`

`const hello = {hello: "ððððĪŠð"}`
`const world = {world: "ððððððĨ°ððĪĐ!"}`

`const helloWorld = {...hello,...world}`
`console.log(helloWorld) // Object { hello: "ððððĪŠð", world: "ððððððĨ°ððĪĐ!" }`

**Give an example of using the spread operator to add a new item to an array.**

`const fruits = ['ð','ð','ð','ð','ð']`
`const moreFruits = [...fruits];`
`console.log(moreFruits) // Array(5) [ "ð", "ð", "ð", "ð", "ð" ]`
`fruits[0] = 'ð'`
`console.log(...[...fruits,'...',...moreFruits]) //  ð ð ð ð ð ... ð ð ð ð ð`

**Give an example of using the spread operator to combine two objects into one.**

`const myArray = [`ðĪŠ`,`ðŧ`,`ð`]`
`const yourArray = [`ð`,`ðĪ`,`ðĪĐ`]`
`const ourArray = [...myArray,...yourArray]`
`console.log(...ourArray) // ðĪŠ ðŧ ð ð ðĪ ðĪĐ`

[References](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

---

## How to Pass Functions Between Components

**In the video, what is the first step that the developer does to pass functions between components?**

**In your own words, what does the increment function do?**

**How can you pass a method from a parent component into a child component?**

**How does the child component invoke a method that was passed to it from a parent component?**

[References](https://www.youtube.com/watch?v=c05OL7XbwXU)

---

## Things I want to know more about
