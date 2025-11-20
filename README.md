# 📱 PepIris — ML-Powered Retail Intelligence App

PepIris is a multi-market retail intelligence platform used for SKU detection, KPI computation, and shelf analytics.  
It combines **React Native**, **Turbo Modules**, **ONNX**, **Node.js**, and **Django REST** into a unified on-device + cloud ML workflow.

---

## 🔧 Tech Stack

### **Mobile**
- React Native  
- Turbo Modules  
- ONNX Runtime (on-device ML inference)

### **Backend**
- Node.js Function Apps (KPI engine)  
- Python Django REST Framework (ML workflows + ingestion)

### **Infrastructure**
- AWS CI/CD  
- Model rollout automation  
- Multi-environment deployment

---

## 🎯 Key Contributions

- Integrated ONNX models inside React Native via **Turbo Modules** for real-time sku/product recognition  
- Optimized ML inference pipeline for lower latency on both Android & iOS  
- Built **Node.js services** for KPI calculations, metric aggregation, and regional data logic  
- Designed and developed **Django REST APIs** for ML model lifecycle, data ingestion, and pipeline coordination  
- Created **HLD/LLD** for new features and worked closely with backend + ML teams  
- Automated CI/CD flows with MLOps to improve reliability of ML releases across markets

---

## 🧩 Architecture Overview

### Below is a clean, readable architecture flow:

React Native App

↓

Turbo Module

↓

ONNX Runtime

↓

Node.js KPI Engine

↓

Django ML Pipeline

↓

Azure Cloud


---


---

## ⭐ Outcome

- Fast, reliable SKU analysis using **local inference**  
- Lower latency during product recognition  
- Accurate KPI computation across multiple markets  
- Stable ML model rollout with automated CI/CD  
- Better cross-team collaboration via clear system designs  

---

## 📌 Status

This project is documented as a **case study only** (no proprietary code included).  
