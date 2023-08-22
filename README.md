# NBA Player Career Outcome Prediction

This project focuses on predicting NBA players' career outcomes using machine learning techniques. By analyzing player statistics and historical data, a predictive model is developed to categorize players into different performance categories, such as "Roster," "Rotation," "Starter," "All-Star," and "Elite."

The main objectives of this project were:
- Create a robust dataset by preprocessing and aggregating player statistics.
- Develop an accurate predictive model using Gradient Boosting Classifier.
- Visualize model results and outcome probabilities for specific players.

## Project Highlights

- **Data Preprocessing:** The project involved meticulous data preprocessing, including calculating per-game statistics, handling missing values, and merging data from different sources.

- **Feature Engineering:** Innovative functions were used to engineer key performance indicators such as points per game, assists per game, rebounds per game, steals per game, and blocks per game.

- **Model Tuning:** We used GridSearchCV to optimize hyperparameters for the Gradient Boosting Classifier, enhancing the model's predictive accuracy.

- **Visualization:** The project included compelling visualizations of feature importances and predicted outcome probabilities, aiding in the interpretation of model results.

## Data Preprocessing

The dataset was meticulously preprocessed to ensure quality input for the predictive model. This included:
- Aggregating statistics for players who played for multiple teams in one season.
- Calculating per-game statistics to standardize player performance metrics.
- Handling missing values through data imputation techniques.
- Merging data from different sources, including awards and player performance.

## Model Development

We developed a predictive model using the Gradient Boosting Classifier. The model underwent rigorous hyperparameter tuning to achieve optimal performance. Key steps in the model development process include:
- Constructing a preprocessing pipeline that scales numeric features using StandardScaler.
- Employing GridSearchCV to tune hyperparameters, including the number of estimators, learning rate, and maximum depth.
- Evaluating different combinations of hyperparameters using 5-fold cross-validation.

## Model Evaluation

The model was evaluated using various techniques:
- Achieved an accuracy of 76% on the test dataset.
- Feature importances were visualized to determine the most influential factors in predicting player outcomes.
- Predicted outcome probabilities were visualized for specific players, enhancing the interpretability of the model.



