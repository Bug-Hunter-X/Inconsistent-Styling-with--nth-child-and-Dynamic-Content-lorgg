# Inconsistent Styling with :nth-child and Dynamic Content

This repository demonstrates a common issue with the CSS `:nth-child` selector when dealing with dynamically generated content.  The `bug.css` file shows a basic example of attempting to style every other list item. However, adding or removing list items leads to incorrect styling.

The solution, found in `bugSolution.css`, utilizes JavaScript to dynamically apply the styling after the DOM changes. This ensures that the styling remains consistent even when the content is updated.