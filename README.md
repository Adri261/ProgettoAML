# Jypyter Structure of the project

- "baseline_model.ipynb": contains the definition of the baseline model, and the PCA model
- "dataExploration_grouped_by_game.ipynb": contains the data exploration relative to data grouped by match type
- "dataExploration.ipynb": contains a preliminary data exploration, expanded then in "groupCSVCreator.ipynb", "groupTrainValTestSplit.ipynb"
- "groupCSVCreator.ipynb": was used to group the original dataset into the dataset made of data grouped by groupId
- "groupModelQuantization.ipynb": was used for obtaining the quantized models
- "groupModelTraining.ipynb": was used for running the hyperparameter optimizers
- "groupTrainValTestSplit.ipynb": contains preprocessing of grouped data and generates the train, val, test split
- "plots": contains various plots extracted from the data
-  "*.h5" and "*.keras" files: contains information about the models that can be loaded using Keras
