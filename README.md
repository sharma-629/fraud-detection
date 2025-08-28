# 💳 Fraud Detection Prediction App

This project is a **Fraud Detection System** that predicts whether a financial transaction is fraudulent or not.  
It uses a **Machine Learning pipeline** trained on transaction data.

---

## 📂 Project Structure

```
fraud-detection/
│── fraud_detection.py          # Streamlit app for prediction
│── analysis_model.ipynb        # Data analysis and model training notebook
│── requirements.txt            # Dependencies
│── README.md                   # Project documentation
```

⚠️ Large files (Dataset & Trained Model) are not stored in this repo due to GitHub size limits.

- **Dataset** 👉 [Download Here](https://drive.google.com/your-dataset-link)  
- **Trained Model (.pkl)** 👉 [Download Here](https://drive.google.com/your-model-link)  

---

## 🚀 How to Run the App

### 1. Clone the Repository
```bash
git clone https://github.com/sharma-629/fraud-detection.git
cd fraud-detection
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

*(Create a `requirements.txt` with: `streamlit pandas scikit-learn joblib`)*

### 3. Place Dataset & Model
- Download the dataset and model files from the links above.  
- Put them inside the project folder.

### 4. Run Streamlit App
```bash
streamlit run fraud_detection.py
```

---

## 📊 Features

- User inputs transaction details via a **Streamlit web app**.
- Predicts whether a transaction is **Fraud (1)** or **Not Fraud (0)**.
- Machine Learning pipeline trained on financial transaction dataset.

---

## 📸 Screenshots (Optional)
_Add screenshots of your app UI here._

---

## 🛠️ Tech Stack

- **Python 3.8+**
- **Pandas, Scikit-learn, Joblib**
- **Streamlit** (for web app UI)

---

## ✨ Future Improvements
- Add real-time transaction monitoring  
- Deploy on **Streamlit Cloud / Heroku / AWS**  
- Improve model accuracy with advanced algorithms  

---

## 👨‍💻 Author
**Sachin Sharma**  
🔗 [GitHub](https://github.com/sharma-629) | [LinkedIn](https://www.linkedin.com/)  

---
