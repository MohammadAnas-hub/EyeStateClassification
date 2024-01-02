# EyeStateClassification
The objective of Eye State Classification using EEG (electroencephalogram) dataset is to accurately classify the state of the eyes as either open or closed based on the signals recorded from the brain.

EEG signals are used to measure electrical activity in the brain, which can provide insights into the state of consciousness and cognitive function. By analyzing EEG data related to eye state, it is possible to develop algorithms that can accurately classify whether a person's eyes are open or closed, which can be useful in various applications such as monitoring driver fatigue, diagnosing sleep disorders, and developing brain-computer interfaces.

The primary goal is to develop a reliable and accurate classification algorithm that can perform well on EEG data and generalize to new subjects and situations.

## Result
The performance of the machine learning models was evaluated using accuracy, which measures the percentage of correctly classified instances. The random forest model achieved an accuracy of approximately 92.18% on the test set, outperforming other models such as logistic regression(62.55%), SGDClassifier(58.44%), SVC(52.92%), and decision tree(83.91%).

In an attempt to improve the performance of the random forest model, hyperparameter tuning was performed using grid search. The hyperparameters that were tuned included the number of trees, the maximum depth of the trees, and the minimum number of samples required to split an internal node.
