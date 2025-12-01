# Digital Twin for CNC Tool Wear Monitoring

This project develops a data-driven **digital twin** for CNC tool-wear monitoring using multi-sensor machining data. It integrates a Random Forest wear classifier, an economic cost model, and a runtime simulation to optimize inspection decisions.

## Contents
- `digital_twin_aqc_miniproject.py` — Full project code  
- `tool_wear_dataset.csv` — Preprocessed sensor dataset  
- `Figures/` — Generated plots  
- Full report (PDF)

## Highlights
- Multi-sensor wear prediction (ROC–AUC = **1.0**)  
- Cost-based inspection optimization  
- Pareto analysis of cost vs inspection rate  
- Digital twin simulation with cumulative cost tracking  

## Run
```bash
python digital_twin_aqc_miniproject.py
