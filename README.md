# 🧠📊 AI-Powered Sales Forecasting Web Application

A Flask-based AI mini-project that uses Machine Learning to predict future sales based on historical data. Built as part of academic coursework, this project demonstrates the integration of data preprocessing, ML modeling, and web deployment.

---

## 🚀 Features

- 📈 Predicts future sales based on input parameters
- 📊 Utilizes real-world **Global Superstore Dataset**
- 🧠 Implements Machine Learning models like **Linear Regression** and **Random Forest**
- 🌐 Built with **Flask** for seamless web-based interaction
- 🔍 Visualizes key metrics and forecasts using graphs

---

## 🧠 Technologies Used

- *Python*
- *Flask*
- *Pandas & NumPy*
- *Scikit-learn*
- *Matplotlib / Seaborn*
- *HTML & CSS (Jinja Templates)*

---

## 📁 Project Structure

AI-Sales-Prediction/   
│   
├── app.py # Flask app entry point   
├── templates/ # HTML templates for the web interface   
│ └── index.html   
│ └── result.html   
├── static/ # CSS/JS files   
│ └── style.css   
├── model/ # Trained ML model(s)   
│ └── sales_model.pkl   
├── data/ # Dataset (Global Superstore)   
│ └── Global_Superstore.csv   
├── requirements.txt   
└── README.md  

---

## 🧪 How to Run Locally

1. **Clone the repository:**

    git clone https://github.com/Harshan07-web/AI-Sales-Prediction.git
    cd AI-Sales-Prediction
   
2. **Create a virtual environment:**

    python -m venv venv
    source venv/bin/activate   
# On Windows: venv\Scripts\activate

3. **Install dependencies:**

    pip install -r requirements.txt

4. **Run the Flask app:**

    python app.py

---

## PS

-Dataset used: Global Superstore Dataset  
-All model files are pre-trained and included.  
-Feel free to tweak the model or frontend to suit your requirements!
