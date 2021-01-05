# Day 16
__01/04/2021__

## What are some of the signs and causes of Callback Hell?

Some of the signs and causes of Callback Hell are when developers try to write their code in a way that makes it read top-down. This leads to nested functions and a pyramid like look in the code that makes the code very hard to read. There is an expectation in many other coding languages that says that whatever happens on the first line will finish before the code on the second line starts running. Javascript is a little different.


## What does the asynchronous mean and how are callbacks involved?

The word 'asynchronous' in the coding aspect means that something will take some time or happen later or just not in that moment. Callbacks are a convention used in Javascript functions that mean that instead of immediately returning a result like a pass or a fail, a function with a callback used in it takes some time to produce a result. These Callbacks are usually reserved for functions that need to return a download of some kind or do something else that is not instantaneous.


## Summarize the 3 ways to avoid / fix Callback Hell.

The three ways to avoid and fix 'Callback Hell' are first: to keep the code written shallow, second: is to modularize, and third is to handle every single error. Shallow code means to keep things simple. Name every function. Split nested functions up. Make the code easier to read. Doing this allows for easier debugging, it allows functions to be moveable, and it allows for the finding of errors easier. Modularizing means to use different files for like code. Importing and exporting files to one another allows the code to stay very readable, and by using different variables from importing and exporting important pieces of reusable code it shortens the code. This allows for readability to become greater. Handling every single error is a little different than the last two rules. This rule is to help the code become more stable. Developers should always think and assume that their code is going to throw an error. When we as developers assume this idea and build things around it debugging and managing program breaking problems becomes easier. The most popular way of addressing errors every single time is to address the error in the first arguement of each callback. This convention of addressing the error first ensures that the errors are almost always dealt with.

