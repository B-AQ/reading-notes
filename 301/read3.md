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

In JavaScript, spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.

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

`[...["😋😛😜🤪😝"]] // Array [ "😋😛😜🤪😝" ]`
`[..."🙂🙃😉😊😇🥰😍🤩!"] // Array(9) [ "🙂", "🙃", "😉", "😊", "😇", "🥰", "😍", "🤩", "!" ]`

`const hello = {hello: "😋😛😜🤪😝"}`
`const world = {world: "🙂🙃😉😊😇🥰😍🤩!"}`

`const helloWorld = {...hello,...world}`
`console.log(helloWorld) // Object { hello: "😋😛😜🤪😝", world: "🙂🙃😉😊😇🥰😍🤩!" }`

**Give an example of using the spread operator to add a new item to an array.**

`const fruits = ['🍏','🍊','🍌','🍉','🍍']`
`const moreFruits = [...fruits];`
`console.log(moreFruits) // Array(5) [ "🍏", "🍊", "🍌", "🍉", "🍍" ]`
`fruits[0] = '🍑'`
`console.log(...[...fruits,'...',...moreFruits]) //  🍑 🍊 🍌 🍉 🍍 ... 🍏 🍊 🍌 🍉 🍍`

**Give an example of using the spread operator to combine two objects into one.**

`const myArray = [`🤪`,`🐻`,`🎌`]`
`const yourArray = [`🙂`,`🤗`,`🤩`]`
`const ourArray = [...myArray,...yourArray]`
`console.log(...ourArray) // 🤪 🐻 🎌 🙂 🤗 🤩`

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
