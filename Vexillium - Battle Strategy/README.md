# Vexillium  - A Battle Strategy Game ⚔️🛡️🔥

<br>


## Overview  
*Vexillium* is a battle strategy game between a human player and AI. The goal is to outmaneuver your opponent and capture their flag. The game challenges players with strategic troop placement, resource management, and combat while providing adaptive AI with multiple difficulty levels.

<br>

## How to Play 

### 1. Starting the Game:

- Choose a difficulty level: Easy , Medium , God Level.
- Place your flag on any row in your starting column.

### 2. Troop Deployment:

- Deploy troops within the first three columns of your side.
- Select troop types (Circle, Square, Triangle) based on available elixir and strategy:
  - Circle: Power = 2, Health = 300, Cost = 2
  - Square: Power = 2, Health = 300, Cost = 4
  - Triangle: Power = 4, Health = 400, Cost = 3
- The elixir is recharged for both teams at an equal rate.

### 3. Combat:

- Troops automatically move towards the opponent's flag or nearest enemy.
- Combat resolves when opposing troops meet:
   - Higher health troop wins, but its health is reduced.
   - If health is equal, both are removed.

### 4. Winning the Game:

- Capture the opponent’s flag by reaching it with your troop.

<br>

## AI Overview  

### Pathfinding Algorithms:

- Greedy BFS (Easy): Moves directly toward the target, prioritizing speed.
- Uniform Cost Search (Medium): Considers movement costs and obstacles.
- A* (God Level): Combines cost and heuristic for optimal paths.


### Minimax Algorithm:

- Determines troop placement by evaluating offensive and defensive strategies.
- Incorporates alpha-beta pruning for efficiency.

<br>

### Ready, Set, CONQUER!

---
