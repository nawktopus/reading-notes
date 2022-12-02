# Passing Functions as Props

## Lists and Keys

1. What does .map() return?
  A new array when it has values passed through it.
2. If I want to loop through an array and display each value in JSX, how do I do that in React?
  We use .map() and pass in the value and use {} to display them as follows `<li> {number} </li>`
3. Each list item needs a unique ____.
  Key.
4. What is the purpose of a key?
  Keys help by identifying which items have changed, been added or removed.
  
## Spread Operator 

1. What is the spread operator?
    Represented by `...`, it expands an iterable object into the list of arguments. 
2. List 4 things that the spread operator can do.
    It can Copy an arry, concatenate or combine arrays, use Math functions, and use an array as an argument. 
3. Give an example of using the spread operator to combine two arrays.
    You can combine two arrays, lets say first and last name arrays. 
4. Give an example of using the spread operator to add a new item to an array.
    When you need to add items to an existing array, like two more names or ages. 
5. Give an example of using the spread operator to combine two objects into one.
    When you would want to combine both methods and properties together. 
    
## How to Pass Functions Between Components

1.In the video, what is the first step that the developer does to pass functions between components?
  They create a function with the app component that will pass in the object
2. In your own words, what does the `increment` function do?
    `increment` grabs the people object and matches the name that is passed in using a loop and increasing the count number. when the button is clicked. 
3. How can you pass a method from a parent component into a child component?
    You can pass a method as a prop using the arrow functions. 
4. How does the child component invoke a method that was passed to it from a parent component?
  Passing the prop value back to the parent utilising `.this.prop`.
## Things I want to know more about

## Resources
[Lists and Keys](https://reactjs.org/docs/lists-and-keys.html)
[Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)
[Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)
