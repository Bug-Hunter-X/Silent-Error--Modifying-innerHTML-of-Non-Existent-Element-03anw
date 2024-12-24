# Silent Error: Modifying innerHTML of Non-Existent Element

This repository demonstrates a subtle bug in JavaScript that can occur when interacting with the DOM.  Attempting to set the `innerHTML` property of an element that doesn't exist results in a silent failure—no error is thrown, but the intended change doesn't happen.  This can be particularly difficult to debug.

The `bug.html` file showcases the problem, and `bugSolution.html` demonstrates a robust way to avoid the issue by using error handling to check for the element before attempting modification.