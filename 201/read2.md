
# HTML book

*Chapter 2: **Text** (pp.40-61)*

There is two types of Markup (Tags)
1. **Structural markup**: the elements that you can use to describe both *headings* and *paragraphs*.
1. **Semantic markup**: provides extra information; such as where emphasis is placed in a sentence, that something you have written is a quotation etc.

<!-- Structural markup Table -->

 | **Structural markup** |Tags|Description|
 |-|-|-|
 |Headings|`<h1> <h2> <h3> <h4> <h5> <h6>`|HTML has six "levels" of headings: `<h1>` is the largest and `<h6>` is the smallest. |
 |Paragraphs|`<p>`|each paragraph has a new line with some space between it.|
 |Bold |`<b>`|make characters appear bold.|
 |talic|`<i>`|make characters appear italic.|
 |Superscript|`<sup>`|Used with dates or mathematical concepts like raising a number|
 |Subscript|`<sub>`|Used with foot notes or chemical formulas such as H20.|
 |Line Breaks|`<br />`|Used to add a line break inside the middle of a paragraph.|
 |Horizontal Rules|`<hr />`|add a horizontal rule between sections. |

---

 <!-- Semantic markup Table -->

  | **Semantic markup** |Tags|Description|
  |-|-|-|
  |Strong|`<strong>`|Used to indicates that content is importent, and it will be in bold |
  |Emphasis|`<em>`|it will be in italic|
  |Quotations|`<blockquote> <q>`|`<blockquote>`used for longer quotes that take up an entire paragraph.`<q>` used for shorter quotes.|
  |bbreviations & Acronyms|`<abbr>`|Used for abbreviation or an acronym |
  |Citations|`<cite>`|Used When referencing a piece of work such as a book, film or research paper.|
  |Definitions|`<dfn>`| Used to indicate the defining instance of a new term.|
  |Author Details |`<address>`|Used to contain contact details for the author of the page.|
  |Changes to Content |`<ins> <del> <s>`|`<ins>`used to show content that has been inserted into a document,`<del>` show text that has been deleted from it and the `<s>`indicates something that is no longer accurate or relevant (but that should not be deleted).|

---

*Chapter 10: **Introducing CSS** (pp.226-245)*

## CSS:
     Allows you to create rules that specify how the content of an element should appear.

### Block elements & Inline elements:
- Block elements: they start on a new line. **Examples** ( `<h1>-<h6>, <p> and <div>`).
- Inline elements: flow within the text and do not start on a new line. **Examples** (`<b>, <i>, <img>, <em> and <span>`).

**Three ways to add CSS**
1. External CSS: we create a folder and link it to the HTML,by adding link element inside the head.
1. Internal CSS: it is inside the html file,by adding the style tag inside the head and we add the curly braces.Internal
1. Inline CSS: by adding the attribute style inside the opening tag.

---


# JavaScript book

*Chapter 2: **Basic JavaScript Instructions** (pp.53-84)*

**Statments**:
A script is a series of instructions that a computer can follow one-by-one. Each individual instruction or step is known as a statement. Statements should end with a semicolon. 

**Comments**:
You should write comments to explain what your code does. They help make your code easier to read and understand. This can help you and others who read your code. 

Two types of **Comments**
1. Single-line comment: two forward slash characters //
1. Multi-line comment: starting with the /* characters and ending with the */ characters

**Variables**: The use of variables to represent numbers or other kinds of data is very similar to the concept of algebra (where le.tters are used to represent numbers). There is one key difference, however. The equals sign does something very different in programming (as you will see on the next two pages). 

JavaScript **DATA TYPES**
- *NUMERIC*: handles numbers.
- *STRING*: anything inside single or double quotes
- *BOOLEAN*: have one of two values: true or false.

**Arrays**: An array is a special type of variable. It doesn't just store one value; it stores a list of values. 

**Values in Arrays**:as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one). 

**Expression**: An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.

**operators**: Expressions rely on things called operators; they allow programmers to create a single value from one or more values.

Types of Operators
 - Assignment operators
 - Comparison operators
 - Arithmetic operators
 - Bitwise operators
 - Logical operators
 - String operators
 - Conditional (ternary) operator
 - Comma operator
 - Unary operators
 - Relational operators

*Chapter 4: **Decisions and Loops** only up to the section on switch statements (pp.145-162)*

#### Decisions:
     Using the results of evaluations, you can decide which path your script should go down.

#### Loops:
     here are also many occasions where you will want to perform the same set of steps repeatedly. 