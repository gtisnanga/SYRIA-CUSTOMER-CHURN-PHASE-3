# Syriatel customer churn analysis

## Business Understanding for Syriatel Churn Analysis
Syriatel's Business and the Impact of Emerging Technologies
Syriatel is a leading telecommunications company in Syria, providing a range of services including mobile and fixed-line telephony, internet access, and data services. As a state-owned enterprise, Syriatel plays a crucial role in the country's communication infrastructure.
Understanding the Problem:
Churn, or customer attrition, is a significant concern for telecommunications companies like Syriatel. When customers leave, it directly impacts revenue, brand reputation, and overall business health. Therefore, understanding the factors driving churn is crucial for developing effective retention strategies.

## Understanding the Problem
The goal is to predict which Syriatel customers are likely to churn and identify the underlying reasons for this behavior. This information can be used to develop targeted retention strategies and improve overall customer satisfaction.
Key Questions and Corresponding Classification Tasks:
1.Which customer segments are most likely to churn?

2.What are the primary reasons for customer churn?

3. What is the cost of customer churn to Syriatel?

## Data Understanding
The SyriaTel dataset from Kaggle is composed of a comprehensive set of customer features, providing multifaceted information about customer usage behaviors, preferences, and interactions.
The dataset contains 3333 entries and 21 columns.
The total memory usage of the dataset is approximately 524.2 KB.
The columns represent various customer attributes, including state, account length, area code, phone number, international plan, voice mail plan, number of voice mail messages, call durations and charges for different time periods and international calls, customer service calls, and churn status.
The dataset does not have any missing values, as indicated by the non-null counts.
The data types of the columns include bool, float64, int64, and object.
The bool column represents the churn status, indicating whether a customer discontinued the service (True) or not (False).
The float64 columns represent numerical values for call durations and charges.
The int64 columns represent numerical values for account length, area code, number of voice mail messages, call counts, and customer service calls.
The object columns include state, phone number, international plan, and voice mail plan, which are categorical variables.
By understanding these features and their implications, we can conduct in-depth analyses and predictive modeling to tackle the issue of customer churn.

## Explorative Data Analysis

![image](https://github.com/user-attachments/assets/b7b92118-79ae-45a7-9391-f39aec417443)
![image](https://github.com/user-attachments/assets/3950b3ba-9187-443e-a575-511fdf3fa7eb)
![image](https://github.com/user-attachments/assets/7c922072-4ced-4e93-855a-e77a97a2256e)
![image](https://github.com/user-attachments/assets/642d1bc7-77df-48f2-a4ed-37e94b49b843)

## Model Evaluation

![image](https://github.com/user-attachments/assets/4f9fb6af-7ba2-48fa-bdc8-1b6966253f8b)


![image](https://github.com/user-attachments/assets/5f23a07e-54b2-4c4c-afb6-193aa19c69ff)

![image](https://github.com/user-attachments/assets/1d98ad2f-7d04-4a7a-8654-72b75700637e)

![image](https://github.com/user-attachments/assets/766fb3e3-760b-4f01-a4d2-3283cef43ff5)

![image](https://github.com/user-attachments/assets/8c737cf2-becc-4f66-93a2-f6720235338e)

## Feature Importance

![image](https://github.com/user-attachments/assets/d9bd85b8-ed35-4f8e-965e-d012bee896a3)

## Conclusion
Recommendations
Customer Service Enhancement
Improve service quality to reduce call frequency.
Collect feedback from frequent callers.
Usage Patterns Analysis
Tailor plans for high call duration or total talk time.
Monitor and ensure positive experiences during long calls.
Plan-Specific Strategies
Offer promotions and support for international and voicemail plans.
Billing and Charges
Review and adjust billing practices; consider loyalty programs.
Align billing with high engagement call volumes.
Communication & Retention Programs
Create targeted campaigns using insights.
Implement churn prevention strategies.

Future Work
Feature Engineering
Explore new features and create interaction terms.
Model Improvement
Refine features using advanced selection techniques.
Continue hyperparameter tuning.
Model Comparison
Test additional models like XGBoost, LightGBM.
Use cross-validation for robustness.
Customer Segmentation
Perform segmentation and cluster analysis for targeted strategies.
Monitoring & Feedback Loop
Implement feedback loops and A/B testing for strategy optimization.






