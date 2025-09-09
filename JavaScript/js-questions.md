JavaScript Interview Questions
---------------------------------------------------
Q1. What is data type in js?
-------------------------------------------------------
Q2:What is closure in javascript?
-----------------------------------------------------------------------------------------
Q3. What is the difference between == and === in JavaScript?
---------------------------
Ans>  == is the loose equality operator, which compares two values after converting them to a common type (type coercion).
=== is the strict equality operator, which returns true only if both the value and the type are the same.
'5' == 5   // true   (string is converted to number)
'5' === 5  // false  (different types: string vs number)
-----------------------------------------------------------------------------------------
Q4>❓ What are truthy and falsy values in JavaScript? Can you list at least 3 falsy values?
ans. In JavaScript, truthy values are those that are considered true when evaluated in a boolean context, and falsy values are those that are considered false.
✅ Falsy Values (Only 7):
These values evaluate to false in conditional checks:
false
0
'' (empty string)
null
undefined
NaN
document.all (legacy, rarely used)
✅ Everything else is considered truthy, such as:
1, -1
"hello" (any non-empty string)
{} (empty object)
[] (empty array)
------------------------------------------------------------------
5> var, let and const 
-----------------------------------------------------------
var → Function-scoped, hoisted with undefined, can be redeclared.
let → Block-scoped, hoisted but in TDZ, can be reassigned.
const → Block-scoped, hoisted but in TDZ, cannot be reassigned (but objects/arrays are mutable).
-------------------------------------------------------------------
6> temporal dead zone
-------------------------------------------------
The Temporal Dead Zone is the phase between a block's entry and the variable's declaration where let and const exist in memory but are not accessible, causing a ReferenceError if accessed before declaration.
---------------------------------------------------------------------
7> Hoisting
------------------------------------------------------------------
Hoisting is JavaScript’s behavior of moving declarations (not initializations) to the top of their scope before code execution, meaning variables and functions can be used before their actual declaration lines, but let/const remain in a Temporal Dead Zone until initialized.
-------------------------------------------------------------------------
8> JavaScript Variable Naming Rules
-------------------------------------------------------------------------
Start with a letter, _, or $.
No spaces or hyphens.
Case-sensitive.
Cannot use JavaScript reserved keywords.
Follow camelCase for readability.
----------------------------------------------------------------------
9>What is Variable Scope?
------------------------------------------------------------------------
Scope determines where a variable can be accessed in your code.
In JavaScript, there are three main types of scope:
1. Global Scope
Variables declared outside of any function or block are global.
Accessible anywhere in the code.
2. Function Scope (for var)
Variables declared inside a function with var are only accessible within that function.
3. Block Scope (for let and const)
Variables declared with let or const inside a block {} are only accessible inside that block.
4. Module Scope (in ES6 modules)
Variables declared in a module are scoped to that module and not added to the global scope.
-----------------------------------------------------------------------
10>Datatype in js.
------------------------------------------------------------------------
JavaScript has 7 primitive types (Number, BigInt, String, Boolean, Undefined, Null, Symbol) and 1 non-primitive type (Object, which includes arrays, functions, etc.).
------------------------------------------------------------------------
11>null → Intentional empty value (set by developer).

undefined → Variable declared but not assigned (default).

NaN → Invalid numeric result; type is number, but not equal to anything, even itself.
--------------------------------------------------------------------------
12>Operator in js
--------------------------------------------------------------------------
JavaScript has arithmetic, assignment, comparison, logical, bitwise, ternary, type-checking, string, spread/rest, nullish, optional chaining, and other special operators (in, delete, new, etc.) that let you perform calculations, comparisons, and object/property handling.
-------------------------------------------------------------------------
13>prototypal inheritance
--------------------------------------------------------------------------
In JavaScript, every object has an internal link to another object called its prototype.
The prototype is like a “blueprint” from which objects can inherit properties and methods.
All objects in JavaScript ultimately inherit from Object.prototype.
This is the basis of prototypal inheritance.
It’s the foundation of JavaScript’s object model, and class in ES6 is just syntactic sugar for it.
--------------------------------------------------------------------------
14>Built-in obects . 
------------------------------------------------------------------------
Built-in Objects are predefined JavaScript objects like Object, Array, Date, Math, JSON, Promise, and more, which provide essential functionality and are always available in the JS runtime.
Built-in Objects (a.k.a. Native Objects) are objects that JavaScript provides by default.
They are part of the ECMAScript specification and are available in any JS environment (browser, Node.js, etc.).
---------------------------------------------------------------------------

