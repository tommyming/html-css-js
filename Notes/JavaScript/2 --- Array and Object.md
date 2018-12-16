# Array and Object
JavaScript supports more advanced types made up of a collection of object.
### Array elements can be of different data types.

```
var myArray = [true, "Thomas", 3, -5 , 45.2]
```
- the type of array is object
## Access arrays by index value

Array indexes start with 0.

[0] is the first element. [1] is the second element, index only up to size - 1.

This statement changes the value of the first element in myArray
```
myArray[0] = "Owen"; // myArray = ["Owen", "Thomas", 3, -5 , 45.2]
```
- full array can be accessed by referring to the array name
```
var newArray = myArray;
```
## Object

Objects use names to access its "members". In this example, person.firstName returns John:
```
var person = {firstName:"John", lastName:"Titor", age:30}; // person.firstName is "John"
```
## The length Property
The length  Property gives the number of array elements in an array.

```
var fruits = ["Banana", "Orange", "Apple"];
fruits.length;   // the length of fruits is 3
```

### The Difference Between Arrays and Objects
- arrays use numbered indexes with [] bracket.  
- objects use named indexes with {} bracket.
```
Arrays are a special kind of objects, with numbered indexes.
```
