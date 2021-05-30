
# HTML book

*Chapter 6: **Tables** (pp.126-145)*

## Tables

A table represents information in a grid format. Examples of tables include financial reports, TV schedules, and sports results.

**Basic Table Structure:**

``<table>``
Used to create a table. The contents of the table are written out row by row.

``<tr>``
You indicate the start of each row using the opening ``<tr>`` tag. (The tr stands for table row.)

``<td>``
Each cell of a table is represented using a ``<td>`` element. (The td stands for table data.)

Table heading:
``<th>``
Used just like the ``<td>`` element but its purpose is to represent the heading for either a column or a row.
(The th stands for table heading.)

---

- The table element is used to add tables to a web page.

- A table is drawn out row by row. Each row is created with the ``<tr>`` element.

- Inside each row there are a number of cells represented by the ``<td>`` element (or ``<th>`` if it is a header).

- You can make cells of a table span more than one row or column using the rowspan and colspan attributes.

- For long tables you can split the table into a ``<thead>, <tbody>, and <tfoot>``.

---

# JS Book

*Chapter 3: **Functions, Methods, and Objects** (pp.106-144)*

## Functions

- Allow you to group a set of related statements together that represent a single task.

- Can take parameters (informatiorJ required to do their job) and may return a value.

## Methods

## Objects

**Built-in Objects**

The first thing you need to do is get to know what tools are available.
You can imagine that your new toolkit has three compartments:

- *The Browser Object Model* contains objects that represent the current browser window or tab. It contains objects that model things like browser history and the device's screen.

- *The Document Object Model* uses objects to create a representation of the current page. It creates a new object for each element (and each individual section of text) within the page.

- *The global JavaScript objects* represent things that the JavaScript language needs to create a model of. For example, there is an object that deals only with dates and times.

WHAT DOES THIS SECTION COVER?
**purpose of this section Cover** is

1. What built-in objects are available to you
1. What their main properties and methods do

#### Object Model

:An object model is a group of objects, each of which represent related things from the real world. Together they form a model of something larger


- GLOBAL Object: *String Object*
Whenever you have a value that is a string, you can use the properties and methods of the String object on that value. This example stores the phrase "Home sweet home " in a variable.

DATA TYPES REVISITED
JavaScript have **six data types**

- Five **simple** (or primitive) data types:

1. String
1. Number
1. Boolean
1. Undefined
1. Null

- One **complex** data type:
Object: Under the hood, **arrays** and **functions** are considered types of objects.

**FUNCTIONS** ARE OBJECTS
Technically, functions are also objects. But they have an additional feature: they are callable, which means you can tell the interpreter when you want to execute the statements that it contains.

**ARRAYS** ARE OBJECTS
As you saw on p118, an array is a set of key/value pairs (just like any other object). But you do not specify the name in the key/value pair of an array - it is an index number.

---

- GLOBAL Object: *Number Object*

Whenever you have a value that is a number, you can use the methods and properties of the Number object on it.

COMMONLY USED TERMS:

- An integer is a whole number (not a fraction).
- A real number is a number that can contain a fractional part.
- A floating point number is a real number that uses decimals to represent a fraction. The term floating point refers to the decimal point.
- Scientific notation is a way of writing numbers that are too big or too small to be conveniently written in decimal form. For example: 3,750,000,000 can be represented as 3.75 x109 or 3.75e+12.

---

- GLOBAL Object:*Math Object*

*Property* ``Math.PI``

*Method:*

- ``Math. round()``
- ``Mat h. sqrt (n)``
- ``Math. cei 1 ()``
- ``Ma th. floor()``
- ``Math. random()``

---

- GLOBAL Object:*Data Object(and Times)*

Once you have created a Date object, the following methods let you set and retrieve the time and date that it represents.

- If you want to display the date in another way, you can construct a different date format using the individual methods listed above to represent the individual parts: day, date, month, year.

- A visitor's location may affect time zones and language spoken. Programmers use the term locale to refer to this kind of location-based information.

- The Date object does not store the names of days or months as they vary between languages. Instead, it uses a number from 0 to 6 for the days of the week and 0to11 for the months. To show their names, you need to create an array to hold them.

---

The Math object has properties and methods for mathematical constants and functions.

An object is a series of variables and functions that represent something from the world around you.

In an object, variables are known as properties of the object; functions are known as methods of the object.

Web browsers implement objects that represent both the browser window and the document loaded into the browser window.

JavaScript also has several built-in objects such as String, Number, Math, and Date. Their properties and methods offer functionality that help you write scripts.

Arrays and objects can be used to create complex data sets (and both can contain the other).
