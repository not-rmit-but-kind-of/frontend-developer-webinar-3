# DEV102 Expert Webinar 03 Javascript Code Walkthrough

## Introductions - David and Ben
## House keeping 
  - Please mute your microphone unless talking.
  - Ask questions whenever, via zoom messaging or voice. Will do a Q&A at the end as well and then obviously you can ask questions on slack.
## Disclaimer ;)  
  
## Agenda 

1. ECMAScript or ES for short (specification)
    - Created to standardise JavaScript
    - JavaScript is an implementation of this specification
    - ES5, ES6/ES2015, ES2016, ES2017, ES2018 and ES.Next (dynamic referring next version)

2. NodeJS (V8 from Chrome)  

3. Form submission example

4. Event listeners

5. Changing style of element via JavaScript

6. Script tag
    - Scripts without async, defer or type="module" attributes, as well as inline scripts, are fetched and executed immediately, before the browser continues to parse the page.
    - External libraries  
    - Modules (https://hacks.mozilla.org/2015/08/es6-in-depth-modules/)
      - Modules are singleton. They will be loaded and executed only once.
      - Modules can use import and export.
      - Modules are always executed in strict mode.
      - All objects (class, const, function, let or var) are private unless explicitly exported.
      - The value of "this" is undefined at the outer scope (not window).
      - Modules are loaded asynchronously.

7. Debugging
    - Debug via the browser
    - Debug directly on your mobile to get a real feel for touch based interaction (didn't get chance to cover last time)  
      
      