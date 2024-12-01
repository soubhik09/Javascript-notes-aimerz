# Javascript Notes (Aimerz.ai)
### ⭐ Slides
![Slide-1](/Images/Slide_1.jpg)
---
![Slide-2](/Images/Slide_2.jpg)
---
![Slide-3](/Images/Slide_3.jpg)
---
![Slide-4](/Images/Slide_4.jpg)
---
### To print something :
```javascript
console.log("Hello World!");
```
### To run javascript file:
```
1. Open terminal
2. write: node filename.js ↩️
```
### Output :
```
Hello World!
```
---
![Slide-5](/Images/Slide_5.jpg)
---
```javascript
Storage; CURD: Create, Read, Update, Delete.

Variables --> Storage --> RAM -> 8gb, 16gb -> Named Storage Location

Three ways to create variables in js => var, let, const ==> keywords


var:
--> Global
--> You can reassign the value
--> You can redeclare

let:
--> Block Scope
--> You can reassign the value
--> You can not redeclare

const:
--> Block Scope
--> You can not reassign the value
--> You can not redeclare

```
---
### Create variables
```javascript
var a = 'Soubhik';
let b = 'Arpan';
const c = 'Anuraj';

console.log(a);
console.log(b);
console.log(c);
```
### Output
```
Soubhik
Arpan
Anuraj
```
---
### Redeclare 
```javascript
var a = 'Soubhik';
let b = 'Arpan';
const c = 'Anuraj';

console.log(a);
console.log(b);
console.log(c);

// Redeclare
var a = 'Soubhik';
let b = 'Arpan';
const c = 'Anuraj';

console.log(a);
console.log(b);
console.log(c);
```
### Output
```
SyntaxError: Identifier "b" has already been declared
```
---
### Reassign
```javascript
var a = 'Soubhik';
let b = 'Arpan';
const c = 'Anuraj';

console.log(a);
console.log(b);
console.log(c);

// Reassign
a = 'Person-1';
b = 'Person-2';
c = 'Person-3';

console.log(a);
console.log(b);
console.log(c);
```
### Output
```
c = 'Person-3';
  ^

TypeError: Assignment to constant variable.
```
---
### Block scope
```javascript
{
    var a = 'Soubhik';
    let b = 'Arpan';
    const c = 'Anuraj';
}

console.log(a);
console.log(b);
console.log(c);

```
### Output
```
Soubhik
D:\Coding\AIMERZ.AI\Javascript\Script.js:8
console.log(b);
            ^

ReferenceError: b is not defined
```
---
### ✅ Javascript is dynamically typed programming language means we are not telling what type the data is while create the variables

### Example

```javascript
srting let name = "Soubhik"
// This syntex is wrong
```
---
### ✅ Javascript is case sensitive
### Example
```javascript
let name = "Person-1";
let NAME = "Person-2";

console.log(name);
console.log(NAME);
```
### Output

```
Person-1
Person-2
```
---
![Slide-6](/Images/Slide_6.jpg)
---
![Slide-7](/Images/Slide_7.jpg)
---
![Slide-8](/Images/Slide_8.jpg)