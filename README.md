# Bullet Hell Action Game

## Overview
The project mainly requires the use of programming paradigms, particularly imperative programming paradigms such as procedural programming and object-oriented programming. We chose to code our bullet hell game using Python with the PyGame library in the PyCharm IDE.

## Game Design
The bullet hell game consists of the stage background, player’s character, and the enemy of the stage. The player’s goal is to defeat the enemy of the stage by continuously shooting them with bullets while dodging the enemy’s attacks with four-directional movement.

## Implementation

#### Player
<img width="215" alt="Screen Shot 2024-05-31 at 10 28 53 PM" src="https://github.com/rliao123/Bullet-Action-Game/assets/92598518/2ca6e73e-4619-4476-89f1-bfbdc1a52451">
- The player is represented with a chinchilla icon and has four-directional movement controlled by arrow keys. 
- The player can shoot bullets by pressing the ‘z’ key.
- The player has a 6x6 rectangle hitbox for dodging enemy bullets.

#### Enemy
<img width="202" alt="Screen Shot 2024-05-31 at 10 29 29 PM" src="https://github.com/rliao123/Bullet-Action-Game/assets/92598518/ed0e68c8-089b-4f0e-860a-9bb9695f0743">

- The enemy is represented with an owl icon and has predetermined movements and attack patterns based on its health level.
- The enemy's health level is displayed via a yellow bar.
- The enemy shoots bullets with different patterns based on its health level.

#### Gameplay
<img width="169" alt="Screen Shot 2024-05-31 at 10 30 51 PM" src="https://github.com/rliao123/Bullet-Action-Game/assets/92598518/92f5dc12-9e3f-4024-8cb0-0165230f4364">
<img width="177" alt="Screen Shot 2024-05-31 at 10 29 12 PM" src="https://github.com/rliao123/Bullet-Action-Game/assets/92598518/627655aa-9924-4a96-b0d3-f43d67d52c86">
<img width="173" alt="Screen Shot 2024-05-31 at 10 29 45 PM" src="https://github.com/rliao123/Bullet-Action-Game/assets/92598518/d68f3ed9-471c-4acf-83ef-67ae7def839d">
- The game initializes player, enemy, and other variables before starting.
- It continuously updates the screen, checks for collisions, and handles game events.
- The player starts the game by pressing SPACE and tries to defeat the enemy without getting hit by enemy bullets. The game over screen is displayed depending on whether the player wins or loses.
<img width="135" alt="Screen Shot 2024-05-31 at 10 30 33 PM" src="https://github.com/rliao123/Bullet-Action-Game/assets/92598518/fd6f2125-9aa5-44dc-b608-8a3a93731ad9">

## Further Improvements
Future improvements could include multiple levels, different enemy movement patterns, and bullet pooling.

## Technical Details
- **Programming Language**: Python
- **IDE**: PyCharm
- **Library**: Pygame
