# Unhelpful TypeScript Error with Array/String Type Mismatch

This repo demonstrates a common TypeScript error where passing an array to a function expecting a string results in an unhelpful error message. The error message can be difficult to understand for developers new to TypeScript.

## Bug

The `greeter` function expects a string argument, but an array is passed. The resulting TypeScript error is not very descriptive, making it hard to diagnose the problem quickly.

## Solution

The solution involves either changing the function signature to accept an array or modifying the function call to pass a string.