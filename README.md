# Bank Marketing Classification

## Project Overview
This project aims to predict whether a customer will subscribe to a term deposit based on bank marketing campaign data using Machine Learning.

## Dataset
- Dataset: Bank Marketing Dataset
- Source: Kaggle
- Records: 11,162
- Original Features: 16 input features and 1 target column
- Target Variable: `deposit`
- Classes: Yes / No

## Project Workflow

### 1. Data Exploration
- Dataset inspection
- Statistical analysis
- Missing values and duplicate checks
- Target distribution analysis

### 2. Exploratory Data Analysis (EDA)
- Target distribution visualization
- Numerical feature distributions
- Correlation matrix
- Categorical features analysis
- Outlier visualization using boxplots

### 3. Data Preprocessing
- Removed the `duration` feature
- Applied One-Hot Encoding to categorical variables
- Encoded the target variable:
  - No = 0
  - Yes = 1
- Applied an 80/20 Train-Test Split
- Used StandardScaler for feature scaling

### 4. Machine Learning Model
**Logistic Regression**

The model was trained to predict whether a customer would subscribe to a term deposit.

## Model Evaluation

| Metric | Score |
|---|---:|
| Accuracy | 69.50% |
| Precision | 73.24% |
| Recall | 56.14% |
| F1 Score | 63.56% |

## Technologies & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Project Structure

```text
bank-marketing-classification/
│
├── bank_marketing_classification.ipynb
├── README.md
└── requirements.txt
```

## How to Run
1. Open the notebook using Google Colab.
2. Install the required libraries.
3. Load the Bank Marketing dataset.
4. Run the notebook cells sequentially.

## Author
Mahmoud Elmowafy
