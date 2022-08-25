# Understanding Forms and JS Events

## HTML Forms 

1. Why are forms so important in web development?
  They are important to collect data from users. It helps allow users to interact with the website much easier by navigating and taking the user to where they need to go. 
2. When designing a form, what are some key things to keep in mind when it comes to user experience?
  Simplicity is key. You shouldn't have a rather complex or large form to fill, just keep it to the main things and leave it at that. A few text fields and buttons. You want the form to be usuable by anyone with ease. 
3. List 5 form elements and explain their importance.
  `<form>` , `<label>` `<input>` `<textarea>`, and  `<button>` are the 5 form elements. Form is the container for the entire form. Label is a caption for the item in the form. Input gets the input from the user via textfield or button. Textarea is an element that allows for multiline text editing to help gather input like email or long messages for a email form. Button is used to select an item or used to complete the form by submitting the information to the web server. 
  
## Learn JS
   
1. How would you describe events to a non-technical friend?
  Events are like when you phone notifies you of a call or new text message and your action is what happens to code in JavaScript. 
2. When using the addEventListener() method, what 2 arguments will you need to provide?
  The name of the event you want to register this handler for and the code that comprises the handler function we wanna run in response. 
3. Describe the event object. Why is the target within the event object useful?
  An event object is passedd to event handlers for more features and info, typically using `e`, `evt`, or `event`.
4. What is the difference between event bubbling and event capturing?
  Event bubbling checks to see if direct parent of the clicked element  has a click event handler for bubbling phase and runs if so. Moves to next immediate ancestor element until end of HTML. Eventing capturing checks if the outer-most ancestor has clcik event for capturing and runs. then moves on to the next element inside HTML until it reaches the direct part of element that was clicked. So opposites. One checks the parent first while the other checks the entire HTML doc. 

## Things I want to know more about 
I would like to know more about event objects and how they are used. 
## Resources 
-[HTML Forms]()
-[Learn JS](https://developer.mozilla.org/en-US/docs/Learn/JavaScript)
-[First Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/Your_first_form)
-[Structure Web Form](https://developer.mozilla.org/en-US/docs/Learn/Forms/How_to_structure_a_web_form)
-[Intro to Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)
