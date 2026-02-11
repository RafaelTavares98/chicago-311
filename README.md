# **Chicago 311 — Applied Analytics**

This repository is an **applied study** of **Data Science** and **ML Engineering**, using [Chicago 311 Service Requests data](https://data.cityofchicago.org/Service-Requests/311-Service-Requests/v6vf-nfxy/about_data). 

---

## **Study Roadmap**

**Core Objective:** Simulate the **end-to-end lifecycle of an Intelligence Solution**, meant to be used for planning and management teams, through:

- A **Data Science study case**, using **CRISP-DM** oriented methodology.

- A **production-ready solution**, applying MLOps princpiples like automated pipelines, monitoring and IaC.

### **1 — First Cycle**

End-to-end flow, from data to serving, with the following order:

`Preprocess → EDA → Modeling → App`

- **Preprocess** — download, consolidate, create a ready-to-use file.
- **EDA** — broad exploratory analysis that supports all downstream use cases
- **Forecasting** — analysis, modeling and evaluation of different forecasting models(e.g. ARIMA, Prophet, LightGBM).
- **production-ready solution MVP** —  App with MLOps principles, featuring a plug-and-play architecture for scalable deployment.

### **2 — Ongoing development and integration**

Using what was learned and the IaC, continue further exploration and modeling of complementary problems then **develop and integrate** into the existing pipeline:

#### **Intended Modeling Examples**

- Spike / Anomaly Detection  
- SLA Breach Risk Scoring
- Demand Clustering / Segmentation  
- Production Demand Inference 
- Crew Allocation Optimization  
- Policy Backtesting & Simulation  

---

## **Dataset Context**

The [Chicago 311 Service Requests data](https://data.cityofchicago.org/Service-Requests/311-Service-Requests/v6vf-nfxy/about_data) was selected due to:

- Compatibility with automated pipelines and end-to-end MLOps integration
- High quality, large-scale, real-world operational data 
- Geospatial attributes allowing spatial aggregation and mapping  

