# Psychic-Game

This project allows the user to play a guessing game with the browser.  

It is expecting lower case alphabetic key strokes as input; 26 options for user choice: ['a', 'b', 'c' 'etc']

Ground rules:
   * 2 actors:  cpu and user
   * 10 chances in one round
   * keyup triggers game playing

Basic functionality:

        1. Check for match between user choice and cpu choice

        2. If user choice matches cpu choice
              increment win count and start over, reset guesses remaining
            Else
              decrease guesses remaining by one
              store guess in array and return to screen.   

        3. Repeat until guess count reaches 10
              if no match, then increment loss count by one and reset guess count to 10.