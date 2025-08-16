# Photo Gallery with Water Jug Problem Solution

This repository contains both a photo gallery and an implementation of the Water Jug Problem using state-space search algorithms.

## Files

- `photo gallery.html` - Original photo gallery implementation
- `water-jug-problem.html` - Water Jug Problem solution with BFS and A* algorithms
- `water-jug-tests.html` - Test suite for validating the algorithms

## Water Jug Problem Implementation

The Water Jug Problem demonstrates state-space search algorithms to solve the classic puzzle of measuring exactly 4 liters using two jugs with capacities of 3 and 5 liters.

### Features

1. **Part A: Basic Operations**
   - Fill Jug A (3L)
   - Fill Jug B (5L)  
   - Empty Jug A
   - Empty Jug B
   - Pour A → B
   - Pour B → A

2. **Part B: State Space Model**
   - State representation: (a, b) where a = amount in 3L jug, b = amount in 5L jug
   - Initial state: (0, 0)
   - Goal state: Any state containing exactly 4 liters
   - Total possible states: 24

3. **Part C: Algorithm Implementation**
   - Breadth-First Search (BFS)
   - A* Search with Manhattan distance heuristic
   - Interactive comparison showing performance metrics

### Running the Application

1. Open `water-jug-problem.html` in a web browser
2. Click on the algorithm buttons to see the solutions
3. Use "Compare Both Algorithms" to see side-by-side analysis

### Test Results

The implementation passes all validation tests:
- Both algorithms find optimal solutions (6 steps)
- A* explores fewer nodes (12 vs 14 for BFS)
- All state operations work correctly
- Goal state detection is accurate