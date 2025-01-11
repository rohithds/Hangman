# Hangman Game

Welcome to the **Hangman Game** repository! This is a simple, text-based word guessing game implemented in Python. Players attempt to guess the word by suggesting letters within a limited number of attempts.

## Features
- Randomly selects a word from a predefined list.
- Provides feedback on guessed letters.
- Supports predefined inputs for non-interactive environments.
- Simple and beginner-friendly code structure.

## Getting Started

### Prerequisites
- Python 3.6 or higher.

### Clone the Repository
```bash
git clone https://github.com/rohithds/hangman.git
cd hangman
```

### Run the Game
To run the game interactively:
```bash
python hangman_game.py
```

For environments without `input()` support, modify the `predefined_inputs` in the `__main__` section of the script.

### Example Usage
Interactive environment:
```
Welcome to Hangman!
Word: _ _ _ _ _ _
Attempts left: 6
Guessed letters: None
Guess a letter: p
Good job! 'p' is in the word.
```

Non-interactive environment:
```python
predefined_inputs = ["p", "y", "t", "h", "o", "n"]
hangman(predefined_inputs=predefined_inputs)
```

## Contributing
Contributions are welcome! Feel free to fork this repository, make changes, and submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## About
Created and maintained by [rohithds](https://github.com/rohithds).

