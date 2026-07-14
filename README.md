# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview

This project is a full-stack **House Price Prediction Application** that uses Machine Learning to estimate house prices based on property characteristics provided by the user. The application combines a **React.js frontend** with a **Flask backend**, allowing users to interact with a trained machine learning model through a simple and responsive web interface.

The project demonstrates the complete machine learning lifecycle, from data preprocessing and model training to deployment through a REST API.

---

## 🎯 Objectives

- Predict house prices using machine learning.
- Build a user-friendly web interface for real-time predictions.
- Deploy a trained model through a Flask API.
- Demonstrate full-stack integration between Machine Learning and Web Development.

---

## 🚀 Features

- Interactive web interface built with React.js
- Real-time house price prediction
- Flask REST API for serving predictions
- Pre-trained Machine Learning model
- Data preprocessing using StandardScaler
- Modular project structure
- Easy local deployment

---

# 🏗️ Project Architecture

```
                User
                  │
                  ▼
        React.js Frontend
                  │
          HTTP Request (API)
                  │
                  ▼
           Flask Backend
                  │
      Load Trained ML Model
                  │
                  ▼
      Random Forest Regressor
                  │
                  ▼
      Predicted House Price
```

---

# 📂 Project Structure

```
House-Price-Prediction/
│
├── backend/
│   ├── app.py
│   ├── model/
│   │   ├── house_price_model.pkl
│   │   └── scaler.pkl
│   ├── notebook/
│   └── requirements.txt
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── vite.config.js
│
├── README.md
├── LICENSE
└── .gitignore
```

---

# 📊 Dataset

The model was trained using a structured housing dataset containing several property-related attributes.

### Input Features

- Number of Bedrooms
- Number of Bathrooms
- Living Area (Square Feet)
- House Condition
- Number of Schools Nearby

### Target Variable

- House Price

---

# ⚙️ Data Preprocessing

The following preprocessing techniques were applied:

- Missing value handling
- Feature scaling using StandardScaler
- Data normalization
- Train-Test Split

---

# 🤖 Machine Learning Model

### Random Forest Regressor

Random Forest was selected because it:

- Handles non-linear relationships effectively
- Reduces overfitting compared to a single decision tree
- Produces stable predictions
- Works well with tabular datasets

### Model Parameters

- n_estimators = 100
- random_state = 42

---

# 📈 Model Evaluation

The model was evaluated using:

- R² Score
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)

The evaluation demonstrates the model's ability to generalize and predict house prices accurately on unseen data.

---

# 🛠️ Technologies Used

## Backend

- Python
- Flask
- Scikit-learn
- Pandas
- NumPy

## Frontend

- React.js
- Vite
- HTML
- CSS
- JavaScript

## Machine Learning

- Random Forest Regressor
- StandardScaler

---

# 🚀 Installation

## Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/House-Price-Prediction.git
```

---

## Backend Setup

```bash
cd backend
pip install -r requirements.txt
python app.py
```

The Flask server will start on:

```
http://127.0.0.1:5000
```

---

## Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

The application will run on:

```
http://127.0.0.1:5173
```

---

# 💻 How to Use

1. Open the web application.
2. Enter property details.
3. Click **Predict Price**.
4. View the predicted house price instantly.

---

# 📷 Project Screenshots

Add screenshots here:

- Home Page
- Prediction Form
- Prediction Result
- Model Workflow

---

# 📚 Skills Demonstrated

- Machine Learning
- Data Preprocessing
- Model Deployment
- Flask API Development
- React.js Development
- REST API Integration
- Python Programming
- Full Stack Development

---

# 💡 Future Improvements

- Deploy using Docker
- Cloud Deployment (AWS/Azure)
- Hyperparameter Tuning
- User Authentication
- Model Monitoring
- Explainable AI (SHAP)

---

# 👨‍💻 Author

**Manoj Ravikumarswamy**

MSc Data Science & Business Analysis

EDC Paris Business School

---

# 📄 License

This project is licensed under the MIT License.

---

# 🙏 Acknowledgements

This project was originally developed as a final-year academic project and has been enhanced as part of my Machine Learning portfolio to demonstrate end-to-end predictive analytics and full-stack deployment.