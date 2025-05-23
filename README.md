# Unit-Project-

Project Idea
I'm building a simulation of predator-prey behavior where rabbits roam and avoid foxes, and foxes chase rabbits using simple autonomous agent logic.

What I’m Modeling
I’ll have a Rabbit class and a Fox class.

Each class will extend a base Agent class that includes properties for position, velocity, and acceleration using vectors.

Rabbits will wander randomly, while foxes will seek the nearest rabbit.

Variables and Data Structures
An array of rabbits (e.g., let rabbits = [];) and an array of foxes (e.g., let foxes = [];).

Constants for maximum speed, steering force, and perception range.

A distance matrix might be used to optimize rabbit detection by foxes.

What I’ll Do in setup()
Initialize the canvas.

Create a population of rabbits (e.g., 20) and a smaller number of foxes (e.g., 5).

This will be based off of chapter 5!

Populate the rabbits and foxes arrays with new object instances.
