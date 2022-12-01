`Date`: 27 Nov 22 Session No. 02

`Subject`: Model Evaluation and Validation

## Notes
- **Underfitting and Overfitting**
  - `Underfitting` A statistical model or a machine learning algorithm cannot capture the underlying trend of the data, it only performs well on training data but performs poorly on testing data 
  
  <img src="https://static.javatpoint.com/tutorial/machine-learning/images/overfitting-and-underfitting2.png" width="300">

  - `Overfitting` A statistical model is said to be overfitted when the model does not make accurate predictions on testing data
  
  <img src="https://static.javatpoint.com/tutorial/machine-learning/images/overfitting-and-underfitting.png" width="300">
  
- **Confusion Matrix**
  - Is a technique for summarizing the performance of a classification algorithm
  - The number of correct and incorrect predictions are summarized with count values and broken down by each class
  
  
  <img src="https://miro.medium.com/max/2560/1*mdtqR2kyElMd0cCGM4gtuw.jpeg" width="450">
  
- **Precision and Recall**
  - Are commonly used metrics to measure the performance of machine learning models or AI solutions
  - `Precision` measures the proportion of correct positive predictions
     ```
     Precision = True Positive/True Positive + False Positive  
     Precision = TP/TP+FP
     ```
  - `Recall` measures the proportion of actual positive labels correctly identified by the model
     ```
     Recall = True Positive/True Positive + False Negative  
     Recall = TP/TP+FN  
     ```
  
- **F1 SCORE and F-BETA SCORE**
  - `F1 SCORE` is an evaluation metric for a classification defined as the harmonic mean of precision and recall. It is a statistical measure of the accuracy of a test or model
  
    <img src="https://camo.githubusercontent.com/21d7bfc19ec219729b9e019bc062bd79f86b26871d9dee8f6f361f1f9b4ce6a5/68747470733a2f2f692e696d6775722e636f6d2f52496a3053776d2e6a706567" width="500">
  
  - `F-BETA SCORE` calculation follows the same form as the F-1 score, however it also allows you to decide how to weight the balance between precision and recall using the beta parameter
  
- **ROC** (RECEIVER OPERATING CHARACTERISTIC CURVE)
  - Is a graph showing the performance of a classification model at all classification thresholds, it plots two parameters:
  
      • True Positive Rate (TPR) is a synonym for recall
     ```
    True Positive Rate = TRUE POSITIVES / ALL POSITIVES
    ```
      
      • False Positive Rate (FPR)
    ```
    False Positive Rate = FALSE POSITIVES / ALL NEGATIVES
    ```
- **Gradient Descent** 
  - It is an Optimization Algorithm to find the Minimum of a Function
  - Start with a random point on the function and move in the negative direction of the gradient of the function to reach the local/global minima
- **Linear Regression is Sensitive to `Outliers`**

## Tasks
 


  
  
  

  
 

  

