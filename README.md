📱 Phone Price Prediction & Analytics Dashboard

An interactive web application that combines machine learning-based mobile phone price prediction with an analytics dashboard for exploring phone specifications, brands, and price trends.

🚀 "Live Demo" (https://phone-price-prediction-dashboard-b60vmnak0.vercel.app/) · 💻 "GitHub Repository" (https://github.com/balachandradas/phone-price-prediction-dashboard)

📊 Overview

This project extends an existing phone price prediction application with an interactive analytics dashboard and an improved user experience. It brings phone price estimation and data exploration together in one web application.

✨ Features

- 📱 Phone Price Prediction — Estimate mobile phone prices based on hardware specifications.
- 📊 Interactive Analytics Dashboard — View dataset summaries and explore phone data.
- 🏷️ Brand-wise Price Analysis — Compare average prices across phone brands.
- 🧠 RAM vs. Price Analysis — Explore the relationship between RAM capacity and phone prices.
- 📈 Price Distribution — Visualize how phone prices are distributed across the dataset.
- 🎛️ Interactive Interface — Navigate between the dashboard and prediction form.
- 📱 Responsive Design — Designed for convenient use across different screen sizes.

🛠️ Tech Stack

Technology| Purpose
Python| Backend and prediction logic
FastAPI| Prediction API
Scikit-learn| Machine learning
HTML5| Web page structure
CSS3| Styling and responsive interface
JavaScript| Dashboard interactions and charts
JSON| Phone dataset
Vercel| Web application deployment

⚙️ How It Works

1. Explore phone statistics and visualizations on the analytics dashboard.
2. Open the prediction page and enter phone specifications.
3. The frontend sends the specification data to the prediction API.
4. The trained machine learning model estimates the phone price.
5. The predicted result is displayed in the web interface.

🌐 Live Application

"Open Phone Price Prediction & Analytics Dashboard" (https://phone-price-prediction-dashboard-b60vmnak0.vercel.app/)

📁 Project Structure

phone-price-prediction-dashboard/

├── api/

├── models/

├── index.html

├── main.py
├── phone_dataset.json
├── requirements.txt
├── vercel.json
├── DEPLOYMENT_GUIDE.md
└── README.md

💻 Run Locally

Prerequisites

- Python 3.8 or later
- pip (Python package manager)

Installation

1. Clone the repository

git clone https://github.com/balachandradas/phone-price-prediction-dashboard.git
cd phone-price-prediction-dashboard

2. Create a virtual environment

python -m venv venv

3. Activate the environment

Windows:

venv\Scripts\activate

macOS/Linux:

source venv/bin/activate

4. Install dependencies

pip install -r requirements.txt

5. Start the application

Use the startup command specified in "DEPLOYMENT_GUIDE.md" and ensure the required model files are available.

🎯 Project Objectives

- Apply machine learning to a practical phone price prediction problem.
- Present dataset insights through interactive visualizations.
- Integrate a prediction model with a web-based interface.
- Improve the usability of a machine learning application.

🤝 Acknowledgment

This project builds upon an original phone price prediction application created by a friend. I acknowledge the original project foundation and have continued developing my version with an analytics dashboard, interface improvements, and related enhancements.

#Author

Balachandradas K P
---

Built as a hands-on learning project to explore machine learning and web application development.
