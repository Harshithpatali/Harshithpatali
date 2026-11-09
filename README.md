<div align="center">

# Harshith Devaraja

### Data Science · Machine Learning · Applied AI

I work on data products that turn messy data into useful decisions — from SQL and statistical analysis to machine learning, experimentation, and deployed applications.

[Portfolio](https://harshith-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/harshith-devaraja-087ba0228) · [Email](mailto:harshikollur302@gmail.com) · [GitHub](https://github.com/Harshithpatali)

</div>

---

## About

I'm an M.Sc. Applied Mathematics & Computing graduate interested in the practical side of data science: understanding a problem, building a defensible analytical approach, evaluating it honestly, and making the result usable.

My work spans customer and marketplace analytics, causal experimentation, graph-based intelligence, forecasting, and AI applications. I enjoy projects where statistical thinking meets engineering — especially when the model is only one part of a larger decision system.

**What I care about:** sound methodology, reproducible workflows, transparent evaluation, and communicating what a result does (and does not) tell us.

## Focus areas

| Data science & decision-making | Machine learning | Applied AI & engineering |
|:--|:--|:--|
| SQL and analytical data modeling | Classification and forecasting | Retrieval-augmented generation |
| Experiment design and A/B testing | Graph ML and anomaly detection | LLM evaluation and monitoring |
| Causal inference and uplift | Explainability and model validation | FastAPI and Streamlit products |
| Cohorts, segmentation, survival analysis | Time-series and feature engineering | Docker, CI/CD and cloud deployment |

## Selected work

A selection of projects that best represents the problems and methods I enjoy working on. Each repository contains its own methodology, implementation details, and limitations.

### 01 — Causal Experimentation Intelligence Platform
**From experiment quality checks to treatment decisions.**

[Repository](https://github.com/Harshithpatali/causal_experimentation_platform)

- Experiment validation with sample-ratio mismatch (SRM) and covariate balance checks.
- A/B testing, confidence intervals, power and minimum detectable effect.
- ATE/ATT estimation and S-, T- and X-learner approaches to heterogeneous treatment effects.
- Qini/AUUC-oriented uplift evaluation and business-policy simulation.
- FastAPI service and Streamlit interface.

### 02 — Customer Intelligence & Graph Anomaly Research
**Customer behaviour, segmentation, anomaly investigation and relationship networks.**

[Repository](https://github.com/Harshithpatali/Graph-anomaly-supervised-neural-prediction) · [Live dashboard](https://graph-anomaly-supervised-neural-prediction-v1.streamlit.app/)

- Customer-level behavioural profiles and exploratory segmentation.
- Isolation Forest and Local Outlier Factor for anomaly ranking.
- User–device–IP graph exploration, connectivity measures and communities.
- Customer 360 investigation workflow with evidence behind review signals.

The dashboard is an exploratory decision-support tool; anomaly and behavioural-risk scores are not calibrated fraud probabilities.

### 03 — Brazilian E-Commerce Intelligence
**SQL-first marketplace analytics with customer decision science.**

[Repository](https://github.com/Harshithpatali/brazilian-ecommerce-data-science) · [Live dashboard](https://olist-ecommerce-ds.streamlit.app/)

- Relational data modeling and analytical SQL transformations.
- Customer value, RFM segmentation, cohorts and retention analysis.
- Kaplan–Meier time-to-second-purchase analysis with right-censoring.
- Point-in-time churn research and comparison against frequency baselines.
- Campaign scenario simulator connecting assumptions to contribution economics.

**Model transparency:** the repository documents that its current churn model did not outperform the lifetime-frequency baseline on the untouched holdout. I keep that result visible rather than presenting an inflated score.

### 04 — Retail Demand Forecasting & Inventory Optimization
**Forecast quality connected to inventory cost and service-level decisions.**

[Repository](https://github.com/Harshithpatali/retail-demand-inventory-optimization) · [Dashboard](https://retail-demand-inventory-optimization-v1.streamlit.app/) · [API](https://retail-demand-inventory-optimization.onrender.com/)

- Naive, seasonal-naive and moving-average baselines compared with XGBoost and LightGBM.
- Chronological validation and out-of-sample uncertainty estimation.
- Periodic-review inventory policy and simulation.
- Held-out forecasting and inventory evaluation.

The README reports validation WAPE of 0.2808 for XGBoost versus 0.6873 for the naive baseline on the documented 200-series modeling subset.

### 05 — Bayesian Sequential Experimentation
**A research project exploring sequential evidence in experiments.**

[Repository](https://github.com/Harshithpatali/bayesian-sequential-experimentation)

A focused space for Bayesian experimentation, sequential decision-making, and interpreting uncertainty as evidence accumulates.

### 06 — LLM Reliability & Evaluation Platform
**Monitoring AI quality as an engineering problem.**

[Repository](https://github.com/Harshithpatali/llm-evaluation-platform) · [Dashboard](https://llm-evaluation-platform-q.streamlit.app/) · [API docs](https://llm-evaluation-platform-1.onrender.com/docs)

- Asynchronous evaluation pipeline using FastAPI, Celery and Redis.
- Statistical distribution monitoring with KS tests and Wasserstein distance.
- Evaluation telemetry, latency and reliability dashboards.

### 07 — Enterprise ML Platform
**A data engineering-to-model-serving workflow.**

[Repository](https://github.com/Harshithpatali/enterprise-ml-platform) · [API](https://enterprise-ml-platform.onrender.com)

- Hadoop HDFS and PySpark medallion-style data processing.
- Temporal customer features and leakage-aware target construction.
- XGBoost model serving, SHAP explanations, FastAPI and Streamlit.

### 08 — Wavelet & Signal Intelligence
**Signal processing as a bridge between mathematics and machine learning.**

[Wavelet experiments](https://github.com/Harshithpatali/Wavelets) · [ECG project](https://github.com/Harshithpatali/Haar_ECG) · [Wavelet/deepfake research](https://github.com/Harshithpatali/deepfake-noise-wavelet-ml)

My work and interests here include wavelet representations, signal analysis and medical-signal classification. I am also interested in researching **wavelet-based attention mechanisms for Transformers** — exploring whether multi-scale frequency and time-frequency structure can contribute useful inductive bias to attention.

---

## How I approach a data problem

```text
Problem framing
      ↓
Data quality, grain and provenance
      ↓
Exploration + statistical reasoning
      ↓
Baseline → model → validation
      ↓
Interpretation + business decision
      ↓
API / dashboard / reproducible delivery
      ↺
Monitor, learn and improve
```

I prefer chronological or otherwise design-appropriate validation, meaningful baselines, explicit assumptions, and a clear distinction between measured results and simulated business scenarios.

## Technical toolkit

**Languages:** Python, SQL, R, MATLAB  
**Data:** PostgreSQL, MySQL, Pandas, NumPy, SciPy, PySpark  
**Statistics:** Hypothesis testing, A/B testing, causal inference, uplift modeling, survival analysis  
**Machine learning:** scikit-learn, XGBoost, LightGBM, PyTorch, TensorFlow, SHAP  
**AI:** RAG, LangChain, FAISS, ChromaDB, Transformers, LLM evaluation  
**Visualization:** Streamlit, Plotly, Matplotlib, Tableau, Power BI  
**Engineering:** FastAPI, Docker, GitHub Actions, Redis, Celery, GCP, Render, Supabase

## Education & learning

**M.Sc. Applied Mathematics & Computing**  
Manipal Academy of Higher Education

Selected learning and certifications:
- IBM Machine Learning
- IBM Data Science
- IBM Generative AI Engineering
- Machine Learning — University of Michigan
- Deep Learning Specialization

## Connect

I'm interested in Data Scientist, Machine Learning Engineer, and Applied AI opportunities, as well as thoughtful collaborations around experimentation, graph learning, signal processing, and reliable ML systems.

- [LinkedIn](https://www.linkedin.com/in/harshith-devaraja-087ba0228)
- [Portfolio](https://harshith-portfolio.vercel.app/)
- [Email](mailto:harshikollur302@gmail.com)

<div align="center">

*Build carefully. Evaluate honestly. Make the result useful.*

</div>
