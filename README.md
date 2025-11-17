=========================== COPY FROM HERE ===========================

<div align="center">

<!-- Sleek Animated Heading -->
<img src="https://readme-typing-svg.herokuapp.com?font=Inter&weight=600&size=32&duration=2500&pause=700&color=00A3FF&center=true&vCenter=true&width=900&lines=Heart+Disease+Prediction+System;Machine+Learning+%7C+MLOps+%7C+Streamlit+%7C+Docker;By+Sriharsha+K" />

<br>

<!-- Professional Badges -->
<img src="https://img.shields.io/badge/Python-3.10-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-Application-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=flat-square&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/MLOps-Pipeline-000000?style=flat-square&logo=mlflow&logoColor=white" />
<img src="https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" />

</div>

---

## 📌 Overview

This project is an **end-to-end, production-ready Heart Disease Prediction System** built with:

- Machine Learning (**Random Forest**)
- Streamlit web application
- Modular MLOps pipeline  
- Logging & artifact tracking  
- Docker containerization  
- (Optional) CI/CD workflows via GitHub Actions  

It supports both:

- **Single-patient prediction**
- **Batch CSV prediction**

Purposefully designed to follow clean architecture principles and production standards.

---

## 📂 Project Structure

```
Heart_Disease_Pred_MLOPS/
│
├── app.py                      # Streamlit UI
├── main.py                     # Entry point / pipeline orchestrator
├── data_processing.py          # Preprocessing pipeline
├── ml_functions.py             # Training & inference logic
├── helper_functions.py         # Logging + utility helpers
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── output/
│
├── artifacts/
│   ├── heart_disease_model.pkl
│   └── data_processing_pipeline.pkl
│
├── logs/                       # Application logs
├── Dockerfile
├── requirements.txt
├── .env.example
└── .github/workflows/          # (CI/CD workflows – disabled)
```

---

## ⚙️ ML Pipeline

```
User Input / CSV
       ↓
Data Preprocessing
       ↓
Feature Encoding & Scaling
       ↓
Random Forest Model
       ↓
Prediction Output
```

---

## 🧠 Model Performance

| Metric     | Score |
|------------|--------|
| Accuracy   | 85%    |
| Precision  | 84%    |
| Recall     | 86%    |
| F1 Score   | 85%    |

---

## ▶️ Running the Application

### **Install dependencies**
```bash
pip install -r requirements.txt
```

### **Run training**
```bash
python main.py
```

### **Launch Streamlit app**
```bash
streamlit run app.py
```

---

## 🐳 Docker Support

### **Build image**
```bash
docker build -t heart-app .
```

### **Run container**
```bash
docker run -p 8501:8501 heart-app
```

---

## 🚀 Future Enhancements

- Model explainability (SHAP/LIME)  
- Model drift monitoring  
- Automated retraining  
- Authentication for clinical use  
- Advanced dashboards  
- Deep learning extension  

---

## 👨‍💻 Maintainer

**Name:** Sriharsha K  
**Email:** sriharsha.ai22@bmsce.ac.in  
**GitHub Username:** SRIHARSHA-BHARADWAJ  
GitHub URL: https://github.com/SRIHARSHA-BHARADWAJ  

---

## 📄 License  
Released under the **MIT License**. See `LICENSE` for details.

=========================== COPY UNTIL HERE ===========================
