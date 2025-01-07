# JavaScript Function: Handling Null and Undefined Values

This repository contains a simple JavaScript function that demonstrates a common error related to null and undefined values.  The original code only handles null values, while the solution extends it to handle undefined values as well.

## Bug

The `foo` function correctly handles cases where one or both arguments are null by returning 0. However, it does not explicitly check for undefined values, leading to potential errors if undefined values are passed in.

## Solution

The solution enhances the `foo` function to explicitly check for both null and undefined values using loose equality (==). This ensures that the function handles both cases gracefully.  Strict equality (===) could be used instead, depending on the desired behavior.
