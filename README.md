# ✈️ Flight Delay Prediction using Machine Learning

This project predicts flight delays using machine learning models. The dataset includes various features related to airline schedules, delays, and weather conditions. The model applies data preprocessing techniques, PCA, and classification algorithms to predict if a flight will be delayed.

---

## 📊 **Features & Preprocessing**
- **Missing Value Handling:** Used `SimpleImputer` to fill missing values.
- **Categorical Encoding:** Used `OneHotEncoder` to convert categorical features.
- **Feature Scaling:** Applied `StandardScaler` for normalization.
- **Dimensionality Reduction:** Used `PCA` to optimize performance.
- **Class Imbalance Handling:** Used `SMOTE` to balance the dataset.

---

## 🚀 **ML Models Used**
- **Random Forest**
- **XGBoost Classifier**
- **Logistic Regression** (for baseline comparison)

---

## 🗂 **Project Structure**
📂 Flight_Delay_Prediction │-- 📄 airline_feature.ipynb # Jupyter Notebook with full ML pipeline │-- 📄 README.md # Project documentation │-- 📄 requirements.txt # Dependencies list │-- 📂 models/ │ │-- flight_delay_model.pkl # Trained ML model │ │-- imputer.pkl # Missing values handler │ │-- encoder.pkl # Categorical encoder │ │-- scaler.pkl # Feature scaler │ │-- pca.pkl # PCA transformer │ │-- train_columns.pkl # Training columns reference

---

## ▶️ **How to Use**
1️⃣ Clone the repository  
```bash
git clone https://github.com/Ahmed4Mostafa/Flight_Delay_Prediction.git
cd Flight_Delay_Prediction
2️⃣ Install dependencies


pip install -r requirements.txt
3️⃣ Run the Jupyter Notebook

bash
Copy code
jupyter notebook
4️⃣ Load the saved model & make predictions

python
Copy code
import joblib
model = joblib.load('models/flight_delay_model.pkl')
📁 Dataset
The dataset used in this project was obtained from Kaggle Airline Delay Data.

Includes flight schedules, delay causes, and airline performance metrics.

## 🏆 Model Performance
| Model               | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| XGBoost             | 99.02%   | 0.89      | 0.95   | 0.92     |
| Random Forest       | 98.97%   | 0.88      | 0.96   | 0.91     |

XGBoost performed the best, achieving 99.02% accuracy.

PCA significantly improved training time and generalization.

🤝 Contributing
Feel free to open an issue or a pull request if you’d like to improve the project.

🌟 Let's Connect
🔗 LinkedIn: https://www.linkedin.com/in/ahmed-mostafa-9aab05305/

🏆 Kaggle: https://www.kaggle.com/ahmed4mostafa

💻 GitHub: https://github.com/Ahmed4Mostafa

🚀 Star the repo if you found it helpful! ⭐

---
