Lesson link:

https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-web-development-foundations/tracks/fscj-22-fundamentals-of-css/modules/wdcp-22-learn-css-selectors-and-visual-rules-0507dd23-134e-4011-af2c-a06b06ad53f2/lessons/learn-css-setup-and-syntax/exercises/linking-the-css-file


### SETUP AND SYNTAX

## Linking the CSS File

Perfect! We successfully separated structure (HTML) from styling (CSS), but the web page still looks bland. Why?

When HTML and CSS codes are in separate files, the files must be linked. Otherwise, the HTML file won’t be able to locate the CSS code, and the styling will not be applied.

You can use the <link> element to link HTML and CSS files together. The <link> element must be placed within the head of the HTML file. It is a self-closing tag and requires the following attributes:

href — like the anchor element, the value of this attribute must be the address, or path, to the CSS file.
rel — this attribute describes the relationship between the HTML file and the CSS file. Because you are linking to a stylesheet, the value should be set to stylesheet.
When linking an HTML file and a CSS file together, the <link> element will look like the following:
```
<link href='https://www.codecademy.com/stylesheets/style.css' rel='stylesheet'>
```
Note that in the example above, the path to the stylesheet is a URL:

https://www.codecademy.com/stylesheets/style.css

Specifying the path to the stylesheet using a URL is one way of linking a stylesheet.

If the CSS file is stored in the same directory as your HTML file, then you can specify a relative path instead of a URL, like so:
```
<link href='./style.css' rel='stylesheet'>
```
Using a relative path is very common way of linking a stylesheet.
