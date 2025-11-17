<!-- ====================================================================== -->
<!-- 🎨 CUSTOM BANNER -->
<!-- ====================================================================== -->

<div align="center">

<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=35&duration=3000&color=00F7FF&center=true&vCenter=true&width=900&lines=HEART+DISEASE+PREDICTION+SYSTEM;Machine+Learning+%7C+MLOps+%7C+CI%2FCD+%7C+Docker;Developed+by+Sriharsha+K" />

</div>

---

<!-- ====================================================================== -->
<!-- ✨ BADGES -->
<!-- ====================================================================== -->

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-Containerized-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![MLOps](https://img.shields.io/badge/MLOps-Pipeline-FFDD00?style=for-the-badge&logo=mlflow&logoColor=black)
![GitHub](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

</div>

---

# 🚀 Overview

A **production-grade Heart Disease Prediction System** built using:

- 🧠 **Machine Learning (Random Forest)**
- ⚙️ **MLOps best practices**
- 🐳 **Docker containerization**
- 🔄 **CI/CD with GitHub Actions**
- 🎨 **Streamlit web application**
- 📦 **Artifact & pipeline tracking**

This project predicts heart disease **risk probability** using both **single-patient input** and **batch CSV prediction**.

---

# 🌈 Features

<img align="right" width="310" src="https://media.giphy.com/media/Q5pO0Q3h43iDi/giphy.gif"/>

### 🔍 **Single Patient Prediction**
- Enter medical values → instant output

### 📂 **Batch Prediction**
- Upload CSV → predictions for all patients

### 📊 **Model Explainability**
- Feature importance visualization  
- Medical reasoning

### 🧹 **Full Data Pipeline**
- Cleaning  
- Scaling  
- Encoding  
- Preprocessing artifacts

### 🧠 **Model**
- Random Forest Classifier  
- Accuracy ~85%

### ⚙️ **DevOps + MLOps**
- Docker build  
- Automated tests  
- Logging  
- Artifact versioning  
- (Workflows present but disabled)

<br><br>

---

# 🗂 Project Structure

```plaintext
Heart_Disease_Pred_MLOPS/
│
├── app.py                         # Streamlit UI
├── main.py                        # Pipeline controller
├── data_processing.py             # Preprocessing steps
├── ml_functions.py                # ML model logic
├── helper_functions.py            # Logging & utilities
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
└── .github/workflows/             # CI/CD workflows (disabled)

🧠 ML Pipeline Workflow
flowchart TD
    A[User Input / CSV Upload] --> B[Data Preprocessing]
    B --> C[Feature Engineering + Encoding]
    C --> D[Random Forest Model]
    D --> E[Prediction Output]

🐳 Docker Usage
Build Image
docker build -t heart-app .

Run Container
docker run -p 8501:8501 heart-app

🖥️ Run Streamlit App
streamlit run app.py

📈 Model Performance
Metric	Score
Accuracy	85%
Precision	84%
Recall	86%
F1 Score	85%
🚧 Future Enhancements

🔬 SHAP & LIME Explainability

📊 Interactive plots

🧪 Model drift monitoring

🔁 Automated retraining jobs

🔐 Authenticated clinical access

🧠 Deep learning extension

👨‍💻 Maintainer

Name: Sriharsha K
Email: sriharsha.ai22@bmsce.ac.in

GitHub: SRIHARSHA-BHARADWAJ

📝 License

This project is licensed under the MIT License.

<div align="center">
⭐ If you like this project, consider giving it a star! ⭐

Made with ❤️ by Sriharsha K

</div> ```