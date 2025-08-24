# Telco-Customer-Churn
This project predicts which customers are likely to churn (leave) a telecom company using machine learning. 
The goal is to help the company retain customers by identifying high-risk users.

## Technologies Used
- Python
- Pandas, NumPy
- scikit-learn (Logistic Regression)
- Matplotlib / Seaborn (for visualizations)
- Git & GitHub

## Dataset
- `telco_churn.csv` contains customer information and whether they churned.
- Features include demographics, service usage, billing info, and contracts.
## Steps
1. Data Cleaning: Handle missing values and encode categorical variables.
2. Exploratory Data Analysis: Understand patterns in customer churn.
3. Feature Engineering: Create new features and scale data.
4. Model Building: Train Logistic Regression and evaluate accuracy.
5. Feature Importance: Identify key factors influencing churn.
## Results
- Accuracy: ~78%
- Key features affecting churn: tenure, monthly charges, contract type
- Confusion matrix and classification report included in notebook

## How to Run
1. Clone this repo: `git clone https://github.com/Shirincode-dot/Telco-Customer-Churn.git`
2. Open `TelcoChurn.ipynb` in Jupyter Notebook.
3. Run all cells step by step.

