# Hacker School application programming tasks

Write code to implement one of the programs below. Use a programming lanugage you are comfortable with. Try and use just the standard library of your chosen language.  Don’t spend more than a couple of hours on your program.  Only implement the functionality described in the task description.  If a description says, "write a function...", it is fine to write helper functions, too.

## Database server

Write a program that runs a server that is accessible on `http://localhost:4000/`.  When your server receives a request on `http://localhost:4000/set?somekey=somevalue` it should store the passed key and value in memory.  When it receives a request on `http://localhost:4000/get?key=somekey` it should return the value stored at `somekey`.

## Depth-first searcher

Write a function that can search a tree of nodes, depth first. The function should take a node name and tree.  If it finds the named node, it should return the node.

For example, if the function is passed `g` and a tree with the structure below, it should return the node named `g`.

       a
      / \
     b   c
    /|\   \
   d e f   g
           |
           h

## Lisp parser

Write a function that takes some Lisp code and returns an abstract syntax tree.  The AST should represent the structure of the code and the meaning of each token.  For example, if your function is passed `"(first (1 (+ 2 3) 9))"`, it should return something like `["first", [1, ["+", 2, 3], 9]]`.  In this example AST, the square brackets indicate arrays.

## Tic Tac Toe game

Write a program that lets two humans play a game of Tic Tac Toe in a terminal.  The program should let the players take turns to input their moves.  The program should report the outcome of the game.

## Fibonacci sequence generator

Write a function that takes a number `n` and returns the nth Fibonacci number.

## Mapper

Write a function that takes a function and an array. It should make a new, empty array, run the function on each element in the original array and insert each return value into the new array. It should return the new array.

For example, if your function is passed an array `[1, 2, 3]` and a function that returns the square of the number it is passed, your function should return `[1, 4, 9]`.
