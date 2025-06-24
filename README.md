# Multiplayer DSA Snake Game (C++) 🐍

A classic Snake game implemented in C++ supporting two players simultaneously. The project emphasizes the use of fundamental data structures and algorithms (DSA) to manage game logic efficiently.

## Features ✨
- Two-player mode with independent snake controls  
- Real-time snake movement and collision detection  
- Dynamic food spawning and snake growth  
- Console-based interface for simplicity and performance

## Data Structures & Algorithms 📚
- **Linked Lists:** Each snake is represented as a linked list to efficiently add or remove segments during movement and growth  
- **Queues:** Manage the order of snake segments for smooth movement updates  
- **Collision Detection:** Algorithms to check snake collisions with walls, self, and other snake using coordinate comparisons  
- **Randomization:** Food spawning uses pseudo-random number generation to appear at valid positions on the grid  
- **Game Loop:** Implements an efficient game loop with input polling, state updates, and rendering

## Controls 🎮
- **Player 1:** W (up), A (left), S (down), D (right)  
- **Player 2:** Arrow keys (↑ ↓ ← →)

## How to Compile and Run ⚙️
1. Clone the repository:
   ```bash
   git clone https://github.com/yashp1932/DSA-Snake-Game.git
   '''
2. Navigate to the project directory:
      ```bash
   cd DSA-Snake-Game
   '''
3. Compile the code:
   ```bash
   g++ -o snake_game main.cpp
   '''
4. Run the executable
      ```bash
   ./snake_game
   '''
---
## Gameplay 🕹️
Control your snake to eat food and grow longer while avoiding collisions. The game ends if your snake crashes into a wall, itself, or the other player's snake. Challenge yourself or a friend in this fast-paced classic!

