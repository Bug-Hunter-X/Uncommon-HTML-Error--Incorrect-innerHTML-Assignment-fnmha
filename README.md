# Uncommon HTML Error: Incorrect innerHTML Assignment

This repository demonstrates an uncommon error in HTML related to the incorrect use of `innerHTML`.  The error occurs when attempting to directly assign a numerical value to the `innerHTML` property of an element.  This results in the content not being rendered and appears as if it wasn't set.

## Bug
The `bug.html` file contains the erroneous code.  Observe that the `div` with the id 'myDiv' remains empty despite the attempt to assign it a numerical value.

## Solution
The `bugSolution.html` file demonstrates the corrected approach.  The numerical value is converted into a string before assignment. 

This error is uncommon because developers usually assign strings to `innerHTML`, and it's easy to overlook this type conversion requirement.