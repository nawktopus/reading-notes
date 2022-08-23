# Object-Oriented Programming HTML Tables

## Domain Modeling
 
1. Explain why we need domain modeling.
  Domain Modeling is good to conceptualize an idea when used with `prototype`. We're able to create a model for a a problem and verify if it's worth tracking or collecting data from. It's proof of concept without the harm and risk of doing so.  

## HTML Table Basics 

1. Why should tables not be used for page layouts?
    The layout for the table reduces accessibility for those visually impaired, produces harder to read and maintain code and not as responsive compared to their proper counterparts. 
2.List and describe 3 different semantic HTML elements used in an HTML `<table>`.
  `<thead>`, `<tfoot>`, and `<tbody>` are 3 semantic HTML elements used in an HTML table. `<thead>` wraps the part of the table that is the header, the coloumn headings. `<tfoot>` needs to wrap part of the table that is foodter, final rows. `<tbody>` wraps other parts of the tabel of contents that aren't neither header or footer.
  
## Introducing Constructors

1. What is a constructor and what are some advantages to using it?
    A constructor is function called with the new keyword, creates a new object and bind this to the new object so you can refer to this in constructor code and run the code and return the new object. 
2. How does the term `this` differ when used in an object literal versus when used in a constructor?
  `this` in object literal, this is bound to the object when called. `this` in constructor will reference the object that will be created when the constructor is finished.
## Object Prototypes Using a Constructor 

1.Explain prototypes and inheritance via an analogy from your previous work experience. *(Common Front End Developer Int Question)*
  It's like making a having a temporary file of an existing excel spreadsheet. There is the original copy that you work on and can save but the temporary is the one that is a copy that isn't saved yet.  
## Things I want to know more about
I want to know more about constructors and how they relate to objects. 

## Resources
-[Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)
-[HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)
-[Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)
-[Object Prototypes](https://ui.dev/beginners-guide-to-javascript-prototype)
