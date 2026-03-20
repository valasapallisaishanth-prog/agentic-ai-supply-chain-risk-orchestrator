# Agentic AI Supply Chain Risk Orchestrator

##  Overview

This project implements a **hybrid Machine Learning + Agentic AI system** for supply chain delay prediction and mitigation.

Unlike traditional ML models that only output predictions, this system combines **predictive modeling with multi-agent reasoning** to:

- Predict shipment delays
- Identify root causes (inventory vs logistics)
- Generate actionable operational recommendations

The goal is to move from **prediction → decision intelligence**, which aligns with real-world operational systems.

---

##  Problem Statement

In supply chain systems, shipment delays are influenced by multiple interacting factors:

- Inventory shortages
- Supplier reliability
- Logistics disruptions (weather, distance, carriers)
- Warehouse constraints
- Seasonal demand spikes

Traditional ML models provide predictions but **lack explainability and actionability**.

This project addresses that gap by integrating ML with specialized agents.

---


### Pipeline

1. **Input Data**
2. **Feature Engineering Layer**
3. **ML Model (Random Forest / Gradient Boosting)**
4. **Agent Layer**
   - Inventory Agent
   - Logistics Agent
5. **Manager Agent (Decision Orchestrator)**
6. **Final Output**
   - Delay Prediction
   - Root Cause
   - Recommended Actions

---

##  Agent Design

### Inventory Agent
Analyzes:
- Inventory coverage vs demand
- Supplier reliability
- Lead times
- Warehouse utilization

Outputs:
- Risk score
- Findings
- Recommended actions (e.g., replenishment, stock rebalancing)

---

### Logistics Agent
Analyzes:
- Shipping distance
- Weather severity
- Carrier performance
- Processing delays

Outputs:
- Risk score
- Findings
- Recommended actions (e.g., rerouting, carrier switch)

---

### Manager Agent
Combines:
- ML prediction probability
- Agent risk signals

Outputs:
- Final delay risk (Low / Medium / High)
- Primary root cause
- Action recommendations
- Reasoning summary

---

##  Machine Learning Models

- Logistic Regression (baseline)
- Random Forest (primary model)
- Gradient Boosting (ensemble model)

### Key Features

- Inventory-demand ratios
- Supplier and carrier reliability
- Distance-weather interactions
- Delivery pressure metrics
- Seasonal and category-based features

---

##  Evaluation Framework

The system compares multiple approaches:

- Rule-based baseline
- Agent-only system
- ML-only models
- ML + Agent hybrid system

### Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- False Negative Rate (critical for operations)

---

##  Results Summary

The hybrid ML + Agent system demonstrated:

- Improved **recall** (better detection of delays)
- Reduced **false negatives** (important for operations)
- Better **decision explainability**
- Actionable recommendations beyond classification

---

##  Business-Aware Analysis

To simulate real-world decision-making:

- Performed **threshold tuning** to prioritize recall
- Conducted **error analysis** (false positives / false negatives)
- Evaluated **high-priority shipment recall**
- Performed **slice analysis** across:
  - Shipment priority
  - Product category
  - Peak vs non-peak season

---


##  Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Streamlit

---

# Agentic AI Supply Chain Risk Orchestrator

## 🚀 Overview

This project implements a **hybrid Machine Learning + Agentic AI system** for supply chain delay prediction and mitigation.

Unlike traditional ML models that only output predictions, this system combines **predictive modeling with multi-agent reasoning** to:

- Predict shipment delays
- Identify root causes (inventory vs logistics)
- Generate actionable operational recommendations

The goal is to move from **prediction → decision intelligence**, which aligns with real-world operational systems.

---

## 🎯 Problem Statement

In supply chain systems, shipment delays are influenced by multiple interacting factors:

- Inventory shortages
- Supplier reliability
- Logistics disruptions (weather, distance, carriers)
- Warehouse constraints
- Seasonal demand spikes

Traditional ML models provide predictions but **lack explainability and actionability**.

This project addresses that gap by integrating ML with specialized agents.

---

## 🧩 System Architecture

![Architecture](assets/architecture.png)

### Pipeline

1. **Input Data**
2. **Feature Engineering Layer**
3. **ML Model (Random Forest / Gradient Boosting)**
4. **Agent Layer**
   - Inventory Agent
   - Logistics Agent
5. **Manager Agent (Decision Orchestrator)**
6. **Final Output**
   - Delay Prediction
   - Root Cause
   - Recommended Actions

---

## 🤖 Agent Design

### Inventory Agent
Analyzes:
- Inventory coverage vs demand
- Supplier reliability
- Lead times
- Warehouse utilization

Outputs:
- Risk score
- Findings
- Recommended actions (e.g., replenishment, stock rebalancing)

---

### Logistics Agent
Analyzes:
- Shipping distance
- Weather severity
- Carrier performance
- Processing delays

Outputs:
- Risk score
- Findings
- Recommended actions (e.g., rerouting, carrier switch)

---

### Manager Agent
Combines:
- ML prediction probability
- Agent risk signals

Outputs:
- Final delay risk (Low / Medium / High)
- Primary root cause
- Action recommendations
- Reasoning summary

---

## 🧠 Machine Learning Models

- Logistic Regression (baseline)
- Random Forest (primary model)
- Gradient Boosting (ensemble model)

### Key Features

- Inventory-demand ratios
- Supplier and carrier reliability
- Distance-weather interactions
- Delivery pressure metrics
- Seasonal and category-based features

---

## 📊 Evaluation Framework

The system compares multiple approaches:

- Rule-based baseline
- Agent-only system
- ML-only models
- ML + Agent hybrid system

### Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- False Negative Rate (critical for operations)

---

## 📈 Results Summary

The hybrid ML + Agent system demonstrated:

- Improved **recall** (better detection of delays)
- Reduced **false negatives** (important for operations)
- Better **decision explainability**
- Actionable recommendations beyond classification

---

## 🔍 Business-Aware Analysis

To simulate real-world decision-making:

- Performed **threshold tuning** to prioritize recall
- Conducted **error analysis** (false positives / false negatives)
- Evaluated **high-priority shipment recall**
- Performed **slice analysis** across:
  - Shipment priority
  - Product category
  - Peak vs non-peak season

---

## 🖥️ Demo (Streamlit App)

![Demo Screenshot](assets/demo_screenshot.png)

The interactive app allows:

- Input of shipment parameters
- Real-time delay prediction
- Agent-based root cause analysis
- Recommended actions for mitigation

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib
- Streamlit

---

## Key Insights 
• Prediction alone is insufficient for operational systems
• Combining ML with agent reasoning improves decision quality
• False Negatives are more costly than false positives in supply chains
• Hybrid systems enable both accuracy abd explainability

---

## Future Improvements
• Integrate LLM-based agents for dynamic reasoning
• Use real-world logistics datasets
• Deploy as a scalable microservice
• Add real-time streaming data integration

---

## Summary

This Project demonstrates how **Agentic AI systems can augment traditional ML Models** to provide explainable, actionable, and business0aligned decisions in complex-operatoional environments.

