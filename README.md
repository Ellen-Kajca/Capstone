# Capstone

### This notebook contains an analysis of the Brazilian E-Commerce Public Dataset by Olist from Kaggle. I explore the data, and evaluate different models as well as looking at the most important features.

The data can be found here: https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

I begin with data cleaning, and then I explore the data. Specifically, I look at a lot of ditribution. Then, I look at clustering, logistic regression and a decision tree model. 

#### Research question:
What factors motivate a consumer to make a purchase, and can we use those factors to identify potential customers?

#### Expected data sources:
Kaggle ecommerce data regarding customer profiles and purchasing information

#### Expected techniques:
CRISP–DM
Explore data, cluster analysis for classification of customer made purchase or did not, predictive model for predicting target customer, feature importance analysis to see what factors are most important to customers that make a purchase

#### Expected results:
I expect that there will be a few strong factors that influence the purchasing decision, I also expect that I will be able to target customers who fit the profile of these factors to make purchases

#### Why the question is important:
This question is important because understanding why a customer purchases is essential to marketing strategies and increasing profitability for a commerce company.

### Techniques:
CRISP–DM
Explore data, cluster analysis for classification of customer made purchase or did not, predictive model for predicting target customer, feature importance analysis to see what factors are most important to customers that make a purchase

### Findings
#### Customer Profile
- The average customer age is ~ 40 years old
- The average customer salary is about $58,000

#### Clustering 
- 92% of customers were in one cluster where the average income was around 60k and were moderate spenders

#### Predictive Model
- With 78% confidence we found that we are able to predict customer satisfaction (rating of above 4)
- The most important features in influencing the model were: Spending Score, Annual Income and Purchase History

### Next Steps / Recommendations 
#### Enhance predictive models
- Improve regression to better predict customer satisfaction
 
#### Clustering
- Segement customers into clusters for marking campagins and other personalized approaches

#### Customer Data
- Continuously update data and models to reflect ordering 
