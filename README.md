# About
A simple and considerably uncomplete Tetris game, made with C++ and SDL2. 
This by no means is a professional project, neither is intended to be.

# Bugs
- Occasionally, when tetromino is just touched the ground, if user presses down arrow key at the wrong time, tetrmoni migh go one cell below the bottom border.

# Issues
- Lots of unnecessary individual texture loading is present, to make it more tidy, related textures should be combined together as a sprite sheet.
- Code is not the most efficient nor tidy one, also lacks comments and explanation.
- Potentially memory usage is highly inefficient.

# To be added
- Saving scores and being able to see previous high scores. Associating player names with scores.
- GUI controlls, e.g. pause/exit/restart buttons, save game / view high scores buttons after the game is over.

# Cotrols
- Right/left arrow keys to move tetromino
- Down arrow key to speed up
- Q/E keys to rotate ccw/cw respectively.
- P key to pause/unpause

# Gameplay
Score increases 1 point, per destroyed line, in case of multiple lines being simultaneously, square of the number of lines destroyed is added to the score.
As score increases, gamespeed also increases, in a slight manner.
