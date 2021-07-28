# Electroic_Dice_Game
Design an electronic dice game by writing synthesizable Verliog code for finite state machines, and to drive the 7-segment LEDs of the BASYS3board.

The idea of the dice game is that two counters are used to simulate the roll of the dice. Each counter counts in the sequence 1, 2, 3, 4, 5, 6, 1, 2, ...... After the "roll" of the dice, the sum of the values in the two counters will be in the range 2 through 12. 

The rules are as follows: 

1> After the first roll of the dice, the player wins if the sum is 7 or 11. The player loses if the sum is 2, 3 or 12. Otherwise, the player obtained on the first roll is referred to as a point, and he or she must roll the dice again. 

2> On the second or subsequent roll of the dice, the player wins if the sum equals the point, and he or she loses if the sum is 7. Otherwise, the player must roll again until he or she finally wins or loses. 

The inputs  to the  dice  game  come  from two push  buttons,  Rb (Roll button) and Reset. Reset is  used  to initiate a new game. When the roll button is pushed, the dice counters count at a high speed, so the values cannot be read on the display. When the roll button is released, the values in the two counters are displayed, and the game can proceed. 
