# Type 'string[]' is not assignable to type 'string'
This repository demonstrates a common TypeScript error: assigning an array of strings to a string variable. The error occurs because the `greeter` function expects a single string argument, but the `user` variable is an array of strings. 

## How to reproduce
1. Clone this repository.
2. Navigate to the repository's directory.
3. Compile and run the code using `tsc bug.ts && node bug.js`.

## Solution
The solution is to modify the `greeter` function or the way the `user` variable is passed to the function. You can either change the `greeter` function to accept an array of strings or join the elements of the array into a single string before passing it to the function.
