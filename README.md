Overview

This is a simple Simon Game built using JavaScript, jQuery, HTML, and CSS. The game challenges players to memorize and replicate an increasing sequence of colors.

How to Play

Press any key to start the game.

A sequence of colors will be displayed, starting with one.

Click the buttons in the correct order to match the sequence.

If you match the sequence correctly, the game advances to the next level with an additional color.

If you click the wrong button, the game will end, and you can restart by pressing any key.

Features

Generates a random sequence of colors.

Animations and sound effects for user interactions.

Game progression with increasing difficulty.

Restart functionality when a mistake is made.

Code Explanation

Variables

buttonColours: An array containing the four possible colors.

gamePattern: Stores the sequence of colors generated by the game.

userClickedPattern: Stores the sequence of colors clicked by the user.

started: Tracks whether the game has started.

level: Keeps track of the current level.

Functions

nextSequence(): Generates the next color in the sequence and updates the level.

checkAnswer(currentLevel): Checks if the user's input matches the game sequence.

animatePress(currentColor): Provides a visual effect when a button is clicked.

playSound(name): Plays a sound corresponding to the button clicked.

startOver(): Resets the game when the player makes a mistake.

Event Listeners

$(document).keypress(): Starts the game when a key is pressed.

$(".btn").click(): Captures user input when a button is clicked and checks the answer.

Requirements

jQuery library

Audio files for the game sounds (e.g., sounds/red.mp3, sounds/blue.mp3, etc.)

Future Enhancements

Add mobile touch support.

Implement score tracking.

Enhance UI with additional animations and effects.
