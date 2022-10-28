# In memory storage

## Understanding the JavaScript Call Stack
  
1. What is a ‘call’?
    
A call is the function invocation. 
    
2. How many ‘calls’ can happen at once?
    
A single call.
    
3. What does LIFO mean?
    
LIFO is last in, first out. The last function gets pushed into the stack is the first to be popped out when the function returns. 
    
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
    
`function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();`
    
5. What causes a Stack Overflow?

This occurs when there is a recursive function, one that calls itself without an exit point.

## JavaScript error messages

1. What is a ‘reference error’?
    
A reference error is when you try to use a variable that is not declared.
    
2. What is a ‘syntax error’?
    
A syntax error is when you try to parse an invalid object using JSON.parse. 
    
3. What is a ‘range error’?
    
A range error is when you try to manipulate an object with an invalid length. 
    
4. What is a ‘type error’?
    
A type error is when trying to use or access in incompatiable. 
    
5. What is a breakpoint?
    
A break point is an intentional line of code to stop or pause for debugging purposes.
    
6. What does the word ‘debugger’ do in your code?

Adding `debugger` intentionally breaks code to evaluate it. 

## Things I want to know more about

## Resources
[Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)
[Error Messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)
