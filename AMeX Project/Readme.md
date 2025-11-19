# AMex-ANN-Project  
American Express Transaction Analysis using Artificial Neural Networks (ANN)

---

# Project Overview
This project performs analytical processing on American Express (AMEX) transaction data and builds an Artificial Neural Network (ANN) model to classify outcomes.  
The workflow includes data preprocessing, feature engineering, model development, and evaluation.

The goal is to understand customer transaction patterns and classify behavior using machine learning.

---

# Repository Contents
├── AMEX.csv # Dataset used for analysis and model training.
├── ANN Working Copy.ipynb # Notebook containing full ANN workflow.
├── README.md # Project documentation.


---

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy  
- TensorFlow / Keras  
- Scikit-learn  
- Matplotlib / Seaborn  
- Jupyter Notebook  

---

# Workflow Overview

# 1. Data Loading**
The dataset is imported and separated into input features (X) and target output (y).

# 2. Data Preprocessing**
Includes:
- Label Encoding for categorical fields  
- One-Hot Encoding for geography-related columns  
- Standard scaling of numerical features  

# 3. Train–Test Split**
The dataset is split into:
- **80% training data**  
- **20% testing data**

# 4. ANN Model Design**
The Artificial Neural Network includes:
- Two hidden layers  
- ReLU activation for hidden units  
- Sigmoid activation for binary output  

# 5. Model Training**
The ANN is trained using:
- **Adam optimizer**  
- **Binary cross-entropy loss**  
- **Accuracy metric**

# 6. Model Evaluation**
Performance is measured using:
- Prediction comparison  
- Confusion Matrix  
- Accuracy score  

# 7. Single & Batch Predictions**
The model predicts:
- Individual sample outcomes  
- All samples in the test dataset  

---

# Key Insights
- Customer transactions show identifiable patterns after preprocessing  
- The ANN model successfully classifies the target variable  
- Categorical encoding and scaling significantly improved model performance  
- The confusion matrix and accuracy score highlight model reliability  

(You can add exact accuracy once obtained.)

---

# How to Use This Project

1. Clone the repository  
2. Open the Jupyter Notebook  
3. Ensure the dataset is correctly placed  
4. Run all notebook cells in order  
5. View training results and evaluation metrics  

# Notes
- Modify the ANN architecture to experiment with better accuracy  
- Ensure proper preprocessing for consistent results  
- The dataset must remain in the same location as referenced in the notebook  


