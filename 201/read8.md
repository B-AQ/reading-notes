# HTML book


Chapter. 15, **Layout**(repeat of Class 4 reading)

## Layout

|Layout|Description|
|---|---|
|position:static|I have not specified a widthproperty for the heading element, so you can see how it stretches the width of the entire browser window by default.|
|position:relative|Moves an element in relation to where it would have been in normal flow|
|position:absolute|When the position property is given a value of absolute, the box is taken out of normal flow and no longer affects the position of other elements on the page. (They act like it is not there.) |
|position:fixed|It positions the element in relation to the browser window. Therefore, when a user scrolls down the page, it stays in the exact same place. It is a good idea to try this example in your browser to see the effect.|
|z-index|If you want to control which element sits on top, you can use the z-index property. Its value is a number, and the higher the number the closer that element is to the front. For example, an element with a z-index of 10will appear over the top of one with a z-index of 5.|
|float|Allows you to take an element in normal flow and place it as far to the left or right of the containing element as possible.|
|clear|allows you to say that no element (within the same containing element) should touch the left or righthand sides of a box. It can take the following values:*(left, right, both and none)*|
|Layout Grids|Grids set consistent proportions and spaces between items which helps to create a professional looking design,Many designers use a grid structure to help them position items on a page, and the same is true for web designers. |
---
### Frameworks

Aim to make your life easier by providing the code for common tasks, such as creating layout grids, styling forms, creating printer-friendly versions of pages and so on. You can include the CSS framework code in your projects rather than writing the CSS from scratch.

**multiple style sheets:**
1. @import
1. link

---

- ``<div>`` elements are often used as containing elements to group together sections of a page.
- Browsers display pages in normal flow unless you specify relative, absolute, or fixed positioning.
- The float property moves content to the left or right of the page and can be used to create multi-column layouts. (Floated items require a defined width.)
- Pages can be fixed width or liquid (stretchy) layouts.
- Designers keep pages within 960-1000 pixels wide, and indicate what the site is about within the top 600 pixels (to demonstrate its relevance without scrolling).
- Grids help create professional and flexible designs.
- CSS Frameworks provide rules for common tasks.
- You can include multiple CSS files in one page.
