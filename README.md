<!-- ========================================================= -->
<!--                🛑 GOD MODE README V4 🛑                  -->
<!--        Futuristic · Premium · Engineered · MLOps         -->
<!-- ========================================================= -->

<p align="center">
  <img src="https://img.shields.io/badge/ML-Heart%20Disease%20Prediction-ff4d6d?style=for-the-badge&logo=canonical&logoColor=white"/>
  <img src="https://img.shields.io/badge/MLOps-Pipeline-00eaff?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Status-Production%20Live-16ff8a?style=for-the-badge&logo=checkmarx&logoColor=white"/>
</p>

<h1 align="center" style="font-weight:900;font-size:40px;">
  🔥 HEART DISEASE PREDICTION — MLOps & Streamlit Dashboard
</h1>

<p align="center">
  <b>End-to-End Machine Learning • CI/CD • Docker • Render Deployment</b>
</p>

---

## 🌐 **🚀 LIVE WEB APPLICATION**
<p align="center">
  <a href="https://heart-disease-app-k9lk.onrender.com" target="_blank">
    <img src="https://img.shields.io/badge/OPEN%20LIVE%20APP-000000?style=for-the-badge&logo=streamlit&logoColor=00eaff"/>
  </a>
</p>

---

## 🧠 **Project Overview**

A fully engineered, production-ready **Heart Disease Prediction System** built using:

- **Machine Learning (Random Forest / Logistic Regression)**
- **Streamlit Premium UI Dashboard**
- **Complete MLOps workflow**
- **Docker Containerization**
- **GitHub Actions CI/CD**
- **Render Cloud Deployment**

This project predicts **probability of heart disease** using medical attributes and provides:

✔ Single patient prediction  
✔ Batch CSV prediction  
✔ Model evaluation dashboard  
✔ Confusion matrix  
✔ Feature importance  
✔ Beautiful, interactive analytics  

---

## 🎯 **Key Features**

### **🔍 1. Real-Time Prediction**
Enter patient details → Get instant heart disease risk.

### **📊 2. Batch Processing**
Upload a CSV → Receive predictions for 10/100/1000+ patients.

### **📈 3. Model Evaluation Dashboard**
- Accuracy  
- Precision / Recall  
- F1-Score  
- ROC insights  
- Confusion matrix heatmap  

### **💡 4. Smart Risk Analysis**
Highlights high-importance medical factors.

### **🌐 5. Live Cloud Deployment**
Deployed via **Docker image + Render Web Service**.

### **⚙️ 6. Automated CI/CD**
Every push to `main` → Auto Docker Build → Auto Deploy.

---

## 🏗️ **Architecture Diagram**

```
                 +------------------------+
                 |   GitHub Repository    |
                 +------------+-----------+
                              |
                              |  Push (main)
                              v
                 +------------------------+
                 |    GitHub Actions CI   |
                 |  Docker Build & Push   |
                 +------------+-----------+
                              |
                              |  Docker Image
                              v
                 +------------------------+
                 |     Render Cloud       |
                 |  Auto Deploy Web App   |
                 +------------------------+
                              |
                              v
           https://heart-disease-app-k9lk.onrender.com
```

---

## 📂 **Project Structure**

```
Heart_Disease_Pred_MLOPS/
│── app.py                    # Streamlit UI
│── main.py                   # Pipeline controller
│── ml_functions.py           # Model prediction logic
│── data_processing.py        # Preprocessing pipeline
│── helper_functions.py       # Logging helpers
│── requirements.txt          # All Python dependencies
│── Dockerfile                # Containerization file
│
├── artifacts/                # Saved ML models
│── data/                     # Raw & processed datasets
├── logs/                     # System logs
│
└── .github/workflows/
      └── docker-build-push.yml   # CI/CD pipeline
```

---

## 📦 **Dataset Features**

| Feature | Description |
|--------|-------------|
| age | Patient age |
| sex | 1 = male, 0 = female |
| cp | Chest pain type (0–3) |
| trestbps | Resting BP |
| chol | Cholesterol |
| fbs | Fasting blood sugar |
| restecg | ECG results |
| thalach | Max heart rate |
| exang | Exercise angina |
| oldpeak | ST depression |
| slope | ST slope |
| ca | Major vessels (0–4) |
| thal | Thalassemia |
| target | 1 = disease, 0 = healthy |

---

## 🚀 **Local Setup (Developer Mode)**

```bash
git clone https://github.com/SRIHARSHA-BHARADWAJ/Heart_Disease_Pred_MLOPS
cd Heart_Disease_Pred_MLOPS

pip install -r requirements.txt
streamlit run app.py
```

---

## 🐳 **Docker (Build & Run Locally)**

```bash
docker build -t heart-app .
docker run -p 8501:8501 heart-app
```

---

## 🤖 **CI/CD (GitHub Actions)**

- Auto build Docker image  
- Auto push to Docker Hub  
- Auto deploy to Render cloud  
- Zero downtime deployment  

Your pipeline file:

```
.github/workflows/docker-build-push.yml
```

Runs automatically for every new commit.

---

## 🌐 **Deployment URL**

➡ **LIVE:** https://heart-disease-app-k9lk.onrender.com

---

## 📝 **License**

This project is licensed under the **MIT License**.  
© **Sriharsha K**

---

## 👨‍💻 **Author**

**Sriharsha K**  
Final year — B.E. AIML  
B.M.S. College of Engineering, Bengaluru  
📧 **sriharsha.ai22@bmsce.ac.in**

---

<p align="center">
  <b>Built with ❤️, ML, and MLOps engineering excellence.</b><br>
  <i>Accuracy meets elegance.</i>
</p>
