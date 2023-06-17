# Customer Retention and ROI Optimization System for E-commerce Promotions

## Project Overview
Merchants often gain many new customers through promotions, but a significant portion of these customers are only interested in one-time deals. The impact of promotions on long-term sales may be limited. This project aims to design a system that maximizes return on investment (ROI), reduces promotional costs, and identifies one-time buyers. The system analyzes a dataset containing information on promotional shopping events from an e-commerce platform.

## Dataset
The dataset provided includes anonymized users' shopping logs and user profiles. The data is available in two different formats: data_format1 and data_format2. You can choose the format that best suits your feature engineering and analysis needs.

## Tasks Performed

### 1. Data Visualization
For data visualization, we analyzed the given dataset and created 10-15 graphs using appropriate visualization techniques. These visualizations helped us gain insights and effectively present information. Some of the key visualizations included:

- Box plots to showcase the distributions of numeric data values, allowing us to compare them between multiple groups.
- Bar charts to visualize the frequency of repeat buyers based on gender and age range.
- Line charts to analyze temporal patterns and trends in user interactions and purchases.
- Scatter plots to explore relationships between variables, such as the correlation between user age range and purchase frequency.

These visualizations provided a snapshot of the dataset, highlighting important patterns, trends, and relationships.

### 2. Feature Engineering
In the feature engineering phase, we leveraged the user interaction logs and user profiles to create valuable features that correlate users and merchants. We added 10-20 derived features to the dataset based on our understanding and creativity. Some of the features we created include:

- Total number of interactions per user
- Total number of interactions per merchant
- Average time between interactions for each user
- User activity level (high, medium, low) based on the frequency of interactions
- Purchase history of users (number of purchases, total purchase amount)
- User demographics (age range, gender) encoded as categorical variables

These derived features provided additional insights and improved the modeling and prediction capabilities of the system.

### 3. Dataset Statistics and Feature Ranking
To gain a better understanding of the dataset, we provided a statistical summary that included descriptive statistics and insights about its distribution. This summary helped us identify key characteristics and patterns within the data. Additionally, we performed feature ranking using correlation analysis and feature importance techniques. This allowed us to determine the most influential features and their relationships with the target variable. We also explored Principal Component Analysis (PCA) for feature reduction, comparing model performance before and after applying PCA with different numbers of features.

### 4. Prediction Models
We built prediction models to identify repeat buyers and design a recommendation system for customers. Our approach involved iterating through different combinations of features to identify optimal features and remove potentially correlated features. We started with a Bayes Classifier to classify customers as repeat buyers or non-repeat buyers. We evaluated the accuracy of the model using training and test datasets. We extended the Bayes Classifier to create a recommendation system that suggests products to customers based on their past interactions.

Furthermore, we implemented non-parametric techniques such as nearest neighbors and Parzen windows for classification. We experimented with different distance measures in nearest neighbor classification and performed a comparative study of performance between nearest neighbors and Parzen windows. Finally, we implemented a neural network model for classification and evaluated its performance in predicting repeat buyers.

### 5. Model Evaluation
To evaluate the performance of each classification technique, we used metrics such as accuracy, precision, recall, F1 score, ROC curve, and confusion matrix. We compared and contrasted the results of each technique to determine the best-performing method for the given classification problem. We discussed the strengths and weaknesses of each technique and provided recommendations for improving the classification task.

Additionally, we provided four recommendations for merchants or e-commerce platforms to address the business problem of stopping one-time buyers. These recommendations were based on our analysis and insights from the models:

- Implement personalized recommendations based on user preferences and past interactions to encourage repeat purchases.
- Offer loyalty programs or rewards to incentivize customers to become repeat buyers.
- Provide targeted discounts or promotions to specific customer segments that have a higher likelihood of becoming repeat buyers.
- Improve the overall customer experience by enhancing website usability, customer support, and post-purchase communication to increase customer satisfaction and encourage repeat purchases.

By following these recommendations, merchants can optimize customer retention and increase ROI by focusing on building long-term relationships with their customers.

## Usage
1. Clone this repository to your local machine.
2. Extract the dataset files (data_format1 or data_format2) to a directory.
3. Implement the tasks mentioned above in your preferred programming environment.
4. Update this README file with any additional instructions specific to your implementation.


