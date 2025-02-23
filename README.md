# Big Data Analytics in Banking: Risk Management & Fraud Detection

## 📌 Project Overview
This project analyzes the impact of **Big Data Analytics (BDA)** on decision-making processes for **risk management** and **fraud detection** in the banking industry. Using machine learning models on a dataset of credit card transactions, we identify fraud patterns and evaluate the effectiveness of different classification models.

## 📂 Project Structure
```
├── README.md          # Project documentation
├── data/              # Dataset (not included due to size, provide link)
├── notebooks/         # Jupyter Notebooks for analysis & modeling
│   ├── 01_data_analysis.ipynb
│   ├── 02_model_training.ipynb
│   ├── 03_model_evaluation.ipynb
├── images/            # Visualizations (plots, confusion matrices, etc.)
├── requirements.txt   # Required Python libraries
```

## 📊 Dataset
- **Source:** Kaggle - [VISA Credit Card Transactions Dataset](https://www.kaggle.com/)  
- **Features:** Transaction time, amount, transaction type (POS, ATM, Online), cardholder demographics, fraud label.
- **Objective:** Identify fraudulent transactions using data analytics.

## 🛠 Technologies Used
- **Programming Language:** Python 🐍
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Machine Learning Models:** Logistic Regression, Decision Tree, Random Forest

## 🏆 Key Findings
- Fraud transactions account for **0.078%** of all transactions.
- **Online transactions** had the highest fraud rate (**44.3%**).
- **Random Forest** achieved the highest accuracy (**99%**) in fraud detection.
- Fraudulent transactions were **higher among younger individuals**.

## 🔍 Model Comparison
| Model              | Accuracy | Precision | Recall | F1-Score |
|-------------------|----------|----------|-------|----------|
| Logistic Regression | 96%      | 0.95     | 0.96  | 0.95     |
| Decision Tree      | 98%      | 0.98     | 0.98  | 0.98     |
| Random Forest     | 99%      | 0.99     | 0.99  | 0.98     |

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/Lavanya-chintha/Big-data-analytics-in-banking]
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebooks:
   ```bash
   jupyter notebook
   ```

## 📌 Future Improvements
- Implement **deep learning models** (e.g., Neural Networks) for fraud detection.
- Optimize feature engineering to improve fraud classification accuracy.
- Integrate real-time fraud detection alerts.

---
📌 **Author:** [Sai Lavanya Chintha]  
📌 **GitHub Repository:** [https://github.com/Lavanya-chintha/Big-data-analytics-in-banking]  
📌 **License:** MIT  
