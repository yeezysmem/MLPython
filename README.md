# Iris Flower Classification with K-Nearest Neighbors (KNN)

## Overview
This project demonstrates a classification task using the famous Iris flower dataset. The goal was to build a K-Nearest Neighbors (KNN) classifier to predict iris species based on their sepal and petal measurements.

## Libraries Used
- **Data Handling**: 
  - `numpy` for numerical operations
  - `pandas` for data manipulation
- **Visualization**:
  - `matplotlib.pyplot` for plotting
  - `mglearn` for enhanced visualization tools
- **Machine Learning**:
  - `sklearn.datasets.load_iris` to load the dataset
  - `sklearn.model_selection.train_test_split` for data splitting
  - `sklearn.neighbors.KNeighborsClassifier` for KNN implementation
- **Display**:
  - `IPython.display` for interactive output

## Dataset Information
The Iris dataset contains:
- 150 samples of iris flowers
- 4 features for each sample:
  - Sepal length (cm)
  - Sepal width (cm)
  - Petal length (cm)
  - Petal width (cm)
- 3 target classes (iris species):
  - Setosa
  - Versicolor
  - Virginica

## Analysis Steps
1. **Data Loading**: Loaded the built-in Iris dataset from scikit-learn
2. **Data Exploration**:
   - Examined dataset keys and structure
   - Printed target names (iris species)
3. **Data Splitting**:
   - Divided data into training (112 samples) and test sets (38 samples)
4. **Data Visualization**:
   - Created scatter matrix plots to visualize feature relationships
5. **Model Building**:
   - Initialized KNN classifier with 1 neighbor
   - Trained the model on the training data
6. **Prediction**:
   - Made predictions on a new sample
   - Evaluated model on test set
7. **Evaluation**:
   - Achieved 97% accuracy on the test set

## Key Findings
- The KNN classifier with k=1 achieved excellent performance (97% accuracy)
- The scatter matrix revealed clear separability between different iris species
- Petal measurements appeared particularly discriminative

## How to Run
1. Install required libraries:
   ```
   pip install numpy pandas matplotlib scikit-learn mglearn ipython
   ```
2. Run the Jupyter notebook or Python script containing the analysis

## Future Work
- Experiment with different values of k in KNN
- Try other classification algorithms (e.g., SVM, Decision Trees)
- Perform feature importance analysis
- Explore cross-validation for more robust evaluation

 
