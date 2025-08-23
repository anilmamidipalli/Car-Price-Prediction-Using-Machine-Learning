# Car-Price-Prediction-Using-Machine-Learning
This project develops a machine learning model to predict car prices using features like brand, model, fuel type, and more. By applying supervised learning to historical data, it identifies patterns to estimate prices for new cars. This helps reduce negotiation inefficiencies, improve pricing accuracy, and enhance market transparency.

The proposed solution aims to develop a machine learning-based car price prediction model using supervised learning techniques. The model will be trained on a structured dataset of car listings, with the goal of accurately estimating car prices based on various vehicle attributes. The solution focuses on the following machine learning stages:
# 1.	Data Preprocessing 
The dataset undergoes preprocessing to prepare it for machine learning. This includes:
•	Handling missing or inconsistent values
•	Encoding categorical variables (e.g., fuel type, transmission, condition)
•	Normalizing or scaling numerical features (e.g., mileage, engine size)
•	Removing irrelevant or redundant features
# 2.	Exploratory Data Analysis (EDA)
EDA is performed to understand the structure, patterns, and relationships within the dataset. This step includes:
•	Analysing the distribution of the target variable (car prices)
•	Identifying outliers and anomalies in features like mileage, price, or engine size
•	Studying correlations between numerical features and the target variable
•	Visualizing relationships using plots such as histograms, boxplots, scatterplots, and heatmaps
•	Examining the impact of categorical features (e.g., fuel type, transmission, brand) on car prices
•	Detecting feature importance and potential data imbalances
# 3.	Feature Selection and Engineering
Important features influencing car prices are selected using correlation analysis and domain knowledge. Additional relevant features may be engineered, such as vehicle age or price per kilo meter, to improve model performance.
# 4.	Model Training
Multiple supervised learning algorithms are implemented and trained on the pre-processed dataset. These include:
•	Linear Regression
•	Lasso Regression
•	Decision Tree Regressor
•	Random Forest Regressor
•	Gradient Boosting Regressor
•	XGBoost Regressor
•	K-Nearest Neighbour (KNN) Regressor
Each model learns patterns and relationships between input features and the target variable (car price).
# 5.	Model Evaluation 
The trained models are evaluated using standard regression metrics such as:
•	Mean Absolute Error (MAE)
•	Mean Squared Error (MSE)
•	Root Mean Squared Error (RMSE)
•	R-squared (R²)
•	F1 Score
# 6.	Model Selection and Optimization
The best-performing model is selected based on evaluation results. Hyperparameter tuning (using Grid Search or Random Search) is applied to further optimize its performance and reduce errors.


# Result:
##### Based On MAE,MSE,RMSE,R-Squared----> Random Forest Regressor (With Out Parameter)
##### Based On F1 Score----->Decision Tree
##### Based On MAE,MSE,RMSE,R-Squared---->XGBoost(With Parameter)

# Conclusion
The car price prediction project successfully demonstrated the use of supervised machine learning techniques to estimate car prices based on key attributes such as brand, model, fuel type, and mileage. After thorough data preprocessing, EDA, feature selection, and model training, multiple algorithms were evaluated using standard regression metrics.
Random Forest Regressor (without parameter tuning) and XGBoost (with tuned parameters) provided the most reliable performance based on MAE, MSE, RMSE, and R², indicating strong predictive capability. Decision Tree showed competitive results based on the F1 Score but with relatively less stability compared to ensemble models.
This project highlights the importance of proper data preprocessing, feature engineering, and model selection for building accurate predictive models. Such a system can enhance market transparency, help buyers and sellers negotiate fairly, and provide more accurate pricing insights for the automotive industry.
