<!-- HEADER -->
<h1 align="center">Mohammed E. — Data Scientist & Machine Learning Engineer</h1>

<p align="center">
  <img src="https://img.shields.io/badge/ML-Deep%20Learning-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/Data%20Science-Python-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Status-Open%20to%20Opportunities-brightgreen?style=flat-square"/>
</p>

<p align="center">
  <a href="mailto:med.marin17@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20Me-red?style=flat-square&logo=gmail"/></a>
  <a href="https://www.linkedin.com/in/mohammed-e-a13664182"><img src="https://img.shields.io/badge/LinkedIn-Profile-blue?style=flat-square&logo=linkedin"/></a>
  <a href="https://github.com/IBOSS24"><img src="https://img.shields.io/badge/GitHub-IBOSS24-black?style=flat-square&logo=github"/></a>
</p>

---

## 🧭 About Me

I am a **state-qualified engineer and Moroccan Royal Navy officer building a career in maritime Data Science and Machine Learning Engineering**. Five years at sea and experience in maritime command centers have shaped my understanding of vessel operations, radar surveillance, and the decisions operators must make with incomplete information.

I bring that operational perspective to hands-on ML engineering. My projects include a **CatBoost fraud-detection API deployed on AWS EC2**, with FastAPI, automated tests, Docker, and GitHub Actions workflows for versioned releases, deployment validation, and rollback. I am developing the skills to build, test, deploy, and maintain reliable ML systems.

My focus is applying these capabilities to **maritime traffic forecasting, vessel behavior analysis, and equipment reliability**—helping anticipate port congestion, identify activity that warrants investigation, and detect early signs of equipment failure. I aim to connect operational questions with measurable ML problems and tools that maritime professionals can use.

---

## 🔥 Featured Projects

### 💳 Credit Card Fraud Detection — API & AWS Deployment
**Repository:** [Fraud-detection-API](https://github.com/IBOSS24/Fraud-detection-API) 

An end-to-end personal machine learning engineering project connecting a **CatBoost / PyCaret** fraud classifier to a **FastAPI** inference service and a versioned **Docker / AWS EC2** deployment workflow.

- **Inference:** validated transaction inputs, fraud probability, configurable decision threshold, and separate API/model versions.
- **Testing:** pytest endpoint tests, mocked predictions, and inference failure checks.
- **CI and releases:** GitHub Actions tests, container readiness checks, tag-based Docker releases, and API version validation.
- **AWS deployment:** GitHub OIDC → IAM → Systems Manager → EC2, with Green candidate validation and rollback checks.
- **Engineering trade-off:** single-host container promotion can briefly interrupt service; health checks do not establish model quality.

**Compétences illustrées :** passage d'un modèle de machine learning à un service d'inférence, tests automatisés, conteneurisation et déploiement contrôlé sur le cloud.

This project demonstrates my progression toward building, testing, deploying, and maintaining ML systems. Experiment tracking and model monitoring are planned extensions.

---

### 🚦 Traffic sign classification 
**Repo:** https://github.com/IBOSS24/Traffic_sign_classification/tree/main

An end-to-end Computer Vision project for multiclass traffic sign classification using Convolutional Neural Networks (CNNs), deployed with Streamlit and enhanced with Grad-CAM Explainable AI visualizations.

This project goes beyond standard image classification by integrating:
- real-world deployment practices,
- explainability (XAI),
- confidence analysis,
- and engineering-level debugging/serialization handling for TensorFlow/Keras production environments.

---
### ✈️ Aircraft Surface Damage Classification & Captioning

**Repository:** [Aircraft Surface Damage Classification and Captioning](https://github.com/IBOSS24/Aircraft-Surface-Damage-Classification-and-Captioning)

A notebook-based computer vision project exploring **surface-damage classification and image description** through two complementary models.

- **Classification:** frozen ImageNet-pretrained VGG16 features with a custom Keras classifier for dents versus cracks.
- **Image description:** pretrained Salesforce BLIP generates descriptions using different prompts.
- **Workflow:** image preprocessing, training/validation/test splits, learning curves, and test evaluation.

**Skills demonstrated:** transfer learning, image classification, pretrained vision-language models, and TensorFlow/PyTorch integration. This educational prototype provides a foundation for future work on equipment inspection and maritime maintenance imagery.

---

### 🚀 SpaceX Falcon 9 — First-Stage Landing Prediction

**Repository:** [SpaceX Landing Prediction](https://github.com/IBOSS24/SpaceX_competitor_-)

An **IBM Data Science capstone** exploring Falcon 9 first-stage landing outcomes through data acquisition, analysis, visualization, and classical machine learning.

- **Data and analysis:** API collection, web scraping, data preparation, SQL exploration, and visual analysis.
- **Geospatial communication:** Folium launch-site maps, a Plotly Dash dashboard, and an analysis report.
- **Model comparison:** logistic regression, SVM, decision tree, and K-nearest neighbors using scikit-learn and cross-validated parameter search.

**Skills demonstrated:** working across an analytical workflow, comparing predictive baselines, and communicating findings. The repository documents evaluation improvements, including moving preprocessing inside a Pipeline before re-evaluating model scores.

---

## 🛠 Skills & Technologies

| Area | Skills and practical experience |
| --- | --- |
| **💻 Data analysis & programming** | Python, pandas, NumPy, SQL; data cleaning, exploratory analysis, visualization, and feature preparation |
| **🤖 Machine learning** | scikit-learn, CatBoost, PyCaret; supervised learning, clustering, anomaly detection, cross-validation, imbalanced classification, and decision-threshold selection |
| **🧠 Computer vision & deep learning** | TensorFlow/Keras, CNNs, transfer learning, Grad-CAM, and pretrained image-captioning models |
| **⚙️ ML engineering & deployment** | FastAPI, Pydantic, pytest, Docker, GitHub Actions, and AWS EC2; validated inference, automated testing, versioned releases, health/version checks, and rollback |
| **🛰 Maritime operations** | Experience at sea, radar surveillance, maritime command-center operations, and operational supervision |

**Currently developing:** MLOps practices for experiment tracking, model lifecycle management, and monitoring, building on an existing deployment and CI/CD foundation.

---

## 📜 Certifications


### **🎓 Data Science & Machine Learning**
- IBM **Machine Learning Specialization**  
- IBM **Deep Learning with Keras & TensorFlow**  
- IBM **Data Science Professional Certificates**  
- IBM **Big Data Analytics with Spark**  
- IBM **Data Analysis in Python**  
- IBM **Data Visualization in Python**  
- IBM **Statistics for Data Science**  
- IBM **Supervised Machine Learning: Regression**  
- IBM **Supervised Machine Learning: Classification**  
- IBM **Unsupervised Machine Learning**  
- IBM **Neural Networks & Deep Learning**  
- IBM **Machine Learning: Dimensionality Reduction**  
- IBM **Feature Engineering**  
- IBM **Model Evaluation & Refinement**  

### **🚀 Additional Engineering & IT Certificates**
- Cisco Networking Basics  
- IT Support & Fundamentals  
- SQL & Database Foundations  
- Python for AI  

> 👉 Full certificate list available here:  
> https://www.linkedin.com/in/mohammed-e-a13664182/details/certifications/

---

## 🌟 Why Work With Me?

- **Operational understanding:** Five years at sea and maritime command-center experience help me connect analytical questions to the decisions operators actually face.
- **Hands-on delivery:** I have taken an ML model from experimentation to a tested API deployed on AWS, with containerization and controlled release workflows.
- **Reliability-minded engineering:** I work with input validation, automated tests, deployment checks, and failure scenarios alongside model evaluation.
- **A clear maritime purpose:** I aim to improve operational productivity through applications such as traffic forecasting, vessel behavior analysis, and equipment reliability, with success measured against a defined operational need.

---

## 📬 Contact

📧 **Email:** med.marin17@gmail.com  
🔗 **LinkedIn:** https://www.linkedin.com/in/mohammed-e-a13664182  
🐙 **GitHub:** https://github.com/IBOSS24  

---

⭐ *If you like my work, consider starring my repositories — it motivates me to build more impactful projects.*  
