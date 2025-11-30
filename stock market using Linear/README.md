
# ✅ **README.md — FULL COPY-PASTE VERSION**

```markdown
# 📈 Stock Market Prediction Web App (Streamlit)

This project is a **Streamlit-based Stock Market Prediction Dashboard** that performs:

- **Regression** → Predict next-day stock closing price  
- **Classification** → Predict market movement (📈 Up / 📉 Down)

The app uses pre-trained machine learning pipelines built with Scikit-Learn.

---

## 🚀 Features

### 🔹 Regression (Price Prediction)
Predict the next day’s closing price using:
- Open  
- High  
- Low  
- Close  
- Volume  

### 🔹 Classification (Direction Prediction)
Predict stock direction (Up/Down) using:
- Open  
- High  
- Low  
- Close  
- Volume  
- Return  
- MA5  
- MA10  
- MA_Crossover  
- Prev_Close  

---

## 📁 Project Structure

```

📦 Stock-Predictor
│── app.py                      # Streamlit App
│── regression_pipeline.pkl     # Regression Model (not uploaded)
│── classification_pipeline.pkl # Classification Model (not uploaded)
│── README.md

```

---

# ⚠️ Model Files (.pkl) Not Included

GitHub does **NOT** allow large files (50MB+).  
Therefore, these files are **excluded**:

```

regression_pipeline.pkl
classification_pipeline.pkl

```

### 📌 Add These Files Manually (Local Setup)

Download or copy your model files and place them **in the same folder as `app.py`**:



stock market using Linear/
│── .conda/
│── data/
│── web app/
│      │── app.py
│      │── classification_pipeline.pkl
|      │── regression_pipeline.pkl     # create your own   cant upload because of size
│
│── classification.ipynb
│── pipeline.ipynb
│── README.md
│── regression.ipynb





### 📌 Recommended Storage Options (Instead of GitHub)
Use one of these to host model files:

- Google Drive  
- Dropbox  
- OneDrive  
- AWS S3  
- HuggingFace Model Hub  

---

# ▶️ Running the Streamlit App

Install required packages:

```bash
pip install streamlit pandas joblib scikit-learn
````

Run the project:

```bash
streamlit run app.py
```

Access in browser:

```
http://localhost:8501
```

---

## 🧠 Machine Learning Pipelines

### Regression Pipeline

Includes:

* Feature scaling
* Preprocessing
* RandomForest / XGBoost (based on training)

### Classification Pipeline

Includes:

* Moving averages
* Technical indicators
* Gradient Boosting / Logistic Regression

Models were exported using:

```python
joblib.dump(pipeline, "regression_pipeline.pkl")
joblib.dump(pipeline, "classification_pipeline.pkl")
```


## 🏁 Summary

This is a ready-to-use Streamlit application for **stock price prediction** and **stock direction classification**, powered by machine learning pipelines.
Add your `.pkl` models, run the app, and you're good to go.

---
