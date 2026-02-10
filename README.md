# hitl-nursing-ml
# Human-in-the-Loop Machine Learning for Nursing Education

This repository contains a technical prototype for classifying nursing students'
clinical decisions and rationales using machine learning and transformer models
(DistilBERT and T5). A human-in-the-loop (HITL) loop is implemented to simulate
educator corrections and incremental model retraining.

## Contents

- notebooks/
  - 01_generate_dataset.ipynb
  - 02_train_baseline_models.ipynb
  - 03_hitl_simulation.ipynb
  - 04_evaluation_and_figures.ipynb

- src/
  - generate_data.py
  - models.py
  - hitl_loop.py
  - evaluation.py
  - utils.py

- data/
  - synthetic_scenarios.csv

## How to run

1. Open the notebooks in order (01 → 04)
2. Run each cell from top to bottom
3. The HITL loop and transformer models will train automatically
4. Evaluation plots will be saved in the figures/ folder

## Requirements

- Python 3.9+
- Jupyter Notebook
- PyTorch
- Transformers
- Scikit-learn
- Pandas
- Matplotlib
