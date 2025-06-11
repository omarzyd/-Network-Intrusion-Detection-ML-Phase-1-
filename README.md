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

(📌 *We’ll upload the final scores and confusion matrices soon!*)

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

- Machine learning isn’t just about algorithms — it’s about asking the right questions.
- Class imbalance can break models — but with the right techniques, it can be handled.
- Collaboration, documentation, and version control (thanks GitHub!) matter as much as the code itself.

---

## 🗂️ Repo Structure

