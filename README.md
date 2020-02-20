# PPG-Image-Classifier
For the paper: An Interpretable Machine Vision Approach to Human Activity Recognition using Photoplethysmograph Sensor Data

The Retrain_Transfer_Learning notebook is for retraining the image classifier. You must edit your own directories prior to using [1]. 

Nested_Cross-Validation is used for the CNN-SVM section of the paper. It uses the extracted features from the retrained Inception network to train a support vector classifier over which the paramaters can be optimised. You may choose the values to optimse over. This is based on the scikit learn Nested Cross-Validation example [2]. 


[1] https://codelabs.developers.google.com/codelabs/tensorflow-for-poets/#0

[2] https://scikit-learn.org/stable/auto_examples/model_selection/plot_nested_cross_validation_iris.html


-------

# Citing

    @inproceedings{Brophy18,
      author    = {Eoin Brophy and
                   Zhengwei Wang and
                   José Juan Dominguez Veiga and
                   Alan F. Smeaton and
                   Tomas E. Ward},
      title     = {An Interpretable Machine Vision Approach to Human Activity Recognition
                   using Photoplethysmograph Sensor Data},
      booktitle = {Proceedings for the 26th {AIAI} Irish Conference on Artificial Intelligence
                   and Cognitive Science Trinity College Dublin, Dublin, Ireland, December
                   6-7th, 2018},
      series    = {{CEUR} Workshop Proceedings},
      volume    = {2259},
      pages     = {232--243},
      publisher = {CEUR-WS.org},
      year      = {2018},
      url       = {http://ceur-ws.org/Vol-2259/aics\_22.pdf}
    }
