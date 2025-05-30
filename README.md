## Heuristic Search for Puzzle Solving Games

The objective of this project is to compare search-based algorithms to determine the most efficient strategies for solving specific puzzles and games, focusing on A*, Uniform Cost Search, and Greedy Best-First Search. This project will analyze how different heuristics—both simple and domain-specific—affect algorithm performance. The evaluation metrics include speed, solution quality (accuracy), and computational resource usage (memory and processing time).

## Problem Statement 

The primary challenge in puzzle-solving using search-based algorithms is identifying heuristics that balance search speed and solution quality without over-consuming computational resources. While simpler heuristics, such as Manhattan distance, offer computational efficiency, they may not always yield the optimal solution in the shortest time. In contrast, more complex, domain-specific heuristics could lead to better results but might demand higher memory and processing power. This project will compare the performance of search algorithms on four selected puzzles, each featuring a domain-specific heuristic, to analyze the trade-offs between simple and complex heuristics.

## Games and Heuristics 

I will concentrate on the following four games, each allowing for unique heuristic designs: 

### ● Sliding Puzzle (8-puzzle) 
    ○ Heuristics: Manhattan distance (simple) vs. Misplaced Tiles (more complex)
    ![PuzzleImg](https://github.com/user-attachments/assets/2b42c761-057b-4331-a246-179aaed8fb5e)

  
### ● MazeSolving (grid-based) 
    ○ Heuristics: Euclidean distance (simple) vs. an advanced heuristic that factors in obstacle density and path complexity 
    ![MazePuzzle](https://github.com/user-attachments/assets/a923187e-aed5-4efa-9880-62c20fda68c3)

  
### ● SnakeGame 
    ○ Heuristics: Distance to food (simple) vs. an extended heuristic that accounts for path safety and self-collision avoidance
    ![AStar](https://github.com/user-attachments/assets/631803c0-7796-43f1-ba5a-a665fc17ae3b)

    
### ● Rubik’s Cube 
    ○ Heuristics: Colour mismatches to compare A* and Uniform Cost search
    ![uniform metric](https://github.com/user-attachments/assets/f5839ec4-2a43-4bfe-87d7-5dccfbdae812)


## Algorithms 

### ● A*: Combines the cost to reach the current node and the heuristic to evaluate the most promising path. 
### ● Uniform Cost Search: Considers only the path cost without any heuristic, ensuring the lowest-cost path is prioritized. 
### ● Greedy Best-First Search: Relies solely on the heuristic value to choose the next node, providing insight into heuristic influence on performance.

## Conclusion 
In conclusion, this project has provided valuable insights into the performance and trade-offs of various AI search algorithms applied to four different puzzle-solving problems. 

Across all the games, A* emerged as the most balanced algorithm, effectively combining speed and accuracy in problems like the Sliding Puzzle, Maze Solver, and Snake Game, although its performance was inconsistent at times. 

Greedy Best-First Search demonstrated stable performance with moderate results, making it suitable for situations where speed is prioritized over optimality, especially in the Snake Game and Rubik's Cube. 
On the other hand, Uniform Cost Search showed its strength in problems requiring guaranteed optimality, such as the Sliding Puzzle and Rubik’s Cube, but its performance was often hampered by inefficiencies and a tendency to get stuck in more complex scenarios, particularly in the Snake Game. 

This project has underscored the importance of selecting the appropriate algorithm based on the specific problem's constraints and objectives. Whether optimizing for speed, accuracy, or resource efficiency, the algorithms demonstrated distinct strengths and weaknesses, reinforcing the value of a strategic approach to problem-solving. 

I would like to express my sincere gratitude to my professor for providing me with the opportunity to explore and experiment with different AI algorithms across diverse problem statements. This experience has deepened my understanding of algorithmic strategies and their practical applications, and I am thankful for the chance to engage in such a rich learning process.
