🚗 Car Price Prediction Web App

This project is a Machine Learning-based Car Price Prediction web application that predicts the selling price of a car based on user-provided details. The application uses a trained ML model and a Flask backend to provide real-time predictions through a simple web interface.

📌 Project Overview

The goal of this project is to demonstrate how a Machine Learning model can be integrated into a real-world web application.
Users enter car details, and the model predicts the expected car price instantly.

🔍 Features

Predicts car price based on:

Car company

Car model

Year of purchase

Fuel type

Kilometers driven

User-friendly web interface

Dynamic dropdowns for company and car models

Real-time prediction without page reload

End-to-end ML deployment using Flask

🧠 Machine Learning Details

Algorithm used: Linear Regression

Dataset: Cleaned car price dataset

Libraries:

Pandas

NumPy

Scikit-learn

Model saved using Pickle

Features Used for Training:

company

name (car model)

year

kms_driven

fuel_type

🌐 Web Technologies Used
Backend:

Flask

Flask-CORS

Pickle

Frontend:

HTML

CSS

Bootstrap

JavaScript (AJAX)

📂 Project Structure
car-price-predictor/
│
├── static/
│   └── css/
│       └── style.css
│
├── templates/
│   └── index.html
│
├── application.py
├── LinearRegressionModel.pkl
├── cleaned_car.csv
├── README.md

▶️ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/car-price-predictor.git


Navigate to the project folder:

cd car-price-predictor


Install required libraries:

pip install flask flask-cors pandas numpy scikit-learn


Run the Flask app:

python application.py


Open your browser and go to:

http://127.0.0.1:5000/

🎯 Output

After entering the car details, the app displays:

Predicted Price: ₹ XXXXX

📚 What I Learned

Building an end-to-end Machine Learning project

Connecting ML models with Flask

Handling real-time user input

Deploying ML models in web applications

Frontend and backend integration

🚀 Future Improvements

Add more ML models (Random Forest, XGBoost)

Improve prediction accuracy

Add model evaluation metrics

Deploy the app on cloud (Heroku / Render)

🙌 Acknowledgements

This project was built for learning and practicing Machine Learning deployment and full-stack ML development.
