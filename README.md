# 🚖 Uber Rides Prediction - ML Model Web App

This project is a simple **machine learning web application** built using **Flask**. It predicts the number of Uber rides based on input features such as price, population, income, and parking cost.

> 🧠 The model used in this project is sourced and adapted from [Thirumurugan240](https://github.com/Thirumurugan240)'s original work and integrated into a modern web app.

---

## 📍 Live Demo

> Run locally using the instructions below.

---

## 🛠 Tech Stack

- **Python** (Model & Backend)
- **Flask** (Web Framework)
- **Jupyter Notebook** (Model Training)
- **HTML/CSS** (Frontend)

---

## 📁 Folder Structure

Uber-prediction-ML-model/
│
├── MLmodel.ipynb # Notebook to train the model
├── model.pkl # Trained model saved with pickle
├── app.py # Flask application script
├── templates/
│ └── index.html # Web UI template
├── static/
│ └── style.css # Styling for the UI
├── requirements.txt # All required packages
└── README.md # You're reading it!

yaml
Copy
Edit

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/AbiVarsanP/Uber-prediction-ML-model.git
cd Uber-prediction-ML-model
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Train the ML Model
Open the notebook in Jupyter and run all the cells:

bash
Copy
Edit
jupyter notebook MLmodel.ipynb
This will generate model.pkl.

4. Run the Flask App
bash
Copy
Edit
python app.py
5. Access the App in Browser
Open: http://127.0.0.1:5000/
