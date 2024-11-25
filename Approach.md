<h1 align="center">This is a step by step Guidance for This Project</h1>


<h1 align="center">Model Training & Evaluation</h1>

- **Reduce k_neighbors in SMOTE** : The k_neighbors parameter controls the number of nearest neighbors SMOTE uses to generate synthetic samples. Reducing this number can significantly speed up the computation.
- **Use Random Undersampling Instead of ENN** : Instead of SMOTEENN, you can combine SMOTE with simpler random undersampling, which is faster than ENN.