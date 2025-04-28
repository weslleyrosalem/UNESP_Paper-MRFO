# UNESP_Paper-MRFO-LSTM-AIOps  

**Aplicação do Algoritmo MRFO para Otimização de Redes LSTM em Previsão Eficiente de Séries Temporais no Contexto de AIOps**  
*Weslley Rosalem · Universidade Estadual Paulista (UNESP)*  

This repository bundles the **complete experimental pipeline** and the **LaTeX manuscript** that demonstrate how the bio-inspired **Manta Ray Foraging Optimization (MRFO)** algorithm boosts Long Short-Term Memory (LSTM) forecasting accuracy for AIOps workloads. Everything is 100 % reproducible and ready for extension.

---

## ✨ Why this repo matters
- **Pioneering MRFO for AIOps** – first public pipeline that marries MRFO with multivariate resource-usage prediction.  
- **Two real-world datasets** – Google Cluster Traces 2019 (memory-normalised) and Prometheus metrics from a production Linux server.  
- **Reproducible end-to-end** – one command downloads data, reruns every search, and rebuilds the paper’s tables/figures.  
- **Easy to extend** – drop-in new meta-heuristics or forecasting models with minimal boilerplate.

---

## 📄 Abstract 
> **ABSTRACT —** This study proposes an innovative approach for tuning Long Short-Term Memory (LSTM) hyper-parameters using the **Manta Ray Foraging Optimization (MRFO)** algorithm in the context of **Artificial Intelligence for IT Operations (AIOps)**. Evaluated on two real-world datasets—Google Cluster Traces 2019 and Prometheus metrics from a Linux server—MRFO outperformed Grid Search, Random Search, Particle Swarm Optimization (PSO), and a fixed-baseline configuration. For Google Cluster Traces, MRFO achieved **6.8 % lower MAE** and **13.6 % lower MAPE**; for Prometheus, it reduced **MAE by 6.1 %** and **RMSE by 9.0 %** versus the baseline. These gains enable proactive downtime avoidance and cost-predictable resource allocation. The proposed pipeline is the first to deploy MRFO in AIOps and releases a reproducible TensorFlow framework for multivariate forecasting. Future work targets hybrid meta-heuristics, anomaly detection, and log correlation for autonomous root-cause analysis, promising significant advances in data-center management.

---

## 📂 Repository layout
