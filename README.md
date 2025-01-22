# Unexpected :hover Behavior on Parent Elements

This repository demonstrates an uncommon CSS bug related to the `:hover` pseudo-class and its unexpected behavior on parent elements.  The issue arises when `:hover` is applied to a parent element, unintentionally affecting its children.

The `bug.css` file contains the erroneous code. The `bugSolution.css` file shows the corrected version.

The problem is that the `:hover` selector is applied to the parent element and inherits to the child elements leading to unexpected behavior.