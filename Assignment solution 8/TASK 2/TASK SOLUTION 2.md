<!-- TASK 2 Problem Statement 
Explain the difference between Absolute and Relative positioning. -->


## Difference between Relative and Absolute Positioning

### Relative Positioning

Relative positioning is a method in CSS that allows you to position an element relative to its normal position on the webpage. It is achieved by using the `position: relative;` CSS property. 

Key characteristics of relative positioning include:

- The element is still a part of the normal flow of the document, so it affects the position of other elements as if it were still in its original position.
- It's positioned relative to its normal position, with the offset specified by `top`, `right`, `bottom`, and `left` properties.
- If no offset properties are set, the element will remain in its original position.

```css
position: relative;
top: 10px;
left: 10px;

```
### Absolute Positioning

Absolute positioning allows you to position an element relative to its nearest positioned ancestor (an element with a specified `position` attribute other than `static`). It is achieved by using the `position: absolute;` CSS property.

**Key characteristics** of absolute positioning include:

- The element is removed from the normal flow of the document, which means it does not affect the position of other elements.
- It is positioned relative to the nearest ancestor with a specified position (if none, it uses the initial containing block, usually the viewport).
- If no positioned ancestor is found, it will be positioned relative to the initial containing block (viewport).
- Overlapping may occur if multiple elements are absolutely positioned in the same area.

```css
position: absolute;
top: 0;
left: 0;
