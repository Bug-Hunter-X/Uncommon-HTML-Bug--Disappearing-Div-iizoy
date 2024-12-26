# Uncommon HTML Bug: Disappearing Div

This repository demonstrates an uncommon bug in HTML where a div element is hidden using JavaScript, but there's no mechanism to make it visible again.  The bug is subtle and might go unnoticed during initial testing.

## Bug Description
The `myFunction()` in `bug.html` hides the div with the id `myDiv`. However, once hidden there is no way to make it visible again. This leads to a situation where the content within `myDiv` is lost to the user. This kind of error can be hard to track down because it does not result in a syntax error or a browser error message. Instead, it shows up only during program runtime and interaction.

## Solution
The solution (`bugSolution.html`) introduces a simple way to toggle the visibility of the `myDiv` element.  This makes the content within `myDiv` accessible to the user once again.

## How to reproduce
1. Open the `bug.html` file in a web browser.
2. Click the 'Click Me' button.  Observe that the div disappears and there's no way to bring it back.
3. Open the `bugSolution.html` file, and repeat step 2. The div will now toggle between visible and hidden.