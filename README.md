# Hacker School application programming tasks

Write code to implement one of the programs below. Use a programming lanugage you are comfortable with. Try and use just the standard library of your chosen language.  Don’t spend more than a couple of hours on your program.  Just implement the functionality described in the task description.

## Key/value data store server

Write a program that runs a server that is accessible on `http://localhost:4000/`.  When your server receives a request on `http://localhost:4000/set?somekey=somevalue` it should store the passed key and value in memory.  When it receives a request on `http://localhost:4000/get?key=somekey` it should return the value stored at `somekey`.

## Depth-first search

Write a function that takes a node name and a tree of nodes. The function should search the tree, depth first. If it finds a node with the passed node name, it should return the node.

For example, if the function is passed `g` and a tree with the structure below, it should return the node named `g`.

       a
      / \
     b   c
    /|\   \
   d e f   g
           |
           h
