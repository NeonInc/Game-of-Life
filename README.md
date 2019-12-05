# Game-of-Life
## A Python implementation of John Conway's classic cellular automaton Game of Life

This code implements game of life with variable start patterns and update speed.

The rules for the Game of Life are as follows,

For a cell that is alive:
- Any cell with one or no neighbors dies - Isolation.
- Any cell with four or more neighbors dies - Overpopulation.
- Any cell with two or three neighbors survives - Survival.

For a cell that is dead:
- Any cell with three neighbors becomes alive - Reproduction.

### Dependencies (pip install)
```
pygame
pygame-menu==1.96.1
```
### Usage

```
python3 game_of_life.py
```

#### Main Menu
