Deep Learning Model Performance Report: Alphabet Soup
**Analysis Overview**
The purpose of this analysis is to evaluate the performance of a deep learning model designed for the Alphabet Soup dataset. The model's effectiveness is assessed based on its ability to classify outcomes accurately.

**Results**
**Data Preprocessing**
**What is the target variable in the model?**

The target variable is "IS_SUCCESSFUL" from the application_df dataset.

**Which variables serve as features in the model?**

All columns in application_df except "IS_SUCCESSFUL" were used as features.

**Which variables were removed from the dataset and why?**
The "EIN" and "NAME" columns were excluded since they do not contribute to predicting the target outcome.

**Model Compilation, Training, and Evaluation**
**How many neurons, layers, and activation functions were used in the model, and why?**

Initially, the model was built with 8 neurons in the first hidden layer and 5 neurons in the second hidden layer. These values were chosen as a starting point for further optimization.

**Did the model achieve the target performance?**

No, the model did not meet the desired 75% accuracy threshold, falling slightly short.

**What strategies were implemented to improve performance?**

Several adjustments were made, including:

Adding more layers.

Removing additional columns.

Increasing the number of hidden nodes.

Experimenting with different activation functions for each layer.

**Summary and Recommendations**
The final model achieved an accuracy of approximately 73%, which, while close, did not meet the target performance goal. To enhance classification accuracy, future models could:

Perform more rigorous data preprocessing to improve the correlation between input features and output labels.

Experiment with different activation functions to optimize network performance.

Continue iterating on the model’s architecture, adjusting layers and neurons to refine accuracy.

A different machine learning model, such as a Random Forest classifier or Gradient Boosting model, might provide better performance by capturing complex relationships in the dataset more effectively.
