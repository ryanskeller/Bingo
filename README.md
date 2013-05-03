Bingo
=====

Java coding excercise to focus on test driven development.


Bingo – create a random set of bingo cards. 
Rules – Cards must be unique
Number can only appear on the card once
There is a bonus space in the middle of the card
The card needs to be 5X5 so that the winner gets a BINGO by getting 5 numbers in a row

# Setup

## Get the code

``` 
git clone git@github.com:octanner/Bingo.git
```

## Bundle and Test

```
mvn clean
mvn install
mvn test
```

# Exercise

The universe of the Game of Life is an infinite two-dimensional orthogonal grid of square cells, each of which is in one of two possible states, alive or dead. Every cell interacts with its eight neighbours, which are the cells that are horizontally, vertically, or diagonally adjacent. At each step in time, the following transitions occur:

1. Any live cell with fewer than two live neighbours dies, as if caused by under-population.
2. Any live cell with two or three live neighbours lives on to the next generation.
3. Any live cell with more than three live neighbours dies, as if by overcrowding.
4. Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.

The initial pattern constitutes the seed of the system. The first generation is created by applying the above rules simultaneously to every cell in the seed—births and deaths occur simultaneously, and the discrete moment at which this happens is sometimes called a tick (in other words, each generation is a pure function of the preceding one). The rules continue to be applied repeatedly to create further generations.

http://en.wikipedia.org/wiki/Conway's_Game_of_Life
