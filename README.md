# JavaScript Loose Equality Bug: Unexpected Null Comparisons

This repository demonstrates a common JavaScript bug caused by the loose equality operator (`==`).  The loose equality operator does type coercion, which can lead to unexpected behavior when comparing values, especially when dealing with `null`.

## Bug Description

The provided `bug.js` demonstrates a scenario where loose equality (`==`) can lead to unexpected results when comparing values to `null`. In particular, it focuses on cases where a developer might inadvertently introduce a type coercion bug while attempting to check for null values.

## Solution

The solution is provided in `bugSolution.js`.  The strict equality operator (`===`) is used to prevent type coercion during comparisons.  This ensures that only values of the same type will compare as equal.