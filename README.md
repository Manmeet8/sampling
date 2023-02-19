# ML Sampling Techniques Comparison

This project evaluates the effectiveness of 5 different sampling techniques for imbalanced datasets using 5 machine learning models. The goal is to compare the performance of each technique and model combination to identify the best approach for addressing class imbalance.
![image](https://user-images.githubusercontent.com/98878944/219968664-21d06338-5b77-4bef-9cee-85331b8e3005.png)

### The sampling techniques used in this project are:

- Near Miss Sampling: selects examples from the majority class that are closest to the minority class.
- Random Under-Sampling: randomly removes examples from the majority class.
- SMOTE Sampling: creates synthetic examples for the minority class based on nearest neighbors.
- TomekLinks Sampling: removes examples from both the majority and minority classes that are close to each other.
- Random Over-Sampling: randomly duplicates examples from the minority class.

### The machine learning models used in this project are:

- Logistic Regression: a linear classification model that uses a sigmoid function to predict class probabilities.
- LGBM Classifier: a gradient boosting model that uses decision trees to predict class probabilities.
- Support Vector Machine: a model that finds the hyperplane that maximally separates the classes in feature space.
- Random Forest Classifier: an ensemble model that uses many decision trees to predict class probabilities.
- Quadratic Discriminant Analysis: a model that estimates class-specific densities to predict class probabilities.

### Getting Started
To get started with this project, you'll need to have the following prerequisites:

Python 3
- Jupyter Notebook
- Pandas, NumPy, Scikit-learn, and LightGBM libraries installed

### Running the Project
To run the project, simply open the Jupyter Notebook file and execute each cell in order. The results will be displayed in the notebook output.

### Conclusion
The results of this project show that LGBM Classifier is the most effective approach for addressing class imbalance in the credit card dataset here. These findings can be used to guide future research and practical applications in this domain.
