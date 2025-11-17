========================= COPY FROM HERE =========================

<!-- -------------------------------------------------------------- -->
<!-- 🔷 PREMIUM FUTURISTIC HEADER -->
<!-- -------------------------------------------------------------- -->

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Space+Grotesk&size=35&duration=2600&pause=700&color=00C6FF&center=true&vCenter=true&width=950&lines=Heart+Disease+Prediction+Application;End-to-End+ML+Pipeline+with+MLOps;Streamlit+%7C+Docker+%7C+CI%2FCD+Ready;Developed+by+Sriharsha+K" />

<br>

<!-- Clean Premium Badges -->
<img src="https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-Web%20App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/Scikit--Learn-ML%20Model-F89500?style=for-the-badge&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-Containerized-2391E6?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/MLOps-Pipeline-000000?style=for-the-badge&logo=mlflow&logoColor=white" />
<img src="https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2671E5?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/License-MIT-2ECC71?style=for-the-badge" />

</div>

---

# 🔷 Overview

This repository contains a **production-style Heart Disease Prediction Application** that uses real medical attributes to estimate the likelihood of heart disease.  
It includes:

- 🚀 A fully working **Streamlit UI**  
- 📦 A modular **ML pipeline**  
- ⚙️ **Data preprocessing** with scaling & encoding  
- 🤖 **Random Forest** trained model  
- 🧱 **Artifact storage** for models & transformers  
- 🔐 **Logging** for complete traceability  
- 🐳 **Docker containerization**  
- 🔄 **CI/CD workflow-ready** (GitHub Actions templates included)

Built following **clean architecture and MLOps standards**, this project is suitable for resumes, ML portfolios, college projects, and real deployment demos.

---

# 🔷 Features (Professionally Enhanced)

### **Single Patient Prediction**
- Input medical features  
- Get instant ML-based risk prediction  

### **Batch CSV Prediction**
- Upload CSV  
- Entire file is processed & predictions exported  

### **Model Explainability**
- Feature importance visualizations  
- Medical interpretation  

### **Comprehensive Logging**
- All actions logged with timestamps  

### **Production-Ready Architecture**
- Clean modular design  
- Scalable & maintainable folders  

---

# 🔷 Project Structure

```
Heart_Disease_Pred_MLOPS/
│
├── app.py                           # Streamlit interface
├── main.py                          # Main controller
├── data_processing.py               # Data preprocessing pipeline
├── ml_functions.py                  # Model training & prediction
├── helper_functions.py              # Logging & utilities
│
├── data/                            # Data directories
│   ├── raw/
│   ├── processed/
│   └── output/
│
├── artifacts/                       # Model artifacts
│   ├── heart_disease_model.pkl
│   └── data_processing_pipeline.pkl
│
├── logs/                            # Logging output
├── Dockerfile                       # Docker setup
├── requirements.txt                 # Dependencies
├── .env.example                     # Env template
└── .github/workflows/               # CI/CD pipeline templates
```

---

# 🔷 Getting Started

## **Prerequisites**
- Python 3.8+  
- pip / conda  
- Optional: Docker

## **Installation**

### Clone the repo
```bash
git clone https://github.com/SRIHARSHA-BHARADWAJ/Heart_Disease_Pred_MLOPS.git
cd Heart_Disease_Pred_MLOPS
```

### Create virtual environment
```bash
python -m venv venv
```

### Activate env  
Windows:
```bash
venv\Scripts\activate
```
Mac/Linux:
```bash
source venv/bin/activate
```

### Install dependencies
```bash
pip install -r requirements.txt
```

### Create .env file
```
DATA_DIR=data
ARTIFACTS_DIR=artifacts
LOGS_DIR=logs
```

---

# 🔷 Running the Application

### Train the model
```bash
python main.py
```

### Launch Streamlit UI
```bash
streamlit run app.py
```

Visit:  
**http://localhost:8501**

---

# 🔷 Usage Guide

### **Single Prediction**
1. Open sidebar → "Single Prediction"  
2. Enter patient data  
3. Click **Predict**  

### **Batch Prediction**
1. Open sidebar → "Batch Prediction"  
2. Upload CSV  
3. Download processed output  

### **Model Explanation**
- Feature importance  
- Clinical interpretation  

---

# 🔷 Technical Details

### **Model**
- Random Forest Classifier  
- Handles mixed numerical & categorical data  

### **Preprocessing**
- StandardScaler  
- One-Hot Encoding  
- Pipeline serialized as `.pkl`

### **Metrics**
- Accuracy: 85%  
- Precision: 84%  
- Recall: 86%  
- F1-score: 85%  
- ROC AUC: ~0.90  

### **Expected Data Format**
| Feature | Description | Type |
|---------|-------------|------|
| age | Age in years | Numeric |
| sex | 1=Male, 0=Female | Binary |
| cp | Chest pain type | Categorical |
| trestbps | Resting BP | Numeric |
| chol | Serum cholesterol | Numeric |
| fbs | Fasting blood sugar | Binary |
| restecg | ECG results | Categorical |
| thalach | Max heart rate | Numeric |
| exang | Exercise induced angina | Binary |
| oldpeak | ST depression | Numeric |
| slope | Slope | Categorical |

---

# 🔷 Model Performance Summary

- High precision & recall  
- Suitable for educational & demo purposes  
- Robust on structured medical datasets  

---

# 🔷 MLOps — CI/CD Pipeline (GitHub Actions)

### Includes templates for:
- Docker build  
- Automated testing  
- Deployment on Render  
- Versioned image pushes  

**Secrets needed:**
- DOCKER_USERNAME  
- DOCKER_PASSWORD  
- RENDER_DEPLOY_HOOK  

### Pipeline Workflow
1. Push to main  
2. CI builds + tests  
3. Docker image built  
4. Auto-push to Docker Hub  
5. Render auto-deploys latest image  

---

# 🔷 Future Improvements

- SHAP / LIME explainability  
- Drift monitoring alerts  
- Automated retraining  
- Advanced Streamlit dashboards  
- JWT authentication  
- Model versioning  
- AB testing support  

---

# 🔷 License  
This project is licensed under the **MIT License**.

---

# 🔷 Maintainer

**Name:** Sriharsha K  
**Email:** sriharsha.ai22@bmsce.ac.in  
**GitHub:** https://github.com/SRIHARSHA-BHARADWAJ  

---

========================= COPY UNTIL HERE =========================
