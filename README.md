# 🛡️ Network Intrusion Detection using Machine Learning (Phase 1)

Welcome to our Machine Learning project a hands-on journey where we tackled a real-world cybersecurity problem with a team of passionate learners.

---

## 🌍 Why This Project Matters

In a world increasingly dependent on digital systems, securing networks is no longer optional, it’s essential. We set out to build a model that could **detect anomalies in network traffic**, potentially flagging cyberattacks before they cause harm.  

This project taught us more than just models and metrics — it was about **collaboration, problem-solving, and thinking critically under constraints**.

---

## 🧩 The Problem

We were given a dataset mimicking a **military network environment**, where each connection needed to be labeled as either:

- ✅ `normal`
- ⚠️ `anomaly` (potential intrusion)

The catch? Anomalies were rare — just like real cyberattacks. This **class imbalance** forced us to think beyond accuracy and dive into **precision, recall, and smarter techniques like SMOTE**.

---

## 📊 What We Did

### 🔎 Data Understanding & Preparation
We started with cleaning and exploring the data:
- Handled missing values and outliers
- Visualized distributions and correlations
- One-hot encoded categorical features
- Scaled numerical values for better model performance
- Selected the **top 20 features** using importance analysis

We also **balanced the dataset** using **SMOTE** (Synthetic Minority Over-sampling Technique) to avoid bias toward the majority class.

---

### 🤖 Models We Built

| Model                | What It Gave Us                                |
|---------------------|-------------------------------------------------|
| K-Nearest Neighbors | A simple, distance-based baseline               |
| Logistic Regression | Fast, linear, and surprisingly effective        |
| Support Vector Machine | Great for high-dimensional data             |
| Random Forest        | Robust, non-linear, and hard to beat            |
| **Voting Classifier**| Combined the wisdom of all models (ensemble)   |

We trained and tested each model and evaluated them using:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

1. Decision Tree performance measures : 
![image](https://github.com/user-attachments/assets/0eba95d2-3daa-4d61-a954-7b131e705302)

2. Logistic Regression performance measures :
![image](https://github.com/user-attachments/assets/5f0cd2c3-fee3-4fce-be5a-072164e29247)

3. KNN performance measures at k = 5 :
![image](https://github.com/user-attachments/assets/2f057fa5-252e-47a0-9063-73621b28134a)

4. Voting performance measures :
![image](https://github.com/user-attachments/assets/490749de-3667-41bd-9c50-5f6780c3f038)

---

## 🤝 Collaboration

This project wasn’t a solo mission — it was a true team effort. We divided tasks smartly:
- One of us focused on **EDA and visualization**
- Another handled **model implementation**
- Others worked on **feature engineering**, **resampling**, and **evaluation**
- We constantly reviewed each other’s work to ensure consistency and quality

If there’s one thing we learned, it’s that **good code is written, but great code is reviewed.**

---

## 🧰 Tools We Used

- **Python** 🐍
- **Pandas**, **NumPy** for data wrangling
- **Matplotlib**, **Seaborn** for visual storytelling
- **Scikit-learn** for modeling
- **Imbalanced-learn** for handling class imbalance

---

## 💡 Key Takeaways

Overall, the project demonstrated that ensemble methods like Soft Voting can significantly improve model performance, making them a good choice for tasks such as network intrusion detection, where accuracy and reliability are crucial.
