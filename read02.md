# Query
-------
- jQuery is a lightweight,( write less, do more) JavaScript library, designed to simplify the client-side scripting of HTML
- Query offers a simple way to achieve a variety of common JavaScript tasks quickly and consistently, across all major browsers and without any fallback code needed.
![](https://i.morioh.com/2dbf4a3dc1.png
)
## WHY USE JQUERY?
1. jQuery doesn't do anything you cannot achieve with pure JavaScript.
2. It is just a JavaScript file but estimates show it has been used on over a quarter of the sites on the web, because it makes coding simpler. 
3. it allows you to achieve the same goals but in fewer lines of code than you would need to write with plain JavaScript. 
![](https://images.slideplayer.com/24/7397456/slides/slide_5.jpg)

## LOOPING
With jQuery, when a selector returns multiple elements, you can update all of them using the one method. There is no need to use a loop. 

### GETTING ELEMENT CONTENT 
- The  html() and  text() methods both retrieve and update the content of elements. 

1. html() When this method is used to retrieve information from a jQuery selection, it retrieves only the HTML inside the first element in the matched set.
2. text() When this method is used to retrieve the text from a jQuery selection, it returns the content from every element in the jQuery selection.


## Chaining in jQuery:
If you want to use more than one jQuery method on the same selection of elements, you can list several methods at a time using dot notation to separate each one. The process of placing several methods in the same selector is referred to as chaining. It results in code that is far more compact. $( 'l i [i d!="one"] ') . hide() .delay(SOO) . fadeln(1400);

Getting element content:
.text: content only. .html: content + html code within.

Adding content:
.append, .preappend, before, after.

Updating elements:
.text, .html, .replacewith, .remove.

## WORKING WITH ATTRIBUTES
- The statements in this example use jQuery methods to change the class and i d attributes of the specified HTML elements. 

## jQuery CSS PROPERTIES
The . css () method lets you retrieve and set the values of CSS properties. 

## Including jQuery in file in code:
When a page loads jQuery from a CDN, you will often see a syntax like the one shown below. It starts with a <script> tag that tries to load the jQuery file from the CDN. But note that the URL for the script starts with two forward slashes (not http:). This is known as a protocol relative URL. If the user is looking at the current page through https, then they will not see an error that tells them there are unsecure items on the page. The position of <script> elements can affect how quickly a web page seems to load.

## Plugins in jQuery:
Plugins are scripts that extend the functionality of the jQuery library. Hundreds have been written and are available for you to use. Plugins are written so that new methods extend the jQuery object and can, therefore, be used on a jQuery selection. As long as you know how to do the following with jQuery:



![](https://miro.medium.com/max/728/1*ttjXOopjcC4gi2JYMh8G3w.png)
2. Pair Programming:
- Pair programing is a technique used to foster a collaborative environment while developing key industry skills, and it is used commonly in many agile work environments. pair programming involves two roles:

- Driver: the programmer who is typing and the only one whose hands are on the keyboard. Manages the text editor, switching files, version control, awriting—code.
Navigator: uses their words to guide the Driver but does not provide any direct input to the computer. Using pai programming touches on all four skills (speaking, listening, reading and writing): developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.
The following are reasons why you should do pair programming:

- Greater efficiency.
Engaged collaboration
Learning from fellow students.
Social skills.
Job interview readiness.
Work environment readiness.


-----------------------------


[Table Of Content](https://omarxzain.github.io/301-reading-notes/read02)














