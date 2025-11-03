
// 1. What is JavaScript?
console.log("JavaScript makes web pages interactive!");

// 2. Data types
let name = "Sahil";      // string
let age = 22;            // number
let isStudent = true;    // boolean
let score;               // undefined
let x = null;            // null

console.log(typeof name, typeof age, typeof score);

// 3. var, let, const
var a = 10;
let b = 20;
const c = 30;

// 4. NaN example
console.log(0 / 0); // NaN

// 5. == vs ===
console.log(5 == "5");  // true
console.log(5 === "5"); // false

// 6. undefined vs null
let u;
let n = null;
console.log(u, n);

// 7. typeof
console.log(typeof "hello"); // string

// 8. Function
function add(x, y) {
  return x + y;
}
console.log(add(5, 3));

// 9. Arrow function
const multiply = (a, b) => a * b;
console.log(multiply(4, 2));

// 10. Hoisting
console.log(hoistedVar); // undefined (hoisted)
var hoistedVar = "Hello!";
