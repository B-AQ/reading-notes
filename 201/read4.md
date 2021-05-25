# HTML book

*Chapter 4:**Links** (pp.74-93)*

## Links

**Writing Links:** using the `<a>` element. Users can click on anything between the opening `<a>` tag and the closing `</a>` tag. You specify which page you want to link to using the href attribute.

- Linking to Other Sites:
When you link to a different website, the value of the hrefattribute will be the full web address for the site, which is known as an absolute URL.

- Linking to Other Pages on the Same Site:
you can use relative URLs. These are like a shorthand version of absolute URLs because you do not need to specify the domain name.

- Opening Links ina New Window,**(target):**
If you want a link to open in a new window, you can use the target attribute on the opening `<a>` tag. The value of this attribute should be _blank.

- Linking to a Specific Part of the Same Page:
To link to an element that uses an id attribute you use the `<a>` element again, but the value of the href attribute starts with the # symbol, followed by the value of the id attribute of the element you want to link to. In this example, `<a href="#top">`links to the `<h1>` element at the top of the page whose idattribute has a value of top.

- Linking to a Specific Part of Another Page:
As long as the page you are linking to has id attributes that identify specific parts of the page, you can simply add the same syntax to the end of the link for that page.

- Email Links **mailto**

- Directory Structure:
On larger websites it's a good idea to organize your code by placing the pages for each different section of the site into a new folder. Folders on a website are sometimes referred to as directories.

1. Structure:The diagram on the right shows the directory structure for a fictional entertainment listings website called ExampleArts.
1. Relationships:The relationship between files and folders on a website is described using the same terminology as a family tree.
1. Homepages: is called index.html

---
*Chapter 15: **Layout** (pp.358-404)*

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
# JavaScript book

*Chapter 3: **Functions, Methods, and Objects** (pp.86-99)*

**Functions:**
let you group a series of statements together to perform a specific task. If different parts of a script repeat the same task, you can reuse the function (rather than repeating the same set of statements).

#### What is an **Object?**

a set of variables and functions to create a model of a something you would recognize from the real world. In an object, variables and functions take on new names.

---
Article: 6 Reasons for **Pair Programming**

**Why pair program?**

1. Greater efficiency
1. Engaged collaboration
1. Learning from fellow students
1. Social skills
1. Job interview readiness
1. Work environment readiness


Reference [**Pair Programming**](https://www.codefellows.org/blog/6-reasons-for-pair-programming/)