---
title: "Binary Drought-Event Classifier"
summary: "End-to-end ML pipeline that converts hydro-climate signals (incl. soil moisture) into binary drought events with XAI (SHAP/LIME)."
date: 2024-10-01
tags: ["Drought","Soil Moisture","Machine Learning","XAI"]
links:
  - icon: "code"
    icon_pack: "fas"
    name: "GitHub"
    url: "https://github.com/Mamadiarrabousso/binary-drought-event-classifier"
# image:
#   filename: "featured.jpg"
#   focal_point: "center"
---
**Goal.** Classify each timestep as *drought / not-drought* for early warning.  
**Pipeline.** preprocessing → feature engineering → model training (e.g., tree-ensembles/XGBoost) → class-imbalance handling → evaluation (PR-AUC/F1).  
**Explainability.** Global + local insights via SHAP/LIME to show the drivers of flagged drought events.
