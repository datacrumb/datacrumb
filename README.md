<img width="100%" src="https://media2.dev.to/dynamic/image/width=800,height=200,fit=cover,gravity=auto,format=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2F4e0d816kuzyu700pdbjn.png" alt="Banner" />

# Data Science

I'm a data scientist who works at the seam between messy production data and decisions people actually act on. Most of my time goes into supervised learning for churn, demand, and risk problems — gradient boosting and transformer fine-tuning where they earn their keep, plain logistic regression where they don't — plus the unglamorous work around it: point-in-time-correct feature pipelines, leakage audits, and calibration checks that keep a model honest after month three. I'm equally comfortable writing the SQL that defines a metric, the PyTorch training loop that models it, and the FastAPI service that serves it under a latency budget.

I believe a model is only as good as the decision it changes, so I start from the counterfactual: what would happen without this, and how would we know? That means baselines before architectures, holdout designs that survive contact with seasonality, and experiments that measure the business outcome rather than a proxy that flatters the model. I write down assumptions where reviewers can see them, prefer an interpretable model I can defend to a stakeholder over a half-point of AUC I can't, and treat monitoring and drift alerts as part of shipping rather than a follow-up ticket. Good analysis should also be legible — I aim for a chart and three sentences that a non-technical reader can repeat correctly.

### 🛠️ Tech Stack & Skills

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white) ![R](https://img.shields.io/badge/R-6366f1?style=for-the-badge&logo=r&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit-learn-6366f1?style=for-the-badge&logo=scikit-learn&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-6366f1?style=for-the-badge&logo=tensorflow&logoColor=white) ![Anaconda](https://img.shields.io/badge/Anaconda-6366f1?style=for-the-badge&logo=anaconda&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![AWS](https://img.shields.io/badge/AWS-6366f1?style=for-the-badge&logo=aws&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![Jupyter](https://img.shields.io/badge/Jupyter-6366f1?style=for-the-badge&logo=jupyter&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-6366f1?style=for-the-badge&logo=pandas&logoColor=white) ![Apache Spark](https://img.shields.io/badge/Apache%20Spark-6366f1?style=for-the-badge&logo=apachespark&logoColor=white) ![MLflow](https://img.shields.io/badge/MLflow-6366f1?style=for-the-badge&logo=mlflow&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-6366f1?style=for-the-badge&logo=airflow&logoColor=white) 

### 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats-ten-kohl-77.vercel.app/api?username=alexrivera-ai&show_icons=true&theme=dark" alt="GitHub Stats" />
  <img src="https://github-readme-stats-ten-kohl-77.vercel.app/api/top-langs/?username=alexrivera-ai&layout=compact&theme=dark" alt="Top Languages" />
</p>

### 💡 Expertise
Predictive Modeling & Machine Learning — I build and tune supervised models for tabular, time-series, and text problems, from regularized GLMs and gradient-boosted trees to fine-tuned transformers, with disciplined cross-validation and probability calibration.

Experimentation & Causal Inference — I design and analyze A/B tests, switchback trials, and quasi-experiments using CUPED, difference-in-differences, and uplift modeling to separate real treatment effects from selection and seasonality.

Feature Engineering & Data Pipelines — I turn raw event and transactional data into reproducible, point-in-time-correct feature sets with SQL, Spark, and orchestrated Airflow DAGs that the same code can serve at training and inference time.

Model Deployment & Monitoring — I package models behind versioned APIs in Docker, track runs and artifacts in MLflow, and instrument drift, calibration, and latency alerts so degradation is caught before stakeholders notice it.

### 🚀 Featured Projects
Churn Uplift Model — Two-model uplift learner (T-learner over XGBoost) trained on 480K subscriber histories that raised retention-campaign ROI 31% while targeting half as many customers.

Demand Forecasting — LightGBM ensemble with a seasonal-naive baseline across 1,200 SKU-store pairs cut weekly forecast MAPE from 18.4% to 9.7% and released $240K of safety stock.

Feature Store — Airflow and Feast pipeline serving 340 point-in-time-correct features that reduced training-set assembly from 6 hours to 11 minutes and eliminated three known leakage paths.

Sequential A/B Engine — mSPRT sequential testing with CUPED variance reduction shortened median experiment runtime from 21 to 12 days at unchanged 80% power and 5% false-positive rate.

Ticket Triage NLP — Fine-tuned DistilBERT classifier over 90K support tickets reached 0.91 macro-F1 and auto-routes 62% of inbound volume at 34 ms p95 inference on CPU.

Fraud Anomaly Detection — Isolation Forest combined with graph-derived device and payee features catches 87% of confirmed payment fraud at a 0.4% false-positive rate, avoiding roughly $1.1M in annual losses.

### 🌐 Connect With Me

[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />](https://linkedin.com/in/alex-rivera-dev) [<img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white" />](https://x.com/alexrivera_tech) [<img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" />](mailto:alex.rivera@techcraft.io) [<img src="https://img.shields.io/badge/Website-4338CA?style=for-the-badge&logo=googlechrome&logoColor=white" />](https://alexrivera.dev)
