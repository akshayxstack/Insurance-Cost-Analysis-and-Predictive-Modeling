# Insurance Cost Analysis and Predictive Modeling

## 📌 Project Overview

This project analyzes insurance data and predicts insurance charges using machine learning regression algorithms. It includes data cleaning, exploratory data analysis (EDA), feature encoding, model training, and performance evaluation to identify the best-performing predictive model.

## 🎯 Objectives

* Analyze insurance data to identify patterns and trends.
* Handle missing values and remove duplicate records.
* Detect and remove outliers using the Interquartile Range (IQR) method.
* Convert categorical variables using one-hot encoding.
* Train and evaluate five regression models.
* Compare model performance and identify the best-fit model.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## 🤖 Machine Learning Models

1. Linear Regression
2. K-Nearest Neighbors (KNN) Regression
3. Decision Tree Regression
4. Random Forest Regression
5. Support Vector Regression (SVR)

## 📊 Model Evaluation

The models are evaluated using the following metrics:

* **R² Score** — Measures how well the model explains variations in insurance charges.
* **Mean Absolute Error (MAE)** — Measures the average absolute prediction error.
* **Mean Squared Error (MSE)** — Measures the average squared prediction error.
* **Root Mean Squared Error (RMSE)** — Measures prediction error in the target variable's units.

## 🏆 Best Performing Model

The Random Forest Regression model achieved an **R² score of 0.9746** in the current evaluation, making it the best-performing model among the five models tested.

## 📈 Visualizations

The project includes:

* Boxplots for outlier detection.
* Regression plots comparing actual and predicted insurance charges.
* Scatter plots for model predictions.
* A bar chart comparing the R² scores of all five models.

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone <your-repository-url>
```

### 2. Install Dependencies

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

### 3. Add the Dataset

Place `new_insurance_data.csv` in the project directory and update the dataset path in the Python script if necessary.

### 4. Run the Script

Run the Python file using Spyder, VS Code, or another Python IDE.

## 📂 Dataset

The project uses `new_insurance_data.csv`, containing insurance-related information used to analyze and predict insurance charges.

## 🔮 Future Enhancements

* Perform hyperparameter tuning to improve model performance.
* Use cross-validation for more reliable model evaluation.
* Develop an interactive dashboard for insurance data analysis.
* Deploy the trained model as a web application.

## 👨‍💻 Author

**Chintha Dora Sri Akshay**
