# hitl-nursing-ml
# Human-in-the-Loop Machine Learning for Nursing Education

This repository contains a technical prototype for classifying nursing student
clinical decisions and rationales using machine learning and transformer models
(DistilBERT and T5). A human-in-the-loop (HITL) loop is implemented to simulate
educator corrections and incremental model retraining.

## Repository Structure

- data/
  - synthetic_scenarios.csv

- notebooks/
  - 01_generate_dataset.ipynb
  - 02_train_baseline_models.ipynb
  - 03_train_distilbert.ipynb
  - 04_train_t5.ipynb
  - 05_hitl_simulation.ipynb
  - 06_evaluation_and_figures.ipynb

## How to Run

1. Open the notebooks in order (01 → 06)
2. Run each cell from top to bottom
3. The HITL loop and transformer models will train automatically
4. Evaluation plots will be generated in the notebook

## Requirements

- Python 3.9+
- Jupyter Notebook
- PyTorch
- Transformers
- Scikit-learn
- Pandas
- Numpy
- Matplotlib
