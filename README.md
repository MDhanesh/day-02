# day-02
Document and Window object


Differences between Document and Window Objects:

Window Object:

*The window object is the topmost object of the DOM hierarchy. It is the root level element in any web page.
* It represents a browser window or frame that displays the contents of the webpage. 
*Whenever a window appears on the screen to display the contents of the document, the window object is created.
* It is the very first object that is loaded in the browser. It is the object of the browser
*Global objects, functions, and variables of JavaScript are members of the window object. All the global variables are defined on the window object.
* The window is part of BOM (browser object model), not DOM (Document object model).
*We can access the window from the window only. i.e. window.window. Properties of the window object cannot be accessed by the document object.

syntax:
            window.propertyname;

Example:
window.innerHeight : will return the height of the content area of the browser.

Properties of the window:
		The properties of Window objects that are commonly used are innerHeight, innerWidth , Name, length, fullScreen ,frames[], Document, etc.
innerHeight: It is used to get the height of the content area of the browser window
innerWidth: It is used to get the width of the content area of the browser window.
Methods of Window:
	The methods defined on the window object are alert(), close(), prompt(), open(),stop(), etc.
alert(): It is used to display an alert box. It displays a specified message along with an OK button and is generally used to make sure that the information comes through the user.
prompt(): It is used to display a dialog with an optional message prompting the user to input some text.


Document Object: 

*The document object represent a web page that is loaded in the browser. 
*By accessing the document object, we can access the element in the HTML page. With the help of document objects, we can add dynamic content to our web page. 
*The document object can be accessed with a window.document or just document.
*It is loaded inside the window. It is the object of window property. All the tags, elements with attributes in HTML are part of the document.
*We can access the document from a window using the window. Document.
*The document is part of BOM (browser object model) and dom (Document object model).
*Properties of document objects such as title, body, cookies, etc can also be accessed by a window like this window. document.title .

Syntax:
            document.propertyname;

Example:  
 document.title :  will return the title of the document

Properties of the Document:
		The properties of Document objects that are commonly used are URL, domain, activeElement, body, charset, etc .
URL: It returns the complete URL of the document.
domain: It returns the domain name of the document server.
body: It returns the content in the body element.

Methods of Document:
	The methods defined on the document object are getElementsByName(), getElementById(), close(), createElement(), createEvent(), etc.
getElementsByName():It returns an object containing all the elements with the specified name in the document as objects.
getElementById():It returns the object of the given ID. If no object with that id exists then it returns null.
createEvent():It is used to create a new events object.
    	




