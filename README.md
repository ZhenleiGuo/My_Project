
# Chinese Chess (AlphaXq)

## Project Overview

Chinese Chess (AlphaXq) is a JavaScript-based Chinese chess AI project designed to provide a simple and easy-to-use playing experience. The project is inspired by the open-source codes of [XQlightweight](https://github.com/xqbase/xqwlight) and [eleeye](https://github.com/xqbase/eleeye).

AlphaXq was developed by Zhenlei Guo, a student at Universite Paris-Saclay. This project introduces an innovative AI engine capable of dynamically adjusting AI thinking time based on the player's moves, thereby adjusting the search depth and difficulty level—a feature not available in other systems. Through this dynamic adjustment, the AI can provide a more challenging and personalized gaming experience for players.

## File Descriptions

- `index.htm`: Main page file providing the user interaction interface.
- `board.js`: Defines the logic for rendering the board and pieces.
- `book.js`: Implements the opening book to help the AI make quick decisions.
- `position.js`: Defines the state representation of the board and pieces.
- `test.js`: Contains test code used to verify the correctness of features.
- `images/`: Stores images of the chess pieces and board.
- `sounds/`: Stores sound effects used during gameplay.

## Usage Instructions

1. Download and extract the project files.
2. Open the `index.htm` file to start the user interface and play against the AI.
3. Players can choose to play as red (first move) or black (second move), and the AI will dynamically adjust its difficulty based on player performance.

## Features

1. **Innovative Adaptive Difficulty Adjustment**: The AI can dynamically adjust its thinking time and search depth based on the player's moves, thereby adjusting the game difficulty.
2. **Opening Book Support**: A basic opening book is implemented to allow the AI to make quicker decisions.
3. **Pure JavaScript Implementation**: All logic is implemented in JavaScript, allowing the game to be run directly in a browser.

## How to Learn from This Project

1. If you have no experience with chess engines, it is recommended to start by learning from [these articles](https://github.com/bupticybee/elephantfish/tree/master/articles).
2. After understanding basic concepts such as board representation and search algorithms, start by reading `position.js`, then proceed to `book.js` and `board.js` to complete your understanding of this project.

## Developer

- **Zhenlei Guo** - Student at Universite Paris-Saclay, supervised by Prof. Hedi Tabia

## License

This project is licensed under the [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html).
