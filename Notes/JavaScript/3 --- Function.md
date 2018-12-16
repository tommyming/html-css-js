# Function

A JavaScript function is a block of code designed to perform a particular task
It is useful because it can be used over and over again

### Someone calls it, it runs.

It is defined with the **function** keyword, followed by a _function name_, followed by parentheses ()

The parentheses may include parameter names separated by commas: 
```
function myFunction(x, y) {
  // statements;
  return x*y;
}
```

## Function calling and return
```
var x = myFunction(4, 3);   // Function is called 3 match with x and 4 match with y, 
                            // return value (4*3 = 12 in this case) will end up in x
```

## Function as an object so it can assign to a variable
```
var func = myFunction;
var x = func(4, 3); // Same as above
```

## Function with no name
```
var d = function(x, y) {return x*y;}
var x = d(3, 4) // Same also
```
# These last two characteristics are commonly used in event handler.
