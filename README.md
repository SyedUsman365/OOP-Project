# Invaders – A 2D Space Shooter Game

## Introduction
**Invaders** is a 2D arcade-style shooting game developed in **C++** using the **Raylib** graphics library. Inspired by the classic Space Invaders, the project aims to deliver a retro gaming experience while showcasing modern programming practices like object-oriented design and efficient graphics handling.

## Objectives
- Implement a simple but engaging 2D shooter game.
- Apply core C++ programming concepts such as classes, inheritance, and pointers.
- Learn the basics of game development including game loops, user input handling, collision detection, and sprite management.
- Gain practical experience with Raylib for game development.

## Tools and Technologies Used
| Tool/Technology | Purpose |
|-----------------|---------|
| C++ | Core programming language |
| Raylib | Graphics, input, and sound handling |
| Visual Studio Code / Code::Blocks | IDE for development |
| Git & GitHub | Version control and collaboration |
| Paint.net / Piskel | Custom 2D sprite design (optional) |

## Gameplay
- Control a spaceship at the bottom of the screen.
- Shoot enemy invaders moving horizontally and descending when reaching screen edges.
- Avoid enemy bullets and eliminate all enemies to win.
- Game ends if the player loses all lives or clears all waves.

## Features
- Player movement and shooting using keyboard input.
- Multiple waves of enemies.
- Collision detection for bullets and sprites.
- Score tracking and a Game Over screen.
- Basic sound effects and background music (optional).

## Controls
- **Arrow Keys**: Move left and right.
- **Spacebar**: Fire bullets.

## Game Loop Structure
1. **Initialize**: Set up window, load assets, initialize variables.
2. **Update**: Handle input, update objects, detect collisions.
3. **Draw**: Render all game elements on screen.
4. **Unload**: Free resources and close the window.

## Implementation Highlights
- Group enemy movement with edge detection and descent.
- Bounding box collision detection.
- UI elements like score display and Game Over menu.
- Basic sound management (if implemented).

## Testing and Debugging
- Manual testing for all modules: movement, shooting, collision, and scoring.
- Use of debug messages and Raylib's drawing functions during development.
- Handling of edge cases (e.g., bullets leaving the screen, multiple bullets hitting enemies).

## Challenges Faced
- Learning Raylib's structure and syntax.
- Timing-based bullet firing and movement.
- Precision and performance of collision detection.
- Code organization for scalability.

## Future Improvements
- Add multiple player lives and health bar.
- Introduce advanced enemy patterns and power-ups.
- Save and display high scores.
- Improve UI, animations, and polish.
- Add levels and boss fights for progressive difficulty.

## Conclusion
The **Invaders** project successfully demonstrates the fundamentals of 2D game development using C++ and Raylib. It provided hands-on experience in handling graphics, user input, and implementing core game mechanics, serving as a solid foundation for more advanced projects in the future.

---

## Setup and Running the Game
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/invaders-game.git
    ```
2. Navigate into the project directory:
    ```bash
    cd invaders-game
    ```
3. Compile the game using your preferred IDE (Visual Studio Code / Code::Blocks) with Raylib installed, or using g++:
    ```bash
    g++ main.cpp -o Invaders -lraylib -lGL -lm -lpthread -ldl -lrt -lX11
    ```
4. Run the game:
    ```bash
    ./Invaders
    ```

## License
This project is for educational purposes. Feel free to modify and improve it!

---
