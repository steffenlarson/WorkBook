# Intro to JavaScript

**1.** Which keywords are used to declare a variable in JavaScript?
<!-- enter you answer in the space below -->
```
The keywords used to declare variables are VAR, LET, and CONST.
```
**2.** What is the definition of a function?
<!-- enter you answer in the space below -->
```
A sub program designed to perform particular tasks.
```
**3.** What are the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The SOLID principles are:
S: Single responsibility
O: Open closed 
L: Liskov substitution
I: Interface segregation
D: Dependency Inversion

```
**4.** Given this array: 
```js
let fruit = ['apple', 'banana', 'pineapple',  'orange', 'strawberry']
``` 
What index is the pineapple's current position? How do you know?
<!-- enter you answer in the space below -->
```
Pineapple is currently located at the index [2]. This is because in arrays the separate objects begin at 0 instead of 1. So where pineapple is the thrid object inside of the array, it means that its index is [2].
```
**5.** With these two objects: 
```js
let you = { name:"You", hair: true, friends: [] }
let them = { name:"Them", hair: false, friends: [] }
```
how would you .push the `them` object into the `you` object's array of friends?
<!-- enter you answer in the space below HELP HERE--> 
```
.push(them)you.[] I am not sure if this is right, I need to ask a question to clarify.
```

**6.** Give an example of a JavaScript `Conditional`:
<!-- enter you answer in the space below -->
```
An if statement is a conditional statement. There are also else, else if, and switch.
```
**7.** In the `for loop` below, what is the name of the piece belongs inside the empty "______" space? What would you put here to increase `i` by one on every iteration?
```js
for ( let i = 0; i < arr.length; _______ ) {
  //...
```
<!-- enter you answer in the space below -->
```
This is the incrimentor. If you wanted to increase i by one on every itteration you would write i++.
```
**8.** What does the `DOM` acronym stand for? Which file is first accessed to render the `DOM`?
<!-- enter you answer in the space below -->
```
DOM stands for the Document Object Model. The html file is always accessed first to render the DOM.
```

**9.** What are the `9` ECMAScript types as defined by MDN?
<!-- enter you answer in the space below -->
```
There are six data types which are (primitive): undefined, boolean, number, string, BIgInt, and symbol. There are two structural types: Objects and functions. And then there is the structual root null.
```
**10.** When it comes to functions or methods, what is the difference between a `parameter` and an `argument`?
<!-- enter you answer in the space below -->
```
Parameters are the variable given to the value of what is being passed into a function. Arguments are the actual value of what is passed to the function. Parameters = variable, Arguments = actual value.
```
**11.** What is the difference between a `primitive` value and a `reference` value?
<!-- enter you answer in the space below -->
```
Primitive types are stored in hte heap while references are stored in the stack.
```