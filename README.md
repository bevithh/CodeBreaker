# CodeBreaker
The CodeBreaker program is designed as a game or puzzle-solving application where the player must guess a hidden code based on feedback provided after each attempt.
he game provides clues in the form of correct matches (both in value and position) and incorrect matches (values that exist in the code but are in the wrong position). The program will handle multiple rounds of guessing, give real-time feedback, and allow the user to continue until the correct code is guessed or the maximum number of attempts is reached.

Key Features:

Code Generation:
At the start of the game, the program generates a secret code. This code can consist of a series of numbers, letters, or any predefined symbols, depending on the game rules.
The code is randomly generated and kept hidden from the player.
User Input:
The player is prompted to enter a guess, which is typically a sequence matching the length of the secret code.
The guess can consist of a set of allowed values (e.g., digits 1-6, letters A-F, etc.).
Feedback Mechanism:
After each guess, the program provides feedback to the player. Feedback usually consists of:
Correct positions (exact matches between guess and secret code).
Correct elements but wrong positions (the number or letter exists in the secret code, but in a different position).
The program will give the player visual feedback, often in the form of colored pegs or numbers.
Limited Attempts:
The player has a fixed number of guesses (typically around 10 to 12 attempts). If the player guesses the code within the allowed attempts, they win; otherwise, they lose.
Win/Loss Condition:
The game ends when the player successfully guesses the code or exhausts all available attempts.
The program will display a congratulatory message if the code is broken, or reveal the secret code if the player fails to guess it within the allowed attempts.
User Interface:
While ARMLite is primarily designed for low-level programming, the CodeBreaker game can be implemented using simple text-based input/output or a more advanced graphical interface depending on the ARMLite capabilities. This may involve creating a terminal-based user interface where players can interact with the program through the console.

Language: ARM Assembly
