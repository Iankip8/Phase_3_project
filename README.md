# SYRIATEL TELCOM CHURN RATE ANALYSIS
![depositphotos_10011130-stock-photo-satellite-dish](https://github.com/Iankip8/Phase_3_project/assets/160301660/b3b68f3d-e600-44eb-a9ad-f40412a10ddc)


**Project Overview:**
Syriatel Telecom aims to understand and mitigate customer churn, utilizing binary classification models to predict attrition. The primary objective is to identify influential factors and minimize financial losses associated with customer defection.

**Problem Statement:**
SyriaTel seeks to maintain or increase its customer retention rate by developing an accurate binary classification model. The model should predict the likelihood of customers discontinuing their services and pinpoint factors to address to reduce attrition.

**Data Science Process Used:**
Adhering to the CRISP-DM Process, the project involves:

1. **Business Understanding:** Telecoms prioritize subscriber acquisition and retention. Addressing customer churn is crucial in the competitive telecom sector, such as Syriatel. Accurate prediction of churn factors enables proactive identification of at-risk customers and formulation of personalized retention strategies, ultimately reducing revenue losses and enhancing customer satisfaction.

2. **Data Understanding:** The SyriaTel Dataset from [Kaggle](https://www.kaggle.com/becksddf/churn-in-telecoms-dataset)., encompassing information on approximately 3,333 customers, was utilized. It includes details like customer location, tenure, plan usage, and customer service interactions.

3. **Exploratory Data Analysis:** During the Exploratory Data Analysis (EDA) phase, we delve into the dataset to uncover its fundamental attributes and patterns. This process involves examining summary statistics, visualizing distributions, identifying correlations, and detecting outliers. EDA is a crucial preliminary step, offering insights that inform subsequent data preprocessing and modeling decisions.
The visualization below illustrates the distribution of customers across the top 5 states and the bottom 5 states. This analysis offers insights into the geographic concentration of customers and highlights regions with potentially lower customer engagement.
![Capture](https://github.com/Iankip8/Phase_3_project/assets/160301660/c884d42d-14e7-4df5-9d5f-0585f732151c)
![bottom5](https://github.com/Iankip8/Phase_3_project/assets/160301660/5bc27992-2176-426a-946c-3dfad48d68fa)

The churn rate analysis by area code, voice mail plan, and international plan reveals variations in churn across different factors. This examination aided in identifying the factors influencing customer attrition. Through this process, we gained valuable insights into customer retention dynamics and formulated strategies to address churn effectively.

![churn](https://github.com/Iankip8/Phase_3_project/assets/160301660/7903bfbf-1b1b-4983-9687-9df2470f40b7)

5. **Data Preparation:** Data underwent transformation, cleaning, and preprocessing, involving tasks such as data type conversion, handling multicollinearity, and data splitting.

6. **Modeling:** Four models—Decision trees, Random forests, Logistic regression, and Gradient Boost Classifier—were fitted to predict customer churn. The Gradient Boost Classifier emerged as the best-performing model with a Training Accuracy of 97.39% and a Validation accuracy of 93.55%.

![roc_auc](https://github.com/Iankip8/Phase_3_project/assets/160301660/827dfaac-4de5-46d7-840f-dc11e9277504)


**Model Evaluation:**
Model performance evaluation includes metrics like accuracy, precision, recall, F1-score, and ROC-AUC, ensuring alignment with the business requirements and goals of Syriatel Telecom.

![validation](https://github.com/Iankip8/Phase_3_project/assets/160301660/078093b1-f70b-4850-8a91-8c125e00a2d0)

Additionally, the key features shown to influence whether a customer would churn can be seen in the bar plot displayed below. We note that  international plan is a key variable in predicting future events.

![key_features](https://github.com/Iankip8/Phase_3_project/assets/160301660/7d7afb45-e68b-4e15-9fdb-854689bdbe04)

### Results and Conclusion
### Results

Our predictive modeling approach effectively addresses the challenge of customer churn for Syriatel. Using advanced data analytics and machine learning techniques, we developed models that accurately identify customers at risk of churning. The XGBoost model demonstrated superior performance, achieving the highest accuracy score.

Key insights from the analysis include:

- **Churn Rate by Area Code, Voice Mail Plan, and International Plan**: Significant variations in churn rates were observed across different area codes, voice mail plans, and international plans, highlighting factors affecting customer churn.
- **Customer Service Interactions and Service Plan Features**: Customer service interactions and specific service plan features emerged as critical factors influencing churn.

### Conclusion

This project provided a robust predictive model and critical insights into customer behavior and preferences. Understanding the key factors influencing churn allows Syriatel to tailor strategies to meet customer needs more effectively. Continuous updates and refinements ensure the model remains accurate in predicting customer churn as market conditions and customer behaviors evolve.

Implementing these models and recommendations will enhance Syriatel's customer retention efforts, reduce churn rates, and improve overall business performance. Proactively identifying at-risk customers enables timely and targeted interventions, crucial for maintaining a satisfied and loyal customer base. Focusing on customer service improvements and personalized promotions will significantly boost customer satisfaction and loyalty.


