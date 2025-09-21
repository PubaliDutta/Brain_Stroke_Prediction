# 🧠 Stroke Prediction Web App  

This project is a **Machine Learning powered web application** built using **Flask** to predict the likelihood of a stroke based on user health data. The model is trained on the **[Playground Series S3E2 Dataset](https://www.kaggle.com/competitions/playground-series-s3e2/data)**.  

The web interface allows users to input personal health details (age, gender, BMI, glucose level, lifestyle, etc.), and the model will predict whether the person is **Likely** or **Not Likely** to experience a stroke.  

---

## 📂 Project Structure  

```
Stroke-Prediction/
│── app.py                        # Flask application
│── Stroke Prediction using python.ipynb  # Model training notebook
│── model_saved.joblib             # Trained ML model (saved using joblib)
│── templates_saved/
│    ├── index.html                # Input form page
│    ├── result.html               # Prediction results page
│── playground-series-s3e2.zip     # Dataset (from Kaggle)
│── README.md                      # Project documentation
```

---

## ⚙️ Installation  

1. **Clone the repository**  
   ```bash
   git clone https://github.com/your-username/stroke-prediction.git
   cd stroke-prediction
   ```

2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

   *(Make sure you have Python 3.9+ installed.)*

3. **Unzip the dataset (optional for retraining)**  
   ```bash
   unzip playground-series-s3e2.zip
   ```

---

## 🚀 Usage  

1. **Run the Flask app**  
   ```bash
   python app.py
   ```

2. **Open in your browser**  
   Go to 👉 [http://127.0.0.1:5000/](http://127.0.0.1:5000/)  

3. **Enter user details** on the form and click **Predict Stroke Likelihood**.  

4. The app will display the prediction result on a new page.  

---

## 🧑‍💻 Tech Stack  

- **Python** (Flask, Pandas, Scikit-learn, Joblib)  
- **Frontend**: HTML5, Bootstrap 5  
- **Model**: Logistic Regression with preprocessing pipeline  
- **Dataset**: [Kaggle Playground Series - Season 3, Episode 2](https://www.kaggle.com/competitions/playground-series-s3e2/data)  

---

## 📊 Features  

✔️ User-friendly web interface with form inputs  
✔️ Machine Learning model for stroke prediction  
✔️ Model trained on health-related features  
✔️ Bootstrap styling for modern UI  

---

## 📈 Future Improvements  

- Deploy on **Heroku / Render / AWS** for public access  
- Improve accuracy with **advanced ML models (Random Forest, XGBoost, Neural Nets)**  
- Add **model explainability (SHAP/LIME)**  
- Create **REST API endpoints** for integration  

---

## 🙌 Acknowledgements  

- [Kaggle Playground Series S3E2](https://www.kaggle.com/competitions/playground-series-s3e2) for the dataset  
- Scikit-learn & Flask documentation  
