

<!-- -------------------------------------------------------------- -->
<!-- PREMIUM PROFESSIONAL HEADER -->
<!-- -------------------------------------------------------------- -->

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Inter&weight=600&size=34&duration=2600&pause=700&color=3DA9FC&center=true&vCenter=true&width=900&lines=Heart+Disease+Prediction+System;End-to-End+Machine+Learning+Pipeline;Streamlit+%7C+MLOps+%7C+Docker+%7C+CI%2FCD;By+Sriharsha+K" />

<br>

<!-- Professional Badge Row -->
<img src="https://img.shields.io/badge/Python-3.10-316FEB?style=flat&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/Streamlit-Application-EA244B?style=flat&logo=streamlit&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-Containerized-2391E6?style=flat&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/MLOps-Pipeline-000000?style=flat&logo=mlflow&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-Actions-2F80ED?style=flat&logo=githubactions&logoColor=white" />
<img src="https://img.shields.io/badge/License-MIT-43A047?style=flat" />

</div>

---

## **Overview**

A fully modular **Heart Disease Prediction System** designed to meet production-level standards using:

- **Streamlit** UI  
- **Random Forest** ML model  
- **Structured preprocessing pipeline**  
- **Artifact storage**  
- **Logging system**  
- **Docker containerization**  
- (Optional) **CI/CD workflows**

Supports both **single-patient predictions** and **batch predictions using CSV files**, making it suitable for clinical simulations, academic demos, or ML deployment practice.

---

## **Project Structure**

```
Heart_Disease_Pred_MLOPS/
│
├── app.py                     # Streamlit UI
├── main.py                    # Pipeline orchestrator
├── data_processing.py         # Preprocessing pipeline
├── ml_functions.py            # ML model logic
├── helper_functions.py        # Logging + utilities
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
├── .env.example
└── .github/workflows/         # (Disabled by choice)
```

---

## **Machine Learning Pipeline**

```
User Input or CSV File
          ↓
Preprocessing Pipeline
          ↓
Feature Encoding & Normalization
          ↓
Random Forest Classifier
          ↓
Prediction Output
```

---

## **Model Performance**

| Metric     | Score |
|------------|--------|
| Accuracy   | 85%    |
| Precision  | 84%    |
| Recall     | 86%    |
| F1 Score   | 85%    |

---

## **Running the Application**

### **Install dependencies**
```bash
pip install -r requirements.txt
```

### **Train model**
```bash
python main.py
```

### **Launch Streamlit application**
```bash
streamlit run app.py
```

---

## **Docker Deployment**

### Build:
```bash
docker build -t heart-app .
```

### Run:
```bash
docker run -p 8501:8501 heart-app
```

---

## **Future Enhancements**

- SHAP / LIME explainability  
- Model drift monitoring  
- Automated continuous training  
- Authentication layer  
- Dashboard-based visual insights  
- Deep learning-based version  

---

## **Maintainer**

**Name:** Sriharsha K  
**Email:** sriharsha.ai22@bmsce.ac.in  
**GitHub Username:** SRIHARSHA-BHARADWAJ  
GitHub: https://github.com/SRIHARSHA-BHARADWAJ  

---

## **License**

Released under the **MIT License**.  
See `LICENSE` file for details.

