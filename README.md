# 8-Puzzle
## Solution of 8-Puzzle Problem Using A* Algorithm
### A* Algorithm
A* Search algorithm is one of the best and popular technique used in path-finding and graph traversals
Informally speaking, A* Search algorithms, unlike other traversal techniques, it has “brains”. What it means is that it is really a smart algorithm which separates it from the other conventional algorithms. This fact is cleared in detail in below sections.
And it is also worth mentioning that many games and web-based maps use this algorithm to find the shortest path very efficiently (approximation).

### f-score
What A* Search Algorithm does is that at each step it picks the node according to a value-‘f’ which is a parameter equal to the sum of two other parameters – ‘g’ and ‘h’. At each step it picks the node/cell having the lowest ‘f’, and process that node/cell.

### g-score
g-score is the movement cost to move from the starting point to a given square on the grid, following the path generated to get there

### h-score
h-score the estimated movement cost to move from that given square on the grid to the final destination. This is often referred to as the heuristic, which is nothing but a kind of smart guess.
