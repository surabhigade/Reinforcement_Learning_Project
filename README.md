# Reinforcement_Learning_Project

**Overview**
Constraint Policy Optimization (CPO) is a reinforcement learning algorithm designed to optimize policies while adhering to predefined constraints. It extends Trust Region Policy Optimization (TRPO) by incorporating constraints on expected costs, ensuring that policies remain within safe operational bounds

**Features**
  Policy network using a Gaussian distribution over actions
  Value function network for estimating state values
  Implementation of Generalized Advantage Estimation (GAE)
  KL divergence constraint for policy updates
  Cost value function for maintaining safety constraints
  Optimization using Adam optimizer

**Requirements**
  Ensure you have the following dependencies installed before running the project:
  ```bash
  pip install torch gym numpy matplotlib
   ```
