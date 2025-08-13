## 🍷 Wine Quality Prediction Web App
A machine learning web application that predicts Wine Quality (Good / Low) based on chemical composition attributes, built with scikit-learn and deployed on Streamlit Cloud.

## 🚀 Live Demo
🔗 Streamlit App: https://winequalityapp-7hkmdhuubuvqwaawokwep8.streamlit.app/

🔗 GitHub Repo: https://github.com/DulakshiniDharmarathne/wine_quality_app

## 👤 Author
Name: I. D. D. R. Dharmarathne
Index No: ITBIN-2211-0174

## 📊 Dataset
The dataset used is the Wine Quality Dataset (Red Wine) from Kaggle.

Total Samples: 1,599 red wine samples

Features (11 numerical physicochemical properties):

Fixed acidity

Volatile acidity

Citric acid

Residual sugar

Chlorides

Free sulfur dioxide

Total sulfur dioxide

Density

pH

Sulphates

Alcohol percentage

Target Variable:

Original: Wine quality score (0–10)

Transformed: Binary Classification

Good Quality (1): Score ≥ 7

Low Quality (0): Score < 7

This dataset is commonly used for classification tasks to explore how chemical properties influence wine quality.

## 🧠 Machine Learning Pipeline
Models Tested:

Logistic Regression (Baseline)

## ✅ Random Forest Classifier (Selected Model)

Evaluation Metrics:

Accuracy Score

Classification Report (Precision, Recall, F1-score)

Confusion Matrix

## 📂 Project Structure
bash
Copy
Edit
wine_quality_app/
│
├── app.py                 # Streamlit application script
├── requirements.txt       # Python dependencies
├── model.pkl              # Trained Random Forest model
│
├── data/
│   └── dataset.csv        # Wine Quality Dataset
│
├── notebooks/
│   └── model_training.ipynb # Jupyter Notebook for model training
│
└── README.md              # Project documentation

## ⚙️ Installation & Usage
Clone the Repository

bash
Copy
Edit
git clone https://github.com/DulakshiniDharmarathne/wine_quality_app.git
cd wine_quality_app
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the Streamlit App

bash
Copy
Edit
streamlit run app.py
Access in Browser
Open http://localhost:8501

