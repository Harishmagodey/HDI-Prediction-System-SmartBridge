# 🌍 HDI Prediction System – Human Development Index Prediction using Machine Learning

A Machine Learning-based web application developed using **Python, Flask, and Linear Regression** to predict the **Human Development Index (HDI)** based on socio-economic indicators such as Life Expectancy, Expected Years of Schooling, and Gross National Income Per Capita.

> Developed as part of the **SmartBridge AI/ML Internship Program**.

---

# 📖 Overview

The HDI Prediction System is an intelligent web application that predicts the Human Development Index (HDI) of a country using Machine Learning techniques. The application analyzes important socio-economic indicators and provides an estimated HDI score through a simple and interactive web interface.

The project combines **Exploratory Data Analysis (EDA), Machine Learning, and Flask** to deliver accurate predictions and demonstrate the practical use of Artificial Intelligence in socio-economic analysis.

---

# 🎯 Problem Statement

The Human Development Index (HDI) is an important measure used to evaluate a country's development based on health, education, and income. Calculating HDI manually for analysis can be time-consuming and difficult when handling large datasets.

This project addresses this challenge by using Machine Learning to predict HDI values quickly and accurately using socio-economic indicators.

---

# 🎯 Project Objectives

- Develop an HDI prediction system using Machine Learning.
- Analyze the HDI dataset using Exploratory Data Analysis (EDA).
- Train and evaluate a Linear Regression model.
- Build an interactive Flask web application.
- Predict Human Development Index values in real time.
- Demonstrate the application of Artificial Intelligence in socio-economic analysis.

---

# ✨ Features

- 🌍 Human Development Index Prediction
- 📊 Exploratory Data Analysis (EDA)
- 🤖 Linear Regression Machine Learning Model
- 🌐 Flask Web Application
- 📱 Responsive User Interface
- ⚡ Instant HDI Prediction
- ✔ Input Validation
- 📈 Model Evaluation using Regression Metrics

---

# 🛠 Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Machine Learning | Scikit-learn, Linear Regression |
| Backend | Flask |
| Frontend | HTML, CSS, JavaScript |
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
│   ├── No. of Functional Features Included in the Solution.pdf
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
│   ├── style.css
│   └── images/
│       └── background.jpg
│
└── templates/
    └── index.html
```

---

# 🖼 Application Screenshots

## 🏠 Home Page

![Home Page](8.%20Project%20Demonstration/Screenshots/1.Home%20Page%20%E2%80%93%20HDI%20Prediction%20Interface.png)

---

## 📝 Prediction Input Form

![Prediction Input Form](8.%20Project%20Demonstration/Screenshots/2.Prediction%20Input%20Form.png)

---

## 📥 User Input with Sample Values

![User Input](8.%20Project%20Demonstration/Screenshots/3.User%20Input%20with%20Sample%20Values.png)

---

## 📈 HDI Prediction Result

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

## 3. Create a Virtual Environment (Recommended)

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

## 6. Run the Application

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
2. Enter the required socio-economic indicators:
   - Life Expectancy at Birth
   - Expected Years of Schooling
   - Gross National Income Per Capita
3. Click **Predict HDI**.
4. The trained Linear Regression model processes the input.
5. The predicted Human Development Index value is displayed.

---

# 🤖 Machine Learning Model

## Algorithm Used

- Linear Regression

## Purpose

- Human Development Index Prediction

The model was trained using the HDI dataset and saved as **hdi_model.pkl**, which is integrated with the Flask backend to provide real-time predictions.

---

# 📊 Dataset Information

| Attribute | Details |
|-----------|---------|
| Dataset | Human Development Index (HDI) Dataset |
| Format | CSV |
| Target Variable | Human Development Index (2021) |

### Input Features

- Life Expectancy at Birth (2021)
- Expected Years of Schooling (2021)
- Gross National Income Per Capita (2021)

### Output

- Human Development Index (HDI)

---

# 🧪 Testing

The application has been tested for:

- Functional Testing
- Model Evaluation
- User Input Validation
- End-to-End Workflow
- Local Deployment

All major functionalities were successfully verified.

---

# ⚠️ Current Limitations

- Uses Linear Regression only.
- Supports local deployment.
- Uses a CSV dataset.
- No user authentication.
- No cloud deployment.

---

# 🚀 Future Enhancements

- Cloud Deployment
- Database Integration
- Advanced Machine Learning Models
- User Authentication
- Dashboard and Analytics
- REST API Support
- Mobile-Friendly Version
- Real-Time Data Integration

---

# 🎥 Project Demonstration

**Demo Video**

https://drive.google.com/file/d/1zkjEX5rhW3mV4N74OzeDzQy-pX_WFttF/view?usp=drivesdk

---

# 👥 Team Members

- **Godey Sai Harishma**
- **Laxmanna Kuruva**

---

# 📜 License

This project was developed for academic purposes as part of the **SmartBridge AI/ML Internship Program**.
