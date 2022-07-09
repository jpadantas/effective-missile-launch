# flames-missile-launch
2022 Winter Simulation Conference (WSC)

Python code for the paper Supervised Machine Learning for Effective Missile Launch Based on Beyond Visual Range Air Combat Simulations.

This work compares supervised machine learning methods using reliable data from constructive simulations to estimate the most effective moment for launching missiles during air combat. We employed resampling techniques to improve the predictive model, analyzing accuracy, precision, recall, and f1-score. Indeed, we could identify the remarkable performance of the models based on decision trees and the significant sensitivity of other algorithms to resampling techniques. The models with the best f1-score brought values of $0.379$ and $0.465$ without and with the resampling technique, respectively, which is an increase of $22.69\%$. Thus, if desirable, resampling techniques can improve the model's recall and f1-score with a slight decline in accuracy and precision. Therefore, through data obtained through constructive simulations, it is possible to develop decision support tools based on machine learning models, which may improve the flight quality in BVR air combat, increasing the effectiveness of offensive missions to hit a particular target.

Please check the ipynb files:

* 1-EDA.ipynb: Exploratory Data Analysis;
* 2-Feature-Selection.ipynb: Feature selection techniques using ANOVA-f Statistic and Mutual Information Statistics;
* 3-LR: Logistic Regression
* 4-KNN: K-nearest neighbors
* 5-SVM: Support Vector Machines
* 6-ANN: Artificial Neural Networks
* 7-NB: Naive Bayes
* 8-RF: Random Forest
* 9-XGBoost:  Extreme Gradient Boosting,
