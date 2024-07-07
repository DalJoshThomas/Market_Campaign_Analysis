# Market_Campaign_Analysis
![Title](https://github.com/DalJoshThomas/Market_Campaign_Analysis/blob/main/Title%20Page.png)

**Executive Summary:** Using Python, I analyzed a Marketing Campaign using A/B testing and used machine learning to find the most important features affecting churn rates. I recommend that the business should focus the majority of their efforts on a specific age group (35 year olds - 55 year olds), additionally they should optimize housing advertisements, in addition to enhancing personlized ads. 

**Aim:** To analyze the performance of the marketing campaigns to identify key factors that drive customers conversion and retention, with the goal of optimizing marketing strategies to enhance customer engagement and increasing conversions.


**Methodology:** 
The data for the Marketing Campaign Analysis project was sourced from a single marketing campaign and included various customer interaction metrics. Initial data preprocessing involved cleaning the dataset by removing duplicates, handling missing values through imputation techniques, and standardizing data formats for consistency. The data was then split into training (70%) and testing (30%) sets to ensure the robustness of the model. The project utilized A/B testing to assess the effectiveness of personalized ad campaigns. The sample was randomly divided into control (existing marketing strategy) and test (personalized ad campaigns) groups, and campaigns were run for a predefined period with equal exposure to both groups. A Chi-squared test was performed to analyze the significance of conversion rate differences, resulting in a significant 36.73% increase in conversion rates for the test group. Following the A/B testing, a Random Forest classifier was employed to identify key drivers of customer behavior and conversion rates. The model was trained on the training dataset, with hyperparameters optimized for improved performance. Feature importance scores from the Random Forest model highlighted crucial factors such as customer engagement metrics and demographic characteristics. The model’s performance was evaluated using accuracy, precision, recall, and F1-score metrics, achieving a predictive accuracy of 91% for customer churn. Cross-validation was used to ensure the model’s robustness. This comprehensive methodology enabled the identification of significant insights that improved marketing strategies and enhanced customer retention efforts.


**Skills:**
Data preprocessing, Experimental design, Statistical analysis, Machine learning techniques, Hyperparameter tuning, Cross-validation, Feature importance analysis, Data analysis,Python


**Results and Business Recommendation:**
![Results](https://github.com/DalJoshThomas/Market_Campaign_Analysis/blob/main/Feature%20importance.png)







