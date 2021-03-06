# Bagels
This is a Python implementation of the deduction game Bagels which was required of me for my Introduction to Computer Science course.

TABLE OF CONTENTS
-----------------
* The name of our project.
* The name(s) of the project submitters.
* Whether our project is a game or a simulation or visualization.
* How to play the game (game rules). <Our program does not require any extra files to run properly.>
* If there are any known bugs or issues with the program.

PROJECT NAME
------------
The name of our project is "Bagels", which is a deduction game.

PROJECT SUBMITTERS
------------------
The projects submitters are Jordan and Brandon Navarro.

PROJECT TYPE
------------
Our project is a game, not a simulation or visualization.

HOW TO PLAY
-----------
Bagels is a deduction game in which the player attempts to guess a random three-digit number (with no repeating digits) generated by the program. After each guess, the program will return one of three clues:

Bagels: None of the three digits guessed is in the correct answer.
Pico: One of the three digits guessed is in the correct answer, but the digit guessed is not in the correct place.
Fermi: One of the three digits guessed is in the correct answer and in the correct place.
	
The program will return the clues in alphabetical order. This is important to note as it means that one cannot assume, for example, that the first digit guessed is in the three-digit number and in the correct place AND the second digit guessed is in the three-digit number, but not in the correct place, from a response that reads: 'Fermi Pico'.

The 'easy' difficulty allows you to have fifteen (15) guesses.
The 'normal' difficulty allows you to have ten (10) guesses.
The 'hard' difficulty allows you to have five (5) guesses.

There is a 'random' difficulty, but this is only enabled if the user fails to decide a difficulty between the choices of 'easy', 'normal', and 'hard'.

KNOWN BUGS OR ISSUES
--------------------
There are no known bugs or issues with this program.
