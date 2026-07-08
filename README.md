
# 🌍 HDI Prediction System – SmartBridge

A Machine Learning-based Human Development Index (HDI) Prediction System developed using **Python, Flask, and Linear Regression** to estimate the Human Development Index of a country based on socio-economic indicators.

> Developed as part of the **SmartBridge AI/ML Internship Program**.

---

# 📖 Overview

HDI Prediction System is an intelligent web application that predicts the Human Development Index (HDI) using Machine Learning. Users provide important socio-economic indicators such as Life Expectancy, Expected Years of Schooling, and Gross National Income Per Capita. The trained machine learning model processes these inputs and predicts the corresponding HDI value.

The project combines **Exploratory Data Analysis (EDA), Machine Learning, and Flask** to provide an easy-to-use web interface for HDI prediction.

---

# 🎯 Problem Statement

The Human Development Index (HDI) is one of the most important indicators used to measure a country's overall development based on health, education, and standard of living.

Manual analysis of socio-economic data can be time-consuming and prone to errors. This project uses Machine Learning to automate HDI prediction, providing fast and reliable estimates based on user inputs.

---

# 🎯 Project Objectives

- Develop a Machine Learning model to predict Human Development Index.
- Analyze HDI dataset using Exploratory Data Analysis (EDA).
- Train and evaluate a Linear Regression model.
- Build an interactive Flask web application.
- Predict HDI values in real time.
- Demonstrate the practical application of Artificial Intelligence in socio-economic analysis.

---

# ✨ Features

- 🌍 Human Development Index Prediction
- 📊 Exploratory Data Analysis (EDA)
- 🤖 Linear Regression Model
- 🌐 Flask Web Application
- 📱 Responsive User Interface
- ⚡ Real-Time Prediction
- ✔ Input Validation
- 📈 Model Performance Evaluation

---

# 🛠 Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Machine Learning | Scikit-learn, Linear Regression |
| Backend | Flask |
| Frontend | HTML, CSS |
| Data Analysis | Pandas, NumPy, Matplotlib |
| Development Tools | Visual Studio Code, Git, GitHub |

---

# 📂 Repository Structure

```text
HDI-Prediction-System-SmartBridge/
│
├── 1. Brainstorming & Ideation/
├── 2. Requirement Analysis/
├── 3. Project Design Phase/
├── 4. Project Planning Phase/
├── 5. Project Development Phase/
│
│   ├── Coding & Solution.pdf
│   ├── Code Layout, Readability and Reusability.pdf
│   ├── Functional Features.pdf
│   │
│   └── Source Code/
│       ├── app.py
│       ├── train_model.py
│       ├── requirements.txt
│       ├── README.md
│       ├── dataset/
│       ├── model/
│       ├── static/
│       └── templates/
│
├── 6. Project Testing/
├── 7. Project Documentation/
└── 8. Project Demonstration/
```

---

# 💻 Source Code Structure

```text
Source Code/
│
├── app.py
├── train_model.py
├── requirements.txt
├── README.md
│
├── dataset/
│   └── HDI.csv
│
├── model/
│   ├── hdi_model.pkl
│   └── imputer.pkl
│
├── static/
│   ├── images/
│   └── style.css
│
└── templates/
    └── index.html
```

---

# 🖼 Application Screenshots

## 🏠 Home Page

![Home Page](8.%20Project%20Demonstration/Screenshots/1.Home%20Page%20–%20HDI%20Prediction%20Interface.png)

---

## 📝 Prediction Input Form

![Prediction Input](8.%20Project%20Demonstration/Screenshots/2.Prediction%20Input%20Form.png)

---

## 📋 User Input with Sample Values

![User Input](8.%20Project%20Demonstration/Screenshots/3.User%20Input%20with%20Sample%20Values.png)

---

## 📊 HDI Prediction Result

![Prediction Result](8.%20Project%20Demonstration/Screenshots/4.HDI%20Prediction%20Result%20Page.png)

---

# ⚙️ Installation & Setup

## 1. Clone the Repository

```bash
git clone https://github.com/Harishmagodey/HDI-Prediction-System-SmartBridge.git
```

## 2. Navigate to the Source Code

```bash
cd "5. Project Development Phase/Source Code"
```

## 3. Create a Virtual Environment

### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

## 4. Install Dependencies

```bash
pip install -r requirements.txt
```

## 5. Train the Model

```bash
python train_model.py
```

## 6. Run the Flask Application

```bash
python app.py
```

## 7. Open in Browser

```
http://127.0.0.1:5000
```

---

# 🔄 Application Workflow

1. Launch the Flask application.
2. Enter:
   - Life Expectancy at Birth
   - Expected Years of Schooling
   - Gross National Income Per Capita
3. Click **Predict HDI**.
4. The Linear Regression model processes the input values.
5. The predicted Human Development Index (HDI) is displayed.

---

# 🤖 Machine Learning Model

### Algorithm Used

- Linear Regression

### Purpose

Predict the Human Development Index (HDI) using socio-economic indicators.

The trained model is saved as **hdi_model.pkl** and integrated with the Flask application for real-time prediction.

---

# 📊 Dataset Information

| Attribute | Details |
|-----------|---------|
| Dataset | Human Development Index Dataset |
| Format | CSV |
| Input Features | 3 |
| Output | Human Development Index (HDI) |

### Input Features

- Life Expectancy at Birth (2021)
- Expected Years of Schooling (2021)
- Gross National Income Per Capita (2021)

### Output

- Human Development Index (HDI)

---

# 🧪 Testing

The application was tested for:

- Functional Testing
- Model Evaluation
- User Input Validation
- End-to-End Workflow
- Local Deployment

All core functionalities were successfully verified.

---

# ⚠️ Current Limitations

- Supports only local deployment.
- Uses Linear Regression model.
- No cloud deployment.
- No user authentication.
- Uses a single dataset.

---

# 🚀 Future Enhancements

- Cloud Deployment
- Advanced Machine Learning Models
- Database Integration
- User Authentication
- Dashboard and Analytics
- REST API Support
- Mobile Application
- Improved Prediction Accuracy

---

# 👥 Team Members

- **Godey Sai Harishma**
- **Laxmanna Kuruva**

---

# 📜 License

This project was developed for academic purposes as part of the **SmartBridge AI/ML Internship Program**.
