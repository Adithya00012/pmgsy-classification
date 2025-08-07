# 🚧 PMGSY Scheme Classification using Machine Learning

This project automates the classification of rural infrastructure projects under different PMGSY schemes (PMGSY-I, PMGSY-II, PMGSY-III, RCPLWEA) using machine learning, based on their physical and financial characteristics.

---

## 📌 Problem Statement

Manual classification of road and bridge projects under PMGSY is slow, error-prone, and not scalable. Each scheme has different rules and objectives. This project uses machine learning to predict the correct PMGSY scheme, improving monitoring and planning.

---

## 📊 Dataset

- **Source**: [AI Kosh - PMGSY Dataset](https://aikosh.indiaai.gov.in/)
- **Features**: State, District, Road Length, Bridges, Project Cost, Completion, etc.
- **Target**: PMGSY Scheme (categorical)

---

## 🧠 Machine Learning Approach

- **Model Used**: XGBoost Classifier
- **Platform**: IBM Watson Studio (Cloud-based training)
- **Deployment**: IBM Watson Machine Learning (WML)
- **Preprocessing**:
  - Missing value handling
  - Label encoding & one-hot encoding
  - Train-test split

---

## ✅ Results

- **Accuracy**: 92.8%
- **Macro F1-Score**: 0.91
- **Observations**:
  - High accuracy for major schemes (PMGSY-I, II)
  - Lower performance on RCPLWEA due to class imbalance

---

## 🧰 Tools & Technologies

- IBM Cloud Lite
- IBM Watson Studio
- IBM Watson Machine Learning
- Python (pandas, numpy, scikit-learn, xgboost, matplotlib)

---

## 🚀 Future Improvements

- Balance class distribution for better RCPLWEA accuracy
- Integrate real-time PMGSY project data using APIs
- Expand dataset with more districts and years

---

## 🙋‍♂️ Author

**K Adithya**  
CMR University – CSE Data Science  
