# 🌊 Water Quality Analysis

## 📌 Overview
This project analyzes water quality data and predicts whether water is **safe** or **unsafe** for consumption.  
Machine Learning models such as **Logistic Regression** and **Random Forest** are applied to classify water samples based on chemical parameters.

---

## 🎯 Problem Statement
Water pollution is a critical issue affecting millions worldwide.  
By predicting water safety using chemical indicators, this project supports **early detection** of unsafe water and helps in **environmental monitoring**.

---

## 📊 Dataset
- **Features:** pH, BOD, COD, DO, and other chemical parameters  
- **Target Variable:** Safe (0) vs Unsafe (1)  
- **Threshold Example:** BOD > 3 mg/l → Unsafe water  

---

## 🧹 Methodology
1. **Data Cleaning**  
   - Handling missing values  
   - Defining target variable (safe vs unsafe)  
   - Preparing dataset for modeling  

2. **Exploratory Data Analysis (EDA)**  
   - Feature distributions  
   - Correlation checks  
   - Outlier detection  

3. **Model Training**  
   - Logistic Regression  
   - Random Forest  

4. **Model Evaluation**  
   - Accuracy comparison  
   - Predictions exported (`submission.csv`)  

---

## 📈 Results
| Model               | Accuracy |
|---------------------|----------|
| Logistic Regression | ~86%     |
| Random Forest       | 100%*    |

> ⚠️ *Note: Random Forest shows perfect accuracy, which may indicate overfitting.*

---

## 🚀 How to Run (Colab)
1. Open the notebook in **Google Colab**.  
2. Upload or mount the dataset (from Drive/GitHub).  
3. Run all cells in order.  
4. Outputs (predictions, plots) will be generated automatically.  

---

## 🔮 Future Work
- Add more robust data cleaning and feature engineering  
- Include advanced evaluation metrics (Precision, Recall, F1, ROC-AUC)  
- Deploy as a Flask/Django API for real-time predictions  
- Integrate IoT sensor data for live monitoring  

---

## 🏆 Hackathon Note
It demonstrates the **end-to-end ML pipeline**: data cleaning, visualization, model training, and evaluation.

## Deliverables
- Notebook (`Water_Quality_Analysis_Final.ipynb`)
- Dataset (`water_dataX.csv`)
- Predictions (`submission.csv`)

## How to Run
1. Open the notebook in Google Colab give in the file named as: Colab_Link.
2. Click **Run all**.
3. All required files are included — no extra steps needed.
