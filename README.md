# CSCI-4502-Data-Mining Group 4 Project

# Box Office Revenue Prediction

## Team member

Nhan Nguyen

Melissa Pollich

Benjamin Breyfogle

### Description of the project

The global film industry is worth over $136 billion. Despite the massive profits, movie industry is one of the riskiest markets for investors due to its uncertainty and unpredictability.

Once a movie fails to meet expectation, it can potentially place a stress on the financial status of the movie studio, and lead to the withdrawal of funds from the investors.

Therefore, through analyzing the performance of movies on the market, we could find the correlation between attributes of a movie and predict the revenue on release.


### Questions sought and the answers 

In this project, we want to see how various elements of a movie contribute to its revenue in box office. These elements are budget, popularity, vote count...

We want to see if a predictive model for revenue can be made from these attributes. The models include Linear, Random Forest and Decision Tree Regression.

This project include Data Cleaning, Data Processing, Data Mapping, Binarizing of categorial attributes, training dataset, testing dataset, predictive model based on Linear, Random Forest and Decision Tree Regression.

Linear Regression:

<img src=https://github.com/nhannguyen2109/CSCI-4502-Data-Mining/blob/master/Data/Linear.png width="425">

<img src=https://github.com/nhannguyen2109/CSCI-4502-Data-Mining/blob/master/Data/Linear%202.png width="425">

Linear Regression Scores(train_test_split):

Mean Absolute Error: 39.43043039854889

Mean Squared Error: 6817.850459880546

Median Absolute Error: 17.201820528760287

Explained Var Score: 0.7808385785290977

R^2 Score: 0.7804132535210337

Root Mean Squared Error: 82.57027588594183

Root Mean Squared Logarithmic Error: 1.0133662599662634

Random Forest Regression:

<img src=https://github.com/nhannguyen2109/CSCI-4502-Data-Mining/blob/master/Data/Random%20Forest.png width="425">

<img src=https://github.com/nhannguyen2109/CSCI-4502-Data-Mining/blob/master/Data/Random%20Forest%202.png width="425">

Random Forest Regression Scores(train_test_split):

Mean Absolute Error: 44.32481404481044

Mean Squared Error: 7290.243562892095

Median Absolute Error: 19.789213599999997

Explained Var Score: 0.7602265722831311

R^2 Score: 0.7600637723525838

Decision Tree Regression:

<img src=https://github.com/nhannguyen2109/CSCI-4502-Data-Mining/blob/master/Data/Tree.png width="425">

<img src=https://github.com/nhannguyen2109/CSCI-4502-Data-Mining/blob/master/Data/Tree%202.png width="425">

Decision Tree Regression Scores(train_test_split):

Mean Absolute Error: 59.009372080795515

Mean Squared Error: 14342.770276189405

Median Absolute Error: 22.663409

Explained Var Score: 0.5280692922902059

R^2 Score: 0.5279512729040885



The predicted values are not close to the reported data values as we had hoped to achieve, but they are not too far off from the actual data.

The predicted values are consistent between three regression model.

Textual data like plot summary, movie name and some more categorial data like actors, directors could help improve the result.

There are many interactions outside the data like trailers, actor’s popularity that affects the revenue.

Using better technique like Deep Neural Network could help make the prediction more accurate

## Applications

While these are not accurate model, we can use this as references for revenues of unreleased movies because of some of the most correlated attributes like budget and vote count.

These models could be improved in the future with better techniques like Scaling, Transforming, analyzing of Textual attributes like plot summary, preview…

Including the amount of interactions on social media, list of actors and directors… from other datasets (integration) could help further improve the predictive model

### Link to video demonstration

Explain what these tests test and why

### Link to final project paper

Explain what these tests test and why
