# Unhandled Exception in TypeScript Arithmetic Functions

This repository demonstrates a common error in TypeScript: unhandled exceptions. The `divide` function throws an error if the denominator is zero, but the calling code doesn't handle this possibility. This can lead to unexpected crashes.

The `bug.ts` file contains the buggy code. The `bugSolution.ts` file shows how to handle the exception using a `try...catch` block.

## How to run the code

1. Clone this repository.
2. Open a terminal and navigate to the repository directory.
3. Run the command `tsc bug.ts` to compile the buggy code.
4. Run the command `node bug.js` to execute the compiled code.  You should see an unhandled exception.
5. Then run `tsc bugSolution.ts` and `node bugSolution.js` to see the corrected, exception-handled code.