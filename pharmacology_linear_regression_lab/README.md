# Pharmacology Linear Regression Lab

This mini-project accompanies the _Linear Regression in Pharmacology_ lecture. It provides five beginner-friendly Python exercises that connect pharmacology and pharmacokinetics questions to hands-on linear regression models.

## What's inside

```
pharmacology_linear_regression_lab/
├── data/                     # Clean CSV files for each scenario
├── notebooks/                # Step-by-step Jupyter notebooks with solutions
└── requirements.txt          # Minimal Python dependencies
```

## Datasets and notebooks

| Notebook                         | Topic                                                    | Dataset                            | Skills practiced                                                  |
| -------------------------------- | -------------------------------------------------------- | ---------------------------------- | ----------------------------------------------------------------- |
| `01_heart_rate_response.ipynb`   | Drug-induced heart rate change vs. dose, weight, and age | `data/heart_rate_response.csv`     | Multi-feature regression, coefficient interpretation              |
| `02_qsar_potency.ipynb`          | QSAR potency modeling (pIC₅₀ prediction)                 | `data/qsar_protease_potency.csv`   | Descriptor visualization, regression coefficients, simple scoring |
| `03_pk_elimination.ipynb`        | Estimating elimination rate from concentration-time data | `data/pk_concentration_time.csv`   | Log transforms, single-feature regression, half-life calculation  |
| `04_hepatic_clearance.ipynb`     | Predicting hepatic clearance during infusion             | `data/hepatic_clearance_study.csv` | Regression with pharmacokinetic units, model evaluation           |
| `05_renal_dose_adjustment.ipynb` | Renal dose adjustment helper                             | `data/renal_dose_adjustment.csv`   | Clinical covariates, simulations for new patients                 |

Each notebook contains:

- A short problem description linking back to the lecture slides.
- Clear bullet-point goals written for students with minimal Python experience.
- Fully worked code cells that can be re-run, tweaked, or extended in class.

## Getting started

1. **Create a virtual environment (recommended):**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # or .venv\Scripts\activate on Windows
   ```
2. **Install the minimal dependencies:**
   ```bash
   pip install -r requirements.txt
   ```
3. **Launch Jupyter:**
   ```bash
   jupyter lab  # or jupyter notebook
   ```
4. **Open each notebook in order** (`01_` to `05_`). Every notebook is self-contained, so you can also run them independently.
