### Creating an interactive resume
- Why there is undefined after console.log in chrome dev tools?
    - It means there is nothing to return. If you type document.URL, it returns file url so there is no undefined.

Jquery append is useful to add contents to an element. Better because it adds content to the end if there is already some.

#### JS Dataypes
- no difference between integers and floating point variables as all are saved as 64 bit floating point.

**string.replace()**
- it is idempotent, it does not change parent string
- var awesomeThoughts = "Venkat is awesome";
- var funThoughts = awesomeThoughts.replace("awesome", "fun");

Checkout string.toUpperCase(), string.slice()

Javascript Falsy values
- false, 0, "", undefined, null, NAN
- undefined means variable does not exist
- null means variable does not have any value.

Javascript Arrays
- ["Euler", 3.14159, {name: "James", job: "Course Developer"}, myFunc]
- Array can have different javscript data types.
- use array.push, array.pop, array.slice for retrieving content from arrays.
- newArray = oldArray.slice(0); just makes a copy

Javascript Objects
- They can hold information and do things.
- There are no classes in javascript. Though they can be mimicked.
- Object literal, `var myObj = {};`
- Objects can be used with dot and string notation.

JSON
- Internet GET and POST requests are in JSON.
- Always lint JSON. eg. use jsonlint.comm
javaScript Object Literals rather than JSON to define your objects. The syntax is very similar, but javaScript Object Literals permit the inclusion of functions as properties and JSON does not.  

Checkout Bracket vs Dot notation vs object Literals in firefox

#### Flow Control

**If Statement**
