ECMAScript Standard to create compilers for various browsers 
There are various engines for various compilers

Node.js is a Javascript runtime, using the V8 engine. Its a compiler used by google which became popular to run backend code.

Where can JS run;
Browser Data centres mobile devices, anyone with javascript engine

Js is single threaded, it is a powerless language
Js is asynchronous in nature
Js can be either strongly or loosely typed 
Js is an interpreted language

We can pass a function parameter in a function as a parameter, think of it as choice of various functions to be called with if statements

There is some native JS and there are API's. We can delegate backend code which we don't wanna show using API

Js is asynchronous in nature ie there is no parallelism .

There is a webAPI call if the thread waits for some response and makes the program wait, then the current thread run the former task in the call stack, once the webAPI cal lis completed, it gets added to JS Queue where it waits for the JS Call Stack to become idle and things are added as per the Queue of API, ie JS can't do 2 things at a time. They can delegate a task which requires response and makes the program idle, and when the delegated task is completed it gets added to the queue. 

