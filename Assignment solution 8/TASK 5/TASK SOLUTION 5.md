## Explanation of z-index

`z-index` is a CSS property that determines the stacking order of elements on a webpage. It applies to positioned elements (those with a specified `position` other than `static`, such as `absolute`, `relative`, or `fixed`).

### How it works:

- Elements with a higher `z-index` value will appear on top of elements with a lower value.
- If two elements have the same `z-index`, the one that comes later in the HTML document will be on top.
- `z-index` only works on positioned elements. If an element is `static`, `z-index` will have no effect.

### Example:



```css
.container {
  position: relative;
}

.box1 {
  position: absolute;
  z-index: 2;
  background-color: red;
  width: 100px;
  height: 100px;
}

.box2 {
  position: absolute;
  z-index: 1;
  background-color: blue;
  width: 100px;
  height: 100px;
}

## Example of z-index

`z-index` is a CSS property used for controlling the stacking order of elements.

### HTML:

```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Z-Index Example</title>
<link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="box red"></div>
  <div class="box blue"></div>
</body>
</html>

