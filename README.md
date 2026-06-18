# 💳 Financial Fraud or Legal Transaction Detection

An AI-powered web application that detects fraudulent financial transactions 
using Machine Learning and Deep Learning algorithms, built with Django.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Backend | Python, Django |
| ML Models | XGBoost, SMOTE |
| Database | SQLite |
| Dashboard | Chart.js |
| Alerts | Gmail SMTP, Twilio SMS, WhatsApp |
| Export | jsPDF |

---

## ✨ Features

- 🔍 Real-time fraud detection using ML/DL models
- 📊 Admin dashboard with pie, bar, and line charts
- 📅 Date filtering for transaction analysis
- 📧 Instant alerts via Gmail, SMS, and WhatsApp
- 📄 PDF export of transaction reports
- ⚖️ Handles class imbalance using SMOTE

---

## 🧠 ML Approach

- **Algorithm:** XGBoost Classifier
- **Imbalance Handling:** SMOTE (Synthetic Minority Oversampling Technique)
- **Domain:** Financial Transaction Fraud Detection (AIML)

---

## ⚙️ Setup & Installation

```bash
# Clone the repo
git clone https://github.com/rohanhosamane/financial-fraud-or-legal-transaction.git
cd financial-fraud-or-legal-transaction

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py migrate

# Start the server
python manage.py runserver
```

---

## 📬 Alerts Configuration

Add your credentials in `.env` or `settings.py`:

```
EMAIL_HOST_USER=your_email@gmail.com
EMAIL_HOST_PASSWORD=your_app_password
TWILIO_ACCOUNT_SID=your_sid
TWILIO_AUTH_TOKEN=your_token
TWILIO_PHONE_NUMBER=your_number
```

---

## 👨‍💻 Author

**Hosamane H Rohan**  
MCA Graduate | Back-End Developer  
[LinkedIn](https://www.linkedin.com/in/hosamane-h-rohan-10b0ab209) • [GitHub](https://github.com/rohanhosamane)
