# Apple Catcher Game

## Description
This is an interactive Apple Catcher game built using Scratch for CS50's Introduction to Computer Science. 

The objective of the game is to use a basket to catch falling red apples to increase your score while strategically avoiding green apples. If a red apple slips past your basket and touches the ground, you lose one of your three lives. The game features automated gravity, dynamic collision logic, variable data tracking, and a broadcast-triggered Game Over end-state.

### Features
* **Dynamic Score System:** Tracks and displays points instantly using variables.
* **Three-Life Constraint:** Tracks missed red apples and triggers a Game Over state upon reaching exactly three misses.
* **Obstacle Mechanics:** Includes falling green apples that penalize the player's total score by -1 if collected.
* **Global Game Freeze:** Utilizes event broadcasting to instantly stop all sprite loops and scripts when game over conditions are met.

## How to Play
1. Click the **Green Flag** to initialize and start the game loop.
2. Use the **Left Arrow Key** and **Right Arrow Key** to move the bowl horizontally across the bottom of the screen.
3. Catch the **Red Apples** to gain points.
4. Let the **Green Apples** fall safely to the floor, or avoid catching them to protect your score total.
5. Prevent the red apples from touching the ground. If **3 Red Apples** hit the floor, the game freezes and displays the Game Over screen.
