# JavaScript: Handling undefined values when accessing object properties

This repository demonstrates a common error in JavaScript: attempting to access a property of an undefined value. The provided code example shows how to handle this error using optional chaining and nullish coalescing operators.

## Bug Description
The original code throws a `TypeError` when an undefined value is passed to the `foo` function because it attempts to access the `length` property of `undefined`.

## Solution
The solution utilizes optional chaining (`?.`) and nullish coalescing (`??`) to gracefully handle undefined values.  Optional chaining allows access to properties only if the object exists, and nullish coalescing provides a default value if the expression before `??` is null or undefined.