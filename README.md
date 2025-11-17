

<div align="center">

<!-- Animated Professional Header -->
<img src="https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=32&duration=2500&pause=800&color=00E7FF&center=true&vCenter=true&width=900&lines=Heart+Disease+Prediction+System;Machine+Learning+%7C+MLOps+%7C+Streamlit;Docker+%7C+Logging+%7C+Artifacts;Developed+by+Sriharsha+K" />

<br>

<!-- Minimal Professional Badges -->
<img src="https://img.shields.io/badge/Python-3.10-1E90FF?style=flat&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-Application-FF4B4B?style=flat&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-Containerized-2496ED?style=flat&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/MLOps-Pipeline-000000?style=flat&logo=mlflow&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-Actions-2F80ED?style=flat&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/License-MIT-3CB371?style=flat" />

</div>

---

## **📌 Project Overview**

A modular, production-oriented **Heart Disease Prediction System** featuring:

- Random Forest ML model  
- Streamlit web interface  
- Clean preprocessing pipeline  
- Full logging system  
- Artifact storage (model + pipeline)  
- Docker support  
- (Optional) CI/CD workflow structure  

Designed to be clean, scalable, and easy to deploy.

---

## **📁 Project Structure**

```
Heart_Disease_Pred_MLOPS/
│
├── app.py                     # Streamlit UI
├── main.py                    # Pipeline orchestrator
├── data_processing.py         # Preprocessing steps
├── ml_functions.py            # ML model logic
├── helper_functions.py        # Logging utilities
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
├── logs/
├── Dockerfile
├── requirements.txt
└── .github/workflows/         # (Workflows exist but disabled)
```

---

## **⚙️ Machine Learning Pipeline**

```
User Input or CSV File
          ↓
Preprocessing & Cleaning
          ↓
Feature Encoding & Scaling
          ↓
Random Forest Classifier
          ↓
Prediction Output
```

---

## **📊 Model Performance**

| Metric     | Score |
|------------|--------|
| Accuracy   | 85%    |
| Precision  | 84%    |
| Recall     | 86%    |
| F1 Score   | 85%    |

---

## **▶️ Running the Application**

### Install dependencies:
```bash
pip install -r requirements.txt
```

### Train the model:
```bash
python main.py
```

### Launch Streamlit:
```bash
streamlit run app.py
```

---

## **🐳 Docker Support**

### Build Image:
```bash
docker build -t heart-app .
```

### Run Container:
```bash
docker run -p 8501:8501 heart-app
```

---

## **🚀 Future Enhancements**

- SHAP / LIME Explainability  
- Drift monitoring  
- Auto-retraining pipeline  
- Security layer for clinical usage  
- Dashboard UI  
- Deep learning model variant  

---

## **👤 Maintainer**

**Name:** Sriharsha K  
**Email:** sriharsha.ai22@bmsce.ac.in  
**GitHub:** https://github.com/SRIHARSHA-BHARADWAJ  

---

## **📄 License**

Licensed under the **MIT License**.


