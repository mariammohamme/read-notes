 JS Object Literals; The DOM
 ### when we want calling function we to need information like parameter you specify the value you want put in pranthess that flow this name 
 ## we can used arguent lik :
 - value ex: sum(2,5)
 -varibel ex : 
 var x=4 ;
 var y=5;
 sum=x+y;
 total(x,y,sum)
 ### function can return multible value using array 
 -----------
 ### ANONYMOUS FUNCTIONS & FUNCTION EXPRESSIONS :
 ------------
- Expressions produce a value. They can be used where values are expected. If a function is placed where a browser expects to see an expression, (e.g., as an argument to a function), then it gets treated as an expression
- function declaration: creates a function that you can call later in your code. It is the type of function
you have seen so far in this book. 
- IMMEDIATELY INVOKED FUNCTION EXPRESSIONS (llFE): Pronounced "iffy," these functions are not given a name. Instead, they are executed once as the interpreter comes across them.
-  hey are used for code that only needs to run once
within a task, rather than repeatedly being called by
other parts of the script. For example:
• As an argument when a function is called (to calculate a value for that function).
• To assign the value of a property to an object.
• In event handlers and listeners  to perform a task when an event occurs.
• To prevent conflicts between two scripts that might use the same variable names
### scope. :
--------------------
 The location where you declare a variable will affect where it can be used within your code. If you declare it within a function, it can only be used within that function. This is known as the variable's 
### LOCAL VARIABLES :
-------------
 When a variable is created inside a function using the var keyword, it can only be used in that function.
### GLOBAL VARIABLES:
-------------
If you create a variable outside of a function, then it can be used anywhere within the script. It is called a global variable and has global scope. In the example shown, wa 11 Size is a global variable.
###  Document Object Model (DOM) :
----------------
specifies how browsers should create a model of an HTML page and how JavaScript can access and update the
contents of a web page while it is in the browser window.
### MAKING A MODEL OF THE HTML PAGE
-----------------
When the browser loads a web page, it creates a model of the page in memory. 
### why  DOM is called an object model
--------------
because the model (the DOM tree) is made of objects. 
### model is called a DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes. 
### Each node is an object with methods and properties.
### Scripts access and update this DOM tree (not the source HTML file). Any changes made to the DOM tree are reflected in the browser. 
### Attribute nodes are not children of the element thar carries them; they are part of that element.
### Text nodes cannot have children. If an element contains text and another child element, the child element is not a child of the text node but rather a child of the containing element
### ACCESSING ELEMENTS
---------
### DOM queries may return one element, or they may return a Nodelist, which is a collection of nodes. 
NODELISTS: DOM QUERIES THAT RETURN MORE THAN ONE ELEMENT
- The browser represents the page using a DOM tree.
- DOM trees have four types of nodes: document nodes, element nodes, attribute nodes, and text nodes.
- You can select element nodes by their id or cl ass attributes, by tag name, or using CSS selector syntax.
- Whenever a DOM query can return more than one node, it will always return a Nadel i st.
- From an element node, you can access and update its content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.
- An element node can contain multiple text nodes and child elements that are siblings of each other.
- In older browsers, implementation of the DOM is inconsistent (and is a popular reason for using jQuery).
Browsers offer tools for viewing the DOM tree .