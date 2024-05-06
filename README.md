# Customer-Churn-Prediction
Absolutely, let's delve into each of these terms:

1. **Accuracy**:
   - **Definition**: Accuracy is the ratio of correctly predicted instances to the total number of instances in the dataset.
   - **Interpretation**: It indicates the overall correctness of the model's predictions. An accuracy of 0.79 means that around 79% of the model's predictions are correct.

2. **Precision**:
   - **Definition**: Precision is the ratio of correctly predicted positive observations to the total predicted positive observations.
   - **Interpretation**: It measures the correctness of positive predictions made by the model. For example, a precision of 0.83 for the "False" class means that out of all customers predicted as not churning, 83% actually did not churn.

3. **Recall (Sensitivity)**:
   - **Definition**: Recall is the ratio of correctly predicted positive observations to the all observations in actual class.
   - **Interpretation**: It measures the model's ability to identify all relevant instances of a class. For example, a recall of 0.91 for the "False" class means that out of all customers who did not churn in the dataset, the model correctly identified 91% of them.

4. **F1-score**:
   - **Definition**: F1-score is the harmonic mean of precision and recall.
   - **Interpretation**: It provides a balance between precision and recall. A higher F1-score indicates better performance, especially when there is an uneven class distribution. For example, an F1-score of 0.87 for the "False" class indicates a good balance between precision and recall for customers who do not churn.

5. **Support**:
   - **Definition**: Support is the number of actual occurrences of the class in the specified dataset.
   - **Interpretation**: It provides context about the distribution of classes in the dataset. Higher support values indicate a larger number of instances for that class. For example, a support of 1036 for the "False" class means that there are 1036 instances of customers who do not churn in the dataset.

Understanding these terms helps in comprehensively evaluating the performance of a classification model and identifying areas for improvement.
