# Snake Game Readme

## Introduction
This is a simple Snake game implemented in Python using the Pygame library. The game features a snake that moves around the screen, eating apples to grow longer. The objective is to achieve the highest possible score without colliding with the boundaries or the snake's own body.

## Files
- **snake.py**: The main Python script containing the game implementation.
- **Graphics/**: Directory containing image files used in the game.
  - **apple.png**: Image of the apple that the snake eats.
  - **body_bottomleft.png, body_horizontal.png, body_topleft.png, body_topright.png, body_vertical.png**: Images representing different segments of the snake's body for proper graphics rendering.
  - **food_G1U6tlb.mp3**: Sound file played when the snake eats an apple.
  - **head_down.png, head_left.png, head_right.png, head_up.png**: Images representing the snake's head facing different directions.
  - **tail_down.png, tail_left.png, tail_right.png, tail_up.png**: Images representing the snake's tail facing different directions.

## Installation
1. Ensure you have Python installed on your machine.
2. Install the Pygame library by running the following command in your terminal or command prompt:
   ```bash
   pip install pygame

## How to Play
1. Run the `snake.py` script.
2. Use the arrow keys (UP, DOWN, LEFT, RIGHT) to control the snake's movement.
3. The snake will grow longer each time it eats an apple.
4. Avoid collisions with the boundaries and the snake's own body.
5. The game ends if the snake collides, and you can restart by running the script again.

## Customization
Feel free to customize the game by modifying the graphics or sound files in the `Graphics/` directory. You can also tweak parameters such as `cell_size` and `cell_number` in the `snake.py` script to change the game's appearance and difficulty.

## Acknowledgments
- The game graphics are based on images from various sources.
- The Pygame library is used for handling game development in Python.
