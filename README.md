

<!-- -------------------------------------------------------------- -->
<!-- 🚀 ULTRA-PREMIUM FUTURISTIC HEADER (FINAL MODE V2) -->
<!-- -------------------------------------------------------------- -->

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Syne&weight=700&size=34&duration=2500&pause=800&color=00D0FF&center=true&vCenter=true&width=1000&lines=Heart+Disease+Prediction+System;End-to-End+Machine+Learning+Pipeline;Streamlit+%7C+MLOps+%7C+Docker+Ready;Developed+by+Sriharsha+K" />

<br>

<!-- Minimal Premium Badges -->
<img src="https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-Web%20App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/Scikit--Learn-ML%20Model-F89C2E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/MLOps-Pipeline-000000?style=for-the-badge&logo=mlflow&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2552CC?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/License-MIT-27AE60?style=for-the-badge" />

<br><br>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/clean.svg" width="100%"/>

</div>

---

# 📌 **Project Overview**

A clean, modular, and production-focused **Heart Disease Prediction Application** built using a complete **Machine Learning + MLOps** workflow.

This project integrates:

- A professional **Streamlit** user interface  
- A fully modular **data preprocessing pipeline**  
- A trained **Random Forest model**  
- Structured **logging**, **artifacts**, and **environment handling**  
- Containerization with **Docker**  
- CI/CD-ready workflow templates (GitHub Actions)

Designed with **clean architecture principles**, suitable for real-world ML deployment, academic showcases, and portfolio-level presentation.

---

# 📋 **Features**

### ✔ Individual Patient Prediction  
Enter medical details → get instant ML prediction  

### ✔ Batch CSV Prediction  
Upload CSV → predictions generated for all rows  

### ✔ Model Explainability  
Feature importance insights  
Medical reasoning for decisions  

### ✔ Comprehensive Logging  
Every step — preprocessing, inference, batch jobs — fully logged  

### ✔ Modular, Maintainable Codebase  
Clean structure aligned with MLOps best practices  

---

# 🏗 **Project Structure**

```
Heart_Disease_Pred_MLOPS/
│
├── app.py                           # Streamlit interface
├── main.py                          # Main ML pipeline controller
├── data_processing.py               # Data preprocessing pipeline
├── ml_functions.py                  # ML training & prediction logic
├── helper_functions.py              # Logging + utility functions
│
├── data/                            # Input/Output folders
│   ├── raw/
│   ├── processed/
│   └── output/
│
├── artifacts/                       # Saved model + pipeline
│   ├── heart_disease_model.pkl
│   └── data_processing_pipeline.pkl
│
├── logs/                            # Application logs
├── Dockerfile                       # Docker build file
├── requirements.txt                 # Dependencies
├── .env.example                     # Environment variable template
└── .github/workflows/               # CI/CD workflow (optional)
```

---

# 🔧 **Technical Details**

### **Model**
- Random Forest Classifier  
- Handles mixed categorical & numerical data  

### **Preprocessing**
- StandardScaler for numeric features  
- One-hot encoding for categorical features  
- Pipeline serialized with pickle  

### **Metrics**
- Accuracy: ~85%  
- Precision: ~84%  
- Recall: ~86%  
- F1-score: ~85%  
- ROC AUC: ~0.90  

---

# 📊 **Expected Data Format**

| Feature | Description | Type |
|--------|-------------|------|
| age | Age in years | Numeric |
| sex | 1=Male, 0=Female | Binary |
| cp | Chest Pain Type | Categorical |
| trestbps | Resting Blood Pressure | Numeric |
| chol | Cholesterol Level | Numeric |
| fbs | Fasting Blood Sugar | Binary |
| restecg | ECG Result | Categorical |
| thalach | Max Heart Rate | Numeric |
| exang | Exercise Angina | Binary |
| oldpeak | ST Depression | Numeric |
| slope | Slope of ST Segment | Categorical |

---

# 📈 **Model Performance Summary**

- High recall for heart disease positive cases  
- Stable and reliable performance  
- Balanced precision-recall relationship  

---

# 🛠 **MLOps: CI/CD Pipeline Overview**

### Workflow Includes:
- Docker image building  
- Automated testing  
- Deployment triggers for platforms like Render  
- Push-to-DockerHub pipeline  

### Secrets Required:
- `DOCKER_USERNAME`  
- `DOCKER_PASSWORD`  
- `RENDER_DEPLOY_HOOK`  

### Pipeline Logic:
```
Push to main 
→ Build pipeline
→ Create Docker image
→ Push to Docker Hub
→ Trigger Render Update (Optional)
```

---

# 🔮 **Future Enhancements**

- SHAP / LIME model explainability  
- Error and drift monitoring dashboards  
- A/B testing for ML models  
- Automated retraining workflows  
- Authenticated multi-user application  
- Cross-validation enhancements  
- Advanced visualization UI  

---

# 📝 **License**

This project is licensed under the **MIT License**.

---

# 📞 **Contact**

**Maintainer:** Sriharsha K  
**Email:** sriharsha.ai22@bmsce.ac.in  
**GitHub:** https://github.com/SRIHARSHA-BHARADWAJ  


