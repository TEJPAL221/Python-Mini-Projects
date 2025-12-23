The objective of this project is to build a simple number guessing game that challenges the user to identify a randomly selected number within a specified range. The game begins by allowing the user to define a range by entering a lower and an upper bound (for example, from A to B). Once the range is set, the system randomly selects an integer that falls within this user-defined interval. The user's task is then to guess the chosen number using as few attempts as possible. The game provides feedback after each guess, helping the user refine their next guess based on whether their previous attempt was too high or too low.
Algorithm-
Accept lower and upper bounds from the user.
Generate a random number in the selected range.
Calculate the maximum allowed guesses using the binary search formula.
Run a loop to take user guesses:
If the guess is too high, print: "Try Again! You guessed too high."
If the guess is too low, print: "Try Again! You guessed too small."
If the guess is correct, print: "Congratulations!" and exit the loop.
If the user runs out of chances, display the correct number and a message: "Better Luck Next Time!"
