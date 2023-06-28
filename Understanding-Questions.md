# Understanding Questions:
1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.
* The user presses the 1 button.
* handle1Click is called
* which dispatches addOne from actions/index.js
* which returns ADD_ONE whose action type is state.total + 1
* therefore...

* TotalDisplay shows the total plus 1.
