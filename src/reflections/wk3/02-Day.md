# Day 12
__12/15/2020__

## What is the purpose of Encapsulation?

Scope generally means where a variable is available for use. There is globally scoped, function/locally scoped, and there is block scoped.

Globally scoped is any instance where VAR is used outside of a code block. This causes problems becuase if the same variable names are used to define in multiple places, then the system will get confused and return an error message. Globally scoped means too that the variable is up for use in the whole window.

Function/Locally scoped is when the variable is defined inside of a function. This means that the variable defined is only available for use inside of the function.

The final scope is prefered, it is Block scoped. Block scoped applies to both the LET and CONST variables. The block is bound by {} anything inside of curley braces is a part of the block. Variables that are block scoped can only be used for that block.


## What were some of the problems with closures and the underscore prefix?

Hoisting is the movement of bringing a variable or a defined variable to the top of the code block. Because functions cannot run without first bringing in those variables that have been defined it is written into the Javascript. This feature is built into Javascript and allows functions to not be hindered because the variables are defined after the functions code block.


## How do we create private variables in a ES6 Class? Why would you do this?

Personally I will do my very best to never use the VAR assignments. VAR assignments are useful and ok for global assignments, but LET is just as easily usable. CONST will be used for any variables that I will not change at all, and LET will be used in all other cases. This will help me keep my code clean and understandable and it will also help me to not confuse my computer.
