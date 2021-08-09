# Object Literals
Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. In an object,variables and functions take on new names.
## IN AN OBJECT: VARIABLES BECOME
### KNOWN AS PROPERTIES
If a variable is part of an object, it is called a
property. Properties te ll us about the object.
## IN AN OBJECT: FUNCTIONS BECOME
### KNOWN AS METHODS
If a function is part of an object, it is called a method.
Methods represent tasks that are associated with
the object.

# CREATING· OBJECTS USING LITERAL NOTATION

`var hotel = {`

`name: 'Quay',`

`rooms : 40,`

`booked: 25,`

`checkAvailability: function() {`

`return this.rooms - this.booked;`

`}`

`} ;`

`var elName = document .getElementByld('hotelName');`

`elName.textContent =hotel .name;`

`var elRooms = document.getElementByid{'rooms');`

`elRooms .textContent = hotel .checkAvailability();`


# about Documents objects model

specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.

# How to caching DOM queries?
Queries are the methods that find elements in DOM and if we need to use an element multiple times we should store queries result in a variable. What we actually do we store element in a variable that we store the location of that element in the DOM tree.

DOM models are stored in the browsers memory

DOMs have four different nodes:

`Document Node`

`Element Node`

`Attribute Node`

`Text Node`

Each node is an object with properties and methods.

# Summary

* The browser represents the page using a DOM tree. DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.

* You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax. Whenever a DOM query can return more than one node, it will always return a Nadel i st.

* From an element node, you can access and update its content using properties such as textContent and i nnerHTML or using DOM manipulation techniques.

* An element node can contain multiple text nodes and child elements that are siblings of each other.

* In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery). 