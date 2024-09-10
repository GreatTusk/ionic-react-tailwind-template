# Ionic React Tailwind Template

This is a template for developing Ionic apps with React and Tailwind CSS.

## Prerequisites
Before getting started, make sure you have the following installed:
- Node.js
- npm
- Ionic CLI

## Installation
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Run the following command to install the dependencies:
    ```
    npm install
    ```

## Running the Project
To run the project, you can use the following scripts:

- **Development Mode**: This script starts the development server and watches for changes in Tailwind CSS files.
  ```
  npm run start:dev
  ```

- **Android**: This script builds the project, syncs the changes with Capacitor, and runs the project on an Android device.
  ```
  npm run start:android
  ```

## Testing
- **End-to-End Tests**: This script runs the Cypress end-to-end tests.
  ```
  npm run test.e2e
  ```

- **Unit Tests**: This script runs the unit tests.
  ```
  npm run test.unit
  ```

## Building
- **Development Build**: This script builds the project for development.
  ```
  npm run build
  ```

- **Production Build**: This script builds the project for production.
  ```
  npm run build:css && tsc && vite build
  ```

## Linting
- **Linting**: This script runs the ESLint linter.
  ```
  npm run lint
  ```

## Configuration
This template is configured to use with Shadcnui.

That's it! You're ready to run and develop your Ionic app with React and Tailwind CSS.

## Documentation
Here are some useful links to documentation for the technologies used in this template:

- [Ionic Documentation](https://ionicframework.com/docs) - Official documentation for Ionic framework.
- [Tailwind CSS Documentation](https://tailwindcss.com/docs) - Official documentation for Tailwind CSS.
- [React Documentation](https://reactjs.org/docs) - Official documentation for React.
- [shadcn/ui Documentation](https://ui.shadcn.com/docs) -Official documentation for shadcn/ui.
Make sure to refer to these resources for detailed information and guides on how to use these technologies effectively.