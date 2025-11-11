# Machine Learning in Pharmacology

Hi, I'm Mohammad Ghazi Vakili. I keep this repo as the hub for my “Machiine Learning in Pharmacology” lecture and the matching Python lab I share with students.

## Why this repo exists

- I wanted one place where I can update the slides of Linear Regression (`teaching_LR_v2.pdf`) without emailing attachments every week.
- The `pharmacology_linear_regression_lab/` folder holds the lab starter kit I walk through in Lab sessions (datasets, notebooks, requirements).

## How I run the lab

1. Make sure Python 3.10+ is installed on the teaching laptop or Colab (when available).
2. Drop into `pharmacology_linear_regression_lab/`, create a fresh virtual environment, and install the requirements.
3. Launch `jupyter lab` (or Notebook) and open each notebook in numerical order—everything is written for students new to Python.

## Quick map of the repo

```
.
├── README.md                        # You are here
├── teaching_LR_v2.pdf               # Lecture deck on QSAR + linear regression
└── pharmacology_linear_regression_lab/
    ├── README.md                    # Detailed lab instructions
    ├── data/                        # CSV files used in the exercises
    ├── notebooks/                   # 01–05 linear regression examples with solutions
    └── requirements.txt             # Minimal stack for the lab
```

If you build on this material (e.g., add gradient descent or nonlinear models), let me know so I can credit you in class.
