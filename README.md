# Color Guessing Game

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-blue)
![Status](https://img.shields.io/badge/status-active-success)

An interactive browser-based guessing game where players try to identify a randomly selected color from a predefined set. Built with vanilla HTML, CSS, and JavaScript.

## Screenshots

> **Note:** Game screenshots will be added soon. Open `index.html` in your browser to play the game.

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
   - Open `index.html` in any modern web browser
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

## Screenshots

> **Note:** Screenshots will be added soon. To see the game in action, simply open `index.html` in any modern web browser - no installation required!

## Troubleshooting

### Common Issues

**Issue:** "Start Game" button doesn't respond when clicked

**Solution:** Check browser console (F12) for JavaScript errors. Ensure JavaScript is enabled in your browser settings. Try refreshing the page.

---

**Issue:** Game prompts appear behind other windows

**Solution:** Browser prompts always appear in the foreground. If you don't see prompts, check if your browser has popup blockers enabled. Allow popups for this page.

---

**Issue:** Background color doesn't change when winning

**Solution:** Ensure you're entering the exact color name (lowercase). Check spelling carefully. Valid colors are: blue, cyan, gold, gray, green, magenta, orange, red, white, yellow.

---

**Issue:** Game seems stuck or unresponsive

**Solution:** Refresh the page to restart. If using the browser back button, this may cause issues - reload the page instead.

---

**Issue:** Typos in game messages

**Solution:** Known issues include "Color Guessing Gamne" in heading and "alphabeltically" in feedback messages. These are cosmetic and don't affect gameplay.

For additional help, please check the browser console for error messages or file an issue on GitHub.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add YourFeature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

**Areas for contribution:**
- Fix existing typos in UI and messages
- Add new color sets or themes
- Implement difficulty levels
- Create visual interface to replace prompts
- Add sound effects and animations
- Write unit tests for game logic

## Contact & Support

- **Author**: José Santiago Echevarria
- **Created**: September 30, 2023
- **Issues**: Report bugs or suggest features via [GitHub Issues](https://github.com/josemsantiago/ColorGuessingGame/issues)
- **Project Type**: Educational JavaScript browser game demonstrating core programming concepts including DOM manipulation, event handling, and game logic

## Author

José Santiago Echevarria
Created: September 30, 2023
A fun and educational JavaScript browser game demonstrating core programming concepts.
