# A-menagerie-of-AL
From cellular automata to adaptive simulations, exploring the beauty of artificial life and emergent complexity.

## Conway's Game of Life
Created by mathemetician John Conway in 1970, this solitaire style zero-player game illustrates how a simple set of rules can lead to the emergence of evolving patterns and even complex behaviors. On a grid of infinite size, each square on the grid, called a cell, is either dead or alive. On the first turn, a player may set up a pattern of living and dead cells or the initial state of the grid could be randomly determined. On each subsequent turn, the grid is updated according to the following rules:

- Birth: A dead cell with 3 living neighbors lives.
- Survival: Every cell with 2 or 3 living neighbors lives.
- Death: Every cell with 4 or more neighbors dies from overopulation. Every cell with 1 or fewer neighbors dies from isolation.


Source: [MATHEMATICAL GAMES - The fantastic combinations of John Conway's new solitaire game "life"](https://web.stanford.edu/class/sts145/Library/life.pdf)

### Areas for exploration and experimentation
- Various methods for displaying the grid from a UI/UX perspective
- Data structure represenations of the grid (2 dimensional array, hash map, etc.)
- Optimization techniques (rule check algorithms, parallel proccessing, etc.)
- Benchmarking of differning implementations
- Detection of still lifes (patterns that do not change) and repeating patterns
- Consider the reality of finite computer resources (simulate a flat board of finite size vs. one that wraps around on itself.)
- Explore different rule sets that stray from Conway's original game
