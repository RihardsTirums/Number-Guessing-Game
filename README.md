# Number-Guessing-Game

## Task: Create a Number Guessing Game in TypeScript

Your task is to create a simple console-based number-guessing game in TypeScript. The game will generate a random secret number between 1 and 100, and the user has to guess this number. After each guess, the game should tell the user if their guess was too high, too low, or correct.

<img width="538" alt="Screenshot 2023-07-06 at 20 36 19" src="https://github.com/RihardsTirums/Number-Guessing-Game/assets/38011256/52a8175b-7f50-4fef-b4ad-939000bb9f76">

## Core Functionality

1. Generate a random secret number between 1 and 100. [Math.random](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/random)
2. Use the readline interface to get the user's guess from the console. [Node.js Readline](https://nodejs.org/api/readline.html)
3. Compare the user's guess to the secret number. [TypeScript Comparison Operators](https://www.w3schools.blog/typescript-operators)
4. Provide feedback to the user: "too low", "too high", or "correct". [TypeScript console.log()](https://developer.mozilla.org/en-US/docs/Web/API/console/log)
5. If the guess is correct, congratulate the user and end the game. [Node.js Readline close()](https://nodejs.org/api/readline.html#rlclose)
6. If the guess is incorrect, allow the user to guess again. [Loops in TypeScript](https://www.tutorialspoint.com/typescript/typescript_loops.htm#)
7. The game should handle invalid inputs gracefully. [TypeScript - If Statement](https://www.tutorialspoint.com/typescript/typescript_if_statement.htm)

## Extra Features

To make the game more interesting, you can add the following features:

1. If the user's guess is close to the secret number (within a range of 5), print a special message, "YOU ARE VERY CLOSE!". [Math.abs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Math/abs)
2. Limit the number of guesses a user can make. If the user hasn't guessed the number within a certain number of guesses, they lose the game. [TypeScript Variables](https://www.typescriptlang.org/docs/handbook/variable-declarations.html)
3. Implement difficulty levels. For instance, 'Easy' could allow more guesses and hints, while 'Hard' could provide no hints and fewer guesses. [Node.js Readline](https://nodejs.org/api/readline.html)
4. Add a scoring system. The fewer guesses the user makes, the higher their score. Display the user's score when they guess correctly. [TypeScript Variables](https://www.typescriptlang.org/docs/handbook/variable-declarations.html)
5. Allow the user to play again without needing to run the program again. After a game ends, ask if they would like to play again. If so, generate a new secret number and start a new game. [Loops in TypeScript](https://www.tutorialspoint.com/typescript/typescript_loops.htm#)
6. Improve user experience by providing clear instructions and feedback after each guess. Remind the user of the rules and state of the game. [TypeScript console.log()](https://developer.mozilla.org/en-US/docs/Web/API/console/log), [String Interpolation in TypeScript](https://upmostly.com/typescript/string-interpolation-in-typescript)

