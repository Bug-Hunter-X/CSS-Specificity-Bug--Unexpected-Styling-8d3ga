# CSS Specificity Bug

This repository demonstrates a common CSS issue related to specificity. The goal is to highlight how specificity rules influence style application and how to resolve conflicts effectively.  The `bug.css` file contains the problematic code, while `bugSolution.css` presents the corrected version.

## Problem

The provided CSS attempts to style a paragraph (`<p>`) within a div with the class `container`. However, due to specificity, the general paragraph style overrides the more specific style.

## Solution

The solution addresses specificity by employing more precise selectors or using the `!important` flag (although this is generally discouraged due to potential maintenance issues).