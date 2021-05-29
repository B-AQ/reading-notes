# JS book

*Chapter 3: **Object Literals** (pp.100-105)*

## Object Literals

**Objects:** group together a set of variables and functions to create a model of a something you would recognize from the real world.

**Note:** In an object, variables and functions take on new names.
Variables become known as **Properties**
Function become known as **Methods**, the value of is is called **Key**

---

**Creating an object using literal notation**

``var`` hote l = {name: 'Quay',rooms: 40,booked : 25,

 checkAvailability: function() {
  ``return`` this.rooms - this.booked;
} 
} ; 
 ``var`` el Name = document .getElementByld('hotelName'); elName.textContent =hotel .name;
 ``var`` elRooms = document.getElementByid{'rooms'); elRooms.textContent = hotel .checkAvailability();



**CREATING MORE OBJECT LITERALS**

``var`` hotel = {name: 'Park',rooms: 120,booked : 77,

  checkAvailabi lity: function() {

   ``return`` this.rooms - this.booked;

}

};
 ``var`` elName = document .getElementByid('hotelName') ;
 elName .textContent =hotel .name ;

 ``var`` el Rooms = document .getElementByid( 'rooms') ;*
 *e 1 Rooms . text Content = hote 1 . checkAvai l abi lity();*

 ---

*Chapter 5: **Document Object Model** (pp.183-242)*

## The Document Object Model (DOM)

 :specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

- **Attribute nodes:** The opening tags of HTML elements can carry attributes and these are represented by attribute nodes in the DOM tree.

- **Text nodes:** Once you have accessed an element node, you can then reach the text within that element. This is stored in its own text node.



Accessing and updating the DOM tree involves **two steps:**

Step One

- Access the elements:(select an individual element node, select multiple elements nodelists,traversing between elements nodes).

Step Two

- Work with those elements: (access/update text nodes,work html content,access or update attribute values).

- Locate the node that represents the element you want to work with.
- Use its text content, child elements, and attributes.

When a DOM method can return more than one element, it returns a Nodelist (even if it only finds one matching element).

**Looping through a Nodelist:**
It involves finding out how many items are in the Nodelist, and then setting a counter to loop through them, one-by-one.Each time the loop runs, the script checks that the counter is less than the total number of items in the Nodelist. 

**Traversing the DOM.**

- When you have an element node, you can select another element in relation to it using these five properties. This is known as traversing the DOM.

**Whitespace NODES**

- Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements.

ADDING ELEMENTS USING DOM MANIPULATION
DOM manipulation offers another technique to add new content to a page (rather than i nnerHTML).
It involves three steps:

- CREATE THE ELEMENT ``createEl ement ()``
- GIVE IT CONTENT ``createTextNode()``
- ADD IT TO THE DOM ``appendChild()``

REMOVING ELEMENTS VIA DOM MANIPULATION
DOM manipulation can be used to remove elements from the DOM tree.

- STORE THE ELEMENT TO BE REMOVED IN A VARIABLE
- STORE THE PARENT OF THAT ELEMENT IN A VARIABLE
- REMOVE THE ELEMENT FROM ITS CONTA INING ELEMENT


||eZement.innerHTML | DOM Manipulation |
|------|-------|-----------|
|Advantages|You can use it to add a lot of new markup using less code than DOM manipulation methods.|It is suited to changing one element from a DOM fragment where there are many siblings. |
|Advantages|It can be faster than DOM manipulation when adding a lot of new elements to a web page.|It does not affect event handlers. |
|Advantages|It is a simple way to remove all of the content from one element (by assigning it a blank string)|It easily allows a script to add elements incrementally (when you do not want to alter a lot of code at once)|
|Disadvantages| It should not be used to add content that has come from a user (such as a username or blog comment), as it can pose a significant security risk which is discussed over the next four pages.| If you have to make a lot of changes to the content of a page, it is slower than i nnerHTML.|
|Disadvantages|Event handlers may no longer work as intended. | You need to write more code to achieve the same thing compared with i nnerHTML.|
|Disadvantages|It can be difficult to isolate single elements that you want to update within a larger DOM fragment.|

---

**Cross-Site Scripting Attacks or (XSS)**

If you add HTML to a page using i nnerHTML (or several jQuery methods), you need to be aware of Cross-Site Scripting Attacks or XSS; otherwise, an attacker could gain access to your users' accounts.


**How XSS Happens?**

- XSS involves an attacker placing malicious code into a site. Websites often feature content created by many different people. For example: The browser represents the page using a DOM tree.

---
XSS can give the attacker access to information in:

- The DOM (including form data)
- That website's cookies
- Session tokens: information that identifies youfrom other users when you log into a site

This could let the attacker access a user account and:

- Make purchases with that account
- Post defamatory content
- Spread their malicious code further I faster

---

DOM trees have four types of nodes: document nodes,element nodes, attribute nodes, and text nodes.
You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax.
Whenever a DOM query can return more than one node, it will always return a Nadel i st.
From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques.
An element node can contain multiple text nodes and child elements that are siblings of each other.
In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery) Browsers offer tools for viewing the DOM tree.
