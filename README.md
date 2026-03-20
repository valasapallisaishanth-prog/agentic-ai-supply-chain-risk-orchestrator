# Agentic AI Supply Chain Risk Orchestrator

## Overview

This project builds a **hybrid ML + Agentic AI system** for supply chain delay prediction and mitigation, combining predictive modeling with multi-agent reasoning to enable decision intelligence in operational workflows.

Unlike traditional ML systems that only output predictions, this system identifies **root causes** and generates **actionable recommendations** using specialized agents.

---

##  Key Highlights

- Built a **multi-agent system** (Inventory, Logistics, Manager)
- Integrated **Random Forest, Logistic Regression, Gradient Boosting**
- Designed a **hybrid ML + agent decision framework**
- Performed **threshold tuning and business-aware evaluation**
- Conducted **error analysis and slice-based performance analysis**
- Developed a **Streamlit demo application** for real-time interaction

## Architecture
Input Shipment Data
        ↓
Feature Engineering Layer
        ↓
ML Model (Random Forest / Gradient Boosting)
        ↓
-----------------------------------------
| Inventory Agent | Logistics Agent |
-----------------------------------------
        ↓
Manager Agent (Decision Orchestrator)
        ↓
Delay Prediction + Root Cause + Actions

## Results

The Hybrid ML + Agent System demonstarted improved performance in:
- Recall (important for detecting layers)
- Reduced false negatives
- Better decisions explainability
- Actionable recommendations beyond classification
