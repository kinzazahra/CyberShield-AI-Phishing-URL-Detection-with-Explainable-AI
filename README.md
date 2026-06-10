# 🔐 CyberShield AI

## 📌 Overview

CyberShield AI is a Machine Learning-based cybersecurity project designed to detect whether a URL is **Safe** or **Malicious**. The system analyzes various URL characteristics and uses classification algorithms to identify phishing, malware, and defacement websites.

This project demonstrates the application of Artificial Intelligence and Machine Learning in Cybersecurity for threat detection and prevention.

---

## 🎯 Objectives

- Detect malicious URLs using Machine Learning.
- Identify phishing websites based on URL patterns.
- Compare different classification models.
- Visualize cybersecurity insights through charts and metrics.
- Provide Explainable AI (XAI) using SHAP.
- Build a reusable URL classification model.

---

## 📊 Dataset

The project uses the **Malicious URLs Dataset**, which contains:

- Benign URLs
- Phishing URLs
- Malware URLs
- Defacement URLs

For binary classification:

```text
Benign      → Safe (0)
Others      → Malicious (1)
Dataset Distribution
Category	Count
Benign	428,103
Defacement	96,457
Phishing	94,111
Malware	32,520
⚙️ Feature Engineering

The following URL-based features are extracted:

URL Length
Number of Dots
Number of Hyphens
Number of Slashes
Number of Digits
Number of Special Characters
HTTPS Presence
IP Address Detection
Subdomain Length
Suspicious Keyword Detection
🤖 Machine Learning Models

The following models were implemented and evaluated:

Random Forest Classifier
Ensemble-based learning algorithm
High accuracy and robustness
Provides feature importance analysis
XGBoost Classifier
Gradient boosting algorithm
Efficient and scalable
Used for performance comparison
📈 Results
Model Performance
Metric	Score
Accuracy	94.27%
Precision	94%
Recall	93%
F1-Score	94%

The model achieved strong performance in distinguishing between safe and malicious URLs.

📊 Visualizations

The project includes:

Dataset Distribution Chart
Correlation Heatmap
Feature Importance Graph
Confusion Matrix
ROC Curve
SHAP Explainability Plot

These visualizations help understand model behavior and prediction performance.

🛡️ Example Predictions
Safe URL

Input

https://www.wikipedia.org

Output

✅ Safe URL
Malicious URL

Input

http://paypal-login-secure.xyz

Output

⚠️ Malicious URL
🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-Learn
XGBoost
Matplotlib
Seaborn
SHAP
Joblib
Google Colab
📂 Project Structure
CyberShield-AI/
│
├── CyberShield_AI.ipynb
├── malicious_phish.csv
├── cybershield_model.pkl
├── README.md
└── requirements.txt
🚀 Future Enhancements
Real-Time URL Scanning
Browser Extension Integration
Domain Reputation Analysis
WHOIS Lookup Integration
SSL Certificate Verification
Deep Learning-Based Detection
Cloud Deployment
🔬 Applications
Phishing Website Detection
Cyber Threat Intelligence
Security Awareness Tools
Secure Browsing Assistance
Educational Cybersecurity Projects

👩‍💻 Author

Kinza Zahra


