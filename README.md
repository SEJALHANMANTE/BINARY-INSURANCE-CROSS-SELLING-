# BINARY-INSURANCE-CROSS-SELLING 

![image](https://github.com/user-attachments/assets/ba1f57c6-adf8-4d4c-8277-2d21bce98301)

# Kaggle Notebook link 
<a id="Kaggle notebook"></a>
[[https://www.kaggle.com/code/sejalhanmante/binary-classification-of-insurance-selling](#Kaggle notebook)

**💡 About The Competition :**
- Task: The objective of this competition is to predict which customers respond positively to an automobile insurance offer..
- Dataset: The dataset for this competition (both train and test) was generated from a deep learning model trained on the Health Insurance Cross Sell Prediction Data dataset. Feature distributions are close to, but not exactly the same, as the original. Feel free to use the original dataset as part of this competition, both to explore differences as well as to see whether incorporating the original in training improves model performance.
- Evaluation: Submissions are evaluated using area under the ROC curve.
- Submission: train.csv - the training dataset; Response is the binary target test.csv - the test dataset; your objective is to predict the probability of Response
for each row sample_submission.csv - a sample submission file in the correct format

**🎄🎋 About The Data Columns :**
- 😃We're studying to predict which customers respond positively to an automobile insurance offer.
- 🥨Gender: Categorical variable indicating the gender of the customer.
- 🌭Age: Numeric variable indicating the age of the customer.
- 🥓Driving_License: Binary variable indicating if the customer has a driving license (1 if yes, 0 if no).
- 🚜Region_Code: Numeric variable indicating the region code of the customer.
- 🥡Previously_Insured: Binary variable indicating if the customer was previously insured (1 if yes, 0 if no).
- 🖼Vehicle_Age: Categorical variable indicating the age of the vehicle.
- 🕸Vehicle_Damage: Categorical variable indicating if the vehicle was damaged in the past.
- 🕶Annual_Premium: Numeric variable indicating the annual premium amount.
- 🎡Policy_Sales_Channel: Numeric variable indicating the sales channel of the policy.
- 🎢Vintage: Numeric variable indicating the number of days the customer has been associated with the company.
- 🎞Response: Binary target variable indicating if the customer responded positively to the automobile insurance offer (1 if yes, 0 if no).

**🎋 Workflow**
1. 🚗 Loading the dataset 🚗
2. 📱 UNDERSTANDING THE DATASET 📱
3. 🔻REDUCING MEMORY USAGE
4. 🎞️ DATA VISUALIZATION 🎞️
5. 🪓 TRAIN-TEST SPLIT ON "train_df" 🪓
6. 🐧 DATA PREPROCESSING 🐧
7. 🏷️ LABEL ENCODING 🏷️
8. ↗️ SCALING THE DATA
9. 📍 MODEL DEVELOPMENT 📍
    - Naive Bayes
    - LightGBM
    - XGBoostClassifier
    - DecisionTrees
    - Neural Network
10. 🧮 SUBMISSION 🧮
 
