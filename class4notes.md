# Class 4 notes

## Wireframe

- wire frame is a blue print to starting your webpage design

- can be done by drawing on paper or utilizing websites as google drawing, Adobe, Miro, etc.

### Mozilla HTML Basics

- HyperText Markup Language is the code that is used to structure a web page and its content. For example, content could be structured within a set of paragraphs, a list of bulleted points, or using images and data tables.

- HTML is a markup language that defines the structure of your content. HTML consists of a series of elements, which you use to enclose, or wrap, different parts of the content to make it appear a certain way, or act a certain way. The enclosing tags can make a word or image hyperlink to somewhere else, can italicize words, can make the font bigger or smaller

- The main parts of our element are as follows:

1. The opening tag: This consists of the name of the element (in this case, p), wrapped in opening and closing angle brackets. This states where the element begins or starts to take effect — in this case where the paragraph begins.

2. The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends — in this case where the paragraph ends. Failing to add a closing tag is one of the standard beginner errors and can lead to strange results.
3. The content: This is the content of the element, which in this case, is just text.
4. The element: The opening tag, the closing tag, and the content together comprise the element.

- Images

1. `<img>` element it embeds an image into our page in the position it appears. It does this via the `src` (source) attribute, which contains the path to our image file.

-Note: Anything in HTML between <!-- and --> is an HTML comment. The browser ignores comments as it renders the code. In other words, they are not visible on the page - just in the code. HTML comments are a way for you to write helpful notes about your code or logic.

- Paragraphs

1. As explained above, `<p>` elements are for containing paragraphs of text; you'll use these frequently when marking up regular text content

- Links

1. Links are very important — they are what makes the web a web! To add a link, we need to use a simple element — `<a>` — "a" being the short form for "anchor". To make text within your paragraph into a link, follow these steps:

2. Choose some text. We chose the text "Mozilla Manifesto".
Wrap the text in an `<a>` element

