# 🏦 Customer Churn Prediction  

[![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)](https://www.python.org/)  
[![Streamlit](https://img.shields.io/badge/Streamlit-1.0+-brightgreen.svg)](https://streamlit.io/)  
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.20-orange.svg)](https://www.tensorflow.org/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)  

A **machine learning web app** built with **Streamlit** and **TensorFlow** that predicts whether a bank customer will churn or stay.  

---

## 🌐 Live Demo  
🚀 **[Click Here to Try the App](https://amankamlesh-qybn4appeezvidh3cb7a9nn.streamlit.app/)**  

---

## ✨ Features  
✅ User-friendly Streamlit interface  
✅ Takes customer details as input  
✅ Preprocessing with saved encoders & scaler  
✅ Predicts **churn probability**  
✅ Displays a clear decision:  
- ⚠️ Likely to Churn  
- ✅ Not Likely to Churn  

---

## 📂 Project Structure  
```
📦 customer-churn-prediction
├── app.py                  # Streamlit web app
├── experiments.ipynb       # Model training & experiments
├── prediction.ipynb        # Prediction testing
├── model.h5                # Trained deep learning model
├── onehot_encoder_geo.pkl  # OneHotEncoder for Geography
├── label_encoder_gender.pkl # LabelEncoder for Gender
├── scaler.pkl              # StandardScaler
├── requirements.txt        # Dependencies
```

---

## ⚙️ Installation  

```bash
# Clone the repo
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt

# Run app
streamlit run app.py
```

---

## 📊 Example Workflow  

1️⃣ Select **Geography** & **Gender**  
2️⃣ Enter details like **Credit Score, Age, Balance, Tenure**  
3️⃣ Click **Predict**  
4️⃣ Get churn probability + final prediction  

---

## 📸 Preview  

*(Add screenshots of your deployed app here for a professional look)*  

Example:  
![App Screenshot](assets/demo.png)  

---

## 🧪 Model Training  
- Developed in `experiments.ipynb`  
- Deep learning model saved as `model.h5`  
- Encoders (`.pkl` files) ensure consistent preprocessing  

---

## 🤝 Contributing  
Contributions are welcome! Open an issue or create a PR to improve the project.  

---

## 📜 License  
This project is licensed under the **MIT License**.  
