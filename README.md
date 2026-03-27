# 📊 Predicting Purchase Intention in E-Commerce Using Behavioural Features & Representation Learning

## 🚀 Project Overview
This project focuses on predicting **online purchase intention** using session-level behavioural data from e-commerce platforms. The study compares:

- Traditional Machine Learning models  
- Autoencoder-based Representation Learning  
- Hybrid Feature Integration  

The objective is to evaluate **predictive performance, robustness, and calibration reliability**, while translating results into **business decision-making insights**.

---

## 🎯 Objectives

- Analyse behavioural engagement patterns influencing purchase decisions  
- Build and evaluate traditional ML models  
- Implement autoencoder-based latent feature extraction  
- Compare engineered vs latent representations  
- Test hybrid feature integration  
- Evaluate robustness using cross-validation  
- Assess calibration and threshold optimisation  
- Translate predictions into business targeting strategies  

---

## 📂 Dataset

- **Source:** UCI Machine Learning Repository  
- **Dataset:** Online Shoppers Purchasing Intention Dataset  
- **Observations:** 12,330 sessions  
- **Type:** Structured tabular data  

### Key Features:
- PageValues  
- ProductRelated_Duration  
- BounceRates  
- ExitRates  
- VisitorType  
- Month, Weekend  

---

## 🛠️ Tech Stack

- **Programming:** Python  
- **Libraries:**  
  - pandas  
  - numpy  
  - scikit-learn  
  - matplotlib  
  - seaborn  
  - tensorflow / keras  
- **Tools:** Jupyter Notebook  

---

## ⚙️ Project Pipeline

1. **Data Preprocessing**
   - Encoding categorical variables  
   - Feature scaling  
   - Train-test split  

2. **Exploratory Data Analysis**
   - Behavioural pattern analysis  
   - Class imbalance understanding  

3. **Model Development**
   - Logistic Regression  
   - Random Forest  
   - Gradient Boosting  
   - Support Vector Machine  

4. **Representation Learning**
   - Autoencoder for latent feature extraction  

5. **Hybrid Model**
   - Combine engineered + latent features  

6. **Evaluation**
   - ROC-AUC  
   - Precision, Recall, F1-score  
   - Confusion Matrix  
   - Calibration Curve  
   - Brier Score  

7. **Business Interpretation**
   - Cumulative Gain  
   - Lift Analysis  
   - Targeting efficiency  

---

## 📈 Key Results

- **Gradient Boosting achieved highest performance**
  - ROC-AUC ≈ 0.92+
- Engineered features showed strong predictive power  
- Autoencoder captured structural patterns but did not outperform traditional models  
- Hybrid model provided **marginal improvement**  
- Models demonstrated **high stability across multiple seeds**  
- Calibration analysis highlighted importance of probability reliability  

---

## 🔍 Key Insights

- Behavioural engagement intensity is the strongest predictor  
- Traditional ensemble models outperform deep learning in tabular data  
- Representation learning provides **complementary, not superior value**  
- Robust validation is essential for reliable results  
- Ranking-based targeting improves business efficiency  

---

## 📊 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1 Score  
- ROC-AUC  
- Brier Score (Calibration)  

---

## 📁 Project Structure
├── data/
│   └── dataset.csv
├── notebooks/
│   └── analysis.ipynb
├── models/
│   └── trained_models.pkl
├── src/
│   ├── preprocessing.py
│   ├── modeling.py
│   ├── evaluation.py
├── outputs/
│   ├── figures/
│   ├── results/
├── README.md
---

## 🧪 Methodology Highlights

- Multi-seed Stratified 10-Fold Cross Validation  
- Controlled comparison across models  
- Calibration and threshold optimisation  
- Hybrid feature experimentation  

---

## 💼 Business Applications

- Customer targeting  
- Conversion rate optimisation  
- Marketing resource allocation  
- Behaviour-based segmentation  

---

## ⚠️ Limitations

- Static dataset (no real-time data)  
- No sequential behaviour modelling  
- No demographic features  

---

## 🔮 Future Scope

- Sequential modelling (RNN/LSTM)  
- Real-time prediction systems  
- Cost-sensitive learning  
- Personalised recommendation systems  

---

## 👤 Author

**Soumya Roy**  
MSc Data Science & Artificial Intelligence  

---

## 📌 Conclusion

This project demonstrates that **domain-driven feature engineering combined with ensemble learning remains highly effective** in structured datasets, while representation learning adds **interpretive depth rather than significant predictive gain**.
