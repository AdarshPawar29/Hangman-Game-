**Hangman**

Given a dictionary (words.txt), write a program that can play hangman by choosing a letter based on the current state of the board.  A board would initially have a series of blanks, each representing one letter in the word.  As letters are guessed, all spaces in the word that match the letter should be replaced with that letter.  Any letters that have no matches are put on a list of missed letters.  Once the list of missed letters reaches 6, the game is lost.


State assumptions and trade-offs made.


Write a driver program that takes the word as input and shows the board after each step as well as ultimate outcome. The guesses should come from the program, not from user.


> ./hangman  hangman

_ _ _ _ _ _ _  missed:


guess: e

_ _ _ _ _ _ _  missed: e


guess: a

_ a _ _ _ a _  missed : e


guess: n

_ a n _ _ a n  missed: e


guess: m

_ a n _ m a n  missed: e


guess: d

_ a n _ m a n  missed: e,d


guess: k

_ a n _ m a n  missed: e,d,k


guess: g

_ a n g m a n  missed: e,d,k


guess: h

h a n g m a n  missed: e,d,k


**Accuracy**

Write a script that gives each word listed in words.txt file as input to above probram and prints the prediction accuracy.

Note : Comment the part of the code that prints board at every level, instead for each word just print if it correctly guessed the word or not.

Eg: CORRECT_GUESSES / TOTAL_WORDS * 100 --> 78% 


**CorrectGuess:  10 out of total words**
Total Accuracy:  0.22 % 
