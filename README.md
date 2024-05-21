# Guessing_Game_Javascript
Welcome to the Number Guessing Game! This is a simple web-based game where the computer picks a number, and you try to guess it. If your guess matches the computer's number, you win; otherwise, you lose.

## Features

- The computer randomly selects a number within a specified range.
- The player attempts to guess the number.
- The game informs the player if they have won or lost after each guess.

## How to Play

1. **Open the game:** Open the `index.html` file in your web browser.
2. **Make a guess:** Enter your guess in the input field provided and submit it.
3. **Check result:** The game will display a message indicating whether you have won or lost.

## Getting Started

### Prerequisites

- A web browser (Chrome, Firefox, Safari, etc.)

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/number-guessing-game.git
    ```
2. Navigate to the project directory:
    ```sh
    cd number-guessing-game
    ```

### Running the Game

To run the game, open the `index.html` file in your web browser:
1. Double-click on `index.html` or
2. Right-click on `index.html` and select "Open with" followed by your preferred web browser.


## Customization

You can customize the range of numbers the computer picks from by modifying the `minNumber` and `maxNumber` variables in the `script.js` file.

```javascript
const minNumber = 1;
const maxNumber = 10;
