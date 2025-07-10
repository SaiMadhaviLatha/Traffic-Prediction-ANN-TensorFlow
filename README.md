# 🚦 Traffic Condition Classification using Deep Learning (ANN)

This project focuses on classifying traffic conditions (Low, Normal, High, Heavy) using real-time vehicle counts (cars, bikes, buses, trucks) and time-based features (hour, day). A Deep Learning model using an Artificial Neural Network (ANN) was built and fine-tuned for high accuracy and generalization.

---

## 🧠 Problem Statement

Urban traffic is a major concern for city planning and public mobility. This project aims to predict the traffic condition at any given time using road sensor data — enabling better traffic control, planning, and congestion management.

---

## 📊 Dataset Overview

The dataset includes:
- **Vehicle counts**: Cars, bikes, buses, trucks
- **Time-based features**: Hour of day, day of week
- **Target**: Traffic condition (Low, Normal, High, Heavy)

---

## 🔍 Exploratory Data Analysis (EDA) – Key Insights

- **Normal** traffic is the most frequent condition, followed by **Heavy**
- **Car count** is strongly correlated with traffic severity
- **Weekday rush hours** are 7–9 AM and 4–6 PM; weekends show more balanced flow
- **Bus/truck counts** are low overall but influence congestion variability
- Traffic is generally stable across different weekdays, indicating time-based factors matter more than the day itself

---

## 🛠️ Tech Stack

- Python, Pandas, NumPy
- TensorFlow, Keras, Keras Tuner
- Scikit-learn, Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

---

## 🧱 Model Architecture (ANN)

- Optimized using **Keras Tuner**
- Used **SMOTE** to handle class imbalance
- Trained with 80/20 split and evaluated using accuracy, precision, recall, and F1 score

---

## 📈 Model Performance

| Metric      | Value     |
|-------------|-----------|
| Accuracy    | 96.03%    |
| Precision   | 96.24%    |
| Recall      | 95.91%    |
| F1 Score    | 95.99%    |

📌 Compared with:
- Random Forest: 99.77%
- SVM: 94.61%

---

## 🙌 Acknowledgements

Thanks to the mentors at **Innomatics Research Labs** for their support and guidance during this project.

---

## 💬 Let's Connect!

I’m actively looking for **Data Analyst**, **Data Scientist**, and **AI roles** where I can apply these skills to solve real-world problems.  
📩 https://www.linkedin.com/in/sai-madhavi-latha-maddali/
