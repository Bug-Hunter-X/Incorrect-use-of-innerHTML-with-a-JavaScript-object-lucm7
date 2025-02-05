# Uncommon HTML Error: Incorrect innerHTML Assignment

This repository demonstrates an uncommon error in HTML related to the `innerHTML` property.  The error occurs when a JavaScript object is directly assigned to the `innerHTML` property of an HTML element, which is designed to accept a string value. This will result in unexpected behavior, typically not updating the HTML content as intended.  The solution highlights the proper use of `innerHTML`, assigning strings.

## Bug

The `bug.html` file contains the incorrect code. The script attempts to assign a JavaScript object to the `innerHTML` property, which leads to the error.

## Solution

The `bugSolution.html` file demonstrates the correct approach. The JavaScript code now correctly assigns a string to the `innerHTML` property, resolving the issue and updating the HTML element with the expected content.