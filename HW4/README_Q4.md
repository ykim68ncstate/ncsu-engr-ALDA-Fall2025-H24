# ANN Binary Classification

## (a) Environment Setup
- **Language:** Python 3.12.7
- **Libraries:**
 - TensorFlow 2.19.0
 - NumPy 2.3.2
 -Pandas 2.3.2
 - Matplotlib 3.10.6
- **Backend:** TensorFlow 2.x (CPU or GPU)

### Installation Example
python -m venv .venv
source .venv/bin/activate  # (Windows: .venv\Scripts\activate)
pip install --upgrade pip
pip install tensorflow pandas numpy matplotlib

## How to Execute
1) Put train.csv, val.csv, test.csv under ./data/
2) Run the notebook cells in order.
3) Check outputs: training logs, accuracy plot, validation summary, test accuracy.

## Deterministic Settings
Set the following before training:
PYTHONHASHSEED=2025, TF_DETERMINISTIC_OPS=1, and seeds for random/numpy/tensorflow=2025