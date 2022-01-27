# Designing Web Pages with CSS

CSS or Cascading Style Sheet is a style sheet language that allows you to make your website more visual pleasing. The syntax of CSS if different than html, but it's quite simple if you know how html is structured. If you wanted to make a h1 header element display as green you would use this syntax:

`h1 {`
    `color: green;`
`}`

Syntax breakdown:

1. Selector `h1`
2. Opening Bracket `{`
3. Declaration `color: green;`

    - Property `color`
    - Value `green`
    - Semi-colon `;`

4. Closing Braket `}`

There are different types of modules that languages is structured around. This basically means that like properties are group together. CSS is upkept by the CSS Working Group. They update it as needed for a many resons. This group is very careful not to update CSS in a way that would cause websites built before the update to break. Be careful! When CSS is update, the browsers don't adopt that update all at the same time. MDN provides a list of browsers compatable with CSS properties.

There are three ways to apply CSS:

1. Exernal CSS
2. Internal CSS
3. Inline CSS

An exernal CSS file should be save with .css. An exernal style sheet allows you to change many elements on the html page while only editing one file.
Internal CSS is put inside of the `<style>` tag that is within the `<head>` tag.
Inline CSS allows you to change only one elment inside the html file. Put `style= "color: green;` inside of a `<p>` opening tag and the element will be styled.
CSS stylesheet types have an order of operations or authority:

1. Inline CSS
2. External and Internal CSS
3. Browser Default

The `color` property will change the color of text. There are a few differnt ways to select a color. Reset CSS is a file that sets css properties to a certain value so the website can look the same across browsers.
