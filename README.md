# ⚡ Power Consumption Prediction

This project aims to predict power consumption in **Zone 3 of Agadir** using machine learning techniques. The dataset contains historical data, including weather conditions, temperature, and emissions, to help forecast energy usage.

---

## 📁 Project Structure

Power-Consumption-Prediction/
│
├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks for EDA and model experimentation
├── scripts/ # Python scripts for model pipeline
│ └── power_prediction.py
├── models/ # Saved trained models
├── requirements.txt # List of Python dependencies
├── README.md # Project overview (this file)
└── .gitignore # Files to ignore in Git


---

## 🧠 Objective

To build and evaluate machine learning models that accurately forecast electricity consumption using features like:
- Temperature
- Emissions
- Humidity
- Wind speed
- Past consumption trends

---

## 🛠️ Tech Stack

- **Python** (pandas, NumPy, scikit-learn, XGBoost)
- **Jupyter Notebook**
- **Matplotlib & Seaborn** for visualization
- **Joblib** or **Pickle** for model saving

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sanjayjoshi15/Power-Consumption-Prediction.git
   cd Power-Consumption-Prediction


📊 Model Evaluation
Models are evaluated using:

RMSE (Root Mean Squared Error)

MAPE (Mean Absolute Percentage Error)

R² Score
