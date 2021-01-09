# UnderStanding Asynchronous Code, and API's

**1.** What is the difference between `asynchronous` code and `synchronous` code?
<!-- enter you answer in the space below -->
```
There is one main difference between asynchronous and synchronous code. Synchronous code runs all at once. Synchronous code runs nonstop until it gets to the end of the jobs that it has. This makes coding with outside data and API's tricky because a request must be sent off and information must be returned. There is a gap of time where the function that is trying to access that information will not have anything for the function to run therefore an error will appear. Enter asynchronous code. Asynchronous code allows developers to tell a function to go make a request, pause the function until the information is resolved by the server that was being accessed and then resume the function. It also allows other functions that are not dependant on that data that is returning to run while the function is waiting for that return.
```
**2.** What is an event listener?
<!-- enter you answer in the space below -->
```
An event listener is something that is very helpful in keeping a webpage as updated as possible. The listener waits to see or hear a change to something that is registered in the Proxystate, and on that change it can be told what to do. This is typically a draw function of some kind. This is at least the main way that we have been using it in class so far. I am sure that there are other situations where using event listeners will be extremely beneficial.
```
**3.** What does the `O` represent in the `SOLID` principles?
<!-- enter you answer in the space below -->
```
The 'O' in the SOLID principles of object oriented programming stands for the Open-Closed priciple. This means that as developers we should build code that will remain unchanged, but at the same time make code that can adapt and be flexible. It is somewhat of a contradiction, but through polymorphism we can use a parent and child relationship and manipulate the child while leaving the parent object intact. The parent is a template of what the child should look like while the child is very specific on how it looks. Parents can be reused, children should not.
```
**4.** What is a callback / higher order function?
<!-- enter you answer in the space below -->
```
Higher order functions and callback functions are essentially functions running either inside of eachother, or running back and forth to one another. Meaning anytime that a function is either cast into a function as an arguement or returns a function on completion (or both), OR when a function is passed to another function with the expectation that the other function will call it. Functions leading to functions and functions inside of functions.
```
**5.** What is a `promise`? How do you capture an error from a `promise`?
<!-- enter you answer in the space below -->
```
A promise is an object and like a callback. They are essentially a callback that can be performed asynchronously. There are three states to a promise. Pending, resolved, and rejected (Pre-success/fail, success, fail). 
Because promises only return as resolved or rejected, Javascript does not automatically throw an error for the rejected state. When developers use a try/catch method we are able to catch the error and report that an error has occured. We put these in the controller after we state what request we are trying to send off to the server.
```
**6.** Name three processes used to make requests over `HTTP`?
<!-- enter you answer in the space below -->
```
The three main processes used to make requests over HTTP are GET, PUT, and POST. There is also DELETE, but DELETE simply removes things from the API. Get retreives information, Put edits information already existing, and POST adds completely new information. These also correspond with CRUD: CREATE (POST), READ (GET), UPDATE (PUT), and DELETE which is still delete despite some developers wanting to use the word destroy for the sake of being different. :)
```
**7.** What does the `API` acronym stand for?
<!-- enter you answer in the space below -->
```
API stands for Application Programming Interface. API's allows two applications to talk to one another. They are essentially the middle men. They communicate between the server and the application and they convey the information to both in a readable method.
```
**8.** In the `MVC` design pattern, who is responsible for making calls to `APIs`?
<!-- enter you answer in the space below -->
```
Inside of the MVC design pattern the Service is responsible for making the calls to the APIs. The Service handles all of the business logic of an application and that is exactly what getting/putting/posting/deleting is. It is all business logic.
```
**9.** What is the purpose of encapsulation in programming?
<!-- enter you answer in the space below -->
```
The purpose of Encapsulation in programming is to keep like concerns together. It also offers a barrier between the user and all of the data. Using an API and blocking the user from being able to directly manipulate the data is a big chunk of why developers write code using this Encapsulation method. It also makes code much much easier to read.
```
**10.** What is `HTTP` response code for a successful request?
<!-- enter you answer in the space below -->
```
I believe that the response code for a successful request is '200 successful' meaning that the request that was sent was accepted and had all of the information that it needed to talk to the server to return a result.
```
**11.** What is a 500 error?
<!-- enter you answer in the space below -->
```
A 500 level error typically means that the server encountered an internal error that is unrelated to the request data that was provided. This means that the server has an error internally and that hopefully there was nothing wrong with the actual request that was submitted.

In addition to these two codes, there are the level 100's- which mean that the request was recieved and that the process is continuing. There are the level 200's- that are the successful requests that were completely understood and accepted. There are the level 300 codes- which translate to further action needed to complete the request. Level 400's- which refer to client errors (probably the most common for me so far). Finally ther are the 500 codes- which mean that the server met an error.
```