# Understanding Problem Domain, Objects and DOM (Document Object Model)

## JavaScript Object Basics 

1. How would you describe an object to a non-technical friend you grew up with?
    An object is like is a book. It contains paragraphs, which would be the variable and chapters, being the function, which can refer back to previous sections and chapters. You can gather information from each paragraph and utilize them in other chapters. 
2. What are some advantages to creating object literals?
  It is more efficient to use one line of code to send an object in one full swoop than to send multiple things individually.
3. How do objects differ from arrays?
    It is easier to work with than arrays using the dot notation than brackets.
4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
    You can't use dot notation when accessing values defined at runtime but you can use bracket notations. For excample `name: ['Bob', 'Smith'], -> console.log(person[input])`
5. Evaluate the code below. What does the term `this` refer to and what is the advantage to using this?
    `this` references to an object with global, function or eval values. The advantage is that you can have the same variable names in different objects but use the same `.this` call helping simplfy the code. `.this` pulls the value of name and age. 
    
`const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}`

## Intro to the DOM

1. What is the DOM?
  The DOM is the document object model, which is the data representation of the objects with in a structure and content of a document on the web. It represents the page so that programs can change the document structure, style and content. 
2. Briefly describe the relationship between the DOM and JavaScript.
  The DOM and JavaScript relate with the DOM is separate, a web API while JavaScript is a scripting language. You wouldn't be able to utilize JavaScript without the DOM. 
## Thing I want to know more about 

More about how .this differs from a variable. seems to function similar but not really. Also how the DOM is used.

## Resources 
- [Javascript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)
- [Introduction to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)
