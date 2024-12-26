# Incorrect Modification of Element Text Content

This repository demonstrates a common mistake when working with HTML elements and manipulating their text content.  The `text` property does not exist for HTML elements.  The correct approach is to use `innerHTML` to change the content of an element, or `textContent` to read it.  This example shows the incorrect usage and the correct fix.

## Bug Description

Incorrect usage of element property.  Attempts to directly use a non-existent property `text` to change the text of an HTML element which leads to no changes reflected in the DOM.