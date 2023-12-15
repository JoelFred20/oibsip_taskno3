# CAR PRICE PREDICTION WITH MACHINE LEARNING

# Introduction
This GitHub repository contains a Jupyter notebook that demonstrates the process of predicting car prices using a Random Forest Regressor. The dataset used in this analysis includes information about various cars, including features such as the year of manufacture, present price, driven kilometers, fuel type, selling type, transmission, and owner details.

# Contents
1. Import Libraries:
Essential Python libraries such as Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn are imported to facilitate data manipulation, visualization, and machine learning tasks.
2. Load and Explore the Dataset:
The car dataset is loaded into a Pandas DataFrame, and basic information about the dataset is displayed, including data types and the first few rows.
3. Data Cleaning and Preprocessing:
Missing values are checked and handled if necessary.
Feature engineering is performed by creating a new feature 'Age' based on the 'Year' column.
Categorical columns are converted to numerical using one-hot encoding.
4. Split Data:
The dataset is split into training and testing sets using scikit-learn's train_test_split function.
5. Model Selection and Hyperparameter Tuning (Random Forest):
A Random Forest Regressor is selected for predicting car prices.
Hyperparameter tuning is performed using GridSearchCV to find the best combination of hyperparameters.
6. Evaluate the Model:
The performance of the Random Forest model is evaluated using mean squared error and R-squared.
7. Feature Importance:
The importance of each feature in predicting car prices is visualized using a bar plot.
8. Data Visualization:
The actual vs. predicted selling prices are visualized to assess how well the model predictions align with the actual prices.

# How to Use
Clone the repository: git clone https://github.com/JoelFred20/oibsip_taskno3.git

Open the Jupyter notebook in your preferred environment.

Run each cell sequentially to observe the step-by-step analysis and predictions.


Feel free to modify the code, experiment with different models, or customize the analysis based on your specific interests or dataset.
