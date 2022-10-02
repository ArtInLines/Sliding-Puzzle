# Sliding Puzzle

A [sliding puzzle](https://en.wikipedia.org/wiki/Sliding_puzzle) in this context defines a `n x m`-sized board filled with unordered numbers and one empty field. Only numbers adjacent to the empty spot can be moved to that place, effectively exchanging the position of the empty field and the moved number. The goal is to sort the numbers (reading from left to right and top to bottm) in the correct order in the least moves possible.

This repo stores submodules, which implement this puzzle in different programming languages. What functionality the modules implement is not predefined, but for now the only implementations allow the user to play the puzzle via the console. The current implementations further support letting the computer solve the puzzle using a pathfinding algorithm like A\*.
