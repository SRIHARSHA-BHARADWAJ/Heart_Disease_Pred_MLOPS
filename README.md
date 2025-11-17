

<!-- -------------------------------------------------------------- -->
<!-- 🚀 PREMIUM FUTURISTIC HEADER -->
<!-- -------------------------------------------------------------- -->

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Montserrat&weight=600&size=32&duration=2600&pause=700&color=00C6FF&center=true&vCenter=true&width=1000&lines=Heart+Disease+Prediction+Application;End-to-End+Machine+Learning+%26+MLOps+Pipeline;Streamlit+%7C+Docker+%7C+CI%2FCD+Ready;Developed+by+Sriharsha+K" />

<br>

<!-- Premium Badges Row -->
<img src="https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-Web%20App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/Scikit--Learn-ML%20Model-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/MLOps-Pipeline-000000?style=for-the-badge&logo=mlflow&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub%20Actions-CI%2FCD-2671E5?style=for-the-badge&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/License-MIT-2ECC71?style=for-the-badge" />

<br><br>

<img src="https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png" width="100%"/>

</div>

---

# 📌 **Heart Disease Prediction Application**

A complete **Machine Learning + MLOps** application designed to predict the probability of heart disease using real-world medical attributes.

This project includes:

- A fully polished **Streamlit UI**
- A clean and modular **Machine Learning pipeline**
- Professional **MLOps-ready architecture**
- Model explanation and visualization
- Production-quality **logging**, **artifacts**, and **pipeline structure**
- Optional deployment pipeline using **Docker** and **CI/CD** workflows

---

# 📋 **Features**

### ✅ **Individual Patient Prediction**
- Enter patient details  
- Real-time ML prediction  

### ✅ **Batch Prediction (CSV File)**
- Upload a CSV  
- Bulk inferencing  
- Export predictions as downloadable file  

### ✅ **Model Explainability**
- Feature importance visualization  
- Medical interpretation  

### ✅ **Comprehensive Logging**
- Data processing logs  
- Model inference logs  
- Debug-level internal logs  

### ✅ **Production-Ready Codebase**
- Modular  
- Scalable  
- Reusable  
- MLOps-oriented  

---

# 🏗 **Project Structure**

```
Heart_Disease_Pred_MLOPS/
│
├── app.py                           # Streamlit interface
├── main.py                          # Application logic controller
├── data_processing.py               # Preprocessing pipeline
├── ml_functions.py                  # Model training & prediction
├── helper_functions.py              # Logging & utilities
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
├── logs/                            # Application logs
├── Dockerfile                       # Docker container file
├── requirements.txt                 # Python dependencies
├── .env.example                     # Env template
└── .github/workflows/               # CI/CD workflows (disabled)
```

---

# 🚀 **Getting Started**

## **Prerequisites**
- Python 3.8 or higher  
- pip or conda  
- (Optional) Docker  

---

## **Installation**

### Clone the repo:
```bash
git clone https://github.com/SRIHARSHA-BHARADWAJ/Heart_Disease_Pred_MLOPS.git
cd Heart_Disease_Pred_MLOPS
```

### Create virtual environment:
```bash
python -m venv venv
```

### Activate env:

Windows:
```bash
venv\Scripts\activate
```

macOS/Linux:
```bash
source venv/bin/activate
```

### Install dependencies:
```bash
pip install -r requirements.txt
```

### Create `.env` file:
```
DATA_DIR=data
ARTIFACTS_DIR=artifacts
LOGS_DIR=logs
```

---

# 💻 **Usage**

## ⭐ **Single Patient Prediction**
- Navigate to “Single Prediction”  
- Input medical details  
- Click **Predict**

## ⭐ **Batch Prediction**
- Go to “Batch Prediction”  
- Upload CSV  
- Download results  

## ⭐ **Model Explanation**
- Visualize feature importance  
- Understand model decisions  

---

# 🔧 **Technical Details**

## **Model Information**
- Algorithm: **Random Forest Classifier**
- Preprocessing:
  - StandardScaler  
  - One-hot encoding  
- Metrics:
  - Accuracy: ~85%  
  - Precision: ~84%  
  - Recall: ~86%  
  - F1-score: ~85%  
  - ROC AUC: ~0.90  

---

# 📊 **Expected Data Format**

| Feature | Description | Type |
|---------|-------------|------|
| age | Age in years | Numerical |
| sex | 1=Male, 0=Female | Binary |
| cp | Chest pain type (0–3) | Categorical |
| trestbps | Resting blood pressure | Numerical |
| chol | Serum cholesterol | Numerical |
| fbs | Fasting blood sugar (>120mg/dl) | Binary |
| restecg | ECG results | Categorical |
| thalach | Max heart rate | Numerical |
| exang | Exercise induced angina | Binary |
| oldpeak | ST depression | Numerical |
| slope | Slope of ST segment | Categorical |
| target | Diagnosis | Binary |

---

# 📈 **Model Performance Summary**

- High test-set performance  
- Balanced precision and recall  
- Robust on clinical datasets  

---

# 🛠 **MLOps: CI/CD Pipeline**

### The workflow includes templates for:
- Docker image build  
- Automated tests  
- Deployment to Render  
- GitHub Actions workflows  

### Required Secrets:
- `DOCKER_USERNAME`  
- `DOCKER_PASSWORD`  
- `RENDER_DEPLOY_HOOK`  

### Pipeline Flow:

```
Push to main → CI → Build Docker Image → Push to Docker Hub → Render Deployment
```

---

# 🔬 **Future Enhancements**

- SHAP & LIME explainability  
- Model drift detection  
- Dataset versioning  
- Advanced dashboarding  
- Authentication for hospital use  
- Auto retraining pipeline  
- A/B testing for ML models  

---

# 📝 **License**

This project is licensed under the **MIT License**.

---

# 📞 **Contact**

For queries or collaboration:  
**Name:** Sriharsha K  
**Email:** sriharsha.ai22@bmsce.ac.in  
**GitHub:** https://github.com/SRIHARSHA-BHARADWAJ  


