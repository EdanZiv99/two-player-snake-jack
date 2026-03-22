# Clash of Snakes – Two Player Snake Game (Nand2Tetris)

A two-player Snake game developed in the Jack programming language as part of the Nand2Tetris course.

The game features real-time interaction between two players, dynamic movement, collision detection, scoring logic, and a simple game loop running on the Nand2Tetris VM Emulator.

---

## Overview

Clash of Snakes is a competitive two-player version of the classic Snake game.

Each player controls a snake, trying to collect food and grow longer while avoiding collisions. The first player to reach 20 points wins.

This project demonstrates object-oriented design and game logic implementation under low-level constraints using the Jack language.

---

## Gameplay

- Two players control separate snakes simultaneously
- Players collect food to gain points
- Snakes grow as they eat
- Collisions result in game over
- First player to reach **20 points wins**

---

## Controls

- **Player 1**: Arrow keys (↑ ↓ ← →)
- **Player 2**: W A S D

- **ENTER** – Start game  
- **ESC** – Exit game

---

## How to Run

This project runs on the **Nand2Tetris VM Emulator**.

### Steps:

1. Open the VM Emulator (web [https://nand2tetris.github.io/web-ide/vm] or local version)
2. Click **Load files**
3. Select all files inside the `vm/` directory
4. Confirm the selection
5. Click **Run**

💡 The program starts automatically from `Main.vm`.

---

## Project Structure

```
src/
  Food.jack
  Game.jack
  Main.jack
  Random.jack
  Snake.jack

vm/
  Food.vm
  Game.vm
  Main.vm
  Random.vm
  Snake.vm
```

- `src/` – Original source code written in Jack  
- `vm/` – Compiled VM code used for execution  

---

## Demo

See the gameplay demo in:

Two_Players_Snake_Game_Demo.mp4

---

## Key Features

- Two-player real-time gameplay
- Object-oriented design in Jack
- Snake movement and growth logic
- Collision detection (self and opponent)
- Randomized food placement
- Game state management (start, play, game over)

---

## Technologies

- Jack (Nand2Tetris high-level language)
- VM Emulator (Nand2Tetris)
- Stack-based virtual machine architecture

---

## Authors

Developed as part of the **Nand2Tetris course**.

- Edan Ziv  
- Tomer Vaener