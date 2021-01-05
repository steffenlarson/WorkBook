# Day 17
__01/05/2021__

## What are the three states of a Promise?

The three states of a promis are first: Pending, second: Resolved, and third: Rejected. The Pending state is the time that the promise exists before it succeeds or fails. The resolved state is what happens when a promise completes and clears or resolved. Finally the Rejected state of a promise refers to when a Promise fails or gets rejected.


## How do promises seek to resolve the issues of 'Callback Hell'?

Callbacks themselves are susceptable to becoming a source of Callback Hell. If a developer puts multiple callbacks nested within one another, that is a form of Callback Hell. Promises can resolve this issue through chaining. Callbacks can be attached to the end of a line of code instead of being passed through like a function. This helps the code avoid becoming a pyramid of doom so to say. This keeps the codes readability.


## What is the difference between .then() and .catch()?

The difference between .then() and .catch() is fairly simple. Then is used for whenever a promise is resolved. Catch is used for when a promise is rejected. Then allows for us to decide after it runs what to do with the resolved promise. If the promise fails, we use the Catch method. Catch can be attached directly after Then. If the promise gets resolved there can be an outcome, and with the Catch method attached on the end if it fails another outcome can be achieved.
