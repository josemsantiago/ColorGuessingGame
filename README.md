# Color Guessing Game

An interactive browser-based guessing game where players try to identify a randomly selected color from a predefined set. Built with vanilla HTML, CSS, and JavaScript.

## Overview

The Color Guessing Game challenges players to guess a randomly selected color from a set of 10 available colors. The game provides intelligent feedback based on alphabetical ordering and includes a visual flowchart demonstrating the game logic.

## Features

### Core Gameplay
- **Random Color Selection**: Game randomly picks from 10 predefined colors
- **Interactive Guessing**: Players enter guesses via browser prompts
- **Smart Feedback System**: Hints based on alphabetical ordering
- **Visual Reward**: Background changes to the correct color upon winning
- **Attempt Tracking**: Counts and displays number of guesses made

### Available Colors
The game includes 10 colors: `blue`, `cyan`, `gold`, `gray`, `green`, `magenta`, `orange`, `red`, `white`, `yellow`

### Feedback System
- **Alphabetically Higher**: "Your guess is alphabetically higher than what I'm thinking"
- **Alphabetically Lower**: "Your guess is alphabetically lower than what I'm thinking"
- **Invalid Color**: "I don't recognize your color"
- **Success**: Congratulations message with attempt count

## Technical Implementation

### Technologies Used
- **HTML5**: Page structure and game interface
- **JavaScript**: Game logic and user interaction
- **CSS**: Minimal styling for background color changes

### Code Structure
```javascript
const COLORS_ARRAY = ['blue', 'cyan', 'gold', 'gray', 'green', 'magenta', 'orange', 'red', 'white', 'yellow'];

function runGame() {
    // Main game loop with random color selection
}

function checkGuess(guess, targetColor) {
    // Validation and feedback logic
}
```

## Installation & Usage

1. **Download the game**:
   ```bash
   git clone https://github.com/josemsantiago/ColorGuessingGame.git
   cd ColorGuessingGame
   ```

2. **Open in browser**:
   - Open `color-guessing-game.html` in any modern web browser
   - No server setup or dependencies required

3. **How to Play**:
   - Click the "Start Game" button
   - Read the list of available colors
   - Enter your guess in the prompt
   - Receive feedback and continue guessing
   - Win by correctly identifying the target color!

## Game Flow

1. **Game Start**: Player clicks "Start Game" button
2. **Color Selection**: Game randomly selects target color
3. **Player Input**: Player enters color guess via prompt
4. **Validation**: Game checks guess against available colors
5. **Feedback**: Player receives directional hint
6. **Continue/Win**: Loop continues until correct guess
7. **Victory**: Background changes to target color, attempts displayed

## Documentation

The project includes comprehensive documentation:
- **README.md**: This file with game description
- **cgg-flowchart.png**: Visual flowchart showing game logic and decision points
- **LICENSE**: GNU General Public License v3.0

## Educational Value

This project demonstrates:
- **JavaScript Fundamentals**: Variables, functions, loops, conditionals
- **DOM Manipulation**: Event handling and style changes
- **User Input**: Browser prompt and alert APIs
- **Array Operations**: Random selection and includes() method
- **Game Logic**: State management and feedback systems

## Browser Support

- Works in all modern browsers supporting ES5+
- No external dependencies or frameworks required
- Responsive design principles for various screen sizes

## Known Issues

- Minor typo in HTML heading: "Color Guessing Gamne" (should be "Game")
- Minor typo in feedback message: "alphabeltically" (should be "alphabetically")

## Future Enhancements

Potential improvements could include:
- **Difficulty Levels**: More colors for advanced players
- **Score System**: Points based on attempts and time
- **Visual Interface**: Replace prompts with custom UI
- **Sound Effects**: Audio feedback for guesses
- **Color Themes**: Different color sets (pastels, primary colors, etc.)
- **Multiplayer Mode**: Compete against other players
- **Statistics**: Track wins, average attempts, best times

## License

This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.

## Author

José Santiago Echevarria
Created: September 30, 2023
A fun and educational JavaScript browser game demonstrating core programming concepts.
