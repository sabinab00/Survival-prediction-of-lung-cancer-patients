# Survival Prediction of Lung-Cancer Patients
The World Health Organization (WHO) reports cancer as the leading cause of death worldwide. Medical records, laboratory, and examination data, as well as questionnaires are continually conducted worldwide to assess and quantify the risk factors and reduce the impact of this global problem through early detection and early based prevention programs. Examining patterns in clinical analysis and finding correlations between symptoms and risk factors can help reduce the implications of lung cancer by avoiding the causes far before the detection of the disease.

In this project, we will use medical examination data that report mortality rates of lung cancer patients and build machine learning predictive models to predict the survival/mortality of patients one year after the thoracic surgery. The approach is to devise comparable machine learning algorithms and implement them in this medical application to predict post-operative life expectancy in lung-cancer patients. The topic described is a supervised learning task, more specifically, a classification problem with risk of mortality as a target variable.

# Team Contribution
Manal Zneit – implemented the ML algorithms, built, and evaluated predictive models.
Sabina Bhuiyan – designed the visualization tool for comparison and analysis of the models, ranked risk factors and made the video. Sabina also participated in designing some predictive models as shown in her report.

The first 14 pages of the report were written by Manal Zneit. Sabina Bhuiyan wrote the rest of the report.


# Algorithms
The project described is a real-world problem - a classification task where we will implement several machine learning classifiers that predict the survival of patients. SVM, MLP, Logistic Regression, Naive Bayes, KNN, DT, and Random Forest were implemented and their performance measures were compared. 


# Results
The performance of the classifiers was compared based on the AUC performance metric. The best performance was achieved by SVM (94%) followed by ANN (87%) and Random Forest (87%). DT and Multinomial Naïve Bayes had the lowest AUC values (64% and 72%) and NB was the weakest classifier in terms of precision, recall, F1 score, and accuracy. The following table shows the performance of the classifiers:

![alt text](https://github.com/mZneit/Survival-prediction-of-lung-cancer-patients/blob/main/table.jpg)

The ROC curve of each of the classifiers is shown in this figure:
![alt text](https://github.com/mZneit/Survival-prediction-of-lung-cancer-patients/blob/main/SMOTE%20Test%20Set.png)

# Video Link: https://youtu.be/tQFzEOe4ZHY 
# Visualization: https://public.tableau.com/profile/sabina.bhuiyan#!/vizhome/MLFinalProjectVisualization/Dashboard1?publish=yes
