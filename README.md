# WordGuess

### Status: In Progress

![License](https://img.shields.io/badge/license-MIT-brightgreen.svg)

## Table of Contents
1. [Description](#description)
2. [Features](#features)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Tools and Technologies](#tools-and-technologies)
6. [Dependencies and Installs](#dependencies-and-installs)
7. [License](#license)
8. [Contributing](#contributing)
9. [Tests](#tests)
10. [Questions](#questions)

## Description
WordGuess is a MERN-stack word puzzle game that allows users to guess letters to reveal a hidden word. The game features a countdown for remaining guesses and provides clear feedback on correct and incorrect guesses. Players can win by solving the word or lose if they run out of guesses. Upon game completion, users can view the solution and restart the game with a "Play Again" button.

## Features
- Interactive letter selection for guessing hidden words.
- Visual feedback for correct and incorrect guesses.
- Countdown display for remaining guesses.
- Win/Loss screen with the solution and a "Play Again" button.
- Fully implemented and passing unit tests for core functionality.

## Installation
To use the application, follow these steps:

- Step 1: Clone the repository.
- Step 2: Navigate to the project directory by typing `cd WordGuess`.
- Step 3: Install the required dependencies by running `npm install`.
- Step 4: Install the required dependencies for both the client and server.
- Step 5: Create a .env file in the server directory and configure the required environment variables.

## Usage
To start the application, run the following command: `npm run develop`.

Game instructions:
- The word appears with blanks representing each letter.
- Click letters to guess. Correct guesses reveal the letter in the word, while incorrect guesses reduce your remaining attempts.
- If you solve the word, you win! If your attempts reach zero, you lose. The solution and a "Play Again" button will be displayed.

## Tools and Technologies
**Programming Language**:
- TypeScript

**Libraries & Frameworks**:
- React
- Express
- Cypress

**Development Environment**:
  - Node.js
  - MongoDB Atlas

## Dependencies and Installs

**NPM Packages**:
- `cypress` - A robust testing framework for component and end-to-end tests.
- `react` - Core framework for the front-end application.
- `mongoose` - ODM for MongoDB, managing schema and data validation.

## License
This project is licensed under the MIT License, which allows you to freely use, modify, and distribute this software, provided proper attribution is given.

## Contributing
This project is part of a coding bootcamp assignment and is not open for contributions. To comply with the course requirements, I must complete this project individually without outside assistance. Therefore, pull requests, issues, or other contributions will not be accepted. Thank you for understanding!

## Tests
This project uses Cypress for both component and end-to-end testing:
- Component tests are located in cypress/component/Quiz.cy.jsx.
- End-to-end tests are located in cypress/e2e/quiz.cy.js.

To run the tests, use `npm run test`.

## Questions
If you have any questions about the repository, feel free to reach out by opening an issue or contacting me directly at cheyennaraelynn@gmail.com You can also find more of my work on GitHub at https://github.com/RaeOfChey.
