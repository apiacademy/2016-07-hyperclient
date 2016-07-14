# 2016-07-hyperclient

Content for hypermedia client tutorial for 2016-07 RESTFest UK in Edinburgh

### Agenda

 - 09:00 - 09:15 : What is a Hypermedia client? (slides)
 - 09:15 - 09:30 : Initializing the SPA Client
 - 09:30 - 10:00 : Enabling `title` and `content` elements
 - 10:00 - 10:30 : Enabling `links` elements 
 - 10:30 - 11:30 : Enabling `items` elements 
 - 11:30 - 12:00 : Enabling `queries` elements 
 - 12:00 - 12:30 : Enabling `templates` elements

### The `dom-help.js` Library
The hypermedia client example we'll work on relies on the `dom-help.js` custom library. This library contains short-hand methods for things like HTML DOM manipulation and FORM handling. The library is quite small but reduces the amount of typing needed to generate solid client code.  At the start, it may be a bit difficult to learn the library's functions and arguments but hopefully, but the end of the session, you'll get the hang of it.

In production cases, you'd probably replace `dom-help.js` with JQuery or some other more robust library. I used this simple one to keep the footprint of the app small and reduce the learning curve for a helper lib.

