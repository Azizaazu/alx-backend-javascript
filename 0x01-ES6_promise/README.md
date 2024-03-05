0. Keep every promise you make and only make promises you can keep
Return a Promise using this prototype function getResponseFromAPI()
1. Don't make a promise...if you know you can't keep it
Using the prototype below, return a promise. The parameter is a boolean.
2. Catch me if you can!
Using the function prototype below

function handleResponseFromAPI(promise)
Append three handlers to the function:

When the Promise resolves, return an object with the following attributes
status: 200
body: success
When the Promise rejects, return an empty Error object
For every resolution, log Got a response from the API to the console
.
.
.
9. Throw an error
Write a function named guardrail that will accept one argument mathFunction (Function).

This function should create and return an array named queue.

When the mathFunction function is executed, the value returned by the function should be appended to the queue. If this function throws an error, the error message should be appended to the queue. In every case, the message Guardrail was processed should be added to the queue.
10. Await / Async
Import uploadPhoto and createUser from utils.js
