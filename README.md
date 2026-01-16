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



## ❓ Why SQL Instead of NoSQL?
SQL was chosen because:
- Agricultural datasets are **highly structured**
- Strong data consistency is required for analytics
- Supports relational queries for yield and profit analysis
- Easier maintenance and reporting for structured data



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
