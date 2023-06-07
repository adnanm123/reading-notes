# Learn HTML

## 1. When should you use an `unordered list` in your HTML document?

 Use an unordered list (`<ul>`) in your HTML document when you want to represent a list of items without a specific order or sequence.

## 2. How do you change the `bullet style` of unordered list items?

To change the bullet style of unordered list items, use CSS and the `list-style-type` property.

## 3. When should you use an `ordered list` vs an `unorder list` in your HTML document?

Use an ordered list `<ol>` when you have a list with a specific order or sequence. Use an unordered list `<ul>` when the list items don't have a specific order or sequence.

## 4. Describe two ways you can change the numbers on `list items` provided by an `ordered list`?

1. CSS: Use CSS to change the `list-style-type` property of the ordered list (`<ol>`) to modify the numbering style.

2. Start Attribute: Use the `start` attribute on the `<ol>` tag to specify a different starting value for the numbering.

# Learn CSS

## 1. Describe the CSS properties of `margin` and `padding` as characters in a story. What is their role in a story titled: “The Box Model”?

In the story of "The Box Model," margin is like a friendly spacekeeper that maintains distance between boxes, preventing them from getting too close. On the other hand, padding is like a cozy cushion within the box, providing a comfortable space for the content to reside. Together, they ensure harmony, spacing, and visual structure in the world of web design.

## 2. List and describe the four parts of an HTML elements box as referred to by the `box model`.

1. **Content**: It represents the actual content of the element, such as text, images, or other media.

2. **Padding**: It is the space between the content and the border.

3. **Border**: It is a line or a set of lines that surrounds the content and padding.

4. **Margin**: It is the space outside the border, creating separation between elements.

# Learn JS

## 1. What `data types` can you store inside of an `Array`?

 Strings, numbers, booleans, objects, and others.

## 2. Is the `people` array a valid JavaScript array? If so, how can I access the values stored? If not, why?

Yes the people array is a valid JavaScript array. You can access the values in the area using brackets and the corresponding index down below;

```javascript
const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing'], ['bill', null, 'artist', null]];

// Accessing values
console.log(people[0]); // Output: ['pete', 32, 'librarian', null]
console.log(people[1]); // Output: ['Smith', 40, 'accountant', 'fishing:hiking:rock_climbing']
console.log(people[2]); // Output: ['bill', null, 'artist', null]

console.log(people[0][0]); // Output: 'pete'
console.log(people[1][1]); // Output: 40
console.log(people[2][2]); // Output: 'artist'
```

## 3. List **five** shorthand operators for assignment in javascript and describe what they do.

1. `x -= f()` = This operator subtracts the value on the right side from the variable on the left side and assigns the result to the variable.
2. `x += f()` = This operator adds the value on the right side to the variable on the left side and assigns the result to the variable.
3. `x *= f()` = This operator multiplies the value on the right side with the variable on the left side and assigns the result to the variable.
4. `x /= F()` = This operator divides the variable on the left side by the value on the right side and assigns the result to the variable.
5. `x %= f()` = This operator divides the variable on the left side by the value on the right side and assigns the remainder to the variable.

## 4. Read the code below and evaluate the last `expression` and explain what the result would be and why.

The result of the expression (a + c) + b would be the string '10falsetdog'. 

a + c performs concatenation between the number a (which is coerced to a string) and the boolean c (also coerced to a string). The result is the string '10false'.

The string '10false' is then concatenated with the string 'dog', resulting in the final string '10falsetdog'.

```javascript
 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;
 ```

## 5. Describe a real world example of when a conditional statement should be used in a JavaScript program

A real-world example of when a conditional statement should be used in a JavaScript program is to determine if a user has provided the correct login credentials before granting them access to a website or application.

## 6. Give an example of when a `Loop` is useful in JavaScript

A loop is useful in JavaScript when you need to perform a repetitive task or iterate over a collection of items.
