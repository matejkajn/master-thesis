# Interpretation of black-box predictive models focused on categorical variables

This repository contains materials for the master thesis **"Interpretation of black-box predictive models focusing on categorical variables"**. 
The main goal of the thesis is to investigate the applicability of interpretability methods on categorical data.

The thesis was written under **Prague University of Economics and Business** on Faculty of Informatics and Statistics

## Contents

The repository contains:
1. Jupyter notebook using Mushroom dataset: **`mushroom.ipynb`**
    - Task: Binary classification
    - https://archive.ics.uci.edu/dataset/73/mushroom
    - Variables: Only categorical
    - Encoding Technique: One-Hot encoding
    - Class target: ['poisonous', 'edible']
    - Model: Random Forest Classifier
   
3. Jupyter notebook using Nursery dataset: **`nursery.ipynb`**
    - Task: Multi-class classification
    - https://archive.ics.uci.edu/dataset/76/nursery
    - Variables: Only categorical
    - Encoding Technique: Ordinal encoding
    - Class target: ['not_recommended', 'priority', 'special_priority']
    - Model: Multi-layer Perceptron Classifier
   
Data for specific Jyputer notebook can be found in **`data`** file

## Requirements

To run the notebooks, you need:
- Python 3.8 or newer.
- Packages listed in the `requirements.txt` file (e.g., `pandas`, `numpy`, `matplotlib`, `shap`, etc.).

You can install the packages using the command:
```bash
pip install -r requirements.txt
```

## How to Run the Notebooks

1. Clone this repository:
   ```bash
   git clone https://github.com/matejkajn/master-thesis.git
   ```
2. Install the required packages.
3. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Open the desired notebook (`mushroom.ipynb.ipynb` or `nursery.ipynb`).

## Author

Bc. Jonáš Matějka<br />

Study programme: Knowledge and Web Technologies<br />
Specialization: Quantitative Methods in Management<br />

