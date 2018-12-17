# Flow Control

## if () ... else ... and switch ()

Use the if statement to specify a block of JavaScript code to be executed if a **condition** is true.

**condition** is a boolean expression that can be either true or false e.g _3 <= 0_ is **false**

```
if (condition) {
  /* block of code to be executed if the
     condition is true
  */
} else {
   /* block of code to be executed if the
    condition is false
   */
}
```
### Use the switch statement to select one of many blocks of code to be executed.
```
switch(expression) {
  case x:
    code block
    break;
  case y:
    code block
    break;
  default:
    code block
}
```
- match the case with the value stored in your expression variable
### The break Keyword
- if no break and case x is match, it will continue run case y and the subsequent blocks
### The default Keyword
- if no case you specified is matched, run the default case's block

## for () ... while () ... and do ... while ()
### while loop
The while loop repeatedly run through a block of code as
long as a specified **condition** is **true**.

```
while (condition) {
    // code block to be executed
}
```
### for loop
```
for (statement 1; statement 2; statement 3) {
    // code block to be executed
}
```
- statement 1: sets a variable before the loop starts (var i = 0)
- statement 2: defines the condition for the loop to run (i must be less than 5), otherwise, it stop looping
- statement 3: increases a value (i++) each time the code block in the loop has been executed
### do while loop
This loop will execute the code block once, before
checking if the **condition** is true, then it will repeat the
loop as long as the condition is **true**.
```
do {
    // code block to be executed
} while (condition)
```
