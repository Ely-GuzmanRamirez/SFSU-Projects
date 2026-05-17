# Guessing Game

This is a Python number guessing game with two modes:

1. **Player Guess Mode**  
   The computer picks a number between 1 and 1000, and the player tries to guess it by asking clue-based questions.

2. **Computer Guess Mode**  
   The player thinks of a number between 1 and 1000, and the computer asks yes/no questions to narrow down the answer.

## How It Works

When the program starts, the user chooses whether the **player** or the **computer** will guess the number.

### Player Guess Mode

The computer randomly chooses a number from 1 to 1000.

The player starts with **100 points** and can ask questions such as:

- Is the number odd or even?
- How many digits are in the number?
- Is the number prime?
- Is the number greater or less than 500?
- What is the last digit?

Each question costs points. The goal is to guess the number before running out of points.

### Computer Guess Mode

The player thinks of a number between 1 and 1000.

The computer asks yes/no questions to eliminate possible numbers. It uses questions about:

- Whether the number is even
- Whether it is divisible by 3, 5, or 10
- Whether the digits are unique
- Whether the sum of the digits is even
- Whether the number is above or below the midpoint

The computer keeps narrowing the list until it finds the number.

## Python Libraries Used

This project uses:

```python
import random
import sympy
import inflect
