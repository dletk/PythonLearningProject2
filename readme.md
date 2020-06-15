# Assignment 2, Tic Tac Toe

## Implement the game tic tac toe with python, User vs Machine

Using only basic python commands and built-in functions/modules. The main statement in this assignment should be in the list of basic commands (but not limited to) `if/else, switch, for, while...` and the main data type should be `number, string, list, dictionary, tuple...`. The use of other, more complex commands is not needed.

Basic funtionality:

1. The game should ask whether the user want to play first or second (answer Y/N in the terminal)
2. User enter their move by type in the terminal, with the format: X,Y (with X,Y is the coordiate of the move on the 3x3 board).
3. The game should print out to the console (the terminal) the current state of the board after each move, example:

```{bash}
X | O | X
X | O | X
O | X | O
```

4. The game should say the result (who is winner or draw) at the end of last move.
5. For the first version, on its turn, the machine should randomly choose an available cell.
6. (Extra) For second version, the machine should choose cell based on some SIMPLE "intelligent strategy"
7. (Extra) The game should ask whether user want to play again and start a new game.
