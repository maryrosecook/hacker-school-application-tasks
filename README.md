# Hacker School application programming tasks

Write code to implement one of the programs below. Use a programming lanugage you are comfortable with. Try and use just the standard library of your chosen language.  Don’t spend more than a couple of hours on your program.  Only implement the functionality described in the task description.  If a description says, "write a function...", it is fine to write helper functions, too.

## Key/value data store server

Write a program that runs a server that is accessible on `http://localhost:4000/`.  When your server receives a request on `http://localhost:4000/set?somekey=somevalue` it should store the passed key and value in memory.  When it receives a request on `http://localhost:4000/get?key=somekey` it should return the value stored at `somekey`.

## Depth-first search

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
