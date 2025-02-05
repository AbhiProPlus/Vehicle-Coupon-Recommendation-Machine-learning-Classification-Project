## **In-Vehicle Coupon Recommendation System**

## **Overview**
This project focuses on developing a machine learning model to predict whether a person will accept a coupon during a drive based on various factors, such as weather conditions, time of day, passenger type, and more. The goal is to predict coupon acceptance in different driving scenarios, helping businesses offer personalized promotions.


## **Dataset Details**

Link : https://archive.ics.uci.edu/dataset/603/in+vehicle+coupon+recommendation

Dataset Name: In-Vehicle Coupon Dataset
Instances (Rows): 12,684
Features (Columns): 26 (includes both categorical and numerical features)
Target Variable: coupon_response (Values: 0 for not accepted, 1 for accepted)

## Key Steps in the Project

1. **Data Preprocessing**:
   - Handling missing values
   - Encoding categorical variables (One-Hot and Binary Encoding)
   - Dropping irrelevant columns (e.g., `occupation`)

2. **Feature Engineering**:
   - Skewness correction using transformations
   - Feature selection based on correlation and importance

3. **Modeling**:
   - Training models (e.g., Random Forest, Gradient Boosting)
   - Hyperparameter tuning using GridSearchCV
   - Model evaluation using accuracy, ROC AUC, and confusion matrix

4. **Pipeline**:
   - Model creation with a pipeline for streamlined training and testing
   - Saving and loading the trained model for future predictions

5. **Prediction on Unseen Data**:
   - Encoding unseen data the same way as the training data
   - Generating predictions for new data

## Data

The dataset includes various features related to the driving scenario, such as:
- `destination`: The destination of the driver (e.g., Home, Work)
- `passenger`: The type of passengers (e.g., Alone, Friend)
- `weather`: Weather condition during the drive (e.g., Sunny, Snowy)
- `coupon`: Type of coupon being offered
- `maritalStatus`: Marital status of the driver
- `education`: Education level of the driver
- `age`, `income`, etc.

The target variable is `coupon_response`, where:
- 1 indicates the coupon was accepted
- 0 indicates the coupon was rejected

## Model Evaluation

The performance of the model is evaluated using various metrics:
- **Accuracy**: The percentage of correct predictions
- **ROC AUC**: Area Under the Receiver Operating Characteristic Curve
- **Confusion Matrix**: To visualize the classification results


 Acknowledgments
The dataset used in this project is publicly available and can be used to predict coupon acceptance behavior.
Thanks to various tutorials and resources that helped in building this project.

## Contributions

Feel free to fork the repository and submit pull requests! Any feedback is appreciated.


## Contact
For any queries, please contact via GitHub or email.
