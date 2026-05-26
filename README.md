# Customer Churn Prediction Using Machine Learning

## Project Overview

Customer Churn Prediction is a Machine Learning project developed to analyze customer behavior and predict whether a customer is likely to leave a company’s service. Businesses such as telecom companies, banks, and subscription platforms use churn prediction systems to improve customer retention and reduce financial loss.

This project uses customer data like contract type, monthly charges, tenure, internet services, and payment methods to identify churn patterns. The system preprocesses the dataset, trains a Machine Learning model, and predicts customer churn with good accuracy.

The project is implemented using Python in Visual Studio Code and includes data visualization techniques for better understanding of customer trends.

---

## Objectives

- Analyze customer behavior patterns
- Identify important churn factors
- Predict customer churn using Machine Learning
- Improve customer retention strategies
- Visualize customer data using graphs and charts

---

## Technologies Used

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| VS Code | Development Environment |
| Pandas | Data Processing |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| Streamlit | Web Dashboard |

---

## Machine Learning Algorithm

The project uses the **Random Forest Classifier** algorithm for customer churn prediction.

### Why Random Forest?

- High prediction accuracy
- Handles large datasets efficiently
- Reduces overfitting
- Works well with categorical and numerical data

---

## Dataset Information

Dataset Name:
IBM Telco Customer Churn Dataset

Dataset Features:

- Customer demographics
- Internet services
- Monthly charges
- Contract type
- Payment method
- Tenure
- Churn status

Target Column:
`Churn`

---

## Project Workflow

### Step 1: Data Collection
The customer churn dataset is collected from Kaggle.

### Step 2: Data Preprocessing
- Remove unnecessary columns
- Handle missing values
- Convert categorical values into numerical values

### Step 3: Data Visualization
Graphs and heatmaps are used to understand customer behavior and churn patterns.

### Step 4: Model Training
The Random Forest model is trained using training data.

### Step 5: Prediction
The model predicts whether a customer will churn or not.

### Step 6: Performance Evaluation
Accuracy score and classification report are generated.

---

## Features of the Project

- Customer churn prediction
- Data cleaning and preprocessing
- Data visualization
- Heatmap analysis
- Classification report generation
- Streamlit dashboard
- Easy-to-use interface

---

## Installation Steps

### 1. Install Python

Download Python from:
https://www.python.org

### 2. Install Visual Studio Code

Download VS Code from:
https://code.visualstudio.com

### 3. Install Required Libraries

Open terminal and run:

```bash
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install scikit-learn
pip install streamlit
```

If pip is not recognized:

```bash
python -m pip install pandas numpy matplotlib seaborn scikit-learn streamlit
```

---

## Project Structure

```text
Customer_Churn_Project/
│
├── churn.csv
├── churn_analysis.py
├── app.py
├── README.md
└── requirements.txt
```

---

## Running the Project

### Run the Python Program

```bash
python churn_analysis.py
```

### Run Streamlit Dashboard

```bash
streamlit run app.py
```

---

## Output

The project generates:

- Customer churn prediction
- Accuracy score
- Classification report
- Churn visualization graph
- Correlation heatmap
- Interactive dashboard

---

## Advantages

- Helps reduce customer loss
- Improves customer retention
- Supports business decision-making
- Detects high-risk customers
- Provides data-driven insights

---

## Applications

- Telecom Industry
- Banking Sector
- E-commerce Platforms
- Subscription Services
- Customer Relationship Management

---

## Future Enhancements

- Deep Learning integration
- Real-time churn prediction
- Power BI dashboard
- Cloud deployment
- AI-based recommendation system

---

## Conclusion

This project demonstrates how Machine Learning can be used to analyze customer behavior and predict churn effectively. By identifying customers who are likely to leave, companies can improve customer satisfaction and develop better retention strategies.

---

## Author

Sabari S

---

## License

This project is developed for educational and learning purposes.
