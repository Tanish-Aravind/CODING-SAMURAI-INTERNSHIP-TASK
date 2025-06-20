# CODING-SAMURAI-INTERNSHIP-TASK
Completed machine learning internship tasks (Batch A-45) from Coding Samurai – includes regression, classification, NLP, and deep learning projects.

Task 1 : 🏠 House Price Prediction – Summary
In this project, I built a Linear Regression model to predict house prices using a dataset containing various property features like area, number of bedrooms, availability of a guest room, air conditioning, and more. I began with essential data preprocessing, where I handled binary categorical features (yes/no) using mapping, and applied OneHotEncoding to multi-class categorical variables. After cleaning the data, I used a ColumnTransformer to ensure smooth preprocessing of categorical and numerical data.

To enhance model performance and stabilize variance, I applied a log transformation on the target variable (price) before training the model. Then, I trained a LinearRegression model using train-test split, predicted log-scaled prices, and inverse transformed them back using np.expm1() for meaningful interpretation. The model’s performance was evaluated using Mean Squared Error (MSE) and R² Score, achieving an R² of ~0.66, which indicates a fairly strong linear relationship between features and house price. The results show the model's potential in real-world price prediction scenarios.

Task 2 :
