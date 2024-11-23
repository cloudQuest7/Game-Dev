
# **Steve Jumps - README**

Welcome to **Steve Jumps**, a fun and fast-paced 2D platformer game where the player controls "Steve" as he dodges obstacles and tries to survive as long as possible! Below you'll find a breakdown of the project, key scripts, and instructions to get you up and running.

## **Table of Contents**
1. [Project Overview](#project-overview)
2. [Game Mechanics](#game-mechanics)
3. [Key Scripts](#key-scripts)
4. [How to Run](#how-to-run)
5. [Contributing](#contributing)
6. [Future Improvements](#future-improvements)
7. [License](#license)

---

## **Project Overview**

This game is designed as a fun jumping challenge with side-scrolling mechanics. Steve automatically runs, and the player needs to jump and avoid various obstacles while the background scrolls continuously.

- **Genre**: Endless Runner / Platformer
- **Current State**: Prototype/Initial Draft
- **Goal**: Avoid obstacles and survive as long as possible!

## **Game Mechanics**
- **Player Control**: Steve runs from left to right. Players can control when he jumps.
- **Obstacles**: Avoid obstacles that spawn periodically. The game gets faster as time progresses, increasing the difficulty.
- **Scrolling Background**: The background scrolls continuously to simulate Steve’s running movement.

## **Key Scripts**

Here’s a breakdown of the core scripts in the game:

1. **MoveLeft.cs**
   - Controls the movement of objects in the game like obstacles and ground that move from right to left to simulate the player’s movement.

2. **PlayerController.cs**
   - Handles all the player inputs (jumping, running) and interactions with the game environment.

3. **RepeatBackground.cs**
   - Manages the infinite scrolling background, resetting its position to give the impression of continuous motion.

4. **SpawnManager.cs**
   - Responsible for spawning obstacles dynamically as Steve progresses through the level.

---

## **How to Run**

1. **Clone the Repository**:
    ```
    git clone https://github.com/yourusername/Steve-Jumps.git
    cd Steve-Jumps
    ```

2. **Open in Unity**:
    - Make sure you have Unity installed. Open the project in Unity by selecting the folder in the Unity Hub.
    - Alternatively, open the folder directly via the Unity editor: `File -> Open Project`.

3. **Hit Play**:
    - In the Unity Editor, simply hit the Play button to test the game and start Steve's adventure!

---

## **Contributing**

We are always looking for improvements and new features! If you're interested in contributing:

1. **Fork the Repository**: Create your own copy on GitHub.
2. **Create a Branch**: Work on your feature or fix in a separate branch.
    ```
    git checkout -b feature/my-awesome-feature
    ```
3. **Submit a Pull Request**: Once your changes are ready, submit a PR, and we'll review it!

---

## **Future Improvements**
- **Power-ups**: Add collectable items that give Steve temporary abilities.
- **Enhanced Obstacles**: More variety in the types of obstacles.
- **Sound Effects**: Adding background music and sound effects to enhance the player's experience.
- **Leaderboard**: Implementing a global leaderboard to track high scores.
  
Feel free to suggest more ideas!

---

## **License**

This project is open-source and free to use under the MIT License. See the `LICENSE` file for more details.

Happy developing! 🎮🚀

--- 

Let me know if you'd like to tweak anything or add additional sections!
