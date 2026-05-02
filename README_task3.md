# ❤️ Task 3: Heart Disease Prediction
**DevelopersHub Corporation — AI/ML Engineering Internship**
**Author:** Abdul Samad

---

## 📌 Objective
Predict whether a patient has heart disease using 13 medical measurements. Binary classification: `1` = disease, `0` = healthy.

---

## 📂 Dataset
- **Source:** Heart Disease UCI (multi-source) — Kaggle
- **Patients:** 920 · **Features:** 13 · **Missing values:** 1,759 (filled with median)
- **Cleaning applied:** Encoded text/bool columns, dropped `id` + `dataset`, converted `num` → binary target

---

## 🤖 Models & Results

| Model | Accuracy | ROC-AUC |
|---|---|---|
| **Logistic Regression** 🏆 | **83.15%** | **0.8949** |
| Decision Tree | 77.17% | 0.8327 |

---

## 💡 Key Findings
1. **Chest pain type (cp)** is the strongest predictor — asymptomatic pain = highest risk
2. **Max heart rate (thalach)** — lower rate during exercise = more disease risk
3. **Blocked vessels (ca)** — direct physical measure of arterial damage
4. **Age is NOT the top predictor** — heart function tests beat age every time

---

## ▶️ How to Run
```bash
pip install scikit-learn pandas numpy matplotlib seaborn jupyter
jupyter notebook heart_disease_prediction.ipynb
```

⚠️ Educational purposes only. Do not use for real medical decisions.

**👤 Abdul Samad** — AI/ML Engineering Intern, DevelopersHub Corporation
