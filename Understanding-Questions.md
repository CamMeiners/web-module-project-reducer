# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- It calls the onClick function
- onClick function dispatches the addOne action, imported from actions folder
- The action returns the type:ADD_ONE
- the reducer function returns state.total + 1 when the ADD_ONE is returned
- TotalDisplay shows the total plus 1.
