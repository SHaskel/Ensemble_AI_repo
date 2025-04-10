# Read-Me

Part of my internship application for Ensemble AI's Machine Learning Research Intern role

In this comparison between the baseline model and the NdLinear-enhanced model, the NdLinear version achieved a slightly lower training loss (1.3217 vs. 1.3480), indicating a marginal improvement in how well it fit the training data. However, this came at a small cost to generalization, as its test accuracy dropped by 2.25 percentage points compared to the baseline (60.05% vs. 62.30%). Interestingly, there was no reduction in parameter count between the models, suggesting that the current NdLinear configuration did not introduce any compression benefits. Training time was also nearly identical, with NdLinear taking about 0.85 seconds longer. Overall, this result suggests that while NdLinear maintained similar complexity and performance, further tuning may be needed to realize its typical advantages in parameter efficiency and inference speed.
