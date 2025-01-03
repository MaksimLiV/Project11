# Project 11: Pinball Game

## Overview

Project 11 is a simple pinball game built using SpriteKit. In this game, the player can interact with the game environment by placing obstacles and launching balls. The goal is to accumulate a high score by getting balls into "good" slots while avoiding "bad" slots. Players can also add obstacles to make the game more challenging.

## Features

- **Game Interaction**: 
  - Players can toggle between "Edit" mode and "Play" mode by tapping the "Edit" label.
  - In "Edit" mode, users can place obstacles on the screen.
  - In "Play" mode, the player can launch balls and try to score by getting them into the good slots.
  
- **Score System**: 
  - The player earns points for balls that land in the "good" slots.
  - Points are deducted for balls landing in the "bad" slots.

- **Game Over Conditions**:
  - The game ends when all obstacles are cleared or when the player runs out of balls.
  
- **Physics and Contacts**:
  - The game uses physics bodies and contacts for the balls, slots, and obstacles.
  - A collision detection system allows for the destruction of balls when they interact with the slots and obstacles.
  
- **Particle Effects**: 
  - When a ball is destroyed, a fire particle effect is shown.

- **End Game**: 
  - A message is displayed when the game ends, indicating whether the player has won or lost.

## Setup and Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/project11.git
