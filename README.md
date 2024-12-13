# ActionScript 3 ReferenceError Bug

This repository demonstrates a common ActionScript 3 error: a `ReferenceError: Error #1069: Property someVariable is not found on Object.`  The error occurs even when the variable appears to be correctly defined and initialized.  The solution highlights the importance of scope and proper variable access within ActionScript 3.

## Bug Description
The provided `bug.as` file contains a function that attempts to access a variable that is *logically* within scope, but due to a subtle scoping issue, is not accessible. This leads to the runtime `ReferenceError`. 

## Solution
The solution file, `bugSolution.as`, corrects the issue by ensuring the variable is properly accessible within the function's scope.  It demonstrates proper handling of variable scope to prevent this common error.