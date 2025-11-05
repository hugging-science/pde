# PDE Benchmark Tasks

This document collects PDE benchmark tasks from The Well paper and similar benchmarks. 

| Task                                       | Description                                                                           | Status | Notes                                         |
|--------------------------------------------|---------------------------------------------------------------------------------------|-------:|-----------------------------------------------|
| Surrogate Modeling                         | Predict simulation fields from initial and boundary conditions without the solver.    |  - [ ] |                                               |
| Super-resolution                           | Convert coarse simulation outputs into high-resolution fields.                        |  - [ ] |                                               |
| Transfer across dimensionality             | Train in one spatial dimension and generalize to another.                             |  - [ ] |                                               |
| Time-steps generalization                  | Train at one time step size and evaluate at other step sizes.                         |  - [ ] |                                               |
| Transfer across a physical parameter range | Train on a limited range of physical parameters and generalize.                       |  - [ ] |                                               |
| Steady-state prediction                    | Predict the steady state from initial and boundary conditions.                        |  - [ ] |                                               |
| Stable long-term forecasting               | Produce long term forecasts that remain stable and preserve the simulator statistics. |  - [ ] |                                               |
| Sensitivity to initial conditions          | Measure robustness to small changes in initial conditions.                            |  - [ ] |                                               |
| Inverse Scattering                         | Recover material or geometry properties from measurements of scattered waves.         |  - [ ] |                                               |
| Simulation acceleration                    | Replace simulations with learned surrogates                                           |  - [ ] |                                               |
| Inverse parameter estimation               | Estimate unknown model parameters from observations.                                  |  - [ ] | The Well dataset is not suited for this task. |