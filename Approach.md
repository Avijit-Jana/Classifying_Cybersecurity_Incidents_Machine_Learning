<h1>Table Of Contents</h1>

- [Data Exploration & EDA](#DataExploration&EDA)
- [Data Preprocessing](#DataPreprocessing)
- [Model Training & Evaluation](#ModelTraining&Evaluation)

<h1 align="center">Data Exploration & EDA</h1>

1. **Load the data :** First we import some libraries and load the big dataset

<h1 align="center">Data Preprocessing</h1>

- **Zip File** : The processed data is in zip file, you can unzip the cleaned_data.zip and you look for the rest of the work.

<h1 align="center">Model Training & Evaluation</h1>

- **Reduce k_neighbors in SMOTE** : The k_neighbors parameter controls the number of nearest neighbors SMOTE uses to generate synthetic samples. Reducing this number can significantly speed up the computation.
- **Use Random Undersampling Instead of ENN** : Instead of SMOTEENN, you can combine SMOTE with simpler random undersampling, which is faster than ENN.