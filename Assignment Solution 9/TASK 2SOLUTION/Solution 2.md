### QUESTION 2 
Explain the role of the following key properties in the Flexbox layout model
1 justify-content
2 align-item
3 gap
4 flex-direction
5 flex-wrap 

# Solution 2

# Role of Key Properties in Flexbox Layout

## 1. `justify-content`

- **Role**: `justify-content` is used to align flex items along the main axis (horizontal axis in a row layout, vertical axis in a column layout).
- **Usage**: It controls the distribution of space between and around items in the flex container.
- **Values**:
  - `flex-start`: Items align to the start of the container.
  - `flex-end`: Items align to the end of the container.
  - `center`: Items align at the center of the container.
  - `space-between`: Items are evenly distributed with the first item at the start and the last item at the end.
  - `space-around`: Items are evenly distributed with equal space around them.
  - `space-evenly`: Items are evenly distributed with equal space around them, including the edges.
  
## 2. `align-items`

- **Role**: `align-items` is used to align flex items along the cross axis (vertical axis in a row layout, horizontal axis in a column layout).
- **Usage**: It determines how flex items are positioned within the flex container in the cross axis.
- **Values**:
  - `flex-start`: Items align at the start of the container.
  - `flex-end`: Items align at the end of the container.
  - `center`: Items align at the center of the container.
  - `baseline`: Items align at the baseline of the container.
  - `stretch`: Items are stretched to fill the container.

## 3. `gap`

- **Role**: `gap` is used in grid layouts to set the spacing between rows and columns.
- **Usage**: It defines the size of the gap between grid items.
- **Value**: It takes a length value (e.g., `10px`, `1rem`, etc.) or a percentage.

## 4. `flex-direction`

- **Role**: `flex-direction` determines the primary axis of a flex container and the direction in which flex items are placed in that container.
- **Usage**: It establishes the main axis (horizontal or vertical) along which flex items are laid out.
- **Values**:
  - `row`: Items are placed along the horizontal axis.
  - `row-reverse`: Items are placed along the horizontal axis in reverse order.
  - `column`: Items are placed along the vertical axis.
  - `column-reverse`: Items are placed along the vertical axis in reverse order.

## 5. `flex-wrap`

- **Role**: `flex-wrap` defines whether flex items should be forced into a single line or can be wrapped onto multiple lines.
- **Usage**: It controls whether the flex container is a single-line or multi-line layout.
- **Values**:
  - `nowrap`: Items are forced into a single line.
  - `wrap`: Items can be wrapped onto multiple lines if needed.
  - `wrap-reverse`: Items are wrapped onto multiple lines in reverse order.

