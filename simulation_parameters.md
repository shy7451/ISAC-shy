# Simulation Parameters

This document records the key settings used in the simulation to ensure reproducibility.

---

## Convergence Condition
All algorithms use the same convergence condition:
```
Threshold: 1e-5
```

---

## Algorithm-specific Settings

### WMMSE-SGD
- Batch Size: 100
- Learning Rate: 0.01
- Max Iterations: 500

### BB-PSO
- Number of Particles: 50
- Inertia Weight: 0.7
- Max Iterations: 500

### Proposed Evolutionary Algorithm
- Population Size: 50
- Crossover Probability: 0.8
- Mutation Probability: 0.05
- Number of Random Samples: 500
- Max Generations: 500

---

## Runtime (with and without Gaussian Randomization)
- Without Gaussian Randomization: **9.87 seconds**
- With Gaussian Randomization: **10.95 seconds**

All measurements performed on the same computational environment.