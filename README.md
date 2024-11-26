This project evaluates the performance of multiple machine learning algorithms on the Iris dataset using cross-validation. It calculates the average accuracy of each model to identify the best-performing classifier.

-> Features:

1. Cross-Validation:
- Uses cross-validation to ensure reliable performance metrics by splitting the data into multiple folds for training and testing.
  
2. Algorithm Comparison:
Evaluates and compares the following models:
- Logistic Regression
- Decision Tree Classifier
- Support Vector Machine (SVM)
- Random Forest Classifier
  
3. Average Accuracy Calculation:
- Computes and reports the average accuracy for each model.

-> Technologies Used:

- Python: Programming language.
- Scikit-learn: For data loading, model training, and cross-validation.
- NumPy: For numerical computations.

-> How It Works:

1. Data Loading:
- Loads the Iris dataset using scikit-learn's load_iris() function.

2. Cross-Validation:
- Performs cross-validation on four classifiers: Logistic Regression, Decision Tree, SVM, and Random Forest.
- Computes accuracy scores for each fold and averages them to evaluate the model's overall performance.
 
3. Comparison:
- Compares the average accuracy of all models to identify the most effective one.  
  
