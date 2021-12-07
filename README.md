# AssistedML_Module17

Overview and Purpose: 
	Employ different techniques to train and evaluate models with unbalanced classification problem. Using imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling, to identity risky loans. For this, we are given data set from LendingClub, a peer-to-peer lending services company.

Results:
  1.	Naïve Oversampling + Logistic Regression  
    a.	Accuracy score = 0.64
    b.	Precision     = 0.99
  2.	Smote Oversampling + Logistic Regression 
    a.	Accuracy score = 0.62
    b.	Precision = 0.99
  3.	Under sampling + Logistic Regression    
    a.	Accuracy score = 0.51
    b.	Precision = -.99
  4.	Combination Over and Under sampling + Logistic Regression 
    a.	Accuracy score = 0.64
    b.	Precision = 0.99
  5.	Ensemble + Balanced Random Forest Classifier 
    a.	Accuracy score = 0.90
    b.	Precision = 0.99
  6.	Easy Ensemble Classifier 
    a.	Accuracy score = 0.93
    b.	Precision = 0.99

Recommendation:

  The choice of selecting a model is subjective and should not really dependent on Accuracy score or Precision. It matters on having a better accuracy score if the model is learning from data. If the model does not learn, a high accuracy score really has no meaning and hence the model is not really learning anything. 

    In the exercise performed so far, Easy Ensemble Classifier has given the best accuracy score, with training data, test data gives a reasonable identification of a riskier loan there by giving the loan approver sufficient red flag to make an informed decision.
