# Ping-Pong-Game

Ping Pong, also known as table tennis, is a sport that is played with two or four players hitting a lightweight ball back and forth over a table that is divided by a net. The game is played using paddles, also called rackets, to hit the ball across the table. The objective of the game is to score points by hitting the ball in such a way that the opponent is unable to return it, or by forcing the opponent to make an error.

The game can be played at various levels, from casual play among friends to competitive tournaments at both the amateur and professional level. It requires a combination of physical agility, hand-eye coordination, and strategic thinking to excel at the game.

Ping Pong is a popular game around the world, and has been an Olympic sport since 1988. It is a fun and challenging game that can be enjoyed by people of all ages and skill levels.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type python pong.py and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* import os and import turtle: The os module provides a way to interact with the operating system, and the turtle module is used for creating graphics and animations.

* Creating the game screen: A turtle screen is created with a yellow background and a size of 1050 x 650 pixels.

* Creating the left and right paddles: Two turtle objects are created for the left and right paddles. The paddles are positioned on the left and right sides of the screen and have a red and blue color, respectively.

* Creating the ball: A turtle object is created for the ball, which is positioned in the center of the screen and has a black color. The ball is given a horizontal and vertical speed (dx and dy) of 5.

* Initializing the score: The left and right player scores are both set to 0.

* Displaying the score: A turtle object is created for displaying the score, which is initially set to 0 for both players.

* Implementing functions for moving the paddles vertically: Four functions are created for moving the left and right paddles up and down. These functions change the y-coordinate of the paddle by 20 pixels.

* Binding the keys for moving the paddles: The functions for moving the paddles are bound to the "r", "c", "Up", and "Down" keys.

* Creating the game loop: A while loop is used to continuously update the game screen and move the ball.

* Updating the ball position: The ball's position is updated by adding the dx and dy values to its current x and y coordinates.

* Checking for border collisions: If the ball hits the top or bottom border of the screen, its y-direction is reversed. If the ball hits the left or right border, the score is updated and the ball is reset to the center of the screen.

* Checking for paddle collisions: If the ball hits a paddle, its x-direction is reversed.

* Clearing the score display and updating the score: After a player scores, the score display is cleared and updated with the new scores for both players.
