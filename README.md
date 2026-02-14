# Snake Game

A classic Snake game implementation in Python using Pygame, featuring custom graphics, sound effects, and smooth gameplay mechanics.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Game Controls](#game-controls)
- [Game Rules](#game-rules)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [License](#license)

## Overview

This is a modern implementation of the classic Snake game where players control a snake that moves around the screen, consuming food to grow longer. The objective is to achieve the highest score possible while avoiding collisions with walls and the snake's own body.

## Features

- **Custom Graphics**: Unique sprite designs for snake head, body segments, and tail with directional variations
- **Dynamic Body Rendering**: Realistic corner pieces and smooth body transitions
- **Sound Effects**: Audio feedback when the snake consumes food
- **Score Tracking**: Real-time score display with visual indicators
- **Checkerboard Pattern**: Aesthetic grass-themed background
- **Collision Detection**: Accurate wall and self-collision detection
- **Smooth Controls**: Responsive arrow key navigation with direction locking
- **Game Over System**: Automatic reset upon collision

## Prerequisites

Before running the game, ensure you have the following installed:

- Python 3.7 or higher
- Pygame library

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MuhammadFurqanMohsin25Apr/Snakegame.git
   cd Snakegame
   ```

2. **Install dependencies**
   ```bash
   pip install pygame
   ```

3. **Verify required assets**
   
   Ensure the following asset files are present in the `snakegame` directory:
   - `apple.png` - Food sprite
   - `head_up.png`, `head_down.png`, `head_left.png`, `head_right.png` - Snake head graphics
   - `tail_up.png`, `tail_down.png`, `tail_left.png`, `tail_right.png` - Snake tail graphics
   - `body_horizontal.png`, `body_vertical.png` - Snake body segments
   - `body_bl.png`, `body_br.png`, `body_tl.png`, `body_tr.png` - Corner pieces
   - `Sound_crunch.wav` - Sound effect

## How to Play

1. Navigate to the game directory:
   ```bash
   cd snakegame
   ```

2. Run the game:
   ```bash
   python game1.py
   ```

3. Use arrow keys to control the snake
4. Eat apples to grow and increase your score
5. Avoid hitting walls or yourself

## Game Controls

| Key | Action |
|-----|--------|
| ↑ (Up Arrow) | Move Up |
| ↓ (Down Arrow) | Move Down |
| ← (Left Arrow) | Move Left |
| → (Right Arrow) | Move Right |

**Note**: The snake cannot reverse direction (e.g., cannot move down if currently moving up).

## Game Rules

1. The snake starts with a length of 3 segments
2. Each apple consumed increases the snake's length by 1 segment and adds 1 to the score
3. The game ends when the snake collides with:
   - Any wall boundary
   - Its own body
4. Upon game over, the snake resets to its initial state
5. The game area is a 15×15 grid with 40-pixel cells

## Project Structure

```
Snakegame/
│
├── snakegame/
│   ├── game1.py              # Main game file
│   ├── apple.png             # Food sprite
│   ├── head_*.png            # Snake head sprites
│   ├── tail_*.png            # Snake tail sprites
│   ├── body_*.png            # Snake body sprites
│   └── Sound_crunch.wav      # Audio effect
│
├── README.md                 # Project documentation
└── LICENSE                   # License information
```

## Technologies Used

- **Python 3**: Core programming language
- **Pygame**: Game development library for graphics, sound, and event handling
- **Vector2**: 2D vector mathematics for movement and positioning

## License

This project is licensed under the terms specified in the [LICENSE](LICENSE) file.

---

Enjoy playing and feel free to contribute or suggest improvements!
 
