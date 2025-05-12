# p-adic Three-Body Problem Simulation

This project simulates the three-body problem using p-adic numbers in SageMath, leveraging their compact representation of large numbers, singularity avoidance, and ultrametric structure for computational efficiency. The script uses a 4th-order Runge-Kutta (RK4) solver to integrate the gravitational equations, demonstrating p-adic arithmetic’s potential for chaotic systems.

## Motivation
The three-body problem—predicting the motion of three bodies under gravity—is computationally challenging due to chaotic orbits, large scales (e.g., `\( 10^{10} \)` meters), and singularities during close encounters. p-adic numbers, with their ultrametric topology, offer:
- **Compact Storage**: Large distances/masses use minimal memory.
- **Singularity Avoidance**: p-adic norms cap forces, stabilizing simulations.
- **Stable Arithmetic**: Modular operations prevent precision loss.
- **Ultrametric Efficiency**: Hierarchical clustering can reduce complexity.

## Requirements
- **SageMath**: Version 9.8 or later (install from [sagemath.org](https://www.sagemath.org/) or use [SageMathCell](https://sagecell.sagemath.org/)).
- No additional dependencies, as SageMath includes p-adic arithmetic support.

## Installation and Running
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/p-adic-three-body-problem.git
   cd p-adic-three-body-problem
