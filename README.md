hangman_sql
===========

Hangman game, with ASCII pictures, implemented with MariaDB/MySQL Stored Procedures... without a particular readon :) 

Hot to play
===========

To start a new game:

USE hangman;
CALL new();

To guess next letter:

CALL guess('x');

To guess the whole word(s):

CALL guess('tiger');

You have 5 attempts. But if you try to guess the whole word and fail, you will lose.

