# Particle_Swarm_Optimization
This project demonstrates Particle Swarm Optimization (PSO) on a Sphere minimization problem. It shows how particles update position and velocity using personal best and global best information, tracks convergence over iterations, and visualizes optimization progress. Created for learning swarm intelligence and metaheuristics.

# Particle Swarm Optimization (PSO)

This project demonstrates Particle Swarm Optimization (PSO), a swarm intelligence-based optimization algorithm, on a Sphere minimization problem. The notebook shows how particles move through the search space by updating their velocity and position based on personal best and global best solutions.

## Purpose
This notebook was created to study how PSO works in practice. It helps explain the core ideas of swarm-based optimization, including particles, velocity updates, personal experience (pbest), social influence (gbest), and convergence behavior.

## What the project does
- Defines an objective function using the Sphere function
- Initializes a swarm of particles with random positions and velocities
- Evaluates particle fitness values
- Tracks:
  - **pbest** = best solution found by each particle
  - **gbest** = best solution found by the swarm
- Updates particle velocity using PSO equations
- Updates particle positions over iterations
- Records the best fitness history
- Visualizes convergence using line plots
- Includes an interactive convergence graph

## Key Concepts Covered
- Population-based optimization
- Swarm intelligence
- Position and velocity updates
- Personal best (pbest)
- Global best (gbest)
- Exploration and exploitation
- Convergence analysis

## PSO Update Rule
Each particle updates its velocity using:
- **Inertia term**: keeps moving in the current direction
- **Cognitive term**: moves toward its own best solution
- **Social term**: moves toward the swarm’s best solution

Then the new position is updated from the new velocity.

## Why this project is useful
This project is useful for:
- learning the basics of Particle Swarm Optimization
- understanding swarm-based search behavior
- visualizing how particles converge toward an optimum
- comparing PSO with other metaheuristic algorithms
- building a foundation for solving more complex optimization problems

## Technologies Used
- Python
- NumPy
- Matplotlib
- Plotly
- Pandas

## Objective Function
The notebook uses the **Sphere Function**:

f(x) = sum(x^2)

Its global minimum is:
- **x = 0**
- **f(x) = 0**

## Outputs
The notebook generates:
- the best solution found
- the best fitness value
- a convergence curve over iterations
- an interactive plot of optimization progress

## Future Improvements
Possible extensions include:
- applying PSO to more difficult benchmark functions
- testing higher-dimensional search spaces
- comparing PSO with GA, DE, and SMA
- tuning parameters such as inertia weight and acceleration coefficients
- adding boundary handling and velocity clamping
