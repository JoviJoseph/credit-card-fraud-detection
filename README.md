# Credit Card Fraud Detection 🚀

## 📌 Project Overview
This project aims to detect fraudulent credit card transactions using machine learning. The dataset consists of anonymized transaction details, and our goal is to build a classification model to distinguish between fraudulent and legitimate transactions.

## 📂 Project Structure
```
credit-card-fraud-detection/
│── data/                  # Dataset files (CSV, JSON, etc.)
│── notebooks/             # Jupyter Notebooks for analysis
│── models/                # Saved ML models
│── src/                   # Python scripts for preprocessing & training
│── README.md              # Project details
│── requirements.txt       # Dependencies
│── fraud_detection.py     # Main script
│── .gitignore             # Ignore unnecessary files
```

## 📊 Dataset
The dataset used for this project contains transaction records with features such as:
- **Time**: Seconds elapsed between transactions
- **Amount**: Transaction amount
- **V1-V28**: Anonymized numerical features
- **Class**: 0 for genuine transactions, 1 for fraudulent transactions

### 🔗 Dataset Source
- [Kaggle Credit Card Fraud Detection Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)

## ⚙️ Installation & Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/JoviJoseph/credit-card-fraud-detection.git
   cd credit-card-fraud-detection
   ```
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🛠️ Steps in Fraud Detection
1. **Data Preprocessing**
   - Handle missing values
   - Scale features using StandardScaler/MinMaxScaler
   - Encode categorical variables if necessary
   
2. **Exploratory Data Analysis (EDA)**
   - Distribution of transactions
   - Fraud vs non-fraud ratio
   - Correlation analysis
   
3. **Handling Class Imbalance**
   - SMOTE (Synthetic Minority Over-sampling Technique)
   - Undersampling majority class
   
4. **Model Training**
   - Logistic Regression
   - Decision Trees
   - Random Forest
   
5. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-Score

## 🚀 Running the Project
To train the model, run:
```bash
python fraud_detection.py
```
To run the Jupyter Notebook, use:
```bash
jupyter notebook
```

## 📈 Results
After training different models, the best model is evaluated based on precision, recall, and F1-score. The final report includes:
- Performance metrics
- Feature importance (if applicable)

## 🤝 Contribution
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## 📝 License
This project is under the MIT License.


