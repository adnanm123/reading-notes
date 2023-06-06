# Introduction to HTML

## 1. Why is it important to use semantic elements in our HTML?

1. It makes your website more **accessible** to people with disabilities.
2. It helps **search engines** understand and rank your content better.
3. It makes your code easier to **maintain and collaborate** on.
4. It promotes **consistency and readability**.
5. It ensures **compatibility** with future HTML standards.

## 2. How many levels of headings are there in HTML?

In HTML, there are six levels of headings represented by `<h1>` to `<h6>` tags.

## 3. What are some uses for the `<sup>` and `<sub>` elements?

The `<sup>` element is used for superscript text (raised above the regular line), while the `<sub>` element is used for subscript text (lowered below the regular line). They are commonly used for mathematical notations, chemical formulas, footnotes, and abbreviations.

## 4. When using the `<abbr>` element, what attribute must be added to provide the full expansion of the term?

The title attribute must be added to the `<abbr>` element to provide the full expansion of the term.

# Learn CSS

## 1. What are ways we can apply CSS to our HTML?

1. **Inline styles**: Applying styles directly to HTML elements using the `style` attribute.
2. **Internal stylesheets**: Defining styles within the `<style>` tags in the HTML document's `<head>` section.
3. **External stylesheets**: Creating a separate CSS file and linking it to the HTML document using the `<link>` tag.

## 2. Why should we avoid using inline styles?

Inline styles should be avoided because they mix presentation with content, reduce reusability, have high specificity, hinder code readability and debugging, and make maintainability challenging. It is better to use external or internal stylesheets to separate styling from HTML content.

## 3. Review the block of code below and answer the following questions:

1. What is representing the selector?

   Selector: `h2`

2. Which components are the CSS declarations?

   CSS Declarations: `color: black;` and `padding: 5px;`

3. Which components are considered properties?

   Properties: `color` and `padding`

```css
h2 {
  color: black;
  padding: 5px;
}
```

# Learn JS

## 1. What data type is a sequence of text enclosed in single quote marks?

A sequence of text enclosed in single quote marks represents a string data type.

## 2. List 4 types of JavaScript operators

1. **Arithmetic operators**: Perform mathematical calculations.
2. **Assignment operators**: Assign values to variables.
3. **Comparison operators**: Compare values and return boolean results.
4. **Logical operators**: Combine and manipulate boolean values.

## 3. Describe a real world Problem you could solve with a Function

A real-world problem that can be solved with a function is calculating the total cost of a shopping cart in an online store.

# Making Decisions In Your Code – Conditionals

## 1. An if statement checks a __ and if it evaluates to ___, then the code block will execute

An if statement checks a condition, and if it evaluates to true, then the code block will execute.

## 2. What is the use of an `else if`?

The `else if` statement is used to specify additional conditions to check in an if-else control structure. It allows for sequential evaluation of multiple conditions and executing different code blocks based on the first true condition encountered.

## 3. List 3 different types of comparison operators

1. Equal to (==): Checks if two values are equal.
2. Not equal to (!=): Checks if two values are not equal.
3. Greater than (>): Checks if the left operand is greater than the right operand.

## 4. What is the difference between the logical operator `&&` and `||`?

The `&&` (AND) operator returns `true` if both expressions are `true`, while the `||` (OR) operator returns `true` if at least one of the expressions is `true`.
