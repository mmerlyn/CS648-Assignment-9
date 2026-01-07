# jQuery Selectors and DOM Manipulation

_This project demonstrates jQuery fundamentals including DOM manipulation, dynamic styling, selector syntax, class manipulation, and document ready events using the Vecta Corp website template._

## Overview

This project is a web-based demonstration of jQuery selectors and DOM manipulation techniques applied to a corporate website template. The application dynamically styles elements, adds/removes classes, and modifies CSS properties programmatically using jQuery.

## Technologies Used

- HTML5
- CSS3
- jQuery 3.7.1
- Normalize.css

## What I Implemented

### Dynamic Heading Styling (index.html)

- **Combined Selectors**: Used `$("section h2, aside h2")` to target multiple elements
- **CSS Method**: Applied multiple style properties via `.css()` method
- **Styling Applied**: Border, color, padding, border-radius, and background-color

### Navigation Menu Enhancement (index.html)

- **addClass()**: Programmatically added "navigation" class to all 5 menu items
- **Chained Styling**: Applied custom styles to dynamically added class
- **Selector Usage**: Used `$("nav ul li")` for precise element targeting

### Class Removal (events.html)

- **removeClass()**: Removed multiple classes ("vprospect", "vconvert", "vretain") from paragraph elements
- **Descendant Selector**: Used `$("main p")` to target paragraphs within main element

### Document Ready Pattern

- **$(document).ready()**: All jQuery code wrapped to ensure DOM is fully loaded
- **Event Handling**: Proper initialization sequence for DOM manipulation

### CSS Styling Techniques

- **Fixed-width Layout**: 960px container with 3-column float-based design
- **Background Images**: Header, footer, and product logos
- **Hover Effects**: Navigation link interactions
- **Semantic HTML5**: Proper use of header, nav, section, aside, and footer elements

## Learnings

- Understanding jQuery selector syntax and specificity
- Manipulating CSS properties dynamically via the `.css()` method
- Adding and removing classes programmatically with `.addClass()` and `.removeClass()`
- Using combined selectors to target multiple elements efficiently
- Implementing the document ready pattern for proper DOM initialization
- Working with descendant selectors for precise element targeting
- Applying multiple style properties in a single jQuery call using object notation

---

**Course:** CS 648 - Modern Web Development Frameworks<br>
**University:** San Diego State University (SDSU)<br>
**Author:** Merlyn Mercylona M
