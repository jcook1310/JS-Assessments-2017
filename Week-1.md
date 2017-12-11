### Javascript Course Assessment

## Week 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. Name some of the data types in Javascript.

 //Your Answer: variables, strings and functions
  
 //Googled Answer: number, string, objects. Things that can be defined using variables.
  

#### 2. Describe what "if" does in Javascript.

  //Your Answer: "if" is a function that tells the function to do something if the parameters are met.
  
  
  //Googled Answer: The if/else statement executes a block of code if a specified condition is true. If the condition is false, another block of code can be executed. 


#### 3. Write a function that takes one number as a parameter and decides if that number is divisble by three or not. If it is, print the number and "is divisible by three". If it is not, print that the number "is not divisble by three".
function number(n){
if((n%3) === 0){
  return n + " is divisible by three"
  }
  else{
  return "is not divisble by three"
  }
  }


#### 4. What is JSON?

  //Your Answer: javascript object notation
  
  
  //Googled Answer: JSON: JavaScript Object Notation.

#### 5. Write about yourself in an object, giving at least three properties of you. Then store your object in a variable with your name.

var Jordan = {age: 24, previousJob: "bartender", hobbies: "soccer, video games, and hiking}

#### 6. What is a closure?

  //Your Answer: closure allows you to use a local scope outside of the function
  
  
  //Googled Answer: A closure is an inner function that has access to the outer (enclosing) function's variables—scope chain. The closure has three scope chains: it has access to its own scope (variables defined between its curly brackets), it has access to the outer function's variables, and it has access to the global variables.

#### 7. What's the difference between =, ==, and === in JavaScript?

  //Your Answer: "=" this assigns a value. ex var number = "string". "==" this means equal to but with a few exceptions. "===" this is an exact match.
  
  
  //Googled Answer: Abstract Equality Comparison (==)
Strict Equality Comparison (===)
  
  
#### 8. Create an array with at least 4 items inside it, then access two of the values and console.log() them. Try to access the two values in two different ways.

var sodas = ["Coke", "Pepsi", "Dr. Pepper", "Sprite", "Root Beer"]
console.log(sodas[3])
for (i = 0; i < sodas.length; i++) { 
   sodas[i];
}


#### 9. Describe the different kinds of loops and why you would use them.

  //Your Answer: a for loop runs a block of code using three conditions. a while loop continues to run a block of code while the conditions are met. 
  
  
  //Googled Answer: for - loops through a block of code a number of times.
for/in - loops through the properties of an object.
while - loops through a block of code while a specified condition is true.
do/while - also loops through a block of code while a specified condition is true
  
#### 10. How would you explain "scope" in javascript?

  //Your Answer: scope is an area of code that stores information. Global scope can be used in the local scope. However local scope can only be used in that function.
  
  
  //Googled Answer: JavaScript has two scopes – global and local. Any variable declared outside of a function belongs to the global scope, and is therefore accessible from anywhere in your code. Each function has its own scope, and any variable declared within that function is only accessible from that function and any nested functions
