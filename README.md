# Credit_Risk_Analysis
<img src="https://github.com/Donik22/Credit_Risk_Analysis/blob/main/Resources/AI-credit-cards.jpeg" alt="drawing" style="width:100px;length:600px"/>

## Project overview

In this project, we will use different Unsupervised machine learning algorithms to detect risky credit card loans. The challenge we face is that our data is highly unbalanced. To overcome this we employed methods like oversampling and undersampling our data and finally a combination of both. To reduce bias we used two machine learning modules BalancedRandomForestClassifier and EasyEnsembleClassifie. 

## Results

To explain our results some terminologies must be defined.

  ![confusion metrix](https://github.com/Donik22/Credit_Risk_Analysis/blob/main/Resources/confusion_matrix2.png)

  A **true positive** is an outcome where the model correctly predicts the positive class. Similarly, a **true negative** is an outcome where the model correctly predicts the negative class.

  A **false-positive** is an outcome where the model incorrectly predicts the positive class. And a **false-negative** is an outcome where the model incorrectly predicts the negative class.

  Precision (pre): attempts to answer the following question:

  `What proportion of positive identifications was actually correct?`
  
```
                    True Positive
Precisicion = ___________________________
  
              True Positive + False Positive
              
```

Recall:  attempts to answer the following question:

`What proportion of actual positives was identified correctly?`

```
            True Positive
Recal = ______________________________
        True Positive + False Negative

```

Accuracy is the fraction of predictions our model got right. The formula to measure accuracy is
```
             Number of correct prediction 
Accuracy =  ______________________________
        
            Number of total prediction

```

With this in mind, let's look at our results.

### Oversampling Algorithm
![Oversampling](https://github.com/Donik22/Credit_Risk_Analysis/blob/main/Resources/Oversampling%20Algorithms%20.PNG)

- Precision = 0.99
- Recal = 0.61
- Accuracy = 0.65

### SMOTE Oversampling
![SMOTE](https://github.com/Donik22/Credit_Risk_Analysis/blob/main/Resources/SMOTE%20Oversampling%20Algorithms.PNG)

- Precision = 0.99  
- Recal = 0.69
- Accuracy = 0.66

### Undersampling method
![Undersamp](https://github.com/Donik22/Credit_Risk_Analysis/blob/main/Resources/Undersampling%20Algorithms.PNG)

- Precision = 0.99
- Recal = 0.40
- Accuracy = 0.66

### SMOTTEEN Algorithm
![SMOTEENN](https://github.com/Donik22/Credit_Risk_Analysis/blob/main/Resources/SMOTEEENN%20algorithm.PNG)

- Precision = 0.99
- Recal = 0.57
- Accuracy = 0.54

### Balanced Random Forest Classifier
![BRFC](https://github.com/Donik22/Credit_Risk_Analysis/blob/main/Resources/BalancedRandomForestClassifier.PNG)

- Precision = 0.99
- Recal = 0.87
- Accuracy = 0.79

### Easy Ensemble AdaBoost Classifier
![EEAC](https://github.com/Donik22/Credit_Risk_Analysis/blob/main/Resources/EasyEnsembleClassifier.PNG)

- Precision = 0.99
- Recal = 0.94
- Accuracy = 0.93

## Summary 
In conclusion, we can say that the Balanced Random Forest Classifier and the Easy Ensemble AdaBoost Classifier showed a better Recal and Accuracy while Precision remained constant on all six methods. I recommend using Easy Ensemble AdaBoost Classifier due to it having the highest Recall and Accuracy score.


## Resources
https://developers.google.com/machine-learning/crash-course/classification





