# SYRIATEL TELCOM CHURN RATE ANALYSIS
![depositphotos_10011130-stock-photo-satellite-dish](https://github.com/Iankip8/Phase_3_project/assets/160301660/b3b68f3d-e600-44eb-a9ad-f40412a10ddc)


**Project Overview:**
Syriatel Telecom aims to understand and mitigate customer churn, utilizing binary classification models to predict attrition. The primary objective is to identify influential factors and minimize financial losses associated with customer defection.

**Problem Statement:**
SyriaTel seeks to maintain or increase its customer retention rate by developing an accurate binary classification model. The model should predict the likelihood of customers discontinuing their services and pinpoint factors to address in order to reduce attrition.

**Data Science Process Used:**
Adhering to the CRISP-DM Process, the project involves:

1. **Business Understanding:** Telecoms prioritize subscriber acquisition and retention. Addressing customer churn is crucial in the competitive telecom sector, such as Syriatel. Accurate prediction of churn factors enables proactive identification of at-risk customers and formulation of personalized retention strategies, ultimately reducing revenue losses and enhancing customer satisfaction.

2. **Data Understanding:** The SyriaTel Dataset from [Kaggle](https://www.kaggle.com/becksddf/churn-in-telecoms-dataset)., encompassing information on approximately 3,333 customers, was utilized. It includes details like customer location, tenure, plan usage, and customer service interactions.

3. **Exploratory Data Analysis:** During the Exploratory Data Analysis (EDA) phase, we delve into the dataset to uncover its fundamental attributes and patterns. This process involves examining summary statistics, visualizing distributions, identifying correlations, and detecting outliers. EDA serves as a crucial preliminary step, offering insights that inform subsequent data preprocessing and modeling decisions.
The visualization below illustrates the distribution of customers across the top 5 states and the bottom 5 states. This analysis offers insights into the geographic concentration of customers and highlights regions with potentially lower customer engagement.
![Capture](https://github.com/Iankip8/Phase_3_project/assets/160301660/c884d42d-14e7-4df5-9d5f-0585f732151c)
![bottom5](https://github.com/Iankip8/Phase_3_project/assets/160301660/5bc27992-2176-426a-946c-3dfad48d68fa)

The analysis of churn rate by area code, voice mail plan, and international plan reveals variations in churn across different factors. This examination aided in identifying the factors influencing customer attrition. Through this process, we gained valuable insights into the dynamics impacting customer retention and formulated strategies to address churn effectively.

![churn](https://github.com/Iankip8/Phase_3_project/assets/160301660/7903bfbf-1b1b-4983-9687-9df2470f40b7)

5. **Data Preparation:** Data underwent transformation, cleaning, and preprocessing, involving tasks such as data type conversion, handling multicollinearity, and data splitting.

6. **Modeling:** Four models—Decision trees, Random forests, Logistic regression, and Gradient Boost Classifier—were fitted to predict customer churn. The Gradient Boost Classifier emerged as the best-performing model with a Training Accuracy of 97.39% and a Validation accuracy of 93.55%.

![roc_auc](https://github.com/Iankip8/Phase_3_project/assets/160301660/827dfaac-4de5-46d7-840f-dc11e9277504)


**Model Evaluation:**
Evaluation of model performance includes metrics like accuracy, precision, recall, F1-score, and ROC-AUC, ensuring alignment with business requirements and goals of Syriatel Telecom.

![validation](https://github.com/Iankip8/Phase_3_project/assets/160301660/078093b1-f70b-4850-8a91-8c125e00a2d0)
