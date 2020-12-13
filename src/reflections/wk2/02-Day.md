# Day 7
__12/8/2020__

## What are the three ways to syntactically write a function? What are the differences in how the function acts (if any)?

There are three ways to syntactically write a function.

 A function declaration defines a named function. In these instances the function definition is hoisted. Meaning that the value of the function is brought up to evaluate the function. This allows for the function to be used before it is defined.

A function expression defines a named or anonymous function. Anonymous functions have no name. These functions are not hoisted, and therefore they must be defined before they can be used. 

An arrow function expression is a shorthand syntax for writing function expressions. These use the => sign in code. 


## What is the difference between Parameters and Arguments?

The difference between Arguements and Parameters is slight. They both are key parts to a function, not every function but a great deal of them. The Parameters are a variable that the function uses. Parameter is used for the variable, while Arguments are the actual value that gets passed into the function. Arguments are the values the function receives from each parameter when the function gets called or runs. Parameters = a variable, Arguments = a value.


## What are higher order functions? Can you provide an example?

A higher order function is a function that uses another function as a parameter. It is a function inside of a function. Kind of. An example of a higher order function could be the use of math random inside of math floor. This allows us to get a whole random number but it uses two functions to accomplish those things in one line of code.