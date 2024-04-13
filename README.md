# Wine_Classification_and_Quality_Prediction_Major_Project
Several machine learning models, including RandomForestClassifier and RandomForestRegressor, were trained and evaluated for both classification and regression tasks, respectively. The performance of each model was assessed using a variety of metrics, such as accuracy, precision, recall, F1-score, mean squared error, RMSE, and R-squared.
Several machine learning models, including RandomForestClassifier and RandomForestRegressor, were trained and evaluated for both classification and regression tasks, respectively. The performance of each model was assessed using a variety of metrics, such as accuracy, precision, recall, F1-score, mean squared error, RMSE, and R-squared.
**Wine Quality Analysis Documentation**

**1. Introduction:**
   - This project aims to predict the quality of wine based on physicochemical attributes. The dataset contains various features such as fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol, which are used to predict the quality of wine represented by a score between 0 and 10.

**2. Data Preprocessing:**
   - The dataset is loaded and analyzed. 
   - Correlation analysis is performed to understand the relationship between different features using a heatmap.
   - A scatter plot is created to visualize the relationship between density, alcohol, and wine quality.
   - Data is split into input features (X) and the target variable (y).
   - Standardization is applied to scale the input features.

**3. Outlier Detection:**
   - Isolation Forest algorithm is utilized to detect outliers in the dataset, which could potentially be excellent or poor quality wines.

**4. Feature Selection:**
   - SelectKBest method with f_regression score function is employed to select the top k features that are most relevant for predicting wine quality.

**5. Model Building and Evaluation (Classification):**
   - RandomForestClassifier is trained on the selected features and evaluated on the test set using accuracy score.
   - Classification report and confusion matrix are generated to analyze the performance of the classification model. Precision, recall, and F1-score metrics are provided for each class to understand the model's predictive capabilities.

**6. Model Building and Evaluation (Regression):**
   - RandomForestRegressor is trained on the selected features and evaluated using mean squared error.
   - An accuracy function is defined to calculate the accuracy of the regression model. Mean squared error and R-squared metrics are provided to assess the model's performance in predicting wine quality scores.

**7. Additional Models:**
   - Linear Regression and another RandomForestRegressor model with different parameters are trained and evaluated. The performance metrics including RMSE and R-squared are provided for each model to compare their predictive accuracy.

**8. Predictive System:**
   - A predictive system is developed to predict the quality of wine based on user input of physicochemical attributes.
   - The model predicts whether the wine quality is good or bad based on the predicted quality score.

**9. Conclusion:**
   - This project illustrates the application of machine learning techniques for wine quality prediction, showcasing the significance of physicochemical attributes in determining wine quality. Through rigorous data preprocessing, including outlier detection and feature selection, we ensured the robustness and relevance of the input data for model training.
   - Several machine learning models, including RandomForestClassifier and RandomForestRegressor, were trained and evaluated for both classification and regression tasks, respectively. The performance of each model was assessed using a variety of metrics, such as accuracy, precision, recall, F1-score, mean squared error, RMSE, and R-squared.
   - The predictive system developed in this project provides a practical tool for users to predict the quality of wine based on their input of physicochemical attributes. This system can be valuable for wine producers, distributors, and enthusiasts in assessing and enhancing wine quality.
   - Moving forward, further exploration can be conducted to improve the predictive accuracy of the models. This may involve exploring advanced machine learning techniques, conducting more extensive feature engineering, and optimizing model parameters. Additionally, the inclusion of domain knowledge and expert insights could enhance the interpretability and effectiveness of the predictive models.
   - Overall, this project contributes to the understanding and utilization of machine learning in the wine industry, facilitating informed decision-making and quality improvement efforts.
