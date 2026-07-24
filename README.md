# **Customer Churn Predictor – Deep Learning & Streamlit**  

🚀 **Live Demo: https://customer-churn-predictor-arm6exmdpzi47rukyew3km.streamlit.app/  

## 📌 **Project Overview**  
Customer churn is a critical business problem where companies lose customers over time. This project uses **Deep Learning** to predict whether a customer is likely to churn based on historical data. The model has been deployed using **Streamlit**, allowing businesses to interactively check churn probability and take proactive retention measures.  

## 🔍 **Features**  
✅ Predicts **customer churn probability** using a trained Deep Learning model.  
✅ **Interactive Web App** built with Streamlit for real-time predictions.  
✅ **Preprocessing Pipelines** for Label Encoding, One-Hot Encoding, and Feature Scaling.  
✅ **Model Deployment** using TensorFlow, Streamlit, and Pickle for efficient inference.  
✅ **User-friendly UI** with dropdowns, sliders, and input fields for seamless data entry.  

## 🛠 **Technologies Used**  
- **Machine Learning & Deep Learning:** TensorFlow/Keras, Scikit-learn  
- **Web Framework:** Streamlit  
- **Data Processing:** Pandas, NumPy  
- **Model Deployment:** Pickle, Streamlit  
- **Frontend UI:** Streamlit Widgets (Dropdowns, Sliders, Number Inputs)  

## 📊 **How It Works**  
1. **User Inputs Customer Data** → Via interactive UI (Credit Score, Age, Balance, etc.).  
2. **Data Preprocessing** → Categorical encoding, feature scaling using pre-trained encoders.  
3. **Prediction by Neural Network** → Deep Learning model predicts churn probability.  
4. **Result Display** → The app shows the likelihood of churn and provides insights.  

## 🚀 **Installation & Usage**  
### **1️⃣ Clone the Repository**  
```bash
git clone https://github.com/your-github-username/customer-churn-predictor.git
cd customer-churn-predictor
```

### **2️⃣ Install Dependencies**  
```bash
pip install -r requirements.txt
```

### **3️⃣ Run the Streamlit App**  
```bash
streamlit run app.py
```

## 📂 **Project Structure**  
```
📦 customer-churn-predictor
├── 📜 app.py                 # Streamlit Web App
├── 📜 experiments.ipynb      # Model Training & Experiments
├── 📜 prediction.ipynb       # Prediction & Evaluation
├── 📜 model.h5               # Trained Deep Learning Model
├── 📜 scaler.pkl             # StandardScaler for numerical features
├── 📜 label_encoder_gender.pkl  # LabelEncoder for Gender
├── 📜 onehot_encoder_geo.pkl    # OneHotEncoder for Geography
├── 📜 requirements.txt       # Dependencies
└── 📜 README.md              # Project Documentation
```

## 🎯 **Future Enhancements**  
🔹 Add **Explainable AI (XAI)** techniques to interpret model decisions.  
🔹 Enhance **visualizations** for better insights on churn factors.  
🔹 Deploy on **cloud platforms** like AWS/GCP for large-scale use.  

---

### 📢 **Contributions & Feedback**  
If you have any suggestions or improvements, feel free to **fork the repo** and submit a PR or raise an issue.  

⭐ **If you like this project, give it a star!** ⭐  

---
