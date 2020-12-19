# Python Checkers Game
Python Checker Game

This is a checkers game that I worked on during IT 450 Artificial Intelligence. I did not create this program, as it was given to me by my school. The goal was to change to algorithms to increase the difficulty of the computer. To use this app, simply download python, download this program, change to the directory it is downloaed to, and type python3 Checkers_v24.py.

I did not write this program, as it was given to me by my instructor. This program is written in Python and is about 850 lines of code. The purpose of this program is to provide an easy to use checkers board that the player can either play against the computer or against another player.

I selected this program because it demonstrates artificial intelligence if the player decides to play against the computer. The algorithms for the logic of this program are found within lines 73 to 211. Much of the other code in this program handle setting up the checkers board, moving the pieces, capturing/jumping over pieces and saving games. Some of the functions that calculate the logic are the CompTurn() function, the hasMorePieces() function and the isMovesSafe function. 

After a few initial play throughs, I felt the computer was not very challenging. My objective with the source code was to modify these functions to make the computer more challenging. One modification I made was modifying CompTurns() function. I modified the selection of moves by implementing a randrange list selects a random move from the list of the good moves. This means the computer may pick a much stronger move at random instead of a mildly strong move. I also promoted the for loop that takes kings for free, over moves that trades kings for trading pieces. After playing the computer again it was noticeably more challenging and not carelessly trading in pieces that it did not have to. After making these code changes I felt I met the objective of enhancing the program to become more challenging. 
