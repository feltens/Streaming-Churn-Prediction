# Streaming Customer Churn Analysis

This project analyzes customer churn behavior for a streaming service using Python. The dataset includes customer demographics, subscription details, and usage patterns to identify factors influencing churn and predict future churn.

This project was developed as part of the **DNC School Data Science Technical Course**, showcasing skills in data analysis, machine learning, and visualization.

---

## 📋 Features of the Project
- **Data Cleaning:** Processed missing values and handled outliers.
- **Exploratory Data Analysis (EDA):** Identified key patterns in customer behavior and subscription types.
- **Feature Importance:** Evaluated the most important variables influencing customer churn.
- **Model Training:** Implemented Logistic Regression and Random Forest for churn prediction.
- **Visualization:** Created impactful graphs to highlight insights using Matplotlib and Seaborn.

---

## 📂 Project Structure

Streaming-Churn-Prediction/
- ├── data/               # Dataset used for the analysis
- ├── notebooks/          # Jupyter Notebook with the entire analysis
- ├── README.md           # Project documentation
- └── requirements.txt    # Python dependencies


---

## 🛠️ Tools and Technologies
- **Languages:** Python (Pandas, NumPy)
- **Visualization:** Matplotlib, Seaborn
- **Machine Learning:** scikit-learn (Logistic Regression, Random Forest)
- **Dataset:** Customer churn data for a streaming service (`churn_data.xlsx`)

---

## 📊 Key Insights
### Feature Importance
The most influential variables in predicting customer churn were:
1. **TotalCharges**
2. **MonthlyCharges**
3. **Tenure**
4. **Contract Type**
5. **Payment Method**

### Model Performance
#### **Random Forest**
- Accuracy: **80.10%**
- **Precision & Recall**:
  - Non-Churn (0): Precision = 83%, Recall = 92%
  - Churn (1): Precision = 68%, Recall = 48%

#### **Logistic Regression**
- Accuracy: **78.54%**
- **Precision & Recall**:
  - Non-Churn (0): Precision = 83%, Recall = 89%
  - Churn (1): Precision = 62%, Recall = 49%

## 🎯 Future Improvements
- Include advanced models like XGBoost or Neural Networks.
- Develop a dashboard for real-time churn tracking.
- Explore customer segmentation for personalized retention strategies.

---

## 🔧 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/feltens/streaming-customer-churn.git

