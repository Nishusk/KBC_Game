# KBC Game

## Introduction

KBC (Kaun Banega Crorepati) is a popular quiz-based game show where participants answer multiple-choice questions to win cash prizes. This project is an implementation of the KBC game in Python, where players answer questions to accumulate points and reach checkpoints.

## Rules

1. The game consists of 16 multiple-choice questions.
2. There are 4 checkpoints at question numbers 4, 8, 11, and 13.
3. At any point, players can quit the game by entering "q".
4. Two lifelines are available: "50:50" and "Ask the Audience".

## Features

- Randomly selected questions from a predefined set.
- Visual effects to create a dynamic and engaging user experience.
- Lifelines to assist players in decision-making:
  - **50:50 Lifeline:** Eliminates two incorrect options from the choices.
  - **Ask the Audience Lifeline:** Simulates audience opinions to suggest an option.

## Usage

1. Run the Python script (`kbc_game.py`) in your terminal.
2. Read the introduction and press "Enter" to start the game.
3. Questions will be displayed with options.
4. Enter your answer choice (a, b, c, d) or use lifelines by entering 'l' for "50:50" or 'a' for "Ask the Audience".
5. Keep answering questions and using lifelines until you complete the game or decide to quit.

## How to Play

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/kbc-game.git
   cd kbc-game
   ```
2. Run the game:
   ```bash
   python kbc_game.py
   ```
3. Follow the on-screen instructions to play the game.

## Dependencies

- Python (>=3.6)

## Acknowledgments

The game questions and options are for demonstration purposes only and can be customized as needed.

## License

This project is licensed under the MIT License.
