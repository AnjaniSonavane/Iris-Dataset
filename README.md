# Iris-Dataset

This is perhaps the best known database to be found in the pattern recognition literature. Fisher's paper is a classic in the field and is referenced frequently to this day. The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. One class is linearly separable from the other 2; the latter are NOT linearly separable from each other.

## Task:
Predict the class of iris plant

## Implementation:
• EDA and Explored the features using histograms
• Encoded the target variable ie converted it to numeric type
• Experimented using two different ratios of training, validation and test data ie 60-20-20, 
80-10-10. On the two different split ratios did the following
o Implemented KFold Cross Validation
o Implemented Grid Search to find optimal hyperparameters for any 3 algorithms
(out of LR, SVM, MLP, RF, Boosting)
o Analyzed the results on Validation set and test set and mentioned which model
performed the best and why?
o Compared the performance of models(using precision, recall, accuracy, latency). 
