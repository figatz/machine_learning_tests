1.	Project Name:
  Machine Learning Tests
2.	Business Problem
  2.1	– Description 
    Data Money company believes that the expertise in training and fine-tuning algorithms, performed by the company's Data Scientists, is the primary reason for       the excellent results consistently delivered by its consulting services to clients.
  2.2	 - Objective 
    The objective of this project is to conduct experiments with Classification, Regression, and Clustering algorithms to analyze how performance behaviour            changes as the values of key parameters controlling overfitting and underfitting are adjusted.
3.	Solution planning
  3.1	– Final delivery
    The final deliverable will consist of 7 tables displaying the performance of the algorithms, evaluated using multiple metrics, across three distinct datasets:     training, validation, and test.
  3.2	– Tested Algorithms
    Classification Algorithms: KNN, Decision Tree, Random Forest and Logistic Regression
    Perfomance Metrics: Accuracy, Precision, Recall and F1-Score

    Regression Algorithms: Linear Regression, Decision Tree Regressor, Random Forest Regressor, Polynomial Regression, Linear Regression Lasso, Linear Regression      Ridge, Linear Regression Elastic Net, Polynomial Regression Lasso, Polynomial Regression Ridge e Polynomial Regression Elastic Net.
    Perfomance Metrics: R², MSE, RMSE, MAE and MAPE

    Clustering Algorithms: K-Means and Affinity Propagation
    Performance Metric: Silhouette Score
  3.3	– Used Tools:
    Python 3.12 and Scikit-learn
4.	Development
  4.1	– Solution Strategy 
    To carry out the algorithm experiments, I will implement the code in Python to train each Machine Learning algorithm, systematically varying their key             overfitting-related hyperparameters and observing the resulting performance metrics.
    The set of values that yields the best algorithm performance will be selected for the final training phase.
  4.2	–  The step-by-step guide
    Step 1: Split the dataset into training, validation, and test sets.
    Step 2: Train the algorithms using the training data with default hyperparameters.
    Step 3: Evaluate the performance of the algorithms (trained with default parameters) on the training set.
    Step 4: Adjust the main overfitting-control hyperparameters until the best-performing parameter set is found.
    Step 5: Evaluate the performance of the algorithms on the validation set.
    Step 6: Combine the training and validation datasets.
    Step 7: Retrain the algorithm using the combined training and validation data, applying the best hyperparameter values.
    Step 8: Evaluate the performance of the retrained algorithm on the test set.
    Step 9: Analyze the experiments and document the top three key insights.
5.	Top insights
  5.1	. Insight 1: Tree-based algorithms demonstrated superior performance across all evaluation metrics when applied to the test data in the Classification           experiment.
  5.2	. Insight 2: The classification algorithms showed similar performance on the validation and test datasets, indicating consistent generalization capability.
  5.3	. Insight 3: All regression algorithms demonstrated poor performance metrics, indicating the need for improved feature selection and better preprocessing of     the dataset’s independent variables.
  5.4	. Polynomial algorithms easily overfit when you increase degrees. 
6.	Results
  6.1	 Classification Algorithms on Training: 
  <img width="654" height="263" alt="image" src="https://github.com/user-attachments/assets/d7cbecb6-36f2-44e5-a217-49d4c0e7ac8c" />

  6.2	Classification Algorithms on Validation:
  <img width="649" height="301" alt="image" src="https://github.com/user-attachments/assets/0e416e13-f6f7-41b8-9680-d728f4247dbc" />

  6.3	Classification Algorithms on Test:
  <img width="648" height="301" alt="image" src="https://github.com/user-attachments/assets/a957a0b6-a92a-4285-a63d-65f26a8cb06a" />

  6.4	Regression Algorithms on Training:
  <img width="665" height="772" alt="image" src="https://github.com/user-attachments/assets/3b8a557c-95fd-403e-91a0-0b8d83fb8e17" />

  6.5	Regression Algorithms on Validation
  <img width="662" height="769" alt="image" src="https://github.com/user-attachments/assets/186b6559-1f12-4376-bf82-d3019b6e98cd" />

  6.6	Regression Algorithms on Test
  <img width="659" height="769" alt="image" src="https://github.com/user-attachments/assets/00562d07-79f3-477b-aa3f-e606c2825193" />

  6.7	Clustering Algorithms
  <img width="534" height="193" alt="image" src="https://github.com/user-attachments/assets/8c729b57-7328-4892-8619-4d1308d4294d" />


7.	Conclusions
    In this Machine Learning experiment, I gained valuable experience and developed a deeper understanding of the limitations of algorithms with respect to            underfitting and overfitting.
    Tree-based algorithms were shown to be particularly sensitive to parameters such as tree depth and the number of trees in the forest. Proper tuning of these       parameters is essential to prevent the model from entering an overfitting state.
    Regression algorithms, on the other hand, demonstrated sensitivity to the degree of the polynomial, a key parameter that governs the balance between               underfitting and overfitting.
    Overall, this experiment was highly valuable for deepening my understanding of how various Classification, Regression, and Clustering algorithms behave, and       for identifying the main hyperparameters that control the transition between underfitting and overfitting.
  	
8.	Next steps
    As next steps in this experiment, I plan to test additional Machine Learning algorithms and apply them to different datasets to further expand my                  understanding of their behavior and identify the scenarios that are most conducive to improved performance.
    For example, in the context of regression algorithms, I intend to experiment with RANSAC and Theil-Sen estimators to evaluate and compare their performance.

