#🧑‍⚕️ Fetal Health Prediction using CTG

## 🚀 Live Demo  
[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://health-prediction-of-fetus-using-ctg-lkvzskmtejgk4yckd3ywue.streamlit.app/)

---

## 📌 Project Overview  
This project predicts the **health condition of a fetus** using **Cardiotocography (CTG)** data.  
It leverages **machine learning models** to classify fetal health into categories such as *Normal, Suspect, and Pathological*, based on various input parameters.  

The system provides:  
- A **Streamlit web app** for real-time predictions.  
- **Batch prediction support** for multiple records.  
- A secure login system for users.  

---

## ✨ Features  
✅ User authentication (Login / Register)  
✅ Single prediction via form inputs  
✅ Batch prediction via file upload  
✅ Multiple ML models (Random Forest, Gradient Boosting, SVM, Neural Network)  
✅ Interactive UI built with **Streamlit**  

---

## 🖼️ Project Preview  
![App Screenshot](screenshot.png)

*(Replace `screenshot.png` with the actual screenshot filename in your repo)*  

---

## 🛠️ Tech Stack  
- **Frontend & Deployment**: Streamlit  
- **Backend & ML**: Python, Scikit-learn, TensorFlow/Keras  
- **Data Handling**: Pandas, NumPy  
- **Model Storage**: Joblib, Pickle  
- **Visualization**: Matplotlib, Seaborn  
- **Database**: SQLite  

---

## 📊 Dataset  
The project uses the **Fetal Health dataset**, which contains Cardiotocography features like:  
- Baseline Value  
- Accelerations  
- Fetal Movement  
- Uterine Contractions  
- Decelerations (Light, Severe, Prolonged)  
- Short/Long Term Variability  
- Histogram features  

---

## ⚙️ Installation (Run Locally)  

1. **Clone the repo**  
```bash
# Clone the repo
git clone https://github.com/rajnandanik/fetal-health-prediction.git
cd fetal-health-prediction
