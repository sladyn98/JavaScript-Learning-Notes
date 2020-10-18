# Javascript Fundamentals

TO-DO: Add javascript fundamentals

# Javascript Hard Parts


### Javascript Execution 

Javascript execution requires two main processes:

a) Thread of Execution: Executing the code line by line and threading through the entire program.

b) Variable Environment: The Environment to store the data while executing.

These two things together are called the `execution context`

#### Function Execution

While executing a function JS creates what we call a `local execution context` and inside that environment continues to execute the function line by line until it hits the return statement.

### Call Stack
 
Javascript keeps track of the function calls by pushing it into a call stack. Whenever a function call is made it is put into the call stack till it completes execution. The `global()` function is always at the bottom of the call stack signifying the context that is called before any function is run.

### Web Browser API's or background threads

Javascript can interact with a number of web browser API's to attain functionality that is not present in native javascript 

eg: `setTimeout()` function spins out of the webBrowser a timer that takes in the function and the timeout that we want to wait before executing the function.