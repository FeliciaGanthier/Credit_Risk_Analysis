# **Credit Risk Analysis**

## **Overview of Project**

FastLending is a peer-to-peer lending services company that wants to use machine learning to predict credit risk to provide a quicker and more reliable loan experience for customers. FinTech commonly uses machine learning or statistical algorithms to perform tasks such as learning from data patterns and making predictions to analyze risk.  For this project, we will use Python and Scikit-Learn (a Python Machine Learning Library) to predict credit risk.

*Purpose of Analysis*

Using machine learning will lead to a more accurate identification of good loan candidates and lower default rates. I am assisting Jill, the lead data scientist, in implementing this plan. I will build and evaluate several algorithms to predict credit risk.  A good data scientist understands both the hows and whys of their model so they can assess its strengths and weaknesses for best usage.  Our analysis will include evaluation tools such as Accuracy, Precision and Recall Scores for our models.

### **Results**

Random Oversampling: Instances of the minority class are randomly selected and added to the training set until the majority and minority classes are balanced

    o Accuracy: 65%

    o Precision (Avg): 99%

    o Recall(Avg): 61%

*Note: For High and Low Risk details, please refer to the image below.*

![Image Random Oversampling](https://github.com/FeliciaGanthier/Credit_Risk_Analysis/blob/main/Random%20Oversampling.png)

SMOTE Oversampling: Synthetic Minority Oversampling Technique; New instances are interpolated

    o Accuracy: 66%

    o Precision (Avg):99%

    o Recall(Avg): 69%

*Note: For High and Low Risk details, please refer to the image below.*

![Image SMOTE Oversampling](https://github.com/FeliciaGanthier/Credit_Risk_Analysis/blob/main/SMOTE%20Oversampling.png)

Undersampling: The size of the majority class is decreased

    o Accuracy: 66%

    o Precision (Avg): 99%

    o Recall(Avg): 42%

*Note: For High and Low Risk details, please refer to the image below.*

![Image Undersampling](https://github.com/FeliciaGanthier/Credit_Risk_Analysis/blob/main/Undersampling.png)

 SMOTEENN: Combines SMOTE and Edited Nearest Neighbors (ENN) Algorithms

    o Accuracy: 54%

    o Precision (Avg): 99%

    o Recall(Avg): 57%

*Note: For High and Low Risk details, please refer to the image below.*

![Image SMOTEENN](https://github.com/FeliciaGanthier/Credit_Risk_Analysis/blob/main/SMOTEEN.png)

Balanced Random Forest: Samples the data and builds several smaller, simpler decision trees

    o Accuracy: 79%

    o Precision (Avg): 99%

    o Recall(Avg): 87%

*Note: For High and Low Risk details, please refer to the image below.*

![Image Random Forest](https://github.com/FeliciaGanthier/Credit_Risk_Analysis/blob/main/Random%20Forest.png)

Adaptive Boosting (ADA Boost): Model is trained then evaluated until the error rate is minimized

    o Accuracy: 93%

    o Precision (Avg): 99%

    o Recall(Avg): 66%

*Note: For High and Low Risk details, please refer to the image below.*

![Image ADA Boost](https://github.com/FeliciaGanthier/Credit_Risk_Analysis/blob/main/ADABoost.png)

#### **Summary**

The analysis shows the Adaptive Boosting (ADA Boost) model is the best option for assessing credit risk. This model has an accuracy score of 93% and its precision score is almost perfect. Its sensitivity score isn’t the lowest of the models but false positives in highly sensitive tests are accepted as a cost of doing business. 
