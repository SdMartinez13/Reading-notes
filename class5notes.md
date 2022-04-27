# Class  5 notes

**Design web pages with CSS**

>How to add CSS

- 3 ways to insert CSS

1. external CSS

+ With an external style sheet, you can change the look of an entire website by changing just one file!  Each HTML page must include a reference to the external style sheet file inside the `<link>` element, inside the head section

2. internal CSS

+ An internal style sheet may be used if one single HTML page has a unique style. The internal style is defined inside the `<style>` element, inside the head section.


3. inline CSS

+ An inline style may be used to apply a unique style for a single element.  To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

>Multiple Style Sheets

- If some properties have been defined for the same selector (element) in different style sheets, the value from the last read style sheet will be used.

>cascading order

- What style will be used when there is more than one style specified for an HTML element?
All the styles in a page will "cascade" into a new "virtual" style sheet by the following rules, where number one has the highest priority:

1. Inline style (inside an HTML element)
2. External and internal style sheets (in the head section)
3. Browser default
So, an inline style has the highest priority, and will override external and internal styles and browser defaults.

**CSS Syntax**

-`color: color|initial|inherant;`

>property values

+ color-Specifies the text color. Look at CSS Color Values for a complete list of possible color values.

+ initial-Sets this property to its default value

+ inherit-Inherits this property from its parent element.  

>examples

1. Set the text color with a HEX value:
`body {color: #92a8d1;}`

2. Set the text color with an RGB value:
`body {color: rgb(201, 76, 76);}`

3. Set the text color with an RGBA value:
`body {color: rgba(201, 76, 76, 0.6);}`

4. Set the text color with a HSLA value:
`body {color: hsla(89, 43%, 51%, 0.6);}`

**CSS Reference**

<a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Reference">link to long list of references</a>

