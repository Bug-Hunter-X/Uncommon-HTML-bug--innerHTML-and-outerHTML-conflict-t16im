# Uncommon HTML Bug: innerHTML and outerHTML Conflict
This repository demonstrates an uncommon HTML bug involving the use of `innerHTML` and `outerHTML` on the same element. Modifying both properties in quick succession can lead to unpredictable results. The example shows how setting `innerHTML` and then immediately changing `outerHTML` can lead to the `innerHTML` changes being overwritten.
The `bug.html` file contains the buggy code, and `bugSolution.html` provides a corrected version. 