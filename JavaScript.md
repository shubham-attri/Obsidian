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
But JS is synchronous Programming language.

>> Callbacks 

There is a webAPI call if the thread waits for some response and makes the program wait, then the current thread run the former task in the call stack, once the webAPI cal lis completed, it gets added to JS Queue where it waits for the JS Call Stack to become idle and things are added as per the Queue of API, ie JS can't do 2 things at a time. They can delegate a task which requires response and makes the program idle, and when the delegated task is completed it gets added to the queue. 


JS is meant for single threaded language meant for simple things, it is good at delegating tasks.

Inject JS code in website to write code in the website, When you inject code in website, it is asynchronous is nature. The requests made are put into queue to be waited for the stack to get free.


>> Promises 

Calling one async call after another makes a chain of async calls for the webAPI to be delegated that gets added in the queue and takes time, it looks very complex chaining asyc calls, if poorly written code could put into the callback Hell


Creating an object in JS and then having one parameter as a function is fine and then we can call the function using the object.