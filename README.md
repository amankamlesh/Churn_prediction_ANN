🏦 Customer Churn Prediction

This project is a machine learning web application built with Streamlit to predict customer churn in a bank. It uses a trained deep learning model (model.h5) to estimate the probability of a customer leaving the bank based on demographic and financial features.

🚀 Features

Interactive web interface using Streamlit

Input fields for customer details (credit score, age, balance, tenure, etc.)

Preprocessing with LabelEncoder, OneHotEncoder, and StandardScaler

Trained deep learning model with TensorFlow/Keras

Outputs the churn probability and a decision (Likely to Churn / Not Likely to Churn)

🌐 Live Demo

👉 Try the deployed app here: Customer Churn Prediction

📂 Project Structure
├── app.py                  # Streamlit web app
├── experiments.ipynb       # Model training & experiments
├── prediction.ipynb        # Prediction testing
├── model.h5                # Trained deep learning model
├── onehot_encoder_geo.pkl  # Saved OneHotEncoder for Geography
├── label_encoder_gender.pkl # Saved LabelEncoder for Gender
├── scaler.pkl              # Saved StandardScaler
├── requirements.txt        # Project dependencies

⚙️ Installation

Clone this repository:

git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction


Create a virtual environment and activate it:

python -m venv venv
source venv/bin/activate  # For Linux/Mac
venv\Scripts\activate     # For Windows


Install dependencies:

pip install -r requirements.txt

▶️ Usage

Run the Streamlit app locally:

streamlit run app.py


Open the link shown in the terminal (usually http://localhost:8501) in your browser.

📊 Example Workflow

Select customer Geography and Gender

Enter Credit Score, Age, Balance, Tenure, etc.

Click Submit to see the churn probability.

The app will display:

Churn Probability (0–1)

Prediction Result:

✅ Not Likely to Churn

⚠️ Likely to Churn

📦 Requirements

See requirements.txt
:

TensorFlow 2.20

Streamlit

Pandas, NumPy, Scikit-learn

Matplotlib

🧪 Model Training

experiments.ipynb contains model development and training experiments.

The trained model is saved as model.h5.

Encoders and scaler are stored as .pkl files for consistent preprocessing.

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you’d like to change.

📜 License

This project is licensed under the MIT License.
