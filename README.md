# Null value handling in function parameters

This example demonstrates an issue with unexpected behavior when null values are passed to a function in Javascript. The bug is that the function does not explicitly handle null values and this leads to an error or unexpected behavior when null values are passed.

## Bug

The original function `foo` does not handle null values properly.  If either `a` or `b` is null, the function proceeds without explicit handling, which may cause errors or unexpected results. 

## Solution

The improved function `foo` explicitly checks for null values and returns early if either parameter is null. This way, unexpected behavior and errors are avoided.
