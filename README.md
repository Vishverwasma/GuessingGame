# Number Guessing Game ( https://roadmap.sh/projects/number-guessing-game )

Welcome to the Number Guessing Game! This is a simple command-line interface (CLI) game where the computer selects a random number, and the user has to guess it. You have a limited number of chances based on the difficulty level you choose.

## Features

- The computer selects a random number between 1 and a user-defined maximum.
- Users can choose a difficulty level that determines the number of chances:
  - Easy: 10 chances
  - Medium: 5 chances
  - Hard: 4 chances
- The game provides feedback if the user's guess is too high or too low.
- A congratulatory message is displayed when the user guesses the number correctly.
- The game shows the number of attempts taken to guess the number.
- If an invalid difficulty level is chosen, the game defaults to Easy level.

## Sample Output

```
Enter a Max number within what you wish to guess : 
100
Please select the difficulty level:
1. Easy (10 chances)
2. Medium (5 chances)
3. Hard (4 chances)
Choose Your Difficulty Level: 
2
Enter your guess (between 1 and 100) : 
50
Too high! Try again.

Enter your guess (between 1 and 100) : 
25
Too low! Try again.

Enter your guess (between 1 and 100) : 
35
Too high! Try again.

Enter your guess (between 1 and 100) : 
30
Congratulations! You've guessed the number.
It took you 4 attempts.
```

## Future Enhancements

- **Play Multiple Rounds:** Allow users to play multiple rounds and ask if they want to play again after each round.
- **Timer:** Implement a timer to see how long it takes the user to guess the number.
- **Hint System:** Add a hint system to provide clues if the user is stuck.
- **High Score Tracking:** Keep track of the user's high score, i.e., the fewest number of attempts to guess the number under a specific difficulty level.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by classic number guessing games.
