# Introduction
JavaScript (JS) is a programming language used mainly inside a browser. 

JavaScript has C/C++ like programming syntax,

i.e.
### If you don't sure what to do, the best way is to write it like C/C++ (if you learnt it before)
### However, semi-colons (;) are not compulsory

## Variable Declaration

Variables are created using the _var_ keyword or from a simple assignment

```
var a; // a created
b = 10; // b created
```

Variable name is **Case-sensitive** means variable _Apple_ is not equal to _apple_.
## Data Types

- number: 20, 5.3 
- string: "Apple"
- boolean: true, false
- object: {}

## Operators
JavaScript operators are almost the same as the C/C++ operators with addition of === and !== operators

- === means comparing for equality of **values** and **types**

```
5 == "5" // true -> since == operator only compare the value
5 === "5" // false -> since 5 is a number and "5" is a string
```
- Basic Arithmetic
```
var num = 4 + 5 * 8 // x = 44
var num = (4 + 5) * 8 // x = 72
```
- Increment & Decrement operators

```
x = 2
x++ // x=x+1 i.e. x = 3
y = 6
x-- // x=x-1 i.e. y = 5
```
- Comparison
```
> larger than (exclude)
< smaller than (exclude)
>= larger than (include)
<= smaller than (include)
!= inequality
== equality
```
