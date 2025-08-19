# Machine Learning Model Deployment with Flask
This project demonstrates how to build, train, and deploy a Machine Learning model using Flask as a REST API service.
The model used in this project is a Gradient Boosting Regressor, exported with joblib for deployment.

## Project Structure
├── test1.ipynb          # Jupyter Notebook for data preprocessing, training, and evaluation  
├── testing_deploy.py    # Flask API script for model deployment  
├── gbr_model.joblib     # Trained machine learning model (serialized)  
└── data/                # Dataset folder (not included in this repository)  
    ├── train.csv         # Training dataset  
    └── test.csv          # Testing dataset

## Technologies
- Python 3.x
- Pandas, NumPy, Scikit-learn
- Joblib
- Flask

## Jupyter Notebook
The notebook test1.ipynb includes:
    - Data loading and preprocessing
    - Exploratory Data Analysis (EDA)
    - Training a Gradient Boosting Regressor
    - Model evaluation
    - Exporting the model to gbr_model.joblib