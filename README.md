# Uncommon HTML Bug: innerHTML and Event Listeners

This repository demonstrates an uncommon bug in HTML related to the use of `innerHTML` and event listeners.  The bug arises from the fact that using `innerHTML` to replace the content of an element will remove any previously attached event listeners to that element.

## Bug Description

The `bug.html` file contains an HTML page with a div and an event listener. The event listener is added after the div content is replaced using `innerHTML`.  As a result, the click event listener does not function.

## Solution

The `bugSolution.html` demonstrates a solution that avoids this issue by using alternative methods to update the content of the div without removing existing event listeners. 