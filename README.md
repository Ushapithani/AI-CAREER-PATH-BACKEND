# AI CareerPath – Backend

**Python, FastAPI, Scikit-Learn, Pandas, pdfplumber, Logistic Regression**

AI CareerPath Backend is a **FastAPI-based machine learning backend** that analyzes resumes, extracts relevant skills, calculates a resume score, and predicts suitable career roles.

## 🚀 Features

* 📄 PDF resume text extraction using **pdfplumber**
* 🔍 Skill extraction using predefined skill keywords
* 📊 Resume quality scoring
* 🤖 Career-role prediction using **Scikit-Learn Logistic Regression**
* 🔢 Label encoding using `LabelEncoder`
* ⚡ REST API using FastAPI
* 📦 Model-based prediction through trained ML components

## 🔄 Workflow

```text
Resume PDF
    ↓
Text Extraction
    ↓
Skill Detection
    ↓
Feature Vector Creation
    ↓
Logistic Regression Model
    ↓
Career Role Prediction
    ↓
Resume Score + Skills + Career Recommendations
```

## 🧠 Machine Learning

The project uses **Logistic Regression** as a classification algorithm for predicting suitable career roles.

The detected skills are converted into numerical feature vectors, which are provided as input to the trained model.

`LabelEncoder` is used to convert career-role labels into numerical values for model training.

## 🔌 API

The frontend communicates with the backend through the FastAPI prediction endpoint:

```text
POST /predict
```

The API processes the uploaded resume and returns information such as:

* Resume score
* Detected skills
* Predicted career roles

## 🛠️ Tech Stack

* Python
* FastAPI
* Scikit-Learn
* Pandas
* NumPy
* pdfplumber
* Joblib

## 📁 Project Structure

```text
AI-CAREER-PATH-BACKEND/
│
├── analyze_resume.py
├── main.py
├── requirements.txt
├── model/
└── README.md
```

## 🎯 Project Objective

The objective of this backend is to transform resume information into **structured skill features** and use machine learning to provide **data-driven career recommendations**.

## 👩‍💻 Author

**Usha Pithani**
