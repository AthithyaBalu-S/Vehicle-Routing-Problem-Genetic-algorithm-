# Vehicle-Routing-Problem-Genetic-algorithm

## Introduction
The Vehicle Routing Problem (VRP) is a classic optimization problem that aims to determine the optimal routes for a fleet of vehicles delivering goods to a set of locations. This project implements a solution using a Genetic Algorithm approach, leveraging Python and the DEAP framework.

## Features
- Randomly generated customer locations within a defined space.
- Support for multiple vehicles to optimize delivery routes.
- Evaluation of routes based on total distance traveled.
- Visualization of the routes using Matplotlib.

## Technologies Used
- Python 3
- NumPy
- Matplotlib
- DEAP (Distributed Evolutionary Algorithms in Python)

## Installation
To get started with the project, you need to install the required libraries. You can do this via pip:

```bash
pip install matplotlib deap
```

## Getting Started
1. Clone the repository:

```bash
git clone <repository-url>
cd <repository-directory>
```

2. Open the Jupyter Notebook:

```bash
jupyter notebook Vehicle_Routing_Problem-1.ipynb
```

3. Run the cells sequentially to generate customer locations, initialize the genetic algorithm, and visualize the routes.

## How It Works
1. **Customer Locations**: The project randomly generates a set number of customer locations and defines a central depot.

2. **Genetic Algorithm**:
   - Initialization of the population.
   - Evaluation of routes based on distance and standard deviation.
   - Selection, crossover, and mutation operations to evolve routes over generations.

3. **Visualization**: The optimized routes are plotted using Matplotlib to show the paths taken by each vehicle.

## Usage
After execution, the notebook will display a plot of the routes taken by each vehicle, showcasing how the algorithm optimizes delivery paths across all customer locations.

