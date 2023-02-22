# Tile Memory Matching Game

## What will the application do?

I imagine the game to consist of three parts
- **Start** *screen*
- **Game** *screen*
- **Loss** *screen*

The start screen will provide instructions on how to play the game,
a start button, and a high score counter.

The game screen will consist of a grid of square tiles, a score counter, and a pause button.
It begins with a grid of blank 10 x 10 squares at one flashing tile. Once that tile flashes, the player must
click the same tile after it goes blank again. If they are correct, two tiles will flash next, n + 1 tiles where n is 
the previous number of flashing tiles. If incorrect, high score will be checked and updated if beaten. 
The player wins if they reach n = 90 flashing tiles.

The loss screen will be displayed if an incorrect tile is selected, projecting the game-score as well as
the current high score. It will also include a play again, or return to start screen button.




## Who will use it?

This project is an application made to entertain. Its purpose will be solely for user
entertainment. It should be an easy pick-up game that anyone can enjoy.



## Why is this project of interest to you?

Video games have always been a part of my life; something to kill time, and to bond with friends and family.
I've always been particularly fond of the puzzle aspects of games, so I thought it would be
interesting to attempt creating one of my own.

## User Stories

- As a user, I want to be able to start the game
- As a user, I want to be able to click tiles
- As a user, I want to be able to lose
- As a user, I want to be able to see a score counter

