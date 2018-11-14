# Nested_C-V
For the paper: An Interpretable Machine Vision Approach to Human Activity Recognition using Photoplethysmograph Sensor Data

The Retrain_Transfer_Learning notebook is for retraining the image classifier. You must edit your own directories prior to using

Nested_Cross-Validation is used for the CNN-SVM section of the paper. It uses the extracted features from the retrained Inception network to train a support vector classifier over which the paramaters can be optimised. You may choose the values to optimse over. This is based on the scikit learn Nested Cross-Validation example [1]. 


[1] https://scikit-learn.org/stable/auto_examples/model_selection/plot_nested_cross_validation_iris.html
