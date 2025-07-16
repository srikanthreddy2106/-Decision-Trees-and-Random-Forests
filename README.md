# -Decision-Trees-and-Random-Forests

Decision Trees and Random Forests are powerful tree-based machine learning algorithms commonly used for classification and regression tasks. In this project, we applied these models to the Heart Disease dataset to predict the presence of heart disease based on patient data.

We first trained a Decision Tree Classifier using Scikit-learn. Decision Trees split the data into branches based on feature values, making decisions at each node. We visualized the tree structure using Matplotlib and Graphviz, which provided a clear view of how features like cholesterol, age, and chest pain type contribute to predictions. However, Decision Trees can easily overfit the training data. To address this, we controlled the tree depth and plotted training vs. testing accuracy for different depths to analyze overfitting.

Next, we implemented a Random Forest Classifier, which combines multiple decision trees to improve performance and reduce overfitting. Random Forests use bagging and feature randomness, making them more robust. The Random Forest model showed higher accuracy compared to a single Decision Tree.

We also evaluated both models using cross-validation for more reliable performance estimation and analyzed feature importances. Features like chest pain type and maximum heart rate were found to be highly influential. Overall, Random Forests provided better generalization and predictive power for this classification task.
