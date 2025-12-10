# 🩺 Diabetes Detection Analysis  
A Machine Learning–powered web application that predicts the likelihood of diabetes based on user-provided medical and lifestyle information.

This project uses a **K-Nearest Neighbors (KNN)** classification model along with a **FastAPI backend** and a **Streamlit frontend** to deliver real-time predictions.

---

## Features

### Machine Learning Model
- Built using **KNN Classifier**
- Trained on diabetes-related health data
- Includes feature scaling and encoding inside the `.pkl` file
- Outputs:  
  - **Diabetic**  
  - **Not Diabetic**
 
## 🖼 Frontend Preview

![Frontend UI](https://github.com/Aman-Ptl/Diabetes-Detection-Analysis/blob/main/Frontend%20UI.png)


### Backend (FastAPI)
- Endpoint: `/predict`
- Accepts JSON input for:
  - Age  
  - Gender  
  - BMI  
  - Hypertension  
  - Heart disease  
  - Smoking history  
  - HbA1c level  
  - Blood glucose level
- Returns prediction in JSON format

### Frontend (Streamlit UI)
- User-friendly form to input health data
- Connects to the FastAPI backend for predictions
- Shows “Diabetic” or “Not Diabetic” instantly

---




