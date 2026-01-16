<h1 align="center">🌾 Intelligent Crop Recommendation System</h1>

<p align="center">
  <b>Machine Learning–Based Decision Support System for Precision Agriculture</b>
</p>



## 📌 Project Overview
Agriculture is a major contributor to the Indian economy, yet many farmers suffer losses due to improper crop selection based on intuition rather than data.  
This project presents an **Intelligent Crop Recommendation System using Machine Learning** that assists farmers in selecting the most suitable crop based on **soil properties, climatic conditions, geographical location, and economic factors**, thereby improving productivity and reducing financial risk.



## 🎯 Problem Statement
Farmers often choose crops without scientific analysis of soil nutrients, rainfall, temperature, and regional conditions. This leads to low yield, financial losses, and reduced agricultural sustainability.



## ✅ Objectives
- Recommend the most suitable crop based on soil and climatic parameters
- Predict crop sustainability and expected yield
- Perform profit analysis using historical agricultural data
- Reduce crop failure and increase farm productivity
- Support data-driven decision making in agriculture

---

## 🏗️ System Architecture

```
User Input
├── State
├── Month
├── Soil Nutrients (N, P, K)
├── Soil pH
└── Climatic Parameters
│
▼
Data Preprocessing
├── Missing Value Handling
├── Encoding Categorical Data
└── Feature Selection
│
▼
Machine Learning Models
├── Linear Regression
├── Logistic Regression
└── Neural Network
│
▼
Prediction & Analysis
├── Crop Recommendation
├── Crop Sustainability Prediction
└── Profit Analysis
│
▼
Final Output
└── Recommended Crops with Insights
```


## 🧠 Technology Stack
- **Programming Language:** Python, HTML5, CSS3, JavaScript  
- **Libraries:** NumPy, Pandas, Scikit-learn  
- **Machine Learning Models:** Linear Regression, Logistic Regression, Neural Network, Random Forest  
- **Data Sources:** Government of India datasets, Kaggle  
- **Tools:** Jupyter Notebook, Git, GitHub  

## ❓ Which Machine Learning Model Performed Best and Why?

**Which model was selected for the final crop recommendation system?**  
Random Forest (RF) was selected as the final model after evaluating multiple machine learning classifiers.

**How was the best model determined?**  
The cleansed dataset was split into **60% training** and **40% testing** data and evaluated using five classifiers:
- Logistic Regression (with pipeline)
- Support Vector Machine (SVM)
- Decision Tree (DT)
- Random Forest (RF)
- K-Nearest Neighbors (KNN)

Each model was evaluated using **confusion matrices, ROC curves, and accuracy scores**.

**Why was Random Forest chosen over other models?**
- Achieved the **highest accuracy** among all evaluated classifiers
- Handles non-linear relationships between soil, climate, and crop parameters effectively
- Reduces overfitting through ensemble learning
- Performs reliably on structured agricultural datasets

**Outcome:**  
Based on comparative evaluation, **Random Forest consistently outperformed other models** and was therefore selected as the best classifier for crop recommendation.



## ⚙️ Key Features
- Crop recommendation based on soil and climatic factors  
- Crop sustainability prediction using neural networks  
- Profit analysis using historical yield and market prices  
- Modular and scalable ML pipeline  
- High prediction accuracy with low computational cost  



## 🚀 Installation & Execution

git clone https://github.com/Jswnt3/Intelligent-crop-recommended-system.git
```
cd Intelligent-Crop-Recommendation-System
pip install -r requirements.txt
python main.py
