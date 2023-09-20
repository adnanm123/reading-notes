# Readings: Express, NPM, TDD, CI/CD

## An introduction to NodeJS and Express

## Explain middleware, answer as though I were a non-technical recruiter.

Middleware is like a helper for web applications. It checks and manages requests from users, ensuring everything works correctly and securely. For example, it can make sure only authorized users access certain parts of a website.

## Express the most popular __ __ ____.

Node.js framework

## Express is “unopinionated.” What does that mean?

Express being "unopinionated" means it doesn't force developers to follow strict rules or conventions when building web applications. It provides flexibility for developers to make their own choices in how they structure and design their code.

## What is a module and why is modularity useful to us as developers?

A module is like a building block of code that does a specific job, and modularity is like organizing these blocks neatly. It helps developers by making code easier to reuse, maintain, and collaborate on. It's like having LEGO pieces that can be put together to create different things without starting from scratch every time.

## What is NPM?

## What version of npm are you running on your machine?

9.8.1

## What command would you type to install a library/package called ‘jshint’ into your node project?

`npm install jshint`

## What is TDD?

## Explain why tests are important. Please explain as though I were your non technical elder

Tests are like quality checks for software, ensuring it works correctly and safely. They save time, help developers communicate, and keep software reliable, like following a good recipe to cook a delicious meal.

## What are three expected benefits of testing

1. **Reliability:** Testing helps ensure that software functions correctly and consistently. It identifies and prevents bugs or errors, making the software more reliable and trustworthy for users.

2. **Quality Assurance:** Testing acts as a quality control measure. It helps maintain a high standard of software quality by catching issues early in the development process, reducing the chances of defects reaching users.

3. **Documentation:** Tests serve as documentation for how the software should behave. They provide clear expectations for developers and serve as a reference point for future changes, making it easier to maintain and improve the software over time.

## Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests

**Individual Pitfalls:**

1. **Overlooking Edge Cases:** Testers may forget to cover edge cases or unusual scenarios in their tests. This can lead to unanticipated issues in real-world usage.

2. **Test Case Duplication:** Sometimes, testers duplicate test cases unintentionally, which can make the test suite harder to maintain and can lead to confusion about which tests cover specific functionality.

**Team Pitfalls:**

1. **Lack of Consistency:** Inconsistent testing practices among team members can lead to confusion. Different naming conventions or testing approaches can make it challenging to understand and maintain the test suite.

2. **Neglecting Collaboration:** Teams may not collaborate effectively on testing, resulting in duplicated efforts or missed testing of critical features. Communication breakdowns can lead to inefficient testing processes.

## CI/CD

## What are three benefits of Continuous Integration?

1. **Early Detection of Issues:** CI automatically integrates code changes from multiple team members into a shared repository and runs automated tests. This helps identify bugs, errors, or conflicts early in the development process, making it easier and less costly to fix issues.

2. **Faster Development Cycles:** CI promotes a faster development pace by automatically building and testing code with every change. This accelerates the development cycle, allowing teams to release new features or updates more frequently and respond to customer needs more rapidly.

3. **Improved Collaboration:** CI encourages collaboration among team members. Developers can work on separate features or components, confident that their changes won't disrupt the overall project. CI systems ensure that changes from different team members integrate smoothly, fostering a more cohesive and efficient development environment.

## What is the difference between Continuos Delivery and Continuous Deployment?

Continuous Delivery (CD) stops at automated testing and requires manual approval for production deployment. Continuous Deployment (CDep) automates everything, including automatically deploying changes to production without manual approval.

## Explain how GitHub fits into this process assuming the listener comes from a non-technical background

GitHub is like a library where computer code is stored and organized. It helps people work together on code, keeps track of changes, and makes sure the code works properly before sharing it with others.
