Lesson Link:

https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-web-development-foundations/tracks/fscj-22-fundamentals-of-css/modules/wdcp-22-learn-css-selectors-and-visual-rules-0507dd23-134e-4011-af2c-a06b06ad53f2/lessons/learn-css-setup-and-syntax/exercises/inline-styles

### SETUP AND SYNTAX

## Inline Styles

Although CSS is a different language than HTML, it’s possible to write CSS code directly within HTML code using inline styles.

To style an HTML element, you can add the style attribute directly to the opening tag. After you add the attribute, you can set it equal to the CSS style(s) you’d like applied to that element.
```
<p style='color: red;'>I'm learning to code!</p>
```
The code in the example above demonstrates how to use inline styling. The paragraph element has a style attribute within its opening tag. Next, the style attribute is set equal to color: red;, which will set the color of the paragraph text to red within the browser.

If you’d like to add more than one style with inline styles, simply keep adding to the style attribute. Make sure to end the styles with a semicolon (;).
```
<p style='color: red; font-size: 20px;'>I'm learning to code!</p>
```
It’s important to know that inline styles are a quick way of directly styling an HTML element, but are rarely used when creating websites. But you may encounter circumstances where inline styling is necessary, so understanding how it works, and recognizing it in HTML code is good knowledge to have. Soon you’ll learn the proper way to add CSS code!


### Instructions
Checkpoint 1 Passed

1. In index.html, use inline styling to set the color of the first paragraph (the first <p> element) to green.

The inline style added to the first paragraph will look like this:
```
<p style="color: green;">

```
