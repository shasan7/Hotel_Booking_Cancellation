Predicting Hotel Booking Cancellation using the Hotel Booking Demand dataset (https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand).

Used scikit-learn's machine learning models for prediction. Logistic Regression, KNN, Random Forest, XGBoost and CatBoost were run.


Obtained the following results:

Classifiers:  LogisticRegression has a score of 78.0 % accuracy.

Classification Report: 

               precision    recall  f1-score   support

           0       0.83      0.81      0.82     15002
           1       0.69      0.71      0.70      8840

    accuracy                           0.78     23842
    macro avg      0.76      0.76      0.76     23842
    weighted avg   0.78      0.78      0.78     23842
    
    Confusion Matrix: 
     [[12218  2784]
     [ 2566  6274]] 


Classifiers:  KNeighborsClassifier has a score of 89.0 % accuracy.

Classification Report: 

               precision    recall  f1-score   support

           0       0.88      0.96      0.92     15002
           1       0.92      0.78      0.85      8840

    accuracy                           0.89     23842
    macro avg      0.90      0.87      0.88     23842
    weighted avg   0.90      0.89      0.89     23842
    
    Confusion Matrix: 
     [[14428   574]
     [ 1949  6891]] 


Classifiers:  RandomForestClassifier has a score of 96.0 % accuracy.

Classification Report: 

               precision    recall  f1-score   support

           0       0.94      0.99      0.97     15002
           1       0.99      0.89      0.94      8840

    accuracy                           0.96     23842
    macro avg      0.96      0.94      0.95     23842
    weighted avg   0.96      0.96      0.96     23842
    
    Confusion Matrix: 
     [[14903    99]
     [  945  7895]] 


Classifiers:  XGBClassifier has a score of 100.0 % accuracy.

Classification Report: 

               precision    recall  f1-score   support

           0       1.00      1.00      1.00     15002
           1       1.00      1.00      1.00      8840

    accuracy                           1.00     23842
    macro avg      1.00      1.00      1.00     23842
    weighted avg   1.00      1.00      1.00     23842
    
    Confusion Matrix: 
     [[14997     5]
     [   41  8799]] 


Classifiers:  CatBoostClassifier has a score of 100.0 % accuracy.

Classification Report: 

               precision    recall  f1-score   support

           0       1.00      1.00      1.00     15002
           1       1.00      0.99      1.00      8840

    accuracy                           1.00     23842
    macro avg      1.00      1.00      1.00     23842
    weighted avg   1.00      1.00      1.00     23842
    
    Confusion Matrix: 
     [[14987    15]
     [   53  8787]] 
