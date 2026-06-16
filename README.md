# Client Subscribed to a Term Deposit

A machine learning project that analyzes customer and marketing campaign data to identify the factors influencing a client's decision to subscribe to a term deposit, and builds predictive models to forecast subscription likelihood.

## 📋 Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Key Features & Insights](#key-features--insights)
- [Author](#author)

## 🎯 Project Overview

**Objective:** To analyze customer and marketing campaign data to identify the factors influencing a client's decision to subscribe to a term deposit and build predictive models for subscription prediction.

**Business Context:** This project focuses on the Portuguese banking institution's marketing campaign data. The goal is to understand which customers are more likely to subscribe to term deposits, enabling more targeted and efficient marketing strategies.

**Target Variable:** Whether a client subscribed to a term deposit (binary classification: Yes/No)

## 📊 Dataset

- **Source:** Portuguese Bank Marketing Campaign Data
- **Files:**
  - `bank.csv` - Original dataset (~918 KB)
  - `data.csv` - Processed/extended dataset (~3.1 MB)
- **Key Statistics:**
  - Multiple customer demographic, economic, and campaign-related features
  - Binary classification target variable
  - Mix of numerical and categorical features

## 📁 Project Structure

```
.
├── README.md                          # Project documentation
├── Advance_Bank_Term_Deposit.ipynb    # Main analysis & modeling notebook
├── Prediction.txt                     # Prediction results/summary
├── bank.csv                           # Original dataset
└── data.csv                           # Processed dataset
```

## 🚀 Installation

### Prerequisites
- Python 3.7+
- Jupyter Notebook

### Required Libraries
```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
```

Or install from requirements (if available):
```bash
pip install -r requirements.txt
```

## 💻 Usage

1. **Clone the repository**
   ```bash
   git clone https://github.com/cTANMAY97/Client-subscribed-to-a-term-deposit.git
   cd Client-subscribed-to-a-term-deposit
   ```

2. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook Advance_Bank_Term_Deposit.ipynb
   ```

3. **Run the analysis**
   - Execute all cells to perform data exploration, preprocessing, and model training
   - Review visualizations and model performance metrics

## 🔬 Methodology

The project follows a standard machine learning workflow:

1. **Exploratory Data Analysis (EDA)**
   - Data distribution analysis
   - Feature correlation studies
   - Missing value handling
   - Outlier detection

2. **Data Preprocessing**
   - Feature engineering
   - Categorical encoding
   - Feature scaling/normalization
   - Class balance handling (if needed)

3. **Model Development**
   - Training multiple classification models
   - Hyperparameter tuning
   - Cross-validation

4. **Model Evaluation**
   - Performance metrics (Accuracy, Precision, Recall, F1-Score, AUC-ROC)
   - Confusion matrices
   - Feature importance analysis

## 📈 Results

Results and predictions are documented in `Prediction.txt`. The models identify key patterns in customer behavior and marketing campaign effectiveness.

**Key Performance Indicators:**
- Model accuracy on test set
- Feature importance rankings
- ROC-AUC scores
- Classification metrics

## 🔍 Key Features & Insights

The analysis identifies which factors most influence subscription decisions:
- Customer demographics (age, job, education)
- Economic indicators (balance, loan status)
- Campaign characteristics (contact duration, frequency)
- Temporal factors (day of week, month, season)

See the Jupyter notebook for detailed visualizations and insights.

## 👤 Author

**cTANMAY97** - [GitHub Profile](https://github.com/cTANMAY97)

## 📝 License

This project is open source and available under the MIT License.

---

**Last Updated:** June 2024
