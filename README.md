# Iris Classification Project

## Dataset Description
The Iris dataset is a classic multiclass classification dataset. It contains 150 samples from three species of Iris (Iris setosa, Iris virginica, and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals, in centimeters.

## Setup Instructions
1. **Dependencies**: This notebook requires `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn`.
2. **Data Loading**: The data is loaded directly from `sklearn.datasets`.
3. **Preprocessing**: Features are scaled using `StandardScaler` to ensure the K-Nearest Neighbors algorithm functions correctly, as it is sensitive to the magnitude of feature values.

## Key Findings
* **Optimal K**: Through cross-validation, an optimal value of $k=3$ was identified for the KNN model.
* **Performance**: The model achieved an **Accuracy Score of 1.0** on the test set, effectively distinguishing between the three species.
* **Metric Insights**: The **F1-Score** for all classes (Setosa, Versicolor, and Virginica) reached 1.0, indicating a perfect balance between precision and recall for this test split.
