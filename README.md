# NUMBER GUESSING GAME

## Short Description
This is a simple but fun game whereby a person will guess the random number to be displayed by a program. 
For the purpose of this task, a number to be displayed by the program would be between 1 and 10.
So, if you guess a number that is lower than that displayed by the program, you`ll have a message, 'Too low, guess again'
however, if your guessed number is higher than that displayed by the program, you`ll have a message, 'Too high, guess again'
but if you guess the correct number displayed by the program, you`ll get a message, "Congratulations, you are correct"

## The Game Algorithm
Click 'Start' to begin
Generate a random number ranges between 1 and 10 and name it 'secret number'
Ask the player to guess the number "between 1 and 10"
Name the number, any number whatsoever, mentioned by the player  as 'Guess'
WHILE 'Guess' is not equal to 'secret number', DO
    IF 'Guess' is less than 'secret number',THEN display "Too low, Try again!"
    ELSE IF 'Guess' is greater than 'secret number', THEN display "Too high, Try Again"
    ENDIF
    Ask the player to guess again
ENDWHILE
Display "Congratulations, you`re correct!"
End

## Author : 
Israel Oladeji
## Peer Reviewer :
Moses Adegoke
---

### Peer Review Suggestion - Moses Adegoke

**Add a Guess Limit**

I feel to make the game more interesting, the program can limit the player to 3 or 5 attempts at maximum. This will make the game more challenging and gives the players a sense of urgency and critical reasoning.


