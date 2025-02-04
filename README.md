# Express.js Route Handler Missing Error Handling for Invalid User ID

This repository demonstrates a common error in Express.js route handlers: missing error handling for invalid input.  Specifically, the provided code attempts to parse a user ID from a route parameter without checking if the ID is valid before parsing it as an integer. This can lead to runtime errors if the ID is not a number or is missing entirely. 

The `bug.js` file contains the erroneous code. The `bugSolution.js` file shows the corrected code with proper error handling.