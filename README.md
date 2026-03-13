# Real Estate Price Prediction Model
## Overview

This project is a machine learning-based price prediction system that estimates the price of real estate properties based on key features such as location, area, number of bedrooms, bathrooms, and other attributes. The goal is to provide accurate price estimations to help buyers, sellers, and real estate agents make informed decisions.

## Features

Data preprocessing & feature engineering (handling missing values, encoding, scaling).
Exploratory Data Analysis (EDA) with insights and visualizations.
Model training using algorithms such as Linear Regression, Ridge, Lasso, Decision Trees, Random Forest, and XGBoost.
Hyperparameter tuning for optimal performance.
Model evaluation using metrics such as R², RMSE, and MAE.
Interactive web application (Flask/Streamlit) for real-time price predictions.

## Tech Stack

Programming Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost
Frontend (Optional): HTML, CSS, JavaScript
Backend: Flask / FastAPI / Streamlit
Deployment: AWS / Heroku / Render (Optional)

## Project Structure

Real-Estate-Price-Prediction-Model/
│── data/                 # Raw and processed datasets  
│── notebooks/            # Jupyter notebooks for EDA & training  
│── models/               # Saved ML models (Pickle/Joblib)  
│── static/               # CSS, JS, images (for web app)  
│── templates/            # HTML templates (for Flask app)  
│── app.py                # Flask/Streamlit app script  
│── requirements.txt      # Dependencies  
│── README.md             # Project documentation  

## Dataset

Source: Kaggle.
Features: Location, Size (sq.ft), Bedrooms, Bathrooms, Year Built, Amenities, etc.
Target: Property Price.

## UI

<img width="940" height="438" alt="image" src="https://github.com/user-attachments/assets/0c25e491-c57c-42b5-a861-e6356c26c416" />


## Installation & Usage

1️⃣ Clone the Repository
git clone [https://github.com/ADITI-VERMA05/Real-Estate-Price-Prediction]
cd Real-Estate-Price-Prediction-Model

2️⃣ Create Virtual Environment & Install Dependencies
```
python -m venv venv
source venv/bin/activate  # On Linux/Mac
venv\Scripts\activate     # On Windows
```
```
pip install -r requirements.txt
```
3️⃣ Run Jupyter Notebook (For EDA & Training)
jupyter notebook

4️⃣ Run Flask/Streamlit App (For Predictions)
```
python app.py
or
streamlit run app.py
```

## Results

Best model achieved: R² Score: ~0.85, RMSE: ~XYZ (replace with your results).
Visualizations show correlation between area, location, and price.

## Deployment (Optional)

The model can be deployed on:
Heroku
Render
AWS EC2 / S3

Dockerized for portability

## Future Enhancements

Adding more advanced models (Deep Learning / Neural Networks).
Incorporating real-time location APIs (Google Maps).
Enhancing UI with React.js.
Adding recommendation system for best property options.

## Contributing

Contributions are welcome! Please fork this repository and create a pull request.

📜 License

This project is licensed under the MIT License.
