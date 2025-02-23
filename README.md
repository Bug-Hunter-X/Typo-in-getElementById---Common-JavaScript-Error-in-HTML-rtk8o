# Uncommon HTML Error: Typo in getElementById

This repository demonstrates a common, yet easily missed, error in JavaScript when working with HTML elements.  The error lies in a simple typo in the `getElementById` method.

## The Bug
The `bug.html` file contains JavaScript code that attempts to change the innerHTML of a div element. However, it uses `getElementByIdx` instead of `getElementById`, which results in a runtime error.

## The Solution
The `bugSolution.html` file corrects the typo, providing the correct way to use the `getElementById` method. This simple fix prevents the error and allows for the correct modification of the element's content.

This example highlights the importance of careful coding and thorough testing to prevent seemingly minor issues from causing significant problems.