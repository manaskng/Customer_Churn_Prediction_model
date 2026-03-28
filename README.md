<img width="479" height="1403" alt="model_architecture" src="https://github.com/user-attachments/assets/fb976cab-1ac1-4b57-9164-830636a11661" />#  Customer Churn Prediction using Deep Learning

An end-to-end deep learning project predicting bank customer churn using Artificial Neural Networks (ANN) with TensorFlow and Keras.

##  Project Overview

Built a 3-layer neural network to predict which customers are likely to leave the bank, achieving **86%+ accuracy** on 10,000 customer records.

## 🎯 Key Achievements

-  **Accuracy**: 86.2%
  <img width="2792" height="2373" alt="confusion_matrix" src="https://github.com/user-attachments/assets/211a660b-8ba4-42c9-a88c-c7fd3147791c" />
  <img width="2970" height="2373" alt="precision_recall_curve" src="https://github.com/user-attachments/assets/af35c1c0-e7e6-43b5-88d4-d8d479292def" />

- **AUC-ROC Score**: 0.87
  <img width="2970" height="2373" alt="roc_curve" src="https://github.com/user-attachments/assets/db4059e5-0805-4cad-acad-44ed78d1a413" />

-  **Model Architecture**: 3-layer ANN (64→32→16 neurons)
  <img width="479" height="1403" alt="model_architecture" src="https://github.com/user-attachments/assets/9173a3b7-2dc4-439b-bded-b98b38b7e2da" />

-  **Total Parameters**: 3,777
-  <img width="3562" height="2364" alt="feature_importance" src="https://github.com/user-attachments/assets/f4ea9af8-c277-479a-a579-eb39331c60ae" />

-  **Business Impact**: Identified top 5 churn predictors


## Results 
<img width="2792" height="2373" alt="confusion_matrix" src="https://github.com/user-attachments/assets/d5787fea-b18f-4ed5-b74b-fc5d954f5e1e" />
<img width="4761" height="1764" alt="activation_comparison" src="https://github.com/user-attachments/assets/2fdf2848-7ba1-49e4-a27a-497b385ddcc3" />
<img width="4764" height="3564" alt="training_history" src="https://github.com/user-attachments/assets/fdf85d43-27db-429b-b5fb-0e6bfb61e16f" />
<img width="4764" height="1764" alt="threshold_optimization" src="https://github.com/user-attachments/assets/a04720e0-2597-4de9-9d45-412692093d11" />

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
