# Market_Campaign_Analysis
![Title](https://github.com/DalJoshThomas/Market_Campaign_Analysis/blob/main/Title%20Page.png)

**Executive Summary:** Using Python, I analyzed a Marketing Campaign using A/B testing and used machine learning to find the most important features affecting churn rates. I recommend that the business should focus the majority of their efforts on a specific age group (35 year olds - 55 year olds), additionally they should optimize housing advertisements, in addition to enhancing personlized ads. 

**Aim:** To analyze the performance of the marketing campaigns to identify key factors that drive customers conversion and retention, with the goal of optimizing marketing strategies to enhance customer engagement and increasing conversions.


**Methodology:** 
The data for the Marketing Campaign Analysis project was sourced from a single marketing campaign and included various customer interaction metrics. Initial data preprocessing involved cleaning the dataset by removing duplicates, handling missing values through imputation techniques, and standardizing data formats for consistency. The data was then split into training (70%) and testing (30%) sets to ensure the robustness of the model. The project utilized A/B testing to assess the effectiveness of personalized ad campaigns. The sample was randomly divided into control (existing marketing strategy) and test (personalized ad campaigns) groups, and campaigns were run for a predefined period with equal exposure to both groups. A Chi-squared test was performed to analyze the significance of conversion rate differences, resulting in a significant 36.73% increase in conversion rates for the test group. Following the A/B testing, a Random Forest classifier was employed to identify key drivers of customer behavior and conversion rates. The model was trained on the training dataset, with hyperparameters optimized for improved performance. Feature importance scores from the Random Forest model highlighted crucial factors such as customer engagement metrics and demographic characteristics. The model’s performance was evaluated using accuracy, precision, recall, and F1-score metrics, achieving a predictive accuracy of 91% for customer churn. Cross-validation was used to ensure the model’s robustness. This comprehensive methodology enabled the identification of significant insights that improved marketing strategies and enhanced customer retention efforts.


**Skills:**
Data preprocessing, Experimental design, Statistical analysis, Machine learning techniques, Hyperparameter tuning, Cross-validation, Feature importance analysis, Data analysis,Python


**Results and Business Recommendation:**
        
1. Optimize House Advertisements:
        
Reduce Frequency: The most important feature determining if someone converted or not was house ads. To improve conversion rates, the business should reduce the frequency of house advertisements. Since, these conversion rates were the lowest relative to the other avenues.
        
Refinement: Analyze the performance of different house ads to identify which ones are performing poorly. Consider refining or replacing them with more engaging content. The business could opt to improve house ads, possibly catering to subsets which like house ads or drop house ads altogether.
        
2. Enhance Personalized Advertisements:
        
Data-Driven Personalization: Invest further into advanced data analytics to gain deeper insights into customer preferences and behavior. Use this data to create highly personalized advertisements that resonate with individual users.
        
Dynamic Content: Implement dynamic ad content that changes based on user interactions and preferences. This will ensure that each ad is relevant to the viewer, increasing the likelihood of conversion.
        
3. Controlled Advertisement:
        
A/B Testing: Continuously perform A/B testing on controlled advertisements to identify the most effective variations. Use the insights from these tests to optimize ad content, placement, and timing.
        
Targeted Campaigns: Create targeted ad campaigns based on specific user segments. Tailor the messaging and creatives to address the unique needs and interests of these segments.
        
4. Language-Related Features:
        
Localization: Even though language-related features were the least important, it's essential not to ignore them completely. Ensure that ads are properly localized to cater to different language speakers, enhancing user experience and potential engagement.
        
Cultural Relevance: Consider cultural nuances and preferences in the content of advertisements to make them more appealing to diverse demographic groups.
        
5. Focus on Demographic Groups (Ages 35-55):
        
Customized Strategies: Develop customized marketing strategies for the 35-55 age group. Understand their specific needs, preferences, and pain points to tailor advertisements that speak directly to them.
        
Engagement Channels: Identify the preferred channels and platforms for this demographic. Ensure that advertisements are prominently placed on these channels to maximize visibility and engagement.

6. Continuous Monitoring and Improvement:
        
Performance Analytics: Implement robust analytics to continuously monitor the performance of different advertisement types. Use these insights to make data-driven adjustments in real-time.
        
Feedback Loops: Establish feedback loops with customers to gather insights on their preferences and reactions to different advertisements. Use this feedback to refine and improve ad strategies.
        
7. Comprehensive Marketing Strategy:
        
Integrated Approach: Combine online and offline marketing efforts to create a seamless customer journey. Ensure consistency in messaging and branding across all touchpoints.
        
Collaborative Efforts: Work closely with sales, product, and customer service teams to align marketing strategies with overall business goals. This collaboration can lead to more cohesive and effective campaigns. 







