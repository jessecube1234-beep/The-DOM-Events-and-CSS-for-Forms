# The-DOM-Events-and-CSS-for-Forms

## JavaScript HTML DOM EventListener

1. Syntax: What are the three parameters (arguments) of the addEventListener method?

   type of the event, the function we want to call when the event occurs, and a boolean value that determines whether to use event bubbling or event capturing

2. How do you remove an event listener from an element? "removeEventListener()"

   for event handlers attached with "addEventListener()"

## HTML DOM Events

Find three types of event, other than click that you would like to learn more about. Why do they interest you? (1 sentence per event.)

touchstart

Because smartphones are everywhere, and I can see where this could be very applicable in creating apps and gui's on touch devices.

keyup

I remember using keydown and keypress to control our sprites in level one. Im pretty sure we never used keyup. It would be interesting to see what this DOM event would be applicable for.

wheel

On my mouse I use this feature all the time. Im interested in it because I see it's used across the web.






## What is the DOM?

1. What are four things the DOM defines? 

    The HTML elements as objects
    The properties of all HTML elements
    The methods to access all HTML elements
    The events for all HTML elements


2. How can you attach an "inline event handler" to an element?

   You can do it directly in html and you add the event attribute directly into the tag for the element
   
3. In the video, what did the function handleBoxClick do in the program?

   This function is going to do the job of handling the box click

4. How would you find the x, y coordinates of a mouse click using an Event Object?

   First you use an event object within your code (function (e)). Then you go into your browser, open dev tools and go to console. Once you have that you can click on the area you need the xy coordinates for.
 
5. There is a subtle difference between using Standard vs. Arrow Functions in event listeners. What does this refer to in the context of a function used as an Event Handler?

   Standard: (function (e)) refers to the actual element itself 

   Arrow: e => Refers to the whole global window object itself

7. What are the classes that were used to center the div horizontally and vertically?

   Bootstrap

   Horizontally:

   by using a container div and making it a flex container and justifying it to center horiz.
   
   ```
   <div class="container d-flex justify-content-center">
   ```

   Horizontally & Vertically:

   ```
   <div class="container min-vh-100 d-flex justify-content-center align-items-center">
   
8. What does the number at the end of the col-* class name mean? (For example, what does the 8 at the end of col-md-8 mean?)

   It means it will take up the space of 8 of the 12 columns on bootstrap 5 (2/3)


