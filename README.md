#🧑‍⚕️ Fetal Health Prediction using CTG

## 🚀 Live Demo  
[View the app on Streamlit Cloud](https://fetal-health-prediction-oebsywmnbgtsoc6opipfml.streamlit.app/)
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
