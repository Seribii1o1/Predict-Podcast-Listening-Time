# Predict Podcast Listening Time
 Predict listening time of podcast episodes

**1.Initial Research**

i. Literature Review and Kaggle Notebooks:

[Use sklearn’s neural network to predict on podcast listening times](https://tracyrenee61.medium.com/use-sklearns-neural-network-to-predict-on-podcast-listening-times-410e3ec856a6)

The author opted for a non-linear model called MLPRegressor(a type of neural network) from the scikit-learn library.

[Podcast Trends: Predicting Listening Time|PS5E4](https://www.kaggle.com/code/marianadeem755/podcast-trends-predicting-listening-time-ps5e4)

This participant completed data exploration, categorical encoding, feature engineering, and used an Ensemble approach, combining predictions from both LGBM and CatBoost models.

[Kaggle-Predict-Podcast-Listening-Time](https://github.com/jhould007/Kaggle-Predict-Podcast-Listening-Time/tree/main)

This participant used the H2O AutoML library to build their model.

[Citation](https://kaggle.com/competitions/playground-series-s5e4):

Walter Reade and Elizabeth Park. Predict Podcast Listening Time. https://kaggle.com/competitions/playground-series-s5e4, 2025. Kaggle.

ii. Data selection:

Train.csv for EDA, transform, and model
Test.csv for model prediction
sample_submission.csv as an example for Kaggle submission

iii. Challenges:

Time is an initial challenge since both the Kaggle and class deadlines are approaching.


**2.EDA**

Notebook where I performed univariate, bivariate, and multivariate exploratory analysis on dataset.
I created relevant graphs to help formulate a hypothesis. 

**3.Data Transformation Pipeline**

Some of the columns had a strong correlation and linearity, so I dropped them.
I saved this dataframe as a new csv file to be used in the next step.

**4.Model Generation, Selection, and Hyperparameter Tuning**
Once we’ve explored this pre-processed dataset, we will then create a notebook where we will create train test splits and implement a RandomForestClassifier, GradientBoostingClassifier, and any other model that you believe would be appropriate for this modeling task. Note that we ask you to generate multiple models, not just one.
After training these initial classifiers and viewing their accuracy measures, we will then move forward with hyperparameter tuning via GridSearchCV or RandomizedSearchCV (again, the choice is yours!)
Upon finding optimal hyperparameters, we should re-train our model using these hyperparameters, generate predictions for this new model. Output the respective accuracy scores for each model, and select the one that has the best performance.

