HEART ATTACK ANALYSIS AND PREDICTION MODEL (Using XGBoost, GradientBoosting, AdaBoosting, KNN, SVM, Naive Bayes, Logistic Regression, Decision Tree, Random Forest and Stacking Models)

The model analyzes patient information to understand the risk of heart attack. Such classification models are becoming popular as they have the ability to interpret several factors that may lead to a heart attack and help in determining the risks before the event occurs. 

The dataset used to build the model is available at: https://www.kaggle.com/datasets/rashikrahmanpritom/heart-attack-analysis-prediction-dataset 
It contains information on 303 patients. The 13 parameters available are:
1. Age: The age of the patient
2. Sex: Gender of the patient. 1 indicates "Male", 0 indicates "Female"
3. cp: Chest pain type having Value 1: typical angina, Value 2: atypical angina, Value 3: non-anginal pain, Value 4: asymptomatic
4. trtbps: The resting blood pressure (in mm Hg)
5. chol: Cholestrol in mg/dl
6. restecg: resting electrocardiographic results: 0 indicates Value 0: normal, 1 indicates Value 1: having ST-T wave abnormality, 2 indicates Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria
7. fbs: Fasting blood pressure. 1 indicates blood sugar > 120 mg/dl. 0 indicates otherwise
8. thalachh: maximum heart rate achieved
9. exng: exercise induced angina. 1 indicates True and 0 indicates False.
10. oldpeak: ST depression induced by exercise relative to rest
11. slp: Slope of the peak exercise ST segment: 0 indicates Value 1: upsloping, 1 indicates Value 2: flat, 2 indicates Value 3: downsloping
12. caa: number of major vessels that ranges from 0 to 3.
13. thall: thal rate

The output 0 indicates low risk of heart attack and 1 indicates high risk. 

The following 10 models are trained to classify patients in low risk and high risk categories: 
1. XGBoost 
2. GradientBoosting
3. Ada Boosting 
4. KNN 
5. Naive Bayes 
6. SVM 
7. Logistic Regression 
8. Decision Tree 
9. Random Forest 
10. Stacking Model which uses KNN, XGBoost and Logistic Regression as the estimators and GradientBoosting as the final model.

The models are evaluated using confusion matrices and accuracy scores. 
Finally, new predictions are made on the model having highest accuracy. 
