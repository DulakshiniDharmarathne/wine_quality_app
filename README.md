## 🍷 Wine Quality Prediction Web App
A machine learning web application that predicts wine quality (Good / Low) based on chemical composition attributes, built using scikit-learn and deployed with Streamlit Cloud.

Live Demo
🔗 Streamlit App: https://winequalityapp-7hkmdhuubuvqwaawokwep8.streamlit.app/
🔗 GitHub Repo: https://github.com/DulakshiniDharmarathne/wine_quality_app

## 👤 Author
Name : I D D R dharmarathne ||
Index No: ITBIN-2211-0174

## 📊 Dataset
The Wine Quality Dataset (Red Wine) from Kaggle contains 1,599 samples of red wine, each described by 11 numerical physicochemical properties. These features include fixed acidity, volatile acidity, citric acid, residual sugar, chlorides, free sulfur dioxide, total sulfur dioxide, density, pH, sulphates, and alcohol percentage. The target variable represents the wine’s quality score on a scale from 0 to 10, which has been transformed into a binary classification: wines with a quality score of 7 or higher are labeled as “Good Quality” (1), while those with a score below 7 are labeled as “Low Quality” (0). This dataset is commonly used for classification tasks and predictive modeling in machine learning, particularly in exploring how chemical properties influence perceived wine quality.


## 🧠 Machine Learning Pipeline
Models Used:
Logistic Regression – Baseline linear model
Random Forest Classifier ✅ (selected model)
Evaluation Metrics:
Accuracy score
Classification report (Precision, Recall, F1-score)
Confusion matrix

## 📂 Project Structure

├── app.py ├── requirements.txt ├── model.pkl ├── data/ │ └── dataset.csv ├── notebooks/ │ └── model_training.ipynb └── README.md
