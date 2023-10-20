# Greek_Tourism_Insight

Project_04

Link to slide deck: https://docs.google.com/presentation/d/1ObROAk8j4MwT3C039XaXKyEsCCQSRPHp7ugol0l518U/edit?usp=sharing

## Members

Reinforcement Learning Rockstars

- Mavin Gill				
- David Kauffman				
- Natalia Lopez				
- Andrew Rexford				

--------------------

## Dataset
https://www.kaggle.com/datasets/teamincribo/greece-travel-data/data

---------------------

## Summary

- Retrieved our dataset from Kaggle
Project focused on analyzing Greek tourism insights
- Some of our topics of discovery were:
1. Best times to travel to Greece
2. What type of accommodation people used when travelling 
3. Exploring relationships between cost and accommodation, date of travel and length of stay


## Data Source and Limitations

Greek tourism data from Kaggle
- 3,000 rows, 13 columns
- Date range January 2020 - August 2023
- Mix of authentic and synthetic data.
Data source did not specify a currency in the documentation
- We assumed cost in Euros
Cost column varies wildly
- Examples:
28 day trip costing 5,032
1 day trip costing 29,909

------------------------------------------

## Cleaning and Exploring the dataset.

- What are the best months to travel to Greece?


Most Affordable:
June
March
September

Smallest Crowds:
July
June
February

Best Overall: June

- Exploring the dataset and finding limitations due to synthetic data. Graphs showing data distribution.

------------------------------------------

## Machine Learning

1. We created a Logistic Regression model focused on the ‘type of stay’ that tourists used most often. 
Accuracy of the model with 1,000 iterations was the strongest, at 27%
Airbnb had the best overall accuracy scores, with an average accuracy percentage of 30% between the 3 models.

2. We created a Logistic Regression model focused on the ‘Duration of the Stay’. 
Accuracy of the model with 2,000 iterations was the strongest, at 79%

3. Regression models to predict:
- Duration of Stay based on Cost. Unsuccesful.
- Cost based on Duration of Stay. Input: Number of days. Output: Cost

--------------------------------------------

## Conclusion

- Best month to travel: June.
- Dataset was not very conducive to accurate machine learning models.
- May be due to inclusion of synthetic data.
