# Customer Churn Prediction

This project aims to predict customer churn in a telecommunications company using various machine learning techniques.

---

## Dataset

The dataset used is the **Telco Customer Churn** dataset, which contains information about customers who left the company in the last month. It includes:

- Demographic information  
- Subscribed services  
- Contract and billing details

---

## Project Structure

The notebook follows this structure:

### 1. Importing Libraries
- Loads all required libraries for data manipulation, visualization, and machine learning.

### 2. Load & Preview
- Loads the dataset.
- Displays the first few rows and checks data types.

### 3. Data Preprocessing
- Converts relevant columns to numeric types.
- Encodes categorical variables using one-hot encoding.
- Handles missing values in the `TotalCharges` column using median imputation.

### 4. Exploratory Data Analysis (EDA)
- Visualizes the distribution of churn.
- Uses a box plot to analyze the relationship between `MonthlyCharges` and churn.
- Uses a count plot to explore the relationship between `Contract` type and churn.
- Displays a heatmap showing correlations between numerical features.

### 5. Splitting
- Splits the dataset into training and testing sets.

### 6. Feature Scaling
- Applies `StandardScaler` to normalize the feature set.

### 7. Model Training & Evaluation
- Trains a **Logistic Regression** model.
- Evaluates performance using a **confusion matrix** and **classification report**.

---

## Libraries Used

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

