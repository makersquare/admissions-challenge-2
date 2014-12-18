# Admissions Challenge 2 of 2: Tic-Tac-Toe

In this project you will be finishing an implementation of the game **tic-tac-toe**.

### When you're finished...

[Submit your solution here.](https://makersquare.typeform.com/to/NWK8PH) Upon submission, you'll automatically be taken to schedule your Technical Interview.

**Note**: Please do not schedule a Technical Interview before conducting your "Admissions Q&A Interview". E-mail admissions@makersquare.com for any further clarification.

### Getting Started

[Download this project](https://github.com/makersquare/admissions-challenge-2/archive/master.zip). You will be writing code in **main.js** for this project.

### Step 1: Getting it Working

Complete the code to do the following requirements:

- Correctly check for a game winner
- Alert the game winner

### Step 2: Stop Cheating!

A player can override the other player's space! This is because the game does not check if a space has been filled or not.

1. Update your `#board .space` click handler to check if a space is free before attempting to fill it in. If the space is filled, tell the player that the space is already taken.
2. Make sure the game does not continue after someone has won.

**HINT:** Do you know about JavaScript truthy and falsey values? `NaN` is a **falsey** value, while a string is a **truthy** value. Take advantage of this when checking the current value of a space.

### Extensions

Completing extensions are optional (but great!). You can complete them in any order you want.

1. Add a button to start a new game after one has finished. Keep track of the number of wins/losses for each player.

2. Add a fancy animation when someone wins. For example, make each space fade in and out in cascade.

3. Add a way for each player to set their player names.

4. Add a way for each player to set their player avatar (to replace the veggies/junkfood avatars).

5. Store game and player information (wins/losses, set player names, player avatars) in [local storage](http://diveintohtml5.info/storage.html) so that the information persists when the page is reloaded.
