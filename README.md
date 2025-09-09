##1. What is the difference between var, let, and const?
   Answer:Var is only function scope . Declaring var outside the function it turns into global variable.Var hoisted and set it value as undefined.
   let is modern way which can be reassigned but not redeclared.
   const is a block-scoped which cannot be redeclared or reassigned (constant).
   
## 2. What is the difference between `map()`, `forEach()`, and `filter()`?
Answer:**forEach()** → It creates  over array elements, executing a specified function once for each element. Does not return a new array.  
- **map()** → Creates a new array by applying a function to each element of the original array. Returns a transformed array.  
- **filter()** → Creates a new array containing only the elements for which the function returns "true".
  
 ## 3. What are arrow functions in ES6?
 Answer:ES6 Arrow functions enable us to write functions with simpler and shorter syntax and make our code more readable and organised. The arrow functions are introduced in the ES6 version.

## 4. How does destructuring assignment work in ES6?
Answer:Array destructuring allows us to extract values from an array and assign them to variables without needing to use the array’s index.
For example:
// Array destructuring
const numbers = [10, 20, 30];
const [a, b, c] = numbers;
console.log(a); // 10
console.log(b); // 20
console.log(c); // 30

// Object destructuring
const person = { name: "Alice", age: 25 };
const { name, age } = person;
console.log(name); // Alice
console.log(age);  // 25

## 5.Explain template literals in ES6. How are they different from string concatenation?
Answer:Template literals are a new feature that was introduced in ECMAScript6,
this offers a simple method for performing string interpolation and multiline string creation and,
The template literals were called template strings before the introduction of ES6.
For example:
const name = "Alice";
const age = 25;

// Traditional concatenation
console.log("My name is " + name + " and I am " + age + " years old.");

// Template literal
console.log(My name is ${name} and I am ${age} years old.);


// Multi-line template literal
const multiLine = ``
This is a string
that spans multiple lines
using template literals.
`;
console.log(multiLine);

