# CS648 Assignment 9 - jQuery Selectors and Commands

## Description

Practice assignment demonstrating jQuery selectors and DOM manipulation techniques using the Vecta Corp website. This assignment covers applying styles programmatically, modifying CSS properties, and dynamically adding/removing classes.

## Features Implemented

### index.html

- **Heading Styling**: All `<h2>` elements within `<section>` and `<aside>` tags styled with:

  - 1px solid black border
  - Color: #CC1C0D
  - Padding: 3px (top/bottom), 20px (left/right)
  - Border radius: 5px (top-left and bottom-left corners)
  - Background color: #DFE3E6

- **Navigation Menu**: Dynamic class addition and styling:
  - Programmatically added "navigation" class to all 5 menu items
  - Applied styles: 1px solid #929C04 border, #CC1C0D text color
  - Padding: 3px (top/bottom), 20px (left/right)
  - Background color: #DFE3E6

### events.html

- **Class Removal**: Programmatically removed "vprospect", "vconvert", and "vretain" classes from all `<p>` tags within the main element

## Technologies Used

- HTML5
- CSS3
- jQuery 3.7.1
- Normalize.css

## Learning Outcomes

- jQuery selector syntax and specificity
- DOM manipulation with jQuery
- CSS property manipulation via jQuery
- Dynamic class addition and removal
- Document ready function implementation
