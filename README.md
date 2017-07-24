# OCR_Game_standalone

This is a multithread OCR game (application to recognize words in images). In this application there are:
1. A list of pictures of known words.
2. A list of pictures of unknown words.

# Gameplay:
- The goal of the game is to move the character from the initial position to the ending position.
- The user will be provided with two words, one of them is a known word and the other one is unknown. The user needs to input two words to proceed; if the known word matches with the word input by the user, we assume the second word he input is the correct value of the unknown word.
- By inserting the correct words, the user will make the character to move closer to the goal.

# NOTES:
This application has three threads (One main one that controls the gameplay; one that performs the running animation of the character and the spinning animation of the goal and a third one that performs the winning animation sequence).
