# Maze Solving Program

## Overview

This program helps Reeborg the robot to navigate through a maze and find the exit. Reeborg follows the right edge of the maze using a series of movements and turns based on the state of the walls around it.

## How It Works

1. **Initial Setup:**
   - Reeborg starts by moving forward until it hits a wall.
   - Reeborg then turns left to begin following the right wall.

2. **Maze Navigation:**
   - Reeborg continuously checks its surroundings:
     - If the right side is clear, Reeborg turns right and moves forward.
     - If the right side is not clear but the front is clear, Reeborg moves forward.
     - If neither the right side nor the front is clear, Reeborg turns left.
   - This process continues until Reeborg reaches the goal.

## Functions Used

- `move()`: Moves Reeborg forward by one step.
- `turn_left()`: Turns Reeborg 90 degrees to the left.
- `right_is_clear()`: Checks if there is no wall to Reeborg's right.
- `front_is_clear()`: Checks if there is no wall directly in front of Reeborg.
- `at_goal()`: Checks if Reeborg has reached the goal.

## Conditions

- `if right_is_clear()`: Checks if there is a clear path to the right of Reeborg.
- `elif front_is_clear()`: Checks if there is a clear path in front of Reeborg.
- `else`: If neither the right nor the front is clear, Reeborg turns left.
## Output
![image](https://github.com/user-attachments/assets/626aaaf9-499f-4ed9-92b6-0bd23ebd12b1)


