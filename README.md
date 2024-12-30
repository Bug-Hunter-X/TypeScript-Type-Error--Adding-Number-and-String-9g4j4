# TypeScript Type Error: Adding Number and String

This repository demonstrates a common type error in TypeScript that occurs when performing arithmetic operations on incompatible types. Specifically, attempting to add a number and a string. The `add` function is defined to accept two numbers, but the code calls it with a number and a string, leading to a type error.

The solution provided uses type guards or input validation to address the type mismatch, ensuring that the function only receives numbers. 

## How to Reproduce
1. Clone this repository
2. Run `tsc bug.ts` (This will show the type error)
3. Run `tsc bugSolution.ts` (This will compile successfully)