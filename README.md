# Sonar Rock vs Mine Prediction using Machine Learning

This project builds a machine learning model that predicts whether an object detected by SONAR is a **Rock** or a **Mine**.

The model analyzes sonar signal patterns and classifies underwater objects using **Logistic Regression**.

---

## Problem Statement

SONAR (Sound Navigation and Ranging) systems are used to detect underwater objects. When sound waves hit an object, they bounce back and create signal patterns.

By analyzing these signals, machine learning can determine whether the object is:

- Rock
- Mine

---

## Dataset

The dataset used in this project is the **Sonar Dataset from the UCI Machine Learning Repository**.

Dataset details:

- Instances: 208
- Features: 60 numerical attributes
- Target classes:
  - R → Rock
  - M → Mine

Each row represents sonar signal strength measurements reflected from objects.

---

## Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook
- Google Colab

---

## Machine Learning Model

Algorithm used:

Logistic Regression

This algorithm is suitable for binary classification problems and provides efficient performance for structured numerical datasets.

---

## Project Workflow

1. Import required libraries
2. Load dataset
3. Data exploration
4. Data preprocessing
5. Train-test split
6. Model training
7. Model evaluation
8. Prediction system

---

## Project Structure

```
sonar-rock-vs-mine-prediction
│
├── dataset
│   └── sonar_dataset.csv
│
├── model
│   └── sonar_model.pkl
│
├── notebook
│   └── sonar_rock_vs_mine.ipynb
│
├── src
│   └── sonar_rock_vs_mine.py
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## Installation

Clone the repository

```
git clone https://github.com/areebsatti-official/sonar-rock-vs-mine-prediction.git
```

Navigate to the project directory

```
cd sonar-rock-vs-mine-prediction
```

Install required libraries

```
pip install -r requirements.txt
```

---

## Running the Project

Run the python file

```
python sonar_rock_vs_mine.py
```

The system will take sonar signal input and predict whether the object is **Rock or Mine**.

---

## Future Improvements

Possible improvements include:

- Deploy the model as a web application
- Create REST API using Flask or FastAPI
- Build a graphical interface
- Experiment with advanced algorithms like:
  - Random Forest
  - Support Vector Machine
  - Neural Networks

---

## Author

Muhammad Areeb Satti  
Software Engineering Student  
Machine Learning & Cybersecurity Enthusiast
