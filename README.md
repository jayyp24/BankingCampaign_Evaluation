# Bank Marketing Analysis


Overview
This project aims to analyze the effectiveness of a bank's marketing campaign for term deposit subscriptions. By employing logistic regression, the goal is to predict whether clients will subscribe to a term deposit based on various factors such as call duration, interest rate, credit score, month of contact, and previous marketing interactions.

Dataset

Training Data

The training dataset (raw_data.csv) comprises the following columns:

Duration: Duration of the call (in minutes).

Interest Rate: Interest rate during the call.

Credit: Client's credit score.

March: Binary indicator (0 or 1) for calls made in March.

Previous: Number of previous marketing interactions.

Outcome (y): Target variable indicating whether the client subscribed to a term deposit (0: No, 1: Yes).


Testing Data

The testing dataset (Bank-data-testing.csv) mirrors the structure of the training data and serves as a means to assess the model's performance.

Data Preprocessing

Removed the 'Unnamed: 0' column.
Transformed the 'y' column into binary format (0 for 'no', 1 for 'yes').

Model Building

Logistic Regression

Single Variable Analysis: Constructed a logistic regression model utilizing solely the 'duration' variable.

Multiple Variable Analysis: Expanded the model to encompass additional predictors such as interest rate, credit score, month of contact, and previous interactions.

Model Evaluation

Utilized confusion matrix to evaluate the model's performance.

Tested the model on the testing dataset and compared the results with the training data performance.
