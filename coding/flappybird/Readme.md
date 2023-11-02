# Simple Flappy Bird Game #

## Title: Simple Flappy Bird Game (Java Swing) ##

Description:

This project is a simple implementation of the popular Flappy Bird game using Java Swing. Flappy Bird is a classic 2D game where the player controls a bird and must navigate it through a series of pipes by jumping. The objective is to see how far you can go without hitting any obstacles. This implementation provides a fun and interactive gaming experience.

Key Features:

Swing-Based GUI: The game utilizes Java Swing to create a graphical user interface for the game. It includes a window, bird character, and pipes, providing an engaging visual experience.

User Interaction: The game is designed to be user-friendly. It responds to user input by allowing the player to control the bird's jumps with the spacebar. This simple and intuitive control mechanism enhances the gameplay experience.

Obstacle Movement: The pipes in the game move from right to left, creating a dynamic and challenging environment. The player must time their bird's jumps carefully to avoid collisions with the moving pipes.

Scoring System: The game includes a scoring system that increases as the player successfully passes through the gaps between the pipes. The score is displayed on the screen, motivating players to aim for higher scores.

Code Highlights:

Bird Class: The Bird class represents the player's bird character and handles its movement. Notable methods include jump() for jumping and update() for gravity and collision handling.

Pipe Class: The Pipe class manages the creation and movement of the pipes. It includes methods for detecting when the bird has passed a pipe, allowing for score updates.

Game Loop: The GameTimerListener class implements the game loop. It updates the positions of the bird and pipes, checks for collisions, and handles game-over conditions.

Painting: The paintComponent method in the FlappyBird class is responsible for rendering the game elements on the screen. It uses Swing's graphics capabilities to draw the bird, pipes, and the game score.

User Input: The BirdKeyListener class responds to spacebar key presses, triggering the bird's jump when detected.

Usage:

To play the game, simply run the application. Press the spacebar to make the bird jump and navigate it through the pipes. The game keeps track of your score, and it ends when the bird collides with a pipe or the ground.


<img src=https://github.com/hansieso/Portfolio/blob/main/Github%20Portfolio%20Pictures/Flappybirdplay1.png>
