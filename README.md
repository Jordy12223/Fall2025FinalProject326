# Number Match
NumberMatch is a two-player Python card game where players match math equation cards to randomly drawn value cards. Each round, players must find and play equations from their hand that evaluate to the current value card. If no matching equation is available, the player draws a new card from the deck. The game continues until one player successfully empties their hand and wins.

This project demonstrates the use of Python classes, lists, dictionaries, loops, conditionals, randomization, and object-oriented programming concepts through an interactive terminal-based game.

## Explain of each file:
  - final_game.py: This file is our final project file that runs our game. 
  - my_scrpit.py: This file was for our final project interim derliverable. 

## How to run the program:
  To run the program in python all you need to type in the command line is: 
  **python final_game.py**
  then follow all the instructions from there like putting in 2 player names, 
  and inserting the correct equation cards if they match the value card. 

## How to use our program:
  1. When the program starts you will be asked to enter Player 1's and Player 2's name.
  2. After that 7 equation cards will be delt to each player at random and along with their cards being displayed each round.
  3. Then a value card will be delt each round, so each player will take turns seeing if they have an equation in thier deck that matches that value card, otherwise they will draw a card.
  6. Any matches will be dropped from the players deck and any non matches will have a new card added to their deck.
  7. When the value deck or equation deck runs out of cards they will be reshuffled and delt again. 
  8. This will continue until someone has no cards left to match. 

## Annotated Bibliography:
  For this we mainly went off lecture videos and past practices/exercises from class. We didn't really use anything that was wasn't from class mainly looking at the
  hangman.py file for understanding how the game should be set up.

## Attribution:
|        Method         |      Primary Author      |          Techniques Demonstrated          |
|-----------------------|--------------------------|-------------------------------------------|
| suffle_decks()        | Jordan Stone             | Sequence Unpacking                        |
| display_game()        | Jordan Stone             | f-strings Containing Multiple Expressions |
| draw_equation_card()  | Jordan Stone             | None                                      |
| deal_cards()          | Shara Mohotti Arachchige | Comprehensions                            |
| check_for_winner()    | Shara Mohotti Arachchige | Conditional expressions                   |
| turn()                | Shara Mohotti Arachchige | None                                      |
| find_playable_cards() | Murad Habtu              | Generator expression                      |
| draw_value_card()     | Murad Habtu              | Optional parameter                        |

# Authors
## Developed by Jordan Stone, Shara Mohotti Arachchige, and Murad Habtu 
