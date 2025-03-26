# 🚀 Cybersecurity Threat Classification with XGBoost

## 🔍 Overview
This project leverages **XGBoost**, a powerful machine learning algorithm, to classify network traffic into two categories:

- ✅ **Normal (BENIGN)** traffic
- ⚠️ **Cyber Threats** (DDoS, PortScan, Bot, Infiltration, and more)

Built on the **CICIDS2017** dataset, this model is designed to detect malicious network activity with high accuracy, helping to safeguard networks against potential cyber attacks.

---

## 📊 Key Results

| **Metric**       | **Score**   |
|------------------|------------|
| **Accuracy**     | 99.65%     |
| **Precision**    | 99.81%     |
| **Recall**       | 99.65%     |
| **F1 Score**     | 99.71%     |

### ✅ **Best At Detecting:**
- **DDoS** and **PortScans**
- Efficiently handles **rare attacks** (e.g., Heartbleed)

---

## 📌 Top Predictive Features

- 🔹 **Flow Duration**
- 🔹 **Packet Length Statistics**
- 🔹 **TCP Flags**
- 🔹 **Packet Rate**

(Full feature importance available in the notebook!)

---

## 🛠 Tech Stack

- **Python 3.7+** — Programming Language
- **XGBoost** — High-performance classification
- **Pandas**, **NumPy** — Data processing
- **Matplotlib**, **Seaborn** — Data visualization

---

## 🚀 Quick Start

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/pankajkumar037/cybersecurity-threat-classification.git
```

### 2️⃣ **Run the Jupyter Notebook**
```bash
jupyter notebook
```

---

## 📚 **Features & Capabilities**

- 🔍 **Data Preprocessing** — Handles missing values and normalizes data
- 📊 **Exploratory Data Analysis (EDA)** — Visual insights into traffic patterns
- 🚀 **Model Training** — XGBoost optimized with hyperparameter tuning
- 📈 **Evaluation Metrics** — Precision, Recall, F1 Score

---

## 📢 **Contributing**
Contributions are welcome! Feel free to open issues or create pull requests to improve this project.

---

## 🏷 **License**
This project is licensed under the **MIT License**.

---

## 🙌 **Acknowledgments**
Special thanks to the creators of the **CICIDS2017** dataset for providing valuable resources for cybersecurity research.
