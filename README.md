# hangman-word-puzzle
The rules are as follows:
The length of the word is the count of chances or guesses that you get.
For every guess - whether correct or incorrect - total guesses is reduced by 1
For every guess, the following is displayed
If the guess is correct, the letter gets displayed at its correct position
If the guess is incorrect, an error message is provided to the user
Conditions for 'Winning'
If all letters are correctly guessed
AND if all chances / guesses count is not yet 0
#Update the code such that the count of 'guesses' updated only when you make a wrong guess. 
#If you make a correct guess, then dont reduce the available count
At the start of the game, don't mark all letters as blank - you can display a maximum of 2 consonants to help the user. The guessing game begins from this point - you can reduce total available guesses based on this update.
