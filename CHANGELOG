Pong Game AI Implementation Project
Paddles are controlled automatically mainly in the update_pong function in pong.c. In addition, an AI_turn variable was created in the pong structure (see pong.h) to identify the turn of each player.
AI_turn is a bool variable that serves to indicate two states: player 1's turn with true and player 2's turn with false.
For example, when AI_turn is true player 1's paddle is "turned on" by changing vy to align its y-coordinate with the ball, while paddle 2's speed is set to 0 so it remains stationary.
Also, AI_turn is set to true or false depending on the collision with player 1’s or player 2's paddle. This is done in pong.c at line 197 and line 213.
