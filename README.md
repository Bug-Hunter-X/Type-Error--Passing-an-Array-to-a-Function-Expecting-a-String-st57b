# Type Error: Passing an Array to a Function Expecting a String

This repository demonstrates a common type error in TypeScript: passing an array to a function that expects a string.

## Bug

The `greeter` function expects a string argument. However, the `user` variable is an array of strings.  This causes a type error.

## Solution

The solution involves either modifying the `greeter` function to accept an array of strings, or changing the `user` variable to a string.