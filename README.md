🚀 Cybersecurity Threat Classification with XGBoost

🔍 Overview
This project uses machine learning (XGBoost) to classify network traffic into:
✅ Normal (BENIGN) traffic
⚠️ Cyber threats (DDoS, PortScan, Bot, Infiltration, and more)

Built on the CICIDS2017 dataset, this model helps detect malicious network activity with high accuracy.

📊 Key Results
🎯 Model Performance
Accuracy: 99.65%
Precision: 99.81%
Recall: 99.65%
F1 Score: 99.71%

✔ Best at detecting: DDoS, PortScans
✔ Handles imbalance: Rare attacks (e.g., Heartbleed) still detected

📌 Top Predictive Features
🔹 Flow Duration
🔹 Packet Length Stats
🔹 TCP Flags
🔹 Packet Rate

(Full feature importance in the notebook!)

🛠 Tech Stack
Python 3.7+

XGBoost (for high-performance classification)

Pandas, NumPy (data processing)

Matplotlib, Seaborn (visualizations)

🚀 Quick Start
1️⃣ Install & Run
bash
Copy
git clone https://github.com/pankajkumar037/cybersecurity-threat-classification.git

jupyter notebook
2️⃣ Explore the Notebook
📌 Data Preprocessing
📌 Exploratory Analysis
📌 XGBoost Training & Evaluation

