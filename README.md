# Whack-a-mole
Based on EP4CE10F17C 8 key control water lamp design of whack-a-mole game
Implementation function:
Use the four keys key0-key3 to control the four small lights LED0-LED3 to simulate the Whack-a-mole game. Press by touch
Press the key to switch modes; Use one digital tube to display the current game mode and two digital tubes to display the current score.
2. When the touch key is not pressed, it is in Mode 1; when pressed, it is in Mode 2. Display the current control with the mode digital tube
Mode.
3. Mode 1 Game mode: When LED0 is lit, if the corresponding control key key0 is pressed, the score will increase by 1, for example
If other keys are pressed, the score remains unchanged. Each time a small lamp is lit, the scoring rules are the same. When the score accumulates to 15, no more
An increase indicates a victory in this round of the game. The switching frequency of the small lamp can be adjusted by yourself. The specific details should be specified in the design report
Frequency value."
4. Mode 2 Game mode: Randomly light up small lights. If the corresponding control key is pressed, the score will increase by 1. If another key is pressed
Press the key, and the score will be reduced by 1. (Note: The switching frequency of the small lamp can be adjusted by yourself. The specific frequency value should be specified in the design report.)
5. When the score accumulates to 15 and no longer increases, it indicates that the round of the game is won. When the score drops to 0, it indicates that this round of the game is lost
"Defeat; Choose your own patterns to indicate victory or defeat in the game.
6. If you win the game, you can increase the switching frequency of the small light and try again. If the game fails, you can slow down the switching of the small light
Frequency, try again. (Note: Whether the frequency is increased or decreased, the specific frequency value must be specified in the design report.)"
7. Add Mode 3. When the touch switch is double-clicked, it will enter Mode 3. Two LED lights will randomly light up and there will be none
Counting limit.
8. In Mode 3, a 30-second countdown has been added. Points will be scored by clicking the corresponding key within the specified time. Points will be deducted if the key is pressed incorrectly.
And there are also victory and defeat light effects.
9. A new win count function has been added. When the first two players win a game, the digital tubes will count the win and the game will continue.
10. A new game pause button has been added. When the key 0 is held down for a long time, the game will pause. When you long press key 1, the game starts.
11. A new game start button has been added. When you long press key 1, the game begins.
12. For Mode 1, add reverse display and restoration of the flowing light. When the button is held down for a long time, the flowing light will run in reverse. When the button is held down for a long time
3 will resume its original operation mode.
