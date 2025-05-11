
# Project Report: Invaders – A 2D Space Shooter Game

## 1. Introduction

This report documents the development of a 2D arcade-style shooting game titled **"Invaders"**, built using **C++** and the **Raylib** graphics library. Inspired by the classic *Space Invaders*, the game aims to deliver a retro gaming experience while showcasing modern programming principles like object-oriented design and structured programming.

---

## 2. Objectives

The main objectives of this project were:

- To implement a simple but engaging 2D shooter game.
- To understand and apply core programming concepts in C++ such as classes, inheritance, and pointers.
- To learn game development basics including game loops, user input, collision detection, and sprite handling.
- To gain hands-on experience with Raylib, a simple and fast C library for game development.

---

## 3. Tools and Technologies Used

| Tool / Technology       | Purpose                                  |
|-------------------------|------------------------------------------|
| C++                     | Core programming language                |
| Raylib                  | Graphics, input, and sound handling      |
| Visual Studio Code / Code::Blocks | IDE for development         |
| Git & GitHub            | Version control and collaboration        |
| Paint.net / Piskel      | Designing custom 2D sprites (optional)   |

---

## 4. Gameplay and Features

### 4.1 Gameplay Description

- The player controls a spaceship at the bottom of the screen.
- Enemy invaders move horizontally and descend after reaching screen edges.
- The player must shoot the invaders while avoiding enemy bullets.
- The game ends if the player loses all lives or eliminates all enemies.

### 4.2 Game Features

- Player movement and shooting using keyboard input.
- Multiple waves of enemies.
- Collision detection between bullets and objects.
- Score tracking and Game Over screen.
- Basic sound effects and music (optional).

---

## 5. Game Loop Structure

The game follows the standard game loop:

1. **Initialize** – Set up window, variables, load assets.
2. **Update** – Handle input, update game objects, check collisions.
3. **Draw** – Render all game elements on the screen.
4. **Unload** – Free memory and close the window.

---

## 6. Implementation Overview

### 6.1 Player Controls

- **Arrow keys**: Move left and right
- **Spacebar**: Fire bullets

### 6.2 Enemy Movement

- Enemies move in groups horizontally.
- Upon reaching the screen edge, they descend and reverse direction.

### 6.3 Collision Detection

- Bounding box (rectangular) collision checks between bullets and enemy/player sprites.

### 6.4 UI Elements

- Score displayed at the top-left.
- Game Over screen with restart option.

### 6.5 Sound Effects

- Background music and shooting/explosion sounds (if implemented).

---

## 7. Testing and Debugging

- Manual testing for modules like player movement, shooting, collision, and scoring.
- Use of debug messages and Raylib’s inbuilt drawing functions for development visualization.
- Edge cases handled, such as:
  - Multiple bullets hitting the same enemy
  - Bullets leaving the screen

---

## 8. Challenges Faced

- Learning Raylib syntax and structure.
- Implementing timing-based bullet firing and movement.
- Managing collision precision and performance.
- Structuring code for scalability and readability.

---

## 9. Future Improvements

- Add multiple player lives and a health bar.
- Implement advanced enemy patterns and power-ups.
- Add high score saving functionality.
- Improve UI and animations.
- Introduce levels and bosses for progressive difficulty.

---

## 10. Conclusion

The Invaders game project successfully demonstrated core game development fundamentals using C++ and Raylib. It enabled the practical application of programming concepts and provided experience in graphics, input handling, game logic, and debugging. The project lays a solid foundation for future, more complex game development endeavors.
