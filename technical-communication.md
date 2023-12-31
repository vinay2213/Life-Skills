# Topic: Browser Rendering

## Context: How does a browser render HTML, CSS, JS to DOM? What is the mechanism behind it?



### Introduction:

When you open a webpage in your browser, have you ever wondered how it transforms HTML, CSS and JavaScript into a visually appealing web page? The process behind this magic is known as browser rendering.


### The Mechanism:

- **HTML Parsing:** The browser starts by parsing the HTML document, reading it from top to bottom. It creates a Document Object Mode (DOM), a tree-like structure that represents the webpage's structure.

- **CSS Styling:** After parsing HTML, the browser processes CSS. It computes the styles for each element and constructs a CSS Object Model (CSSOM).

- **Render Tree Construction:** The browser combines the DOM and CSSOM to create a Render Tree. It contains only the elements that will be visible on the screen.

- **Layout:** The browser calculates the layout, determining the exact position and size of each element on the webpage.

- **Painting:** Finally, it paints the elements on the screen pixel by pixel.
   

### References:

- [How Browsers Work: Behind the scenes of modern web browsers](https://www.html5rocks.com/en/tutorials/internals/howbrowserswork/)

- [The Critical Rendering Path](https://developers.google.com/web/fundamentals/performance/critical-rendering-path)


### Conclusion:

This process ensures that web pages are displayed accurately and efficiently. It's a fascinating journey from code to what we see on our screens.
