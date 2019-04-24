#### Explanation
1. `.clearfix::after` defines a pseudo-element.
2. `content: ''` allows the pseudo-element to affect layout.
3. `clear: both` indicates that the left, right or both sides of the element cannot be adjacent to earlier floated elements within the same block formatting context.

#### Browser support
### 100%

 ⚠️ For this snippet to work properly you need to ensure that there are no non-floating children in the container and that there are no tall floats before the clearfixed container but in the same formatting context (e.g. floated columns).
