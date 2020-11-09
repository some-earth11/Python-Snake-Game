# Python-Snake-Game
Created partly in a MLSA workshop, the game offers its players a leaderboard system managed in MySQL

The game has a string of objects emulating a snake and runs across the playing grid according to the user's inputs trying to intercept an object called the snake's food.

Arrow keys are used to navigate the snake in the game in order to intercept food and add a point to the score.
The game ends either when the snake goes out of bounds of the playing grid or interepts itself or if the user takes too much time to intecept the target.

A user starts the game by entering their name which gets stores in a MySQL database, allowing users to accumulate scores and improve their rankings on the leaderboard.
A user may access the leaderboard through the main interface of the game.

NOTE: The game will not run in IDLE or the terminal in VS Code, CMD is the easiest way to run the game.
