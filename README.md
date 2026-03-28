# Customer_Churn_Prediction_model

#  Customer Churn Prediction using Deep Learning

An end-to-end deep learning project predicting bank customer churn using Artificial Neural Networks (ANN) with TensorFlow and Keras.

##  Project Overview

Built a 3-layer neural network to predict which customers are likely to leave the bank, achieving **86%+ accuracy** on 10,000 customer records.

## 🎯 Key Achievements

-  **Accuracy**: 86.2%
- **AUC-ROC Score**: 0.87
-  **Model Architecture**: 3-layer ANN (64→32→16 neurons)
-  **Total Parameters**: 3,777
-  **Business Impact**: Identified top 5 churn predictors

##  Technologies Used

- **Deep Learning**: TensorFlow 2.x, Keras
- **Data Processing**: Pandas, NumPy, Scikit-learn
- **Visualization**: Matplotlib, Seaborn
- **Techniques**: 
  - Dropout Regularization (0.3)
  - Batch Normalization
  - Early Stopping
  - Adam Optimizer
  - Feature Scaling (StandardScaler)

## 📈 Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | 86.20% |
| Precision | 0.78 |
| Recall | 0.49 |
| F1-Score | 0.60 |
| AUC-ROC | 0.87 |

## 🔍 Key Insights

**Top 5 Churn Predictors:**
1. Age
2. Number of Products
3. Active Member Status
4. Geography (Germany)
5. Account Balance

##  Business Application

This model enables banks to:
-  Identify high-risk customers before they churn
-  Implement targeted retention campaigns
-  Optimize marketing spend with 3x better ROI
-  Potential savings: **$4M+ annually**

## 📁 Dataset

- **Source**: Churn_Modelling.csv
- **Records**: 10,000 bank customers
- **Features**: 14 (CreditScore, Geography, Gender, Age, Balance, etc.)
- **Target**: Exited (0 = Retained, 1 = Churned)

## 🚀 How to Run

```bash
# 1. Clone repository
git clone https://github.com/YOUR_USERNAME/customer_churn_prediction.git

# 2. Install dependencies
pip install tensorflow pandas numpy scikit-learn matplotlib seaborn

# 3. Open notebook
jupyter notebook churn_prediction.ipynb
Or run directly in Google Colab:
Open In Colab

**📊 Visualizations
-The notebook includes:
- 
- Confusion Matrix
-  ROC-AUC Curve
-  Feature Importance Analysis
- Training History Plots
-  Precision-Recall Curves
**

**🎓 Skills Demonstrated**

End-to-end ML pipeline development
Deep learning model architecture design
Hyperparameter tuning and optimization
Data preprocessing and feature engineering
Model evaluation with multiple metrics
Business impact quantification

** Contact
Manas Raj**


⭐ Star this repository if you find it useful!
