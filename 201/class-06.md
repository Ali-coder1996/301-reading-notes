# object

**WHAT IS AN OBJECT?**

- Objects group together a set of variables and functions to create a model
  of a something you would recognize from the real world. In an object,
  variables and functions take on new names.

- **IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES**
  If a variable is part of an object, it is called a
  property. Properties tell us about the object, such as
  the name of a hotel or the number of rooms it has.
  Each individual hotel might have a different name
  and a different number of rooms.

- **IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS**
  If a function is part of an object, it is called a method.
  Methods represent tasks that are associated with
  the object. For example, you can check how many
  rooms are available by subtracting the number of
  booked rooms from the total number of rooms.

**This object represents a hotel. It has five properties and one method. The object is in curly braces. It is stored in a variable called hotel .**

![object](https://miro.medium.com/max/1964/1*FV5pGUFrVhshmxQI9WdsuA.png)

## The Document Object Model

- The Document Object Model (DOM) specifies
  how browsers should create a model of an HTML
  page and how JavaScript can access and update the
  contents of a web page while it is in the browser window.

![DOM tree](https://snipcademy.com/img/articles/javascript-document-object-model/dom.svg)

**ACCESSING ELEMENTS:**

- getElementByld(id)

- querySel ector(css selector)

**METHODS THAT RETURN ONE OR MORE ELEMENTS (AS A NODELIST):**

1- getEl ement sByClassName(class)

2- getEl ementsByTagName(tagName)

3- querySelectorAll ( css select)

> summary

1- The browser represents the page using a DOM tree.

2- DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes.

3-You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax.

4- Whenever a DOM query can return more than one
node, it will always return a Nadel i st.

5- From an element node, you can access and update its
content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.

6- An element node can contain multiple text nodes and
child elements that are siblings of each other.

7- In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).
Browsers offer tools for viewing the DOM tree .
