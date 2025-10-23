# 🚗 Traffic Satisfaction Analysis and Prediction

## 📘 Overview
This project analyzes transport satisfaction data using Python and machine learning techniques.  
It explores demographic and travel-related factors affecting passenger satisfaction through visualization and exploratory data analysis (EDA).  
Classification models such as **Decision Tree**, **Random Forest**, and **Logistic Regression** are implemented to predict overall satisfaction levels.

---

## 🎯 Objectives
- Understand the key factors influencing passenger satisfaction.  
- Analyze demographic and travel-related variables using EDA and visualization.  
- Build and compare machine learning models for satisfaction prediction.  
- Provide data-driven insights to improve travel experience.

---

## 🧩 Dataset
- **Name:** `dummy_transport_satisfaction.csv` (sample dataset)  
- **Features Include:**  
  - `Gender`, `Age`, `Travel Class`, `Seat Comfort`, `Food`, `Distance Travelled`, and `Satisfaction`.  
- **Target Variable:** `Satisfaction` (Satisfied / Dissatisfied)

---

## ⚙️ Technologies Used
- **Programming Language:** Python  
- **Libraries & Tools:**  
  - `Pandas`, `NumPy`, `Matplotlib`, `Seaborn` — Data handling & visualization  
  - `Scikit-learn` — Machine learning models and evaluation  
  - `Joblib` — Model saving and loading  

---

## 🔍 Exploratory Data Analysis (EDA)
- Data cleaning and inspection  
- Gender and age distribution analysis  
- Relationship between travel class and comfort levels  
- Correlation of service quality factors with satisfaction  

---

## 🤖 Machine Learning Models
Implemented and compared multiple classifiers:  
- Decision Tree Classifier  
- Random Forest Classifier  
- K-Nearest Neighbors (KNN)  
- Logistic Regression  

**Evaluation Metrics:**  
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- ROC-AUC Score  

---

## 📈 Results
- Random Forest showed the highest overall accuracy in satisfaction prediction.  
- Key influencing factors include **Seat Comfort**, **Travel Class**, and **Onboard Service Quality**.  

---

## 🧠 Insights
- Younger passengers tend to give more varied ratings compared to older ones.  
- Higher travel class generally correlates with greater satisfaction.  
- Food quality and comfort strongly influence overall experience.  

---

## 🚀 How to Run the Project
1. Clone this repository  
   ```bash
   git clone https://github.com/YOUR-USERNAME/Traffic_Satisfaction_Analysis.git
   cd Traffic_Satisfaction_Analysis
   ```
2. Install required libraries  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook  
   ```bash
   jupyter notebook Traffic_analysis.ipynb
   ```
4. (Optional) Save the trained model  
   ```python
   joblib.dump(model, 'satisfaction_model.pkl')
   ```

---

## 📂 Repository Structure
```
Traffic_Satisfaction_Analysis/
│
├── Traffic_analysis.ipynb        # Main notebook
├── dummy_transport_satisfaction.csv  # Dataset
├── requirements.txt              # Dependencies
└── README.md                     # Project documentation
```

---

## 🏁 Conclusion
This project provides valuable insights into the factors affecting passenger satisfaction in transportation systems.  
By leveraging data analytics and machine learning, it enables data-driven decisions to enhance customer experience and operational efficiency.
