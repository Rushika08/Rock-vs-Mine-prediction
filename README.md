# Rock-vs-Mine-prediction
A system in Python that can predict whether an object is either Rock or Mine with SONAR Data. For this use case, the Logistic Regression Model is used for prediction.

The logistic Regression Model is a statistical method used for binary classification problems, where the goal is to predict the probability of an instance belonging to a particular class.



1. Data Collection and Processing:

  - Loaded the sonar dataset into a Pandas DataFrame.
  - Checked the first few rows, the shape, and statistical measures of the data.
  - Checked the distribution of rock (R) and mine (M) classes.
  - Grouped the data based on whether they are rocks or mines.

2. Data Separation:

  - Separated the features (X) and labels (Y) from the dataset.

3. Training and Test Data Split:

  - Split the data into training and testing sets using train_test_split.

4. Model Training (Logistic Regression):

  - Created a Logistic Regression model.
  - Trained the model using the training data.

5. Model Evaluation:

  - Checked the accuracy of the model on both the training and test datasets.

6. Making Predictions:

  - Provided an example of making predictions on new data (a single instance).
  - Reshaped the input data and used the trained model to predict whether it's a rock or mine.
  - Displayed the result as "Rock" or "Mine" based on the prediction.
