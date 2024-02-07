# Automated Testing
Automated testing in React involves using tools and frameworks to automate the process of verifying the correctness and functionality of your React applications. These tests are written as code and executed automatically, allowing developers to quickly identify bugs, regressions, or unintended behavior as they make changes to the codebase. In a nutshell, automated testing is simply __writing code to test code__.

# Types

a) **Unit testing** 

This involves testing individual units or components of your React application in isolation. These units can be functions, modules, or React components.
In React, unit testing often focuses on testing individual components, ensuring that they render correctly, handle props and state appropriately, and emit the expected output based on various scenarios.
Unit tests are typically fast to execute and provide rapid feedback on the correctness of specific units of code.

b) **Integration Testing**

Integration testing involves testing the interaction between multiple units or components within your React application.
In React, integration testing might involve testing how different components interact with each other, how data flows between parent and child components, or how components integrate with external services or APIs.
Integration tests help ensure that different parts of the application work together seamlessly and that changes in one component do not adversely affect the behavior of other components.

c) **End-to-End (E2E) Testing**:

End-to-end testing involves testing the entire application from the user's perspective, simulating real user interactions with the application.
In React, E2E tests typically involve automating interactions with the application's UI, such as clicking buttons, entering text into input fields, and navigating between pages.
E2E tests help ensure that the application functions correctly as a whole, including its UI, user flows, and interactions with external dependencies.
Tools like Selenium, Cypress, and Puppeteer are commonly used for writing and executing end-to-end tests in React applications.

# Screenshots
![TestRun](https://github.com/IanKaire/ReactTesting/assets/114652346/8dd023b5-c506-480e-9f12-4d2be333b04b)


# Dependencies Used
For this project I simply use Jest, the javascript testing framework

1. **@testing-library/jest-dom**:
   - This library provides custom Jest matchers for asserting on DOM elements.
   - It enhances Jest's built-in assertions by providing additional matchers specifically tailored for testing React components.
   - With @testing-library/jest-dom, you can write more expressive and readable test assertions for DOM elements, such as checking for element visibility, content, attributes, and more.

2. **@testing-library/react**:
   - This library provides utilities for testing React components in a way that simulates how users interact with the application.
   - It offers functions like `render`, `screen`, and `fireEvent` for rendering components, querying DOM elements, and simulating user events, respectively.
   - @testing-library/react encourages writing tests that focus on the behavior of components from the user's perspective rather than testing implementation details, resulting in more maintainable and resilient tests.

3. **@testing-library/user-event**:
   - This library provides utilities for simulating user events, such as clicking, typing, and navigating, in your tests.
   - It offers a more realistic way to interact with your components compared to directly triggering events on DOM elements.
   - @testing-library/user-event helps you write tests that closely mimic user interactions with your application, ensuring that your components behave as expected in real-world scenarios.


# Getting Started
1. Clone this repository to your local machine.
   
2. Install the necessary dependencies using npm install.
   
3. Run the test with _npm test_ and *npm start* to check out the application.
   
