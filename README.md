# Unexpected NaN Result in foo Function with Undefined Input

This repository demonstrates a common JavaScript error involving the unexpected handling of undefined values.  The `foo` function aims to add 1 to a number, handling `null` gracefully, but fails to properly handle `undefined` inputs, resulting in `NaN`.

The `bug.js` file contains the faulty code. The solution, found in `bugSolution.js`, addresses the issue by explicitly checking for both `null` and `undefined`. This ensures that the function behaves predictably and robustly under different input conditions. 