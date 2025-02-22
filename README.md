# Self-Driving Car Using NEAT and Pygame
This project is a self-driving car simulation where you can draw a path for the car to follow, and the car uses the NEAT (NeuroEvolution of Augmenting Topologies) algorithm to learn and drive along the path autonomously. The system leverages the power of artificial neural networks to train the car in real-time based on the user's drawn path.

Requirements
To run this project, you'll need Python 3.x and the following libraries:

pygame: for rendering the canvas where you can draw the path.
neat-python: for implementing the NEAT algorithm to train the car.

The project is compatible with Python versions suited for both pygame and neat-python.

Python Version Compatibility
Python 3.6 or higher is recommended.
Make sure you have pygame and neat-python installed in your environment for proper functionality.

Installation
Follow these steps to set up the project on your local machine.

Install Python 3.x
If you don't have Python 3.x installed, you can download it from the official Python website.

Install Dependencies
Install pygame and neat-python by running the following commands in your terminal or command prompt:

pip install pygame

pip install neat-python

Run the Project
You can start the simulation by running:

##python main.py

The Pygame window will open, and you can start drawing the path for the car to follow.




How It Works
1. Drawing the Path
Once the game window is open, you can draw the path by holding the mouse button down and moving the cursor along the path you want the car to follow.
The path will be recorded, and the car will attempt to follow it by learning using the NEAT algorithm.

2. Car Learning Process
The car uses the NEAT algorithm to evolve its neural network through generations.
Each generation tries to improve the car's performance by adjusting weights and connections in the neural network.
The car continuously learns to drive along the drawn path by evaluating its performance, with each new generation becoming better.

4. NEAT Algorithm
NEAT evolves neural networks by adding new nodes and connections over generations.
The fitness of the car’s driving performance is evaluated based on how well it stays on the path.
The algorithm evolves better strategies to improve the driving behavior over multiple iterations.


Instructions
Draw the Path: Click and hold the left mouse button to draw the path on the screen. The car will learn to follow the path you create.
Press C to Continue: After drawing the path, press the C key to start the car's learning process and begin simulating.
Toggle Path Lines with H: Press the H key to toggle the visibility of the drawn path lines. This allows you to view or hide the path as needed while the car is learning.

