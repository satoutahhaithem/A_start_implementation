# A* Algorithm Implementation with Tkinter

## Overview

Embark on a journey through the implementation of the A* pathfinding algorithm, seamlessly woven into the fabric of Python's Tkinter package. A testament to efficiency in graph traversal, this algorithm elegantly balances heuristic functions and node costs to pave the way from start to goal.

## Technical Nuances

Picture a 25x25 grid, where each square signifies a strategic step. The dance of movement, be it vertical, horizontal, or diagonal, is choreographed with a uniform cost of one. Enter the heuristic luminary, the square Manhattan distance, shaping the algorithm's perception of cost-effectiveness.

**Manhattan Distance Illuminated:**
\[ \text{Manhattan Distance} = | x_1 - x_2 | + | y_1 - y_2 | \]

The algorithm gracefully pirouettes through procedural steps, mirroring the pseudocode symphony found on the revered Wikipedia stage.

[Pseudocode Waltz](https://en.wikipedia.org/wiki/A*_search_algorithm)

## Visual Symphony

The denouement unfolds on a Tkinter canvas, a graphical interface orchestrating the A* algorithm. Each pixel on the grid narrates the algorithm's saga—decision-making in real-time, navigating obstacles, and embracing the allure of the least costly path.

<div style="text-align:center;">
  <img src="anim.png" alt="Untitled" width="70%">
</div>

## Dance of Interaction

Engaging with the canvas is akin to a pas de deux:

1. **Choose the Origin:**
   - A click designates the starting point, setting the stage for the algorithmic performance.

2. **Navigate to Destiny:**
   - A second click establishes the endpoint, where the algorithm aims to deliver its protagonist.

3. **Obstacles as Props:**
   - Click and hover to summon obstacles, a ballet of hindrances. Click again to conclude the obstacle interlude.

4. **Commence Algorithmic Overture:**
   - The 'Enter' key initiates the algorithm, a crescendo of computation unfolding on the stage.

5. **Encore, Restart:**
   - The 'R' key commands a restart, an invitation to craft a new narrative with fresh starting and ending points.

**Note:**
- Obstacle embellishment is optional; the algorithm gracefully proceeds with only the start and goal in focus.
- Witness the algorithm's choreography, unraveling the optimal path with each calculated step.

This implementation beckons exploration, offering a visually enthralling saga of the A* algorithm. Users are not just spectators; they are active participants, guiding the algorithm through a ballet of points and paths.
