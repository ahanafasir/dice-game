# Diced - Dice Game

visit: https://diced-game.netlify.app/

Diced is a simple two-player dice game built with HTML, CSS, and JavaScript. In this game, two players take turns rolling a dice to accumulate points. The goal is to be the first player to reach or exceed 100 points. Below is an overview of the code and how to play the game.

## Table of Contents

- [Game Structure](#game-structure)
- [Game Elements](#game-elements)
- [How to Play](#how-to-play)
- [Game Logic](#game-logic)
- [Contributing](#contributing)

## Game Structure

The game's structure consists of an HTML file, a CSS file, and a JavaScript file. These files work together to create the game interface and functionality.

### HTML Structure

The HTML file (`index.html`) contains the following structure:

- `<!DOCTYPE html>`: The document type declaration.
- `<html>`: The root HTML element.
- `<head>`: Contains meta information and external resources like stylesheets and scripts.
- `<meta>`: Provides metadata about the document.
- `<link>`: Links to external CSS stylesheets.
- `<title>`: Sets the title of the web page.
- `<body>`: The main content of the game, including player sections, buttons, and the dice image.
- `<script>`: Links to the JavaScript file for game logic.

### CSS Styles

The CSS styles are defined in two separate stylesheets (`style.css` and `queries.css`). They handle the game's visual appearance and responsiveness. The CSS code includes styles for the game layout, player sections, buttons, and more. It also uses Google Fonts to style the text.

### JavaScript Logic

The JavaScript file (`script.js`) contains the game's logic. It handles player turns, dice rolling, score tracking, and determines the winner. The script uses event listeners to respond to button clicks and updates the game state accordingly.

## Game Elements

The game interface includes the following elements:

- Two player sections, each with a name, current score, and total score.
- A dice image that displays the rolled number.
- Buttons for starting a new game, rolling the dice, and holding the current score.

## How to Play

1. **Start a New Game**: Click the "New Game" button to start a new game. This resets all scores and prepares the game for the first roll.

2. **Roll the Dice**: Click the "Roll dice" button to roll the dice. The number rolled will be displayed as an image. If you roll a 1, your current score resets, and it becomes the other player's turn. If you roll any other number, it gets added to your current score.

3. **Hold Your Score**: Click the "Hold" button to add your current score to your total score. It's now the other player's turn.

4. **Winning the Game**: The game continues until one player reaches or exceeds 100 points. The player with 100 points or more wins, and the game ends.

5. **Start a New Game**: To play again, click the "New Game" button.

## Game Logic

- The game keeps track of each player's total score and current score.
- Players take turns rolling the dice.
- Rolling a 1 resets the current score and switches to the other player.
- Clicking "Hold" adds the current score to the player's total score.
- The game ends when a player's total score reaches or exceeds 100.
- The winning player's section is highlighted, and the game can be reset for a new round.

## Contributing

Contributions to this game are welcome! Feel free to suggest improvements, fix bugs, or add new features. Please follow good coding practices and consider testing your changes thoroughly before submitting a pull request.

Enjoy playing Diced!
