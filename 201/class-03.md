# Understanding HTML Lists, Control Flow in JavaScript and the CSS Box Model. 

**Learn HTML**

1. When should you use an **unordered list** in your HTML document?
  Usually you should use an unordered list when you don't need numerical ordering. You can use a bullet point and list things without any specific order.
2. How do you change the **bullet style** of unordered list items?
  You can use the `list-style-type` to change it to circle, square, even an emoji like a rocket or UFO. 
3. When should you use an **ordered list** vs an **unorder list** in your HTML document?
  It is all dependent on the meaning of the order. If it is an instruction for baking, we would like the order to be sequential but if there is no meaning to the order we can utilize an unordered list. 
4. Describe two ways you can change the numbers on **list items** provided by an **ordered list**?
  You can list the type `<ol type="i">`, which will list the ordered items using roman numerals. You can also list using the alphabet with `...type="a"`. Capitalizing the `a` or `i` will capitalize the roman numerals or alphabet letter.

**Learn CSS**

1. Describe the CSS properties of **margin** and **padding** as characters in a story. What is their role in a story titled: “The Box Model”?
  Margin and Padding are siblings apart of the crazy travelling circus called `The Box Model`. Their act along with Border and Content is to be the crazy nesting box model. Margin holds Border, Padding and Content tightly and covers them. Border holds Padding and Content tightly and covers them. Padding holds Content tightly and covers it. When they all release, they all are displayed showing each individual behind each other being the box model. 
2. List and describe the four parts of an HTML elements box as referred to by the `box model`.
  The four parts of the HTML elements box are Content box, Padding Box, Border Box, and the Margin Box.

**Learn JS**

1. What data types can you store inside of an Array?
  We can store numbers, strings, objects and even arrays within an array.
2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
 `const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];`
  I believe this is a valid JavaScript. I know null can be a value as well as the `fishing:hiking:rock_climbing`, you should be able to access it by people[[0]] for the value of `pete`.
3. List five shorthand operators for assignment in javascript and describe what they do.
  Five shorthand operators are Assignment `=`, Addition Assignment `+=`, Subtraction Assignment `-=`, Multiplication Assignment `*=`, and Division Assignment `/=`.
4. Read the code below and evaluate the last expression and explain what the result would be and why.
 `let a = 10;
 let b = 'dog';
 let c = false;
 // evaluate this
 (a + c) + b;`
  It should equate to `10dog`. For Booleans, true = 1 and false = 0, so adding 0 + 10 should be 10 and adding number and strings is going to be number-string or string-number depending on which side the number and string are. 

5. Describe a real world example of when a conditional statement should be used in a JavaScript program.
  A conditional statement would be work in the situation if you needed to get to school but your bike was flat. Your thought process would be if bike is flat, else if take the bus, but if late for bus, else ask your parents as a last resort.
6. Give an example of when a Loop is useful in JavaScript.
  A loop is useful when combining it with a condition. It allows for certain automation to happen. Eases work load and can be more precise than writing hundreds lines of code.
  
## Things I want to know more about
I would like to know more about arrays and if my answer is correct about the `null` and `fishing:hiking:rock_climbing'` portion. I'm not too sure if arrays can contain variables such as `null`


## Resources
- [Learn HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [Learn CSS](https://developer.mozilla.org/en-US/docs/Learn/CSS)
- [Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
- [Arrays](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/Arrays)
- [Expressions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Expressions_and_Operators)
- [Conditionals](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)
- [Loops](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Looping_code)
