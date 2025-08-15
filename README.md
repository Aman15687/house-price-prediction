cat << 'EOF' > README.md
# 🏠 House Price Prediction App

A Machine Learning web application built with **Streamlit** to predict house prices based on user inputs.

## 📌 Features
- Data preprocessing with OneHotEncoding for categorical features
- Trains **SVR**, **Random Forest Regressor**, and **Linear Regression**
- Selects the best model based on **MAPE** (Mean Absolute Percentage Error)
- Saves the trained model & encoder using `pickle`
- Interactive **Streamlit UI** for predictions

🌐 Usage

Open the Streamlit app in your browser

Enter house details

Get an instant price prediction

📜 Requirements

pandas

scikit-learn

streamlit

matplotlib

seaborn

openpyxl
