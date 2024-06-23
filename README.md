# Linear Regression Project: Predicting Yearly Amount Spent by E-commerce Customers

## Project Overview
This project involves developing a linear regression model to predict the yearly amount spent by customers of an e-commerce company using various customer metrics. The dataset includes features such as average session length, time spent on the app, time spent on the website, and length of membership.

## Data Description
The dataset contains the following columns:
- **Avg. Session Length**: Average session of in-store style advice sessions.
- **Time on App**: Average time spent on the app in minutes.
- **Time on Website**: Average time spent on the website in minutes.
- **Length of Membership**: How many years the customer has been a member.
- **Yearly Amount Spent**: The target variable, which we aim to predict.

## Steps and Methodologies

### 1. Data Import and Exploration
- Import necessary libraries: pandas, numpy, matplotlib, seaborn.
- Read in the data from a CSV file and display basic information using `head()`, `info()`, and `describe()` methods.
- Visualize the relationships between features using seaborn's `jointplot` and `pairplot`.

### 2. Feature Selection and Data Splitting
- Select numerical features for the model: `Avg. Session Length`, `Time on App`, `Time on Website`, `Length of Membership`.
- Split the data into training and testing sets using `train_test_split` from sklearn.

### 3. Model Training
- Import `LinearRegression` from sklearn and create an instance of the model.
- Train the model on the training data.

### 4. Model Evaluation
- Predict the test set results.
- Create a scatter plot to compare the real test values versus predicted values.
- Calculate evaluation metrics: Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).

### 5. Residual Analysis
- Plot a histogram of the residuals to check for normal distribution.

### 6. Conclusion
- Interpret the model coefficients to determine the importance of each feature.
- Discuss whether to focus on mobile app development, website improvements, or membership duration based on the analysis.

## Files in Repository
- `02-Linear Regression Project.ipynb`: Jupyter notebook containing the complete project code and analysis.
- `Ecommerce Customers`: CSV file containing the dataset.

## How to Run
1. Clone the repository.
2. Ensure you have the necessary libraries installed: pandas, numpy, matplotlib, seaborn, scikit-learn.
3. Open the Jupyter notebook and run the cells sequentially.

## Conclusion
This project demonstrated a strong predictive capability with a clear understanding of feature importance. The analysis suggested that the length of membership had the most significant correlation with the yearly amount spent, offering valuable insights for strategic decision-making in customer relationship management and product development.

## Contact
For any questions or suggestions, feel free to reach out.

---

Happy coding!
