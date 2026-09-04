<h1 align="center">Hi 👋, I'm Harshith Devaraja</h1>
<h3 align="center">Data Scientist | Machine Learning Engineer | M.Sc. Applied Mathematics & Computing</h3>

<p align="center">
  I build end-to-end AI systems — from data pipelines to deployed, explainable models —
  across <b>healthcare</b>, <b>finance</b>, and <b>NLP</b>.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/harshith-devaraja-087ba0228"><img src="https://img.shields.io/badge/LinkedIn-Harshith%20Devaraja-0A66C2?logo=linkedin&logoColor=white" /></a>
  <a href="mailto:harshikollur302@gmail.com"><img src="https://img.shields.io/badge/Email-harshikollur302%40gmail.com-D14836?logo=gmail&logoColor=white" /></a>
  <a href="https://github.com/Harshithpatali"><img src="https://img.shields.io/badge/GitHub-Harshithpatali-181717?logo=github&logoColor=white" /></a>
  <a href="https://share.streamlit.io/user/harshithpatali"><img src="https://img.shields.io/badge/Streamlit-Apps-FF4B4B?logo=streamlit&logoColor=white" /></a>
</p>

---

## ⚙️ Tech Stack

<p align="center">
  <img src="https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/-TensorFlow-FF6F00?logo=tensorflow&logoColor=white" />
  <img src="https://img.shields.io/badge/-Scikit--Learn-F7931E?logo=scikitlearn&logoColor=white" />
  <img src="https://img.shields.io/badge/-XGBoost-FF9900?logo=xgboost&logoColor=white" />
  <img src="https://img.shields.io/badge/-Pandas-150458?logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/-LangChain-00C7B7?logo=chainlink&logoColor=white" />
  <img src="https://img.shields.io/badge/-FAISS-0099E5?logo=facebook&logoColor=white" />
  <img src="https://img.shields.io/badge/-HuggingFace-FECC00?logo=huggingface&logoColor=black" />
  <img src="https://img.shields.io/badge/-MLflow-0194E2?logo=mlflow&logoColor=white" />
  <img src="https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/-Kubernetes-326CE5?logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/-Google%20Cloud-4285F4?logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/-Streamlit-FF4B4B?logo=streamlit&logoColor=white" />
  <img src="https://img.shields.io/badge/-PostgreSQL-336791?logo=postgresql&logoColor=white" />
</p>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Harshithpatali&show_icons=true&theme=default&hide_border=true" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Harshithpatali&layout=compact&hide_border=true" height="165" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Harshithpatali&hide_border=true" height="165" />
</p>

---

## 🏆 Top 5 Projects

*Selected from 90+ repositories for technical depth, real metrics, and end-to-end delivery (data → model → deployment).*

| # | Project | Domain | Headline Result |
|---|---|---|---|
| 1 | [Math RAG Chatbot](#-1-math-rag-chatbot) | GenAI / RAG | Live on GCP Cloud Run |
| 2 | [Multi-Condition Health Risk App](#-2-multi-condition-health-risk-prediction-app) | Healthcare ML | ROC-AUC **0.91** |
| 3 | [Haar_ECG](#-3-haar_ecg--ecg-denoising--arrhythmia-detection) | Healthcare / Signal Processing | CNN + SVM on MIT-BIH |
| 4 | [Stock Price Forecasting](#-4-stock-price-forecasting-lstm--mlflow--gcp) | Finance / Time Series | R² **0.92**, RMSE **12.4** |
| 5 | [Supply Chain Risk Assessment](#-5-supply-chain-risk-assessment-nlp--sentiment-analysis) | NLP / Sentiment | Accuracy **0.89** on 20K+ articles |

---

### 📘 1. [Math RAG Chatbot](https://github.com/Harshithpatali/math-rag-chatbot) · [🔗 Live Demo](https://math-rag-chatbot-314201399185.europe-west1.run.app)
`Python` `LangChain` `FAISS` `HuggingFace` `Streamlit` `GCP`

A Retrieval-Augmented Generation assistant that solves and explains Linear Algebra problems step by step — the standout project for showing applied LLM/GenAI engineering, not just classical ML.

- Semantic retrieval with `all-MiniLM-L6-v2` embeddings + FAISS vector search
- **FLAN-T5** for step-by-step reasoning and explanation generation
- Deployed on **Google Cloud Run** via Docker for scalable, low-latency access
- Source passages shown alongside answers for transparency

---

### 🏥 2. [Multi-Condition Health Risk Prediction App](https://github.com/Harshithpatali/health-risk-app)
`Python` `Scikit-Learn` `Streamlit` `SHAP`

An interactive dashboard that predicts risk across multiple health conditions from patient data, with model explainability built in.

| Metric | Value |
|---|---|
| F1-score | **0.87** |
| ROC-AUC | **0.91** |
| Records processed | **50,000+** |
| Models compared | Random Forest, XGBoost, Logistic Regression |

- Explainable AI via **SHAP** feature-importance plots
- Unified dashboard for cross-condition risk comparison
- Cleaned and normalized data from multiple healthcare sources

---

### 🩺 3. [Haar_ECG — ECG Denoising & Arrhythmia Detection](https://github.com/Harshithpatali/Haar_ECG)
`Python` `Haar Wavelet` `CNN` `SVM` `Streamlit`

Signal-processing meets deep learning: denoises raw ECG traces with a Haar wavelet transform, then classifies arrhythmias with CNN and SVM models trained on the **MIT-BIH Arrhythmia Database**.

- Haar wavelet soft-threshold denoising with coefficient visualization
- Dual modeling approach — CNN and SVM — for arrhythmia classification
- Interactive **Streamlit app** for uploading ECG signals and getting live predictions
- A rarer, more research-flavored addition next to the other applied-ML projects

---

### 📈 4. [Stock Price Forecasting (LSTM + MLflow + GCP)](https://github.com/Harshithpatali/sensex-prediction)
`Python` `TensorFlow` `Keras` `XGBoost` `MLflow` `Docker` `Kubernetes` `GCP`

| Metric | Value |
|---|---|
| RMSE | **12.4** |
| R² | **0.92** |

- LSTM-based next-day price prediction on **15 years of NIFTY50 data**
- Experiment tracking and model versioning with **MLflow**
- Dockerized service deployed on a **GCP Kubernetes cluster** with a REST API

---

### 🏭 5. [Supply Chain Risk Assessment (NLP + Sentiment Analysis)](https://github.com/Harshithpatali/Supply-Chain-Risk-Assessment-Pipeline-Using-NLP-and-Sentiment-Analysis)
`Python` `NLTK` `SpaCy` `Scikit-Learn` `Streamlit`

- Scraped and processed **20,000+ news articles** to flag supply-chain risk signals
- Sentiment classifier for risk detection, **accuracy: 0.89**
- Risk-score dashboard plus automated alerts for high-risk events

---

<details>
<summary><strong>Other notable repos</strong> (customer churn pipeline, heart-attack risk prediction, more)</summary>

- **[Customer Churn Prediction Pipeline](https://github.com/Harshithpatali/customer_churn_pipeline)** — Random Forest + XGBoost ensemble, ROC-AUC 0.88, MLflow-tracked
- **[Heart Attack Risk Prediction](https://github.com/Harshithpatali/heart-attack-risk-prediction)** — CatBoost model with a mapping/visualization module for regional risk

</details>

---

## 🎓 Internships & Certifications

**Virtual Internships**
- Data Science Virtual Internship — predictive modeling, data visualization, ML deployment pipelines
- AI & Machine Learning Virtual Internship — time-series forecasting, NLP pipelines, model monitoring

**Certifications (Coursera)**
- [IBM Machine Learning with Python & Scikit-learn](https://coursera.org/share/d9ffb9b63066bc4bb0594266dca054dd)
- [IBM Generative AI Engineering with LLMs Specialization](https://coursera.org/share/f0ab2a153db668d8c6e1c19b678bfc2f)
- [Applied Data Science Specialization (IBM)](https://coursera.org/share/dce559647fcbfa553f169425d7684998)
- [Applied Data Science Specialization (IBM)](https://coursera.org/share/e25c3eee6b6e18dc5e756e466f28d579)
- Machine Learning — University of Michigan (Coursera)
- Python Programming — Duke University (Coursera)

---

## 🌱 Currently Exploring
- LLM-based financial analysis assistants using RAG pipelines
- AI application deployment on GCP with Kubernetes orchestration
- Advanced time-series modeling and optimization

---

<p align="center"><i>Always learning. Always building impactful AI solutions.</i></p>
