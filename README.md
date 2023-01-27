# Wordle Game

To play the game, click here:  https://justinkenealy.github.io/Music-Wordle-Project/ 

## Game Instructions

- Use the Keyboard below to enter your letters, building a five-letter word
- Hit 'Enter' when you are ready
- A green tile means that letter is an exact match, while yellow means correct letter in the wrong position
- You have multiple attempts to guess the full word.
- Keep playing build a score streak.
- Choose easy for 1 point, medium for 2, and hard for 3!

## Code

This game is built using HTML, CSS and JavaScript. The code has two stored arrays, one with all possible 5-letter words and one with all the possible chosen game words, which are selected at random before each game.

Prior to beginning, the user may select their desired difficulty rating, which adjusts how many guesses they are allowed for that round by altering the grid-template-rows of the game grid. Once the game has begun, the functionality of these buttons is disabled. The user inputs their chosen word into the game grid using the built-in keyboard, before confirming with the enter button. A number of for loops compares the users word to the answer, before highlighting exact-match letters in green and other letter matches in yellow. These matches are also reflected on the keyboard. Letters which do not match are muted with a grey colour. 

Each time the user makes a guess, the game counter increases which reduces the number of guesses remaining and shifts the target location of the next keyboard input to the following row. This process repeats until either 1) the user guesses the correct word or 2) the user runs out of guesses and the game is over. 

Buttons and event listeners are used for the customisable background music and difficulty settings, and other sounds effects are built in to the functions that signal an error guess, or the outcome of the round. Messages for error guesses and for either the win or loss of a round are hidden behind the game screen using deliberate z-index manipulation. 

Each time the user wins a round, the winstreak variable is added to and the user's score streak is displayed on the page. When they eventually lose a round, this score is their final outcome and they have the option to share on their desired social media page with the built-in achor tag buttons. 