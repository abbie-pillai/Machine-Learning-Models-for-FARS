# Machine-Learning-Models-for-FARS
Implemented  Naïve Bayes, Random Forest, PCA, Decision Trees from scratch on the dataset for classifying the impact various factor on the fatalities
### About the Dataset
The dataset provides detailed information about traffic accidents, including the state and county where the accidents occurred, the number of vehicles and pedestrians involved, the total number of individuals affected, and various temporal attributes such as the day, month, year, hour, and minute of the accidents. It also includes additional details such as the city name, road characteristics (e.g., route type, rural/urban classification), ownership of the road, location coordinates, special jurisdictions,factors contributing to the accidents (e.g., weather conditions, intoxication), and various codes and names associated with different aspects of the accidents. The dataset offers a comprehensive view of traffic accidents, allowing for analysis and exploration of factors contributing to road incidents and their potential consequences, such as fatalities and incidents involving drunk drivers.

### Conclusion 
Accuracy: 0.43491437367712144
The accuracy score of the logistic regression model is quite low at 0.43. This indicates that the model is not performing well in predicting the drug resistance status of the cases. It might be necessary to consider additional variables or feature engineering to improve the model's performance.

In our analysis of the dataset, we have found that classification models perform better than regression models in predicting the number of fatalities in a car accident.

We have identified the following features as the most important predictors: 'PERMVIT', 'PERSONS', 'VE_FORMS', 'VE_TOTAL', and 'MAN_COLL'. These features are related to the number of people and vehicles involved in the accident, as well as the manner in which the collision occurred.

By using these features as input to a classification model, we can train the model to predict the likelihood of a car accident resulting in a certain number of fatalities, such as none, one, two, or more. This can help inform policy decisions and allocate resources to improve road safety.

It is important to note that while regression models can also be used to predict the number of fatalities, classification models have shown better performance in our analysis. This may be due to the discrete nature of the dependent variable (number of fatalities), which is better suited for classification rather than regression.

'PERSONS' (total number of persons involved in the accident), 'PERMVIT' (total number of persons in the accident who suffered fatal injuries), 'VE_FORMS' represents the number of vehicles involved in the accident, 'VE_TOTAL' represents the total number of vehicles in the accident, and 'MAN_COLL' represents the manner of collision. are better predictor of fatalities
