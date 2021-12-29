# 8-1: Develop an Expand/Collapse Application
In this exercise, you’ll develop an application that displays the first paragraph of text for three topics and then lets the user click a link to expand or collapse the text for each topic.
## Instructions
1. Review the HTML. Note that each topic consists of two div elements followed by an \<a> element. Also, note that a class named “hide” is assigned to the second div element of each topic. Then, review the style rule for this class.
2. In the JavaScript file, add an event handler for the ready() event method.
3. Within the ready() event method, code an event handler for the click() event method of the \<a> elements. This event handler should start by preventing the default action of the link and storing the clicked link in a constant. Then, it should use the toggleClass() method to add or remove the “hide” class from the div element above the link element that’s clicked depending on whether that class is present.
4. Complete the click() event handler by testing if the div element above the current link element has the “hide” class. If it doesn’t, change the text for the link to “Show less”. If it does, change it back to “Show more".