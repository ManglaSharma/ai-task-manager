# 🧠 AI-Powered Task Management System

## 📘 Project Description

**AI-Powered Task Management System** is an intelligent productivity assistant that uses **Natural Language Processing (NLP)** and **Machine Learning (ML)** to automate task classification, predict priority levels, and assist users in managing workloads efficiently.

This project is designed to understand the context of tasks based on their descriptions, estimate urgency, and help users plan better. By combining structured data like deadlines and time taken with unstructured data like task descriptions, the system delivers accurate and adaptive task recommendations.

Whether you're a student juggling assignments or a team lead handling multiple project deliverables, this system aims to transform how tasks are analyzed and prioritized.

## 🎯 Key Highlights

- **Task Classification** using NLP and ML models (Naive Bayes, SVM)
- **Priority Prediction** based on time estimation, workload, and user behavior
- **Preprocessing Pipeline** for text cleaning, vectorization (TF-IDF), and feature engineering
- **Model Optimization** using hyperparameter tuning (GridSearchCV)
- **Performance Evaluation** through accuracy, confusion matrix, and classification reports

## 🚀 Features

- 📊 **Data Exploration & Cleaning**
- 🧹 **Text Preprocessing**
- 🗂 **Task Categorization**
- ⏱ **Priority Prediction**
- 🎯 **Model Tuning**
- 📈 **Evaluation Reports**

## 🗃 Dataset

- File: `task_dataset.csv`
- Columns:
  - `Task Description`
  - `Deadline`
  - `Time Taken (hours)`
  - `User Workload`
  - `Past Task Behavior`
  - `Priority`

## 🛠 Tech Stack

- Python: `pandas`, `numpy`, `nltk`, `sklearn`, `matplotlib`, `seaborn`
- Models: Naive Bayes, SVM, Random Forest
- Feature Extraction: TF-IDF

## 📂 Folder Structure

AI-Powered-Task-Management/
│
├── AI-Powered Task Management.ipynb  # Main notebook
├── task_dataset.csv                  # Input data
├── README.md                         # Project documentation
└── requirements.txt                  # Dependencies 

## 📥 Installation & Usage

1. Upload dataset to Google Drive.
2. Open notebook in Google Colab.
3. Mount Drive and run cells sequentially.
4. Customize model logic as needed.

## 📎 Future Improvements

- Add task deadline urgency logic
- Deploy as Flask/Streamlit app
- User-specific model tuning

## 📧 Contact

For queries or contributions, feel free to reach out.


