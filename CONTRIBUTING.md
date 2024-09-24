# Contributing to Our Project

Thank you for considering contributing to our project! We appreciate your help and support. Please follow these guidelines to ensure a smooth collaboration.

## Project Structure

- Please adhere to the established project structure and folder organization. This helps maintain consistency and makes it easier for everyone to navigate the codebase :

root/<br/>
│ ├── public/ # Static files (e.g., index.html, images)<br/>
│ │ ├── medias   # static and public medias<br/>
│ │ ├── documents # static and public document files<br/>
│ │ │ . . .<br/>
│ ├── src/ # Source files<br/>
│ │ ├── app/ # Pages and layouts and ... (next app routing folder)<br/>
│ │ ├── assets/ # Assets files (Static files that need to be imported in the code)<br/>
│ │ ├── components/ # Reusable components ( Preferably, keep the components stateless. )<br/>
│ │ ├── containers/ # Stateful components for managing UI logic.<br/>
│ │ ├── lib/ # Holds reusable utilities and helper functions.<br/>
│ │ ├── locales/ # Contains translation files for internationalization.<br/>
│ │ ├── sections/ # Holds components representing distinct page sections.<br/>
│ │ ├── stores/ # Manages global state and data for the application.<br/>
│ │ ├── stories/ # Contains Storybook files for UI component examples.<br/>
│ │ ├── styles/ # Includes CSS or styled components for styling.<br/>
│ │ └── types/ # Defines TypeScript types and interfaces for the project.<br/>
│ ├── tests/ # test functions<br/>
│ │ ├── e2e/ # E2E tests<br/>
│ │ └── integration/ # Integration testing functions.<br/>

- and component structure :

module-name/<br/>
│ ├──  index.ts # export module components and types <br/>
│ ├──  module.types.ts # shared module types <br/>
│ ├──  component-name/ # component folder <br/>
│ │ ├── index.ts # export items that need to be imported in other parts of the project. <br/>
│ │ ├── ComponentName.tsx # component function <br/>
│ │ ├── ComponentName.test.tsx # component tests <br/>
│ │ ├── ComponentName.types.tsx # component types <br/>
│ │ └── ComponentName.stories.tsx # component stories <br/>

or 

├──  component-name/ # component folder<br/>
│ ├── index.ts # export items that need to be imported in other parts of the project.<br/>
│ ├── ComponentName.tsx # component function<br/>
│ ├── ComponentName.test.tsx # component tests<br/>
│ ├── ComponentName.types.tsx # component types<br/>
│ └── ComponentName.stories.tsx # component stories<br/>


## Feature Requests

- Before implementing a new feature, please discuss it with us. This ensures that your idea aligns with the project goals and helps avoid duplicated efforts.

## Code Quality

- Aim for minimal warnings in your code. Clean code improves readability and maintainability.

## Pull Request Guidelines

- Before submitting a pull request, ensure that your branch is free of errors by running tests and building the project. This helps maintain the integrity of the codebase.

## Stateless Components

- As much as possible, your components should be stateless. Stateless components are easier to test and reason about, leading to a more predictable application.

## Major Changes

- For changes that affect the entire application, such as editing a global component, please discuss your idea with us beforehand. This helps us coordinate and plan for larger changes effectively.

## Documentation

- All global components require Storybook documentation. Providing documentation helps others understand how to use your components effectively.

## Code Simplicity

- Avoid complex code. If necessary, explain your code with comments to enhance understanding for future developers.

## Principles to Follow

- Please adhere to the following principles in your code:
  - **SOLID**: Follow the principles of object-oriented design to create understandable and maintainable code.
  - **KISS**: Keep it simple, stupid. Avoid unnecessary complexity in your code.
  - **DRY**: Don’t repeat yourself. Aim to reduce code duplication.
  - **YAGNI**: You aren’t gonna need it. Only implement features that are necessary for the current requirements.

## Communication

- If you have any questions or need clarification on any aspect of the project, feel free to reach out to us through [issue tracker](https://github.com/CleverDevsCommunity/odin-front/issues) or [telegram](https://t.me/+PCmSPD_byMI5MzJk).

Thank you for contributing!