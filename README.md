# Alien Invasion (2D Game)

## Overview
Alien Invasion is a 2D game where players control a spaceship to fend off waves of aliens. The game includes scoring, levels, and a high score feature.

## How to Run

1. **Download the Code:**
    - Download the code as a zip file and extract it.

2. **Install Dependencies:**
    - Ensure you have Python installed.
    - Install the `pygame` package by running:
      ```sh
      pip install -r requirements.txt
      ```

3. **Run the Game:**
    - Execute the game with the following command:
      ```sh
      python alien_invasion.py
      ```

## Game Window Fields

- **Top Left:** Number of ships left.
- **Top Center:** High score.
- **Top Right:** Current score.
- **Top Right Below Score:** Current level.

## Game Controls

- **Move Ship:** Use arrow keys (left/right) to move the ship.
- **Fire Bullets:** Press the space bar to shoot bullets.

## Adjusting Game Settings

To control various aspects of the game such as ship speed, bullet speed, and alien fleet speed, modify the corresponding values in `settings.py`.

Example settings you can adjust:

```python
# Ship settings
self.ship_speed = 1.5

# Bullet settings
self.bullet_speed = 1.0

# Alien settings
self.alien_speed = 1.0