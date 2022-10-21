# Putting it all together 

## Thinking in React

1. What is the `single responsibility principle` and how does it apply to components?
    A component should ideally only do one thing. 
2. What does it mean to build a ‘static’ version of your application?
    To build a website that has no state. No interactivity. 
3. Once you have a static application, what do you need to add?
    Add inverse data flow.
4. What are the three questions you can ask to determine if something is state?
  Is it passed in from a parent via props? Does it remain unchanged over time? Can you compute it based on any other state or props in your component?
5. How can you identify where state needs to live?
  Identify each component and check the hierarchy and where state should live. 
## Higher-Order Functions

1. What is a “higher-order function”?
  Functions that operate on other functions by either taking them as arguments or returning them. 
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
  If m is greater than n, we return m. 
3. Explain how either map or reduce operates, with regards to higher-order functions.
  Map applies a function to all of the elements and builds a new array with those returned values. Reduce builds a value by repeatedly taking a single element from the array and combines it with the current value.
  
## Things I want to know more about 

## Resources 
[Thinking](https://reactjs.org/docs/thinking-in-react.html)
[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)
