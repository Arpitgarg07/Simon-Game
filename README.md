# Simon Game

Welcome to the Simon Game, a classic memory challenge brought to life with JavaScript! This game tests your ability to remember and replicate sequences of colors. The game logic involves generating sequences of button flashes, which the player must then replicate in the correct order. Here's a breakdown of how the game functions:

### Game Flow
Game Start: The game begins when any key is pressed. This triggers the levelUp function, which increments the game level and generates a new color sequence. <br>
Button Flash: A random button (red, yellow, green, or blue) is chosen to flash, indicating the sequence the player needs to remember. <br>
User Interaction: The player must click the buttons in the correct order. Each button click triggers the btnPress function, which handles the player's input and checks it against the game sequence. <br>
Sequence Check: The checkAns function compares the player's input with the game's sequence. If the player is correct, they advance to the next level. If not, the game ends, and the player is prompted to start again. <br>
Game Over: If the player makes a mistake, the game displays a "Game Over" message with the player's score and resets the game. <br>
### Key Functions
levelUp: Advances the game level, generates a random button to flash, and updates the game sequence. <br>
gameFlash: Adds a visual flash effect to the game buttons. <br>
userFlash: Adds a visual flash effect to the user's button clicks. <br>
checkAns: Compares the user's input to the game sequence and determines if the game should continue or end. <br>
btnPress: Handles user button clicks and updates the user's input sequence. <br>
reset: Resets the game state to allow for a fresh start. <br>
### Visual and Interactive Elements 
Buttons: Four colored buttons (red, yellow, green, blue) for user interaction. <br>
Level Display: An HTML element to display the current level. <br>
Game Over Message: An HTML element to display the game over message and the player's score. <br>
This Simon Game implementation provides an engaging and interactive way to challenge your memory and concentration skills. Give it a try and see how many levels you can conquer!

![logo](https://github.com/Arpitgarg07/Simon-Game/blob/master/simon-game.png)
