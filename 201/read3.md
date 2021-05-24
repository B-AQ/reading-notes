# HTML book

*Chapter 3: **Lists** (pp.62-73)*

## Lists

HTML provides us with **three** different types:

- Ordered lists:are lists where each item in the list is numbered. For example, the list might be a set of steps for a recipe that must be performed in order, or a legal contract where each point needs to be identified by a section number

- Unordered lists: are lists that begin with a bullet point (rather than characters that indicate order).

- Definition lists: are made up of a set of terms along with the definitions for each of those terms.

**Note**: there is somthing called **Nested list**You can put a second list inside an `<li>` element to create a sublist or nested list.

---
*Chapter 13: **Boxes** (pp.300-329)*

## Boxes

- **width, height:**
The most popular ways to specify the size of a box are to use pixels, percentages, or ems.

- **min-width, max-width:**
Some page designs expand and shrink to fit the size of the user's screen. In such designs, the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide.

- **min-height, max-height:**
In the same way that you might want to limit the width of a box on a page, you may also want to limit the height of it. This is achieved using the min-heightand max-height properties.

- **overflow:**
The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of **two values:**

1. *hidden:* hides any extra content that does not fit in the box.
1. *scroll:* adds a scrollbar to the box so that users can scroll to see the missing content.

#### **Border, Margin & Padding**

**Border:** Every box has a border (even if it is not visible or is specified to be 0 pixels wide). The border separates the edge of one box from another.

**Margin:** Margins sit outside the edge of the border. You can set the width of a margin to create a gap between the borders of two adjacent boxes.

**Padding:** Padding is the space between the border of a box and any content contained within it. Adding padding can increase the readability of its contents.

---

# JS book

*Chapter 2: **Basic JavaScript Instructions** (pp.70-73)*

### Arrays

is a special type of variable. It doesn't just store one value; it stores a list of values.

**CREATING AN ARRAY:** The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. The values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array.

**VALUES IN ARRAYS:** are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).

---
*Chapter 4: **Decisions and Loops** (pp.162-182)*

### Conditional Statements

In JavaScript we have the following conditional statements:

- Use **if** to specify a block of code to be executed, if a specified condition is true
- Use **else** to specify a block of code to be executed, if the same condition is false
- Use **else** if to specify a new condition to test, if the first condition is false
- Use **switch** to specify many alternative blocks of code to be executed

### Loops

Loops offer a quick and easy way to do something repeatedly

JavaScript **statements for loops** are:

- for
- do...while
- while
- labeled
- break
- continue
- for...in
- for...of

**for** statement
: A for loop repeats until a specified condition evaluates to false

**while** statement
: executes its statements as long as a specified condition evaluates to true, In other words if the condition becomes false, statement within the loop stops executing and control passes to the statement following the loop.
