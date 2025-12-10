# 🧾 **SpendGenie – AI-Based Personal Expense Tracking & Forecasting Tool**

### *Infosys Springboard Virtual Internship 6.0 – Batch 4*

SpendGenie is an AI-powered personal finance assistant that helps users **track expenses, analyze spending patterns, and forecast future financial trends** using machine learning. It provides a clean, user-friendly interface with smart dashboards, automated data processing, and predictive analytics to support better financial decision-making.

---

## 📌 **Table of Contents**

* [Introduction](#introduction)
* [Features](#features)
* [Tech Stack](#tech-stack)
* [System Architecture](#system-architecture)
* [Screenshots](#screenshots)
* [Project Workflow](#project-workflow)
* [Machine Learning Model](#machine-learning-model)
* [Challenges Faced](#challenges-faced)
* [Future Enhancements](#future-enhancements)
* [Contributors](#contributors)
* [Acknowledgements](#acknowledgements)

---

# 📖 **Introduction**

SpendGenie is designed as part of the **Infosys Springboard Virtual Internship 6.0** to provide users with an intelligent and automated solution for managing personal finances. By uploading expense data in CSV format or entering values manually, users can view:

* Interactive dashboards
* Category-wise spending
* Monthly and yearly trends
* AI-generated expense predictions
* Personalized financial insights

The system uses **Flask**, **SQLAlchemy**, **Pandas**, and **Linear Regression ML models** to deliver an end-to-end personal finance management experience.

---

# 🚀 **Features**

### ✔ **User Authentication**

* Secure login and registration using bcrypt encryption
* Session management for individual users

### ✔ **CSV Upload & Smart Data Cleaning**

* Automatic detection of date and amount columns
* Cleaning inconsistent formats (commas, currency symbols, negatives)
* Restores missing values intelligently

### ✔ **Expense Categorization**

* Classifies expenses (Food, Travel, Rent, Bills, Shopping, etc.)
* Supports manual expense entry

### ✔ **Interactive Dashboard**

Built using **Plotly**, featuring:

* Monthly expense trends
* Category-wise distribution
* Daily peak spending graph
* Year-wise summaries

### ✔ **AI-Based Forecasting**

* Predicts next month’s expenses
* Category-wise forecast
* Adaptive learning based on user behavior

### ✔ **Chatbot Assistance**

* Provides budgeting tips
* Answers user queries
* Real-time responses

### ✔ **Responsive UI**

* Sidebar navigation
* Hamburger menu
* Light/Dark mode toggle

### ✔ **PDF Report Generation**

* Allows users to export financial summaries

---

# 🛠 **Tech Stack**

| Component            | Technology                       |
| -------------------- | -------------------------------- |
| **Frontend**         | HTML, CSS, JS, Plotly Charts     |
| **Backend**          | Flask (Python)                   |
| **Database**         | SQLite (via SQLAlchemy)          |
| **Machine Learning** | Linear Regression (scikit-learn) |
| **Data Handling**    | Pandas, NumPy                    |
| **Security**         | Flask-Bcrypt                     |
| **Deployment**       | Local / Cloud (Ngrok optional)   |

---

# 🧱 **System Architecture**

```
User → UI → Flask Backend → ML Engine → Database → Dashboard
                                 ↓
                           Data Processing
```

### Components:

* Data ingestion module
* Cleaning & preprocessing layer
* Expense classifier
* ML prediction model
* Visualization dashboard
* API-based chatbot

---

# 🖼 **Screenshots**


1. Landing Page
2. Login/Signup Page
3. CSV Upload Page
4. Dashboard with analytics
5. Add Expense Page
6. Forecast Page
7. Chatbot
8. Generated PDF Report
9. Contact Page

---

# 🧬 **Project Workflow**

### **1. User Authentication**

Register → Login → Create personal session storage

### **2. Upload Expense Data**

* Supported: CSV files from banks, digital wallets, UPI apps
* Fault-tolerant cleaning ensures accurate processing

### **3. Data Processing**

* Column detection
* Date formatting
* Amount standardization
* Expense categorization

### **4. Dashboard Generation**

* Visual graphs and trends

### **5. ML-Based Forecasting**

* Linear Regression predicts next-month expenses
* Generates category-wise budget suggestions

### **6. Report & Chatbot**

* PDF export
* AI chatbot assistance

---

# 🤖 **Machine Learning Model**

SpendGenie uses **Linear Regression** for time-series prediction based on:

```
X → Past monthly expenses  
Y → Predicted next month’s expense  
```

Model improvements:

* Outlier removal
* Normalization
* Rolling averages

Accuracy improves as more user data is added.

---

# 💡 **Challenges Faced**

* Handling inconsistent CSV formats
* Real-time integration of ML predictions
* Achieving responsive UI design
* Maintaining user-specific sessions
* Ensuring secure authentication
* Improving model accuracy with limited data

---

# 🔮 **Future Enhancements**

✔ Integration with bank APIs
✔ Multi-user family budgeting
✔ Export to Excel/Google Sheets
✔ Deep Learning–based prediction models (LSTM)
✔ Mobile app version (Flutter/React Native)
✔ Alerts for overspending & bill reminders

---

# 👨‍💻 **Contributors**

Team Members (Batch 4):
*Kavya Sampathirao
Kokila M
Nandi Mangalam Geervani
Poolasetty Chandana
Pratyasha Basak
Priyanshi Jayant*

---

# 🙏 **Acknowledgements**

We would like to thank **Infosys Springboard** for providing the opportunity and learning environment to build this AI-driven project. Special appreciation to our mentor **Sangeetha** for constant support and guidance.

---

# ⭐ **If you like this project, consider giving it a star on GitHub!** ⭐

---
