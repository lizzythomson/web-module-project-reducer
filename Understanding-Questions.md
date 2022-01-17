# Understanding Questions:

1. What are the steps of execution from the pressing of the 1 button to the rendering of our updated value? List what part of the code excutes for each step.

- The user presses the 1 button.
- OnClick handler function is called.
- Calls addOne function to return an ADD_ONE action object.
- Dispatch is called with ADD_ONE action object.
- Reducer is called with the current state and the ADD_ONE action object.
- The switch matches the ADD_ONE case.
- The ADD_ONE case returns a new state containing the total from the current state.total + 1.
- The new state triggers a rerender of the APP component.
- TotalDisplay shows the total plus 1.
