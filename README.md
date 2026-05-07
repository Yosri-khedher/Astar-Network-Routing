# A* Network Routing Simulation

## Description
This project simulates network routing using the A* algorithm in Python under Google Colab.

The network is represented as a grid and graph structure where:
- each node represents a router
- obstacles represent network failures or congestion
- bandwidth and distance are used to calculate transmission cost

The A* algorithm searches for the optimal path between the source and destination.

## Cost Function

cost = distance / bandwidth

- high bandwidth → low cost
- low bandwidth → high cost
- long distance → high cost

## Features
- A* search algorithm
- Grid-based network simulation
- Dynamic path simulation
- Obstacles management
- Bandwidth integration
- Distance integration
- Cost optimization

## Technologies Used
- Python
- Google Colab

## Project Structure

- `Astar_Routing.ipynb` : Google Colab notebook
- `presentation.pptx` : project presentation

## Author
Yosri Khedher
Software Engineering Student
