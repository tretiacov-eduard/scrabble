Word Scoring Game

This C program is a simple implementation of a word-scoring game for two players. Players input words, and the program calculates and compares their scores based on predefined letter scores.
How to Play

    Compile the program using a C compiler (e.g., gcc word_game.c -o word_game).
    Run the compiled program (e.g., ./word_game).
    Enter a word for Player 1 when prompted.
    Enter a word for Player 2 when prompted.
    The program will calculate the scores for both players and announce the winner or declare a tie.

Implementation Details

    The program uses the CS50 library for input and standard C libraries (ctype.h and string.h).
    Each letter of the alphabet is assigned a score, stored in the POINTS array.
    The compute_score function calculates the score for a given word based on the letter scores.
    The winner is determined by comparing the scores of both players.

Feel free to modify and improve upon this code for your specific needs.