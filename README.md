
# Optimizing Marketing Campaigns in Banking Industry



# Introduction

Growing revenue through different marketing strategies along with a focus on the acquisition and retention of customers is the essence for marketing campaigns in order to complete the sales goal. We want to build a model that can enable banks to increase revenue and decrease cost by determining the timing of marketing campaigns and find out the potential clients who are the most likely persuaded into purchasing a product or service.

## Explanatory data analysis

![Correlation Matrix](https://i.imgur.com/JsSgRyq.png)

![Distributions of important variables](https://i.imgur.com/PVXOg24.png)

![](https://i.imgur.com/RllcS0v.png)




## Model building

The algorithm of Random Forest (RF) was used in order to do classification for the bank customers in this marketing campaign. A grid-search was set up which enables the model to run iteratively with the predefined parameter values. The data was divided into 5 equal parts with a ratio of 4:1 for training and testing respectively. With the assigned parameter values for the random forest model, the process was repeated 5 times and the average value yielded the final accuracy. After employing the algorithm on the training data, an AUC-ROC curve was created to test the performance of this model. An approximate score of 0.8 for the current model, which indicated the high accuracy and validity the model had. To find which variables were of the most significance, feature selection using random forest was applied. The top five features that contributed to decreasing the impurity of the model were selected and visualized using a bar chart from the seaborn package in Python. As a result, four social and economic attributes (euribor rate, employment variation rate, number of employees, consumer confidence index) and number of days past since the last campaign are the top five features in the RF model. 

## Visualize important features of random forest classifier

![Feature importance of random forest classifier](https://i.imgur.com/dVULOvj.png)




## Recommendation

Based on the importance of variables in the model, we make our recommendation to the marketing team.

The team should convey the idea of safe investment and steady income source as the value proposition. People generally want to open a deposit account when interest rate is higher and market is stable. Bank will have a better outcome in the marketing campaign when people have faith in the market.

