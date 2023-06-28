# dyanmic web pages with JavaScript

[Javascript](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

- compiled programing language with first class functions.
- scripting or programming language that allows you to implement complex features on web pages
- javaScript is a scripting or programming language that allows you to implement complex features on web pages — every time a web page does more than just sit there and display static information for you to look at — displaying timely content updates, interactive maps, animated 2D/3D graphics, scrolling video jukeboxes, etc. — you can bet that JavaScript is probably involved. It is the third layer of the layer cake of standard web technologies, two of which (HTML and CSS) we have covered in much more detail in other parts of the Learning Area.

- [Intro to Javascript](https://code-maven.com/introduction-to-javascript)

- 3 major parts that are distinguish 
    - The language itself. This is fairly standard among the various environments, both in the various browsers and in the various server-side environments.
    - The DOM API - how the language can interact with the various parts of a web page while in the browser. While in this respect the various browsers are getting closer to each other they still differ. Several libraries, most prominently JQuery, is trying to provide a unified API.
    - The server API (or just API) provided by Node.js or one of the other server-side systems.
Editor of IDE
    - any text editor can be used
Embed or Include
    - embed the Javascript code directly inside the Html file
    - In order to do that we add the < script> opening and </ script> closing tags. Between the two we write our JavaScript code.
Input Output 
    - alert function
       - < script language= "javascript">
 - document write
 - console.log 
 
 JavaScript input with prompt and confirm

 - prompt: it will show a pop-up window with the text provided as the first parameter and with a textbox the user can fill in. 

 - confirm:  Calling the confirm() function will show a pop-up window with the provided texts and with two buttons. If the user presses OK the confirm() function will return 
 
 The other pop-up is not really an input method. It allows the developer to ask a Yes/No question. Calling the confirm() function will show a pop-up window with the provided texts and with two buttons. If the user presses OK the confirm() function will return true, if the user presses cancel or hits the ESC key, the function will return false.

Of course in order for this to make more sense you'll have to understand what true and false really mean and what this if - else construct does. If you have programming background then you probably already understand the code, and even if you don't have programming background you might figure out.

That code can basically be translated to the following English sentence:

If confirm returned true, print "Hello World", otherwise print "OK, I won't print it."

Or even better:

If the user presses OK when we asked "Shall I print Hello World?", then print "Hello World", otherwise print "OK, I won't print it."