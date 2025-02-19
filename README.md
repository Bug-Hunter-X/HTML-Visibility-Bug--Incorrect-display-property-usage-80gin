# Uncommon HTML Bug: Incorrect display property usage
This repository demonstrates an uncommon bug related to using the CSS `display` property to show and hide an HTML element. The issue arises from not setting the initial `display` style, leading to unpredictable behavior when toggling visibility.

## Bug Description
The provided HTML code includes a div element that should initially be hidden. A button allows users to show or hide the div. However, due to an improper handling of the `display` property, the initial visibility state is not correctly managed.  The code incorrectly assumes an initial value for `style.display`, causing the toggle function to behave inconsistently across different browsers.

## Solution
The solution involves setting the initial `display` style of the div to `none` in the HTML or using a class to manage the visibility.

## How to Reproduce
1. Clone this repository.
2. Open `bug.html` in your web browser.
3. Click the button. Observe the inconsistent behavior of the div's visibility.
4. Open `solution.html` to see the corrected code.