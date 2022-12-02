# React and Forms

## Forms

1. What is a ‘Controlled Component’?
  An input form element whose value is controlled by React.
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
  Should update as soon as they enter them because it's easier to pass to other UI elementes or reset. We can use the information much quicker. 
3. How do we target what the user is entering if we have an event handler on an input field?
  we use `event.target`.
  
## Conditional Ternary Operator

1. Why would we use a ternary operator?
  Helps to write cleaner code; especially one line code.
2. Rewrite the following statement using a ternary statement:

`if(x===y){
  console.log(true);
} else {
  console.log(false);
}`

`x === y ? true : false; `

## Things I want to know more about 

## Resources 
[Forms](https://reactjs.org/docs/forms.html)
[Ternary](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
