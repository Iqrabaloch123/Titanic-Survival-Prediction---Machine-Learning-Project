#  Project Overview 
The sinking of the RMS Titanic on April 15, 1912, resulted in the loss of 1502 out of 2224 passengers and crew. This project analyzes passenger data (name, age, gender, socio-economic class, etc.) to determine what sorts of people were more likely to survive.

#  Key Features 

**Data Exploration & Visualization**: Comprehensive analysis using seaborn and matplotlib to understand feature distributions and correlations

**Feature Engineering: Created new features including**:

Title extraction from passenger names (Mr, Mrs, Miss, Master, Rare)

Family Size (SibSp + Parch + 1)

IsAlone indicator

Age bands and Fare bands

Age*Class interaction feature

**Data Cleaning**: Handled missing values for Age, Embarked, and Fare using strategic imputation

**Model Training**: Implemented and compared multiple algorithms:

**Logistic Regression**

**Support Vector Machines (SVM)**

**K-Nearest Neighbors (KNN)**

**Gaussian Naive Bayes**

**Perceptron**

**Decision Tree**

**Random Forest**

**Gradient Boosting**

**RidgeClassifierCV**

**Hyperparameter Tuning**: Used GridSearchCV to optimize Random Forest and Gradient Boosting models

**Ensemble Learning**: Implemented a VotingClassifier combining top models for improved predictions

# Results
Model	Accuracy
Random Forest	91.47%
Decision Tree	91.47%
Gradient Boosting	87.88%
KNN	86.20%
SVM	81.59%
Technologies Used
Python

**pandas & numpy for data manipulation**

**scikit-learn for machine learning models**

**seaborn & matplotlib for visualization**

**GridSearchCV for hyperparameter optimization**

#**Key Insights**

Women had significantly higher survival rates than men

First-class passengers had better survival odds

Children (especially infants) had higher survival rates

Passengers traveling alone had lower survival rates

Higher fares correlated with better survival chances




