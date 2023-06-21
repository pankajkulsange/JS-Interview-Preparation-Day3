# What are promises and why do we need it?

- promise are use to handle async operations in JS
- easy to handle callback hell
- also use to handle the errors

1. Pending
2. Resolve (then method)
3. Reject (catch method)

- initial stage of any promise is always pending

# Q. We have three promise, and we want to combine all then catch method by using promise.all

# Q. promise chaining?

- technique to chain mulitple asynchronous operation in a specific order by chaining together using promise

# Q. DOM - document object model

- mechanism by which we can change the document structure
- structure html document elements on the web
- we can use document object and it's method for change the
  document structure such as toggle the button and etc
- getElementById
- getElementsByClassName
- getElementsByTagName
- querySelector
- querySelectorAll
- addEventListener(event, callbackfunction)

# Q. Closure

- combination of two or more nested functions
- where the inner function access the variable for the parent function
- in it's lexical environment called closure

# Q. How many operators in JS

1. Arithmatic
   +, -, \*, \*\*, /, %, ++, --
2. Assingment
   =, +=, -=, \*=, /=, %=
3. Bitwise
   bitwise or | , bitwise and &, bitwise not ~, left shift <<, right shift >>
4. Comparision
   ==, ===, <=, >=, !=, !==
5. Logical operator
   &&, ||, !
6. Ternary
   (condition) : true block code ? false block code;
7. typeof - return datatype

# Q. Object

- non primitive datatype that stores key value pairs seperated by colon
- key also called Property

// method 2 - using new keyword
let obj = new Object();
obj.age = 23;
obj['name'] = 'Jane'
