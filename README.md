🔐 CyberShield AI

CyberShield AI is a Machine Learning-based cybersecurity project that detects whether a URL is safe or malicious using URL feature analysis. The system helps identify phishing, malware, and defacement URLs by learning patterns from a large cybersecurity dataset.

🚀 Features
Malicious URL Detection
Phishing Website Identification
Feature Engineering from URLs
Random Forest & XGBoost Models
Model Performance Evaluation
Explainable AI using SHAP
Interactive URL Prediction
📊 Dataset

The project uses the Malicious URLs Dataset containing:

Benign URLs
Phishing URLs
Malware URLs
Defacement URLs

For binary classification:

Benign → Safe (0)
Others → Malicious (1)
⚙️ Extracted Features
URL Length
Number of Dots
Number of Hyphens
Number of Slashes
Number of Digits
HTTPS Presence
IP Address Usage
Subdomain Length
Suspicious Keywords Detection
🤖 Machine Learning Models
Random Forest Classifier
XGBoost Classifier
📈 Results
Accuracy: 94.27%
Precision: 94%
Recall: 93%
F1-Score: 94%
🛡️ Example

Input

http://paypal-login-secure.xyz

Output

⚠️ Malicious URL

Input

https://www.wikipedia.org

Output

✅ Safe URL
🛠️ Technologies Used
Python
Pandas
NumPy
Scikit-Learn
XGBoost
Matplotlib
Seaborn
SHAP
Google Colab
📂 Project Structure
CyberShield-AI/
│
├── CyberShield_AI.ipynb
├── malicious_phish.csv
├── cybershield_model.pkl
├── README.md
└── requirements.txt
🔮 Future Enhancements
Real-time URL Scanning
Browser Extension Integration
Domain Reputation Analysis
Deep Learning-based Detection
Cloud Deployment
👩‍💻 Author

Kinza Zahra
