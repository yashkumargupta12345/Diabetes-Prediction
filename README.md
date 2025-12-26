# 🩺 Diabetes Prediction Web App (Machine Learning + Streamlit)

A full-stack ML project that predicts whether a person is diabetic based on medical diagnostic input parameters.  
This project includes **model training**, **pickle-based persistence**, and a **Streamlit interactive web interface**, deployed online using **Streamlit Cloud**.

👉 **Live Demo:** https://diabetes-prediction8.streamlit.app/

---

## 🚀 Features

- Predicts diabetes using ML (Binary Classification)
- Trained using the **PIMA Diabetes Dataset**
- **SVM Classifier** used for model training
- Interactive UI built using **Streamlit**
- Input values accepted manually
- Real-time prediction displayed
- Fully deployed & publicly accessible

---

## 🧠 Machine Learning Workflow

| Step | Description |
|------|-------------|
| 📥 Data Source | PIMA Diabetes Dataset |
| ⚙️ Preprocessing | Scaling, Cleaning, Train-Test Split |
| 🧩 Model Training | Support Vector Machine Classifier |
| 📦 Model Save | Stored using Pickle (`trained_model.sav`) |
| 🔁 Deployment | Streamlit Cloud |

---

## 📂 Project Structure

📁 diabetes-prediction
│
├── diabetes_prediction_web_app.py # Streamlit main app
├── trained_model.sav # Pickle ML model
├── requirements.txt # Required Python libraries
└── README.md


---

## 🧪 Input Parameters

| Feature | Description |
|---------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic BP |
| SkinThickness | Triceps skin fold thickness |
| Insulin | Serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes Pedigree Score |
| Age | Age of person |

---

## 🧾 How to Run Locally

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/<your-username>/diabetes-prediction.git
cd diabetes-prediction
```

2️⃣ Create Virtual Environment (recommended)
conda create -n ml python=3.10
conda activate ml


3️⃣ Install Dependencies
pip install -r requirements.txt


4️⃣ Run Web App
streamlit run diabetes_prediction_web_app.py


🌍 Deployment (Streamlit Cloud)
This app is deployed using Streamlit Cloud.


🛠 Tech Stack

Python
Scikit-Learn
NumPy
Streamlit
Pickle
GitHub
Streamlit Cloud

<img width="744" height="727" alt="Screenshot 2025-12-26 at 11 05 26 PM" src="https://github.com/user-attachments/assets/0e70347a-cc91-4f63-92b2-26ae2fe0bce4" />


🤝 Contributing
PRs, suggestions, and improvements are welcome!


📧 Contact

👤 Yash Kumar Gupta
📮 for collaboration / internship

