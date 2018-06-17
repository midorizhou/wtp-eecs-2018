# WTP CS Problem Set 8.2 - Hangman: Day 2

You'll need your solution from problem set 8.1. Duplicate your problem set 8.1 solution into your problem set 8.2 folder and call it `hangman.py`.

### 1. Warm Up -  Drawing Hangman - `drawing.py`
Before we start modifying our hangman game from yesterday, let’s get some practice using `graphics.py`. Be sure to take a look at the overview in `graphics.py` for an example; if you get stuck, try running the example code written in the comments of `drawing.py`.  

For this question, write a program in `drawing.py` that draws the scaffold, head, torso, left leg, right leg, left arm, and right arm of the hangman in a window. 
 
Check that your program draws the parts correctly before moving on to the next question!
*Hint 1: Read 3.1, 3.2, and 3.3 in the graphics reference.
Hint 2: Consider writing individual functions that draw each body part*
 
### 2. Setting up the Window/Background - `hangman.py`
Edit your own `hangman.py` file from yesterday so that it creates a window and draws your scaffold similar to in question 1 before running the game from yesterday. 

At the top of your file `hangman.py` file from yesterday, add the line:
```python
from graphics import *
```
Remember: this allows you to access classes and functions in `graphics.py` in your own file. Make sure your game still runs correctly before moving on!
 
### 3. Incorrect Guesses - `hangman.py`
After every incorrect guess, your program needs to draw a new part of the hangman. You can accomplish this by writing one function that draws a new part based on the number of incorrect guesses or by writing 6 functions, each of which is called after a specific number of incorrect guesses. 
 
### 4. Win/Lose - `hangman.py`
When the game is over, display a message that tells whether Player 2 won or lost in the game window.
*Hint: Read 3.7 in the graphics reference.*

### 5. Win/Lose Unique Endgame Displays (Optional) - `hangman.py`
Instead of just displaying a Text message when the game ends, make unique endgame displays for when Player 1 wins and for when Player 2 wins. Feel free to make these whatever you want - be creative!

### 6. Secret Word with Guessed Letters (Optional) - `hangman.py`
Modify the display function you made yesterday to show the current guessed secret word in the game window rather than the terminal.

### 7. Previously Guessed Letters (Optional) - `hangman.py`
Modify your program so that the window also displays all of the letters that Player 2 had previously guessed.
 
### 8. Enter Guesses (Challenge) - `hangman.py`
Use the graphics object Entry (section 4 in the reference) to have Player 2 input guesses directly in the game window.
*Hint: Use getMouse()*
		 	 	 		
### Submitting your PSET
After you’ve finished your PSET, log into your Edmodo account, find the post for Problem Set 8.2, click "Open Assignment", attach all of the files that you created or edited for Problem Set 8.2, and then click "Turn in Assignment". You can resubmit the assignment as many times as you'd like. After you turn in your assignment, you're all done!
