🤖 Credit Score Prediction with AI – Full Pipeline

This project builds and deploys a machine learning model to predict customer credit scores based on behavioral and profile data. It includes data preprocessing, model training, evaluation, and real-world application to new customer data.

🚀 Features

Loads and cleans customer datasets

Encodes categorical features using LabelEncoder

Trains two machine learning models: Random Forest and K-Nearest Neighbors

Evaluates model accuracy and selects the best performer

Applies the trained model to predict credit scores for new customers

🧰 Technologies Used

Python 3

Pandas – Data manipulation

Scikit-learn – Machine learning models and metrics

📁 Project Structure

Código
credit-score-prediction-full/

│

├── clientes.csv             # Historical customer data

├── novos_clientes.csv       # New customer data for prediction

├── score_prediction.py      # Full pipeline script

└── README.md                # Project documentation


📈 Workflow Overview

Data Exploration – Understand and clean the dataset

Preprocessing – Encode categorical variables (profession, credit mix, payment behavior)

Model Training – Train Random Forest and KNN classifiers

Model Evaluation – Compare accuracy scores and select the best model

Deployment – Use the selected model (Random Forest) to predict scores for new customers

Output – Add predicted scores to the new customer dataset

⚠️ Notes

Ensure that the same preprocessing steps are applied to both training and new data

The dataset is anonymized and used for educational purposes

Accuracy may vary depending on dataset quality and feature selection

📬 Contact

Rodrigo Gonçalves Gusmão de Souza 📧 rodrigoggusmao@gmail.com
