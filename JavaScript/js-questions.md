JavaScript Interview Questions
---------------------------------------------------
Q1. What is data type in js?
-------------------------------------------------------
Q2:What is closure in javascript?
-----------------------------------------------------------------------------------------
Q3. What is the difference between == and === in JavaScript?
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