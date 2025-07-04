Space Shooter Game - Alien Room 13


A classic space shooter game built with Pygame where you defend against alien invaders. This project features Arabic title localization and immersive sound effects.

Game Features
Dynamic enemy movement: Aliens move horizontally and advance downward

Weapon system: Fire projectiles at enemy ships

Score tracking: Earn points for each alien destroyed

Immersive audio: Background music and sound effects

Responsive controls: Smooth ship movement and shooting mechanics

Arabic localization: Game title in Arabic ("alien أوضة 13")

Game Assets
Asset Type	Files
Images	19140031 (1).jpg (background), ufo.png (icon), astronomy.png (player), alien.png (enemy), bullet.png (projectile)
Sounds	background.wav (music), laser.wav (shooting), explosion.wav (enemy hit)
Requirements
Python 3.x

Pygame library (pip install pygame)

Installation
Clone the repository:

bash
git clone https://github.com/your-username/space-shooter.git
cd space-shooter
Install dependencies:

bash
pip install pygame
Place all game assets (images and sounds) in the same directory as main.py

How to Play
Run the game:

bash
python main.py
Controls:

Left Arrow: Move spaceship left

Right Arrow: Move spaceship right

Space: Fire weapon

Objective:

Shoot as many alien ships as possible

Prevent aliens from reaching the bottom of the screen

Achieve the highest score

Game Mechanics
Player ship moves horizontally at the bottom of the screen

Enemies spawn randomly at the top and move in patterns

Each enemy hit increases your score

Bullets disappear when they reach the top of the screen

Game continues indefinitely (no win/lose condition in current version)

Customization
You can easily modify these game parameters in the code:

python
# Number of enemies
num_of_enemies = 10

# Player movement speed
playerX_change = 0.4

# Bullet speed
bulletY_change = 1

# Enemy movement characteristics
enemyX_change.append(0.4)
enemyY_change.append(3)
Future Improvements
Add player lives and health system

Implement different enemy types with varied behaviors

Create levels with increasing difficulty

Add game over and victory conditions

Include power-up items

Add high score tracking

Known Issues
Enemies don't have collision with player ship

No game over condition when enemies reach bottom

Score doesn't reset after each game session

Limited visual feedback for hits

Dependencies
Pygame: Handles graphics, sound, and input

Math module: Calculates collision detection
