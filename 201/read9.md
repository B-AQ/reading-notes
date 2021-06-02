
# HTML book

*Chapter 7: **Forms** (p.144-175)*

## Forms

The best known form on the web is probably the search box that sits right in the middle of Google's homepage.

- **Form Controls**

There are several types of form controls that you can use to collect information from visitors to your site:

1. Adding Text
1. Making Choices
1. Submitting Forms
1. Uploading Files

- **Form Structure**

``<form action=http www.example.com/subscribe.php``

- Whenever you want to collect information from visitors you will need a form, which lives inside a ``<form>`` element.

- Information from a form is sent in name/value pairs.

- Each form control is given a name, and the text the user types in or the values of the options they select are sent to the server.

- HTML5 introduces new form elements which make it easier for visitors to fill in forms.





# JS book

*Chapter 14: **Lists, Tables & Forms** (pp.330-357)*

## Lists

Event object

Every event handling function receives an event object. It has methods and properties related to the event that occurred.

1. Give the event object a parameter name.
1. Use that name in the function to reference the event object.
1. Access the properties and methods of the object using the familiar
dot notation (the member operator).

PROPERTY| DESCRIPTION|
|---|---|
|type|Type of event, (e.g., click, mouseover)|
|which|Button or key that was pressed |
|data|An object literal containing extra information passed to the function when the event fire (See right-hand page for an example)|
|target|DOM element that initiated the event |
|pageX|Mouse position from left edge of viewport |
|pageY|Mouse position from top of viewport|
|timeStamp|Number of milliseconds from Jan 1st, 1970, to when the event was triggered (this is known as Unix Time). Does not work in Firefox. |

---

|METHOD|DESCRIPTION|
|---|---|
|preventOef au 1 t ()|Prevents the default (e.g., submitting a form)|
|stopPropagati on()|Stops the event bubbling up to ancestors|

*ADDITIONAL PARAMETERS FOR EVENT HANDLERS*

Here you can see two additional properties that can be used with the • on() method.

- This is the event(s) that you want to respond to. If you want to respond to more than one event, you can provide a spaceseparated list of event names, e.g., 'focus click ' will work on both focus and click .

- If you just want to respond to the event happening on a subset of the elements in the initial jQuery selection, you can provide a second selector that will filter its descendants.

- You can pass extra information to the function that is called when the event is triggered. This information is passed along with the event object (e).

- This is the function that should be run when the specified events occur on one of the elements in the matched set.

- The function is automatically passed the event object as a parameter, as you saw on the previous two pages. (Remember, if you use it you must give it a name in the parentheses.)

**EFFECTS**

When you start using jQuery, the effects methods can enhance your web page with transitions and movement.

BASIC EFFECTS:

``.show ()`` Displays selected elements.

``.hi de()`` Hides selected elements.

``. togg 1 e ()`` Toggles between showing and hiding selected elements.

FADING EFFECTS:

``. fadeln()`` Fades in selected elements making them opaque.

``. fadeout()`` Fades out selected elements making them transparent.

``. fade To()`` Changes opacity of selected elements.

``. fade Togg 1 e ()`` Hides or shows selected elements by changing their opacity (the opposite of their current state).

SLIDING EFFECTS

``. s l i deUp ()`` Shows selected elements with a sliding motion.

``. s 1 i de Down()`` Hides selected elements with a sliding motion.

``. s 1 i deToggl e()`` Hides or shows selected elements with a slidingmotion (in the opposite direction to its current state).

CUSTOM EFFECTS

``.delay()`` Delays execution of subsequent items in queue.

``. stop()`` Stops an animation if it is currently running.

``. animate()`` Creates custom animations.

---

**ANIMATING CSS PROPERTIES**

The .animate() method allows you to create some of your own effects and animations by changing CSS properties.



## Tables & Forms

**SELECTORS FOR FORM ELEMENTS**

|SELECTOR|DESCRIPTION|
|---|---|
|button |``<button> and <input>`` elements whose type attribute has a value of button|
|checkbox| ``<input>`` elements whose type attribute has a value of checkbox. Note that you get better performance with $('(type="checkbox"]')|
|checked| Checked elements from checkboxes and radio buttons (see : selected for select boxes)
|disabled |All elements that have been disabled|
|enabled |All elements that are enabled|
|focus |Element that currently has focus. Note that you get better performance with$ (document. acti veEl ement)|
|file |All elements that are file inputs|
|image|All image inputs. Note that you get better performance using (type=11 image"]|
|input|All ``<button>, <input>. <select>, and <texta rea>`` elements. Note that you get better performance from selecting elements, then using • filter ( 11 : input 11 )|
|password| All password inputs. Note that you get better performance using$ ('input: password')|
|radio|All radio inputs. To select a group of radio buttons, you can use$(' input (name="gender"] : radio')|
|reset|All inputs that are reset buttons|
|selected| All elements that are selected. Note that you get better performance using a CSS selector inside the • filter()method, e.g .. . filter(": selected")|
|submit| ``<button> and <input>`` elements whose type attributehas a value of submit. Note that you will get better performance using (type=" submit"]|
|text| Selects ``<input>`` elements with a type attribute whose value is text, or whose type attribute is not present. You will likely get better performance from ('input: text')|
