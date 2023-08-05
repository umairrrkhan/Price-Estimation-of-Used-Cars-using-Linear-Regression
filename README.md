# Price Estimation of Used Cars using Linear Regression

## Introduction
This project aims to estimate the price of used cars using the Linear Regression algorithm. Linear Regression is a popular supervised machine learning technique used for predicting continuous target variables, making it suitable for predicting the price of used cars in this case.

## Dataset
The project uses a dataset containing information about various used cars, including features like make, model, year, mileage, fuel type, transmission, etc. The dataset is stored in a CSV file named "cars data.csv."

## Libraries Used
The following Python libraries were used in this project:
- Pandas: Used for data manipulation and analysis.
- Scikit-learn: Used for implementing the Linear Regression model and data preprocessing.
- Plotly Express: Used for creating interactive visualizations.
- Matplotlib and Seaborn: Used for creating static visualizations.

## Methodology
1. Data Preprocessing: The dataset was loaded using Pandas, and any missing or irrelevant data was handled appropriately. Categorical features were encoded, and numerical features were scaled if required.

2. Exploratory Data Analysis (EDA): An exploratory data analysis was performed to gain insights into the dataset. Visualizations were created to understand the distribution of features and their relationship with the target variable (price).

3. Feature Selection: Features were selected based on their correlation with the target variable and their impact on the model's performance.

4. Train-Test Split: The dataset was divided into training and testing sets using the `train_test_split` function from Scikit-learn.

5. Model Training: Two models were trained: Linear Regression and Lasso Regression. Lasso Regression was used to potentially handle any feature selection and regularization.

6. Model Evaluation: The models were evaluated using various metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared score to assess their performance.

7. Visualizations: Plotly Express, Matplotlib, and Seaborn were used to create visualizations of the model predictions and performance metrics.

## How to Run the Code
1. Ensure that Python and the required libraries are installed on your system.

2. Clone the repository containing the project code.

## Results
The project provides insights into the key factors affecting the prices of used cars and offers a price estimation model using Linear Regression and Lasso Regression. The evaluation metrics help assess the model's accuracy and provide an understanding of its performance.

## Conclusion
The Price Estimation of Used Cars using Linear Regression project offers a practical example of implementing a machine learning model for predicting car prices based on historical data. The project can be extended to include other regression algorithms or more advanced techniques to further enhance the model's performance.

Feel free to explore the code, experiment with different algorithms, and contribute to the project's improvement. Happy coding!

## Contact 
- email : umairh1819@gmail.com
