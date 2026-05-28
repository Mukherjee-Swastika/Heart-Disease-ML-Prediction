# 🫀 Heart Disease Prediction System

A machine learning project that predicts the risk of heart disease using KNN (K-Nearest Neighbors) algorithm with a user-friendly Streamlit web interface.

---

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Model Details](#model-details)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Author](#author)
- [License](#license)
- [Contributing](#contributing)
- [Contact & Support](#contact--support)

---

## 🎯 Overview

This project implements a machine learning model to predict whether a person is at risk of heart disease based on various health parameters. The project includes:
- **Data Analysis & Exploration (EDA)** - Jupyter Notebook
- **Model Training** - KNN Classification Model
- **Web Application** - Streamlit interface for predictions

---

## ✨ Features

✅ Exploratory Data Analysis with visualizations  
✅ Data preprocessing and feature engineering  
✅ KNN model training and evaluation  
✅ Interactive web UI for real-time predictions  
✅ Input validation and user-friendly interface  
✅ Pre-trained model for quick predictions  

---

## 📊 Dataset

**Source:** Heart Disease Dataset  
**Records:** Multiple health attributes  
**Features Include:**
- Age
- Sex
- Chest Pain Type (ATA, NAP, TA, ASY)
- Resting Blood Pressure
- Cholesterol Level
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- Oldpeak (ST Depression)
- ST Slope

**Target Variable:** HeartDisease (0 = No Risk, 1 = High Risk)

---

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Libraries:**
  - pandas - Data manipulation
  - numpy - Numerical computations
  - scikit-learn - Machine Learning
  - matplotlib & seaborn - Data visualization
  - streamlit - Web interface
  - joblib - Model serialization

---

## 📥 Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package manager)

### Steps

1. **Clone the repository**
```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```

2. **Create a virtual environment (optional but recommended)**
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

3. **Install required packages**
```bash
pip install -r requirements.txt
```

---

## 🚀 Usage

### Run the Web Application

```bash
streamlit run app.py
```

The application will open in your browser at `http://localhost:8501`

### Using the Streamlit Interface

1. Enter your health parameters using the sliders and dropdowns
2. Click the **"Predict"** button
3. View your heart disease risk assessment:
   - 🟢 **Low Risk** - Green success message
   - 🔴 **High Risk** - Red warning message

### Run the GoogleColab Notebook

```bash
GoogleColab notebook HeartdiseaseFinal.ipynb
```

This will allow you to:
- Explore the dataset
- View data visualizations
- Understand model training process
- Modify and experiment with the model

---

## 📁 Project Structure

```
heart-disease-prediction/
├── app.py                          # Streamlit web application
├── HeartdiseaseFinal.ipynb        # Jupyter notebook with EDA & model training
├── knn_heart_model.pkl            # Trained KNN model
├── heart_scaler.pkl               # Feature scaler
├── heart_columns.pkl              # Expected feature columns
├── heart.csv                       # Dataset
├── requirements.txt               # Project dependencies
└── README.md                      # Project documentation
```

---

## 🤖 Model Details

**Algorithm:** K-Nearest Neighbors (KNN)  
**Approach:** Supervised Learning - Classification  
**Data Split:** Training and Testing sets  
**Feature Scaling:** StandardScaler (for KNN optimization)  
**Input Features:** 11 health parameters + encoded categorical variables  
**Output:** Binary classification (Heart Disease Risk: Yes/No)

### Model Workflow:
1. Data loading and cleaning
2. Exploratory Data Analysis
3. Feature encoding (One-Hot Encoding for categorical variables)
4. Feature scaling (StandardScaler)
5. Model training with KNN
6. Model evaluation and validation
7. Model serialization for web app

---

## 📈 Results

- Successfully trained KNN model with preprocessed heart disease dataset
- Model saved for production use in web application
- Provides real-time predictions through interactive interface
- User-friendly visualization of results

---

## 🔮 Future Improvements

- [ ] Add more ML algorithms (Random Forest, SVM, Neural Networks)
- [ ] Model comparison dashboard
- [ ] Feature importance visualization
- [ ] Confidence score for predictions
- [ ] Medical report generation
- [ ] Database integration for patient records
- [ ] Deploy on cloud platforms (Heroku, AWS, Azure)
- [ ] Mobile app version
- [ ] Real-time risk monitoring
- [ ] API development for integration

---

## 👨‍💻 Author

**SWASTIKA MUKHERJEE**  
BTech 3rd Year Student  
Machine Learning Enthusiast  
January 2008 - Present

---


## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

---

## 📧 Contact & Support

For questions or support, feel free to reach out or open an issue in the repository.

---

## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Streamlit Documentation](https://docs.streamlit.io/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Heart Disease Dataset](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

---

**Last Updated:** May 2026  
⭐ If this project helped you, please give it a star!
