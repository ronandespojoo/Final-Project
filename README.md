# Final-Project

Uses the WineQT dataset in order to compare a standrd multilayer architecture with gated residual blocking, the two architectures being a BaselineNetwork and a CustomGatedNetwork. 

Objective is to analyze whether gating and residual connections provide improvements to learning and stability compared to the regular pipeline architecture.

The Gated Residual Block applies nonlinear transformation and learns a gate (sigmoid) in order to blend input and transformed features. The Custom Gated Network stacks multiple gated residual blocks. These are designed to learn better feature representations as opposed to just predictions.

Othed details include: 
- Loss-Function: Cross-Entropy Loss
- Evaluation metric: F1 Score

Results: 
- No improvement as a result of weights.
- No convergence observed
- Loss is flat across epochs
- Gated blocks can learn better representations however training is necessary
