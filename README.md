# SyriaTel Customer Churn Model
    by Kevan Muthomi Ndwiga
## Introduction
Did you know that in the fiercely competitive telecommunication industry, a staggering 80% of customer churn happens within the first 90 days?  This means that for every 5 customers a company acquires, 4 might leave within a short period, leading to significant revenue loss.

### Problem Statement
SyriaTel, like many telecommunication companies, faces a significant challenge: customer churn. Customers who discontinue their services lead to lost revenue and increased customer acquisition costs. This hinders SyriaTel's growth and overall profitability.

### Main Objective
Develop a machine learning model to predict customer churn for SyriaTel.

### Specific Objectives
  1. Identify patterns and relationships within customer data that are indicative of churn.
  2. Identify patterns and relationships within customer data that are indicative of churn.
  3. Select the best performing model and interpret its results to understand key factors influencing churn.

## Notebook Structure
- Data Wrangling
- Exploratory Data Analysis
- Data Preprocessing
- Modeling
- Conclusions
- Recommendations

### Data Understanding
The data used in this notebook was obtained from Kaggle. It contains the following columns:
            
            account length - The duration in which a customer has been a subscriber to SyriaTel            
            area code - Area code of the subscriber        
            phone number - Subscriber telephone number              
            international plan -Whether a customer is subscribed to an international call plan
            voice mail plan  - Whether a customer is subscribed to the voicemail plan
            number vmail messages   - Count of the number of voicemail messages sent by a subscriber
            total day minutes       - Total duration in minutes spent by a subscriber during calls made during the day 
            total day calls         - Total number of calls made during the day
            total day charge        - Total cost given to the subscriber during the day
            total eve minutes       - Total duration in minutes spent by a subscriber during calls made during the evening
            total eve calls         - Total number of calls made during the evening
            total eve charge        - Total cost given to the subscriber during the evening
            total night minutes     - Total duration in minutes spent by a subscriber during calls made during the night
            total night calls       - Total number of calls made during the night 
            total night charge      - Total number of calls made during the evening
            total intl minutes      - Total duration in minutes spent by a subscriber during calls made internationally
            total intl calls        - Total number of calls made internationally
            total intl charge       - Total cost given to the subscriber during international calls
            customer service calls  - Number of calls made to the customer service center by a subscriber
            churn - Whether or not a customer is retained

### Methodology
### Data Wrangling
The dataset had 0 null and 0 missing values.

### Exploratory Data Analysis
1. Univariate EDA Univariate data analysis focuses on analyzing individual variables to remove any outliers within the dataset
2. Bivariate Analysis Bivariate analysis examines the relationship between two variables. This helped in understanding how different features relate to customer churn.
3. Multivariate Analysis Multivariate analysis investigates the interplay among multiple variables, focusing on their correlation with the target variable, customer churn

     Relevant visaulizations were generated from the analysis

### Data Preprocesing
-A train test split was performed on the data in order to divide the dataset into the training and testing data.

### Modelling
-For this project, models were created, evaluated and tuned to provide accurate predictions for customer churn

The models used include:
-  Decision Tree Classifier. This algorithm partitions the dataset into refined subsets, predicting the class of new data based on feature values.
-  K- Nearest Neighbour. 
-  XGBoost XGBoost merges weak models, like decision trees, using features such ensemble learning, which result in a more accurate model.


## Conclusions
- The column total_charge has the highest correlation with customer churn since it has proved to be crucial during the training and testing of the models

- XGBoost proved to be the best suited model due to its high accuracy scores

## Recommendation(s)
1. Pricing and Contract Flexibility: If pricing is a major churn factor, consider offering more flexible plans, introductory discounts, or tiered pricing options to cater to different customer needs and budgets.
2. Targeted Promotions and Discounts: Use the model to identify customer segments at risk of churning and offer them targeted discounts, loyalty programs, or bundled packages that address their specific needs and usage patterns.
3. Improved Customer Service: Analyze customer service interactions within the data to identify areas for improvement. Train customer service representatives to address churn-related concerns effectively and offer personalized solutions.
    












## Canva Presentation Link
The link to the [Canva Presentation](https://www.canva.com/design/DAF_HMwFw10/Vw1AUyZcAAV0t2lUz4gbug/edit?utm_content=DAF_HMwFw10&utm_campaign=designshare&utm_medium=link2&utm_source=sharebuttonhttps://www.canva.com/design/DAF_HMwFw10/Vw1AUyZcAAV0t2lUz4gbug/edit?utm_content=DAF_HMwFw10&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)
