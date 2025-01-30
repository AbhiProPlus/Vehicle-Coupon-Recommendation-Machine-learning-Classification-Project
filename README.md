In-Vehicle Coupon Recommendation

Project Overview
This project focuses on building a machine learning model to predict whether a person will accept a coupon while driving in various scenarios. The model uses features related to the driver's behavior and environment to classify coupon acceptance or rejection.

Dataset
The dataset contains 12,684 instances and 25 features (categorical, integer, binary). The target column is coupon_response, which indicates whether the person accepts the coupon.

Dataset available at: https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation

Steps
Data Preprocessing:

Handle missing values in the dataset.
Encode categorical features into numerical values and drop original categorical columns after encoding.
Scale or normalize numerical features as needed.

Modeling:
Train a classification model to predict coupon acceptance.
Evaluate model performance using accuracy and other classification metrics.

Prediction on Unseen Data:
Used the trained model to predict coupon acceptance for unseen data.
Made predictions using the model on new inputs in the same feature format.
