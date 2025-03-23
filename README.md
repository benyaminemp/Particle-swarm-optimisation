# Particle Swarm Optimisation (PSO)

## Description
This Jupyter Notebook demonstrates a basic implementation of the **Particle Swarm Optimisation (PSO)** algorithm for solving an optimization problem. It includes the core PSO logic along with plotting and result visualization.

## Structure
- **6 code cells**: Implementing the core PSO algorithm, cost function definition, initialization, iteration loop, and final visualization.
- **6 markdown cells**: Providing clear section headings and explanations to guide the user through the PSO implementation process.

## Key Features
- **Custom Cost Function**: Users can define and optimize their own cost function.
- **PSO Implementation**: Includes position/velocity updates, inertia, cognitive and social terms.
- **Visualization**: Final solution plotted to help understand the convergence behavior.
  
## How to Use

### Prerequisites
- Python environment with the following libraries:
  - `numpy`
  - `matplotlib`

### Instructions
1. Open the notebook in Jupyter or another compatible environment.
2. Run the cells in sequence to execute the PSO algorithm.
3. Modify the cost function or PSO parameters as needed for your application.

## Results
- Visual output of the best-found solution.
- Tracks the progress of the best cost per iteration.

## Customization Tips
- Change the cost function in the `# Cost Function` cell to solve different optimization problems.
- Tune the PSO parameters such as swarm size, inertia weight (`w`), cognitive/social coefficients (`c1`, `c2`), and number of iterations.

## Additional Information
Each cell is accompanied by markdown explanations to facilitate learning and modification. This notebook is ideal for educational purposes and experimentation with swarm-based optimization techniques.
