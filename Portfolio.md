Project Background - Pandemics are large scale outbreaks of diseases/illness that can shake the world in the aspect of health, economic and societies. This kind of pandemics can affect substantial amount of the population. So to tackle this, we are trying to understand which countries' response of this pandemic is good, which countries need to improve on their publlic health respose and awareness.

Business Objective - Analyse time series data to monitor patterns (recovery/death rate) on  COVID-19 in each country to understand the health response.

Work Accomplished - Data attained from the atleast 188 countries dataset on the Covid 19 (Active, Recovered and Death Rates). Data Cleaning done to remove any duplicate, missing values and irelevant data.
Data Transformation was done by converting data into suitable format for analysis eg. normalizing the dates to similar format and placing data in the correct categorical variables.
Data Splitting was done so as to validate the training set and test sets to ensure model's performance is done accurately to prevent overfitting. Model used for this data model is time series forecasting (LSTM).
I have tried to train the model using epoch = 20 to see what are my losses and my prediction rate so that fine tuning can be done to get a prediction of higher accuracy value. I also tried to cross validate to tune my hyperparameters to improve the model.
I also evaluated using relevant performance such as accuracy, mean squared error.

Recommendation and Analysis - The LSTM model showed low loss values during training but the prediction did not the match the expectation as the model might need to be fine tuned so as to get a better outcome. I was not able to create a another model as i kept getting error on the outcome which made my analysis incomplete. I will definitely fine tune and train another model to get a better outcome on dataset.
In overall, this model and predictions can be used for early warning systems and scenario analysis to guide interventions. he use of the LSTM model for COVID-19 recovery case forecasting and improve public health responses to future pandemics is highly useful if trained correctly.
This model can be used to predict future pandemic and prepare to ensure high recovery and low death stats.

AI Ethics - I ensure that the dataset is representative of diverse populations to avoid biasness. This dataset I extracted contained no data of any individual which violates thir privacy. I will be able to explain and create documentation of any of my preprocessing steps.
