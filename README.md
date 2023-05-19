# Number-Guessing-Game-Project
This is the step-by-step explanation of what the code does:

1) It imports the random module for generating random numbers and the math module for mathematical calculations.

2) The user is prompted to enter the lower bound of the range of numbers to guess.

3) The user is prompted to enter the upper bound of the range of numbers to guess.

4) A random number x is generated using random.randint() within the given range.

5) The number of guesses allowed is calculated based on the range using the formula round(math.log(upper - lower + 1, 2)).

6) The count variable is initialized to 0 to keep track of the number of guesses.

7) A loop is started to allow the user to make guesses until they guess the correct number or exhaust the maximum number of guesses.

8) Inside the loop, the user is prompted to enter their guess.

9) The code compares the user's guess with the generated random number and provides feedback: whether the guess is too small or too high.

10) If the user's guess is correct, the code displays a congratulatory message along with the number of tries made, and the loop breaks.

11) If the user's guess is incorrect but within the allowed range, the loop continues, and the user is prompted for another guess.

12) If the number of guesses exceeds the allowed number of tries, the code displays a message revealing the correct number and indicates that the user was unsuccessful.
