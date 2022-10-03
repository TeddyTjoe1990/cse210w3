# Jumper Game
Jumper game is a game which the player seeks to solve a puzzle by guesting the letters of a secret word one at a time. The game is based on python <This is a learning project>

## Rules
- Need one player
- The Puzzle is a secret random word chosen from a list.
- The Player guesses a letter in athe puzzle
  - if the guess is right, the letter is revealed, player saved.
  - if the guess is wrong, a line is cut on the player's parachute.
  - if the word puzzle is solved the game is done, you win the game, you could play it again.
  - if the player ha no more parachute, the game will be over.

## How to start the game?
- Need updated python
- Go to main.py and run it
- Also, you can run the program from an IDE like Visual Studio Code. Start you IDE and open the project folder.

## Project Structure
The project files and folders are organized as follows:
```
root                    (project root folder)
+-- cse210w3            (source code for game)
  +-- game              (specific classes)
    +-- main.py         (program entry point)
    +-- game.py         (game code)
    +-- player.py       (player code)
    +-- puzzle.py       (words code)
    +-- parachute.py    (parachute display)
  +-- README.md         (general info)
