# Intelligent Classification of Rural Infrastructure Projects 🚧🤖

This project leverages machine learning and AutoAI to classify PMGSY (Pradhan Mantri Gram Sadak Yojana) road and bridge infrastructure projects into their respective schemes (PMGSY-I, PMGSY-II, RCPLWEA, etc.) using physical and financial attributes. It aims to replace error-prone manual categorization with a scalable, accurate, and automated classification system.

---

## 📌 Problem Statement

Government rural infrastructure projects are manually categorized into schemes based on location, cost, completion status, and more. This process is slow, inconsistent, and not scalable. The goal is to automate this classification to improve speed, accuracy, and decision-making.

---

## ✅ Proposed Solution

Using machine learning classification models (KNN, XGBoost, Random Forest), we built a robust system that:
- Classifies projects into schemes with over **91% accuracy**
- Uses structured tabular data from the **AI Kosh PMGSY dataset**
- Applies **AutoAI pipelines** for model training, tuning, and deployment
- Supports real-time predictions for new/unseen projects

---

## ⚙️ Tech Stack

- **Platform**: IBM Watson Studio (AutoAI)
- **Language**: Python
- **Libraries**:  
  - `pandas`, `numpy` for data preprocessing  
  - `scikit-learn`, `xgboost` for ML  
  - AutoAI for automated model building & comparison

---

## 📂 Dataset

- Source: [AI Kosh PMGSY Dataset](https://data.gov.in)
- Attributes:
  - Sanctioned/completed length of roads and bridges
  - Project cost
  - State, district
  - Completion status
  - Scheme label (PMGSY-I, II, RCPLWEA)

---

## 🧠 Model Approach

1. **Data Cleaning & Feature Engineering**
2. **Model Selection via AutoAI**
3. **Hyperparameter Optimization**
4. **Cross-validation Evaluation**
5. **Deployment-ready Pipeline Generation**

---

## 📊 Results

- Top model: **KNN Classifier**
- Accuracy: **91.4% (Cross-Validation)**
- Build time: < 2 mins per pipeline
- Enhanced with Feature Engineering and Hyperparameter Tuning (HPO-1, HPO-2)

---

## 🚀 Deployment

- The final model can be deployed via IBM Watson ML service as a REST API
- Supports real-time predictions by inputting new project details

---

## 📈 Future Scope

- Integrate additional features like GIS data, weather, terrain type
- Expand to cover other infrastructure schemes
- Explore deep learning or stacked ensemble models
- Real-time predictions via edge computing devices for on-site project classification

---

## 📚 References

1. PMGSY Official Guidelines – [https://pmgsy.nic.in](https://pmgsy.nic.in)  
2. IBM AutoAI Docs – [https://www.ibm.com/cloud/watson-studio](https://www.ibm.com/cloud/watson-studio)  
3. XGBoost Paper – T. Chen & C. Guestrin (2016)  
4. AI Kosh Dataset – [https://data.gov.in](https://data.gov.in)  
5. Scikit-learn Documentation – [https://scikit-learn.org](https://scikit-learn.org)

---

## 🙌 Author

**Jayasree S**  
B.Tech AI & DS – Anna University Regional Campus, Coimbatore

---

## 📌 Note

This project was developed as part of a capstone submission and can be adapted for large-scale government or civic infrastructure planning initiatives.
