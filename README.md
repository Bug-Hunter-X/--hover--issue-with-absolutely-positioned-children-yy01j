# :hover Issue with Absolutely Positioned Children

This repository demonstrates a common issue where the `:hover` pseudo-class doesn't work as expected on a parent element when it contains absolutely positioned children.  The hover effect may not trigger consistently or at all.

The `bug.css` file contains the problematic code. The `bugSolution.css` file provides a solution to fix this behavior.

This issue is often caused by the absolutely positioned children overlapping the parent element, preventing the hover event from being registered on the parent. The provided solution adjusts the positioning or z-index to resolve this.