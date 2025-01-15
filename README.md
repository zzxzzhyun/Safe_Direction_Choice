# Implementation of ML Models to Predict Movement Direction of a Rat Based on Neural Signals  
**Movement Direction**:  
- Left: -1  
- Right: 1  
- No Go: 0  

## 1. Logistic Regression Model  
- **Accuracy**: Achieves 93% for predicting left/right movement  
- **Limitation**: Unable to predict "no go" due to the constraint of binary classification  

## 2. Bayesian Convolutional Network  
- **Implementation**:  
  - Simplified the module wrapper in `BBBConv2d` from the `BayesianCNN` package  
- **Performance**:  
  - Achieved a **true positive rate of 84%**  
  - Frequently predicts "no go" instead of left/right, leading to a conservative decision-making process  
  - Results in a **false negative rate of 38%** 




