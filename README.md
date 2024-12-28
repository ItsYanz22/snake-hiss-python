# SNAKE HISS - Python
This repository contains two Python-based Snake games built using `pygame` and `random`:

**Snake Hiss - Classic** (**`snakegame.py`**): A classic Snake game with fixed speed.
**Snake Hiss - Speedy** (**`snakegame2.py`**): The Snake's speed increases each time it eats food.
Both games feature intuitive controls, a clean UI, and the ability to restart or quit after losing.

##Features
 -**Snake Hiss - Classic:**
  . Classic gameplay with a fixed speed.
  . Track your score during gameplay.
  . High-score tracking displayed when the game ends.
- **Snake Hiss - Speedy:**
  . Classic gameplay with a twist: the Snake's speed increases with each piece of food consumed.
  . Track your score and high-score after losing.
  . Speed resets when restarting the game.

## Project Structure:
  ```
├── snakegame1.py        # Snake game where the snake cannot pass through walls
├── snakegame2.py        # Snake game where the snake speed increases as the gamne advances
└── README.md            # Project documentation
```
## Screenshots:
  This is a representation of the game in action. As you guide the black Snake toward the red food, your score increases, and the Snake grows longer!

## Game Controls
![image](https://github.com/user-attachments/assets/50b07d8b-6c8a-4ddd-8317-2da628227d6b)

## How to Run the Games
  ### Step 1: Install Python and Pygame
  1. Ensure you have Python installed. Download it here.
  2. Install the Pygame library by running the following command in your terminal:
```bash
pip install pygame
```
  ### Step 2: Clone the Repository
  1. Copy the repository link:
```plaintext
https://github.com/yourusername/snake-hiss-python.git
```
  2. Clone it to your local machine:
```bash
git clone https://github.com/yourusername/snake-hiss-python.git
```
  3. Navigate to the repository folder:
```bash
cd snake-hiss-python
```
  ### Step 3: Run the Game
  Run either of the two games:

   .For Snake Hiss - Classic:
   ```bash
   python snakegame.py
   ```
   .For Snake Hiss - Speedy:
    ```bash
    python snakegame2.py
    ```
  ## Explanation of Code
   ### Common Features:
   Snake Movement: The Snake moves using arrow keys and grows when it eats food. Movement logic is handled using **`x1_change`** and **`y1_change`**.
   Food Generation: Food appears at random locations on the grid.
   Collision Detection: The game ends when the Snake collides with itself or the screen borders.
   Restart and Quit Options: After losing, players can restart (**`C`**) or quit (**`Q`**).

   ### Functions Used:
   **`our_snake(snake_block, snake_list)`**: Draws the Snake on the screen using its current coordinates.
   **` your_score(score)`**: Displays the current score on the screen.
   **`message(msg, color)`**: Renders and displays messages (e.g., "You Lost!").
   **`draw_food(x, y)`**: Draws food as a circle.
  ## Future Prospects:
   ### Here are some ideas for expanding this project:
   1.Add Multiplayer Support: Implement a two-player mode where players compete on the same screen.
   2.Introduce Obstacles: Add randomly placed obstacles to make the game more challenging.
   3.Enhance Visuals: Introduce new themes, Snake skins, or particle effects for food consumption.
   4.Leaderboard System: Store high scores locally or online for competitive play.
   5.Power-Ups: Add special items that shrink the Snake or freeze its speed temporarily.

  ## Contributing
   Feel free to fork this repository and submit a pull request to improve the games or add new features.
 
  ## License
   This project is open-source and free to use.


  


   


  



