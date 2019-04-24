## Constant width to height ratio
Given an element of variable width, it will ensure its height remains proportionate in a responsive fashion (i.e., its width to height ratio remains constant).

#### Explanation

`padding-top` on the `::before` pseudo-element causes the height of the element to equal a percentage of its width. `100%` therefore means the element's height always be `100%` of the width, creating a responsive square.

This method also allows content to be placed inside the element normally.

#### Browser support
### 100%
