# Agentic_AI
Agentic AI refers to an artificial intelligence system that operates autonomously, making decisions and taking actions to achieve a defined goal while adapting to dynamic environments.

## Problem Setup

## 1. Agent Setup
- The agent begins at the coordinate (0,0), which is the top-left corner of the grid.
- The goal is to reach (9,9), the bottom-right corner.
- As it moves, it records the path it takes.
## 2. Obstacle Generation
- 15 obstacles are randomly placed on the grid.
- The placement ensures that:
- The agent’s start position (0,0) is never blocked.
- The goal position (9,9) is never blocked.
- Obstacles are placed in random positions but do not completely block the agent’s path (ideally).
## 3. Movement Logic
- The agent moves one step at a time toward the goal.
It follows an intelligent decision-making process:
- Prioritize moving right (increasing x) or down (increasing y), as these moves bring it closer to (9,9).
- If an obstacle blocks the preferred move, the agent chooses an alternate path (like moving left or up if necessary).
- The agent avoids revisiting the same position unnecessarily to prevent looping.
- The goal is to find an efficient path to (9,9) while avoiding obstacles.

### In the given scenario:

- Autonomous Navigation – The agent independently moves from (0,0) to (9,9) without external intervention.
- Obstacle Awareness – It detects and avoids randomly placed obstacles while ensuring an efficient path.
- Goal-Driven Behavior – The AI prioritizes movements that bring it closer to the goal (9,9) while avoiding loops.
- Decision-Making – The agent evaluates the best possible move step-by-step based on current conditions.
- Memory and Adaptability – It tracks its path to prevent getting stuck and adjusts movements when encountering blocks.
