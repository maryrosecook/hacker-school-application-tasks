# Hacker School application programming tasks

Write code to implement one of the programs below. Use a programming lanugage you are comfortable with. Try and use just the standard library of your chosen language.  Don’t spend more than a couple of hours on your program.  Just implement the functionality described in the task description.

## Key/value data store server

Write a program that runs a server that is accessible on `http://localhost:4000/` When your server receives a request on `http://localhost:4000/set?somekey=somevalue`, it should store `somevalue` at `somekey` in memory.  When it receives a request on `http://localhost:4000/get?key=somekey`, it should return the value stored at `somekey`.
