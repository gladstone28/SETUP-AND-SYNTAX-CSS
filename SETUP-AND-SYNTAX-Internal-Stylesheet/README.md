Lesson link:

https://www.codecademy.com/journeys/full-stack-engineer/paths/fscj-22-web-development-foundations/tracks/fscj-22-fundamentals-of-css/modules/wdcp-22-learn-css-selectors-and-visual-rules-0507dd23-134e-4011-af2c-a06b06ad53f2/lessons/learn-css-setup-and-syntax/exercises/internal-stylesheet

### SETUP AND SYNTAX

## Internal Stylesheet

As previously stated, inline styles are not the best way to style HTML elements. If you wanted to style, for example, multiple *h1* elements, you would have to add inline styling to each element manually. In addition, you would also have to maintain the HTML code when additional *h1* elements are added.

Fortunately, HTML allows you to write CSS code in its own dedicated section with a *style* element nested inside of the *head* element. The CSS code inside the *style* element is often referred to as an internal stylesheet.

An internal stylesheet has certain benefits and use cases over inlines styles, but once again, it’s not best practice (we’ll get there, we promise). Understanding how to use internal stylesheets is nonetheless helpful knowledge to have.

To create an internal stylesheet, a *style* element must be placed inside of the *head* element.

```
<head>
  <style>


  </style>
</head>
```
After adding opening and closing <style> tags in the head section, you can begin writing CSS code.
```
<head>
  <style>
    p {
      color: red;
      font-size: 20px;
    }
  </style>
</head>
```

The CSS code in the example above changes the color of all paragraph text to red and also changes the size of the text to 20 pixels. Note how the syntax of the CSS code matches (for the most part) the syntax you used for inline styling. The main difference is that you can specify which elements to apply the styling.

### Instructions
Checkpoint 1 Passed
1. Let’s move the inline style that was added to the paragraph into an internal stylesheet.

Start by adding an empty <style> element in the head of index.html.

Place the empty <style> element below the <title> element in index.html. Be sure to include the opening and closing tags.

Checkpoint 2 Passed
2. Inside of the <style> element, add a CSS ruleset targeting the paragraph (the <p> element). You can leave the declaration block empty for now.

An empty ruleset looks like this:
```
selector {

}
```
The declaration block is the code that goes inside of (and includes) the curly braces.

Checkpoint 3 Passed
3. Next, place just the declaration from the inline style into the empty declaration block in the inline stylesheet.

Remember that the declaration syntax is property: value;, and goes inside of the declaration block.

selector {
  declaration
}

Checkpoint 4 Passed
4. Finally, delete the inline style from the <p> element.

Notice how the styling works the same in the stylesheet as it did in the inline style!

The inline style starts with the style attribute, and ends with the ' after the declaration.
```
style='color: green;'

```
