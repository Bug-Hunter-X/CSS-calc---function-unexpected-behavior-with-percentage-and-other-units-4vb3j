# CSS calc() function unexpected behavior with percentage and other units
This repository demonstrates an uncommon bug related to the CSS `calc()` function when used with a mixture of percentage and other units. The issue occurs when there's a lack of proper spacing between the percentage value and the other units involved in the calculation. This leads to an incorrect rendering of the element's width.

## Bug Description
The `calc()` function in CSS is a powerful tool for performing calculations within CSS properties. However, when combining percentage values and other units like pixels (px), ems (em), or rems (rem), it requires precise syntax. The bug arises when the calculation does not have clear separation using spaces between the elements of the calculation, which leads to unexpected results.

## Solution
The solution is quite simple: Ensure there are spaces between the percentage value and other units within the `calc()` function. This correct spacing allows the browser to correctly parse the mathematical operations and render the layout as expected.