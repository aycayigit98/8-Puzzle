# 8-Puzzle
## Solution of 8-Puzzle Problem Using A* Algorithm

We have some rules in order to solve 8-Puzzle. Instead of moving the tiles in the empty space we can visualize moving the empty space in place of the tile, basically swapping the tile with the empty space. The empty space can only move:
1. Up
2. Down
3. Right
4. Left

and can take only one step at a time.

Since uninformed search techniques take a lot of time to complete a search, since they don't know where to look, we use informed search.

### A* Algorithm
A* Search algorithm is one of the best and popular technique used in path-finding and graph traversals
Unlike other traversal techniques, it has “brains”. What it means is that it is really a smart algorithm which separates it from the other conventional algorithms. This fact is cleared in detail in below sections.
And it is also worth mentioning that many games and web-based maps use this algorithm to find the shortest path very efficiently (approximation).

Down below are given screenshots after program execution:

![astar1](https://user-images.githubusercontent.com/25644372/55915869-628b7d00-5bf3-11e9-958d-b2bb2166e4c9.PNG)

![astar2](https://user-images.githubusercontent.com/25644372/55915873-64554080-5bf3-11e9-90f2-eed7c8395e18.PNG)
