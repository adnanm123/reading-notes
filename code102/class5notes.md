# Notes on Design web pages with CSS

## 1. What is the purpose of CSS?

CSS (Cascading Style Sheets) is a programming language used for styling web documents. Its main purpose is to separate the presentation and layout of HTML elements from the actual content. By defining styles in a CSS file, web developers can ensure consistent visual formatting across multiple pages or an entire website. CSS allows for flexible layout control, responsive design, and enhanced user experiences through interactive elements and visual effects. It also promotes web accessibility by providing customization options for improved readability. In summary, CSS is essential for creating visually appealing, well-structured, and user-friendly web pages and applications.

## 2. What are the three ways to insert CSS into your project?

1. Inline CSS: Styles are applied directly to individual HTML elements using the style attribute. It is useful for applying unique styles to specific elements but can become unwieldy when used extensively.

2. Internal CSS is defined within style tags in the head section of an HTML document. It affects the styles of elements within the same HTML file. With internal CSS, you can define styles for multiple elements in a single file, simplifying the management and organization of styles within the HTML document itself.

3. External CSS: Styles are written in a separate CSS file and linked to the HTML document using the link element. The CSS file contains all the styles to be applied to the HTML elements. External CSS allows for the separation of concerns, making it easier to maintain and reuse styles across multiple HTML files in larger projects.

## 3. Write an example of a CSS rule that would give all <p> elements red text.

- p {
  color: red;
}