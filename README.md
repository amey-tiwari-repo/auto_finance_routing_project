LendingClub Loan Data (https://www.kaggle.com/datasets/wordsforthewise/lending-club)
L&T Vehicle Loan Default Prediction (https://www.kaggle.com/datasets/mamtadhaker/lt-vehicle-loan-default-prediction)


project-root/
│
├── data/
│   ├── original/              # Raw datasets (LendingClub, L&T)
│   └── processed/             # Cleaned & feature-engineered datasets
│
├── models/                    # Saved ML models
│
├── output/
│   ├── plots/
│   │   ├── eda/
│   │   │   ├── lc/            # LendingClub EDA plots
│   │   │   └── lt/            # L&T EDA plots
│   │   │
│   │   └── training/
│   │       ├── lc/            # LendingClub training plots
│   │       └── lt/            # L&T training plots
│   │
│   └── tables/
│       └── eda/               # EDA summary tables
│
├── notebooks/                 # Jupyter notebooks
├── src/                       # Core pipeline code
└── README.md


data/
├── original/
│   ├── lending-club/
│   │   └── accepted_2007-2018Q4.csv
│   │
│   ├── lt-vehicle-loan-default-prediction/
│   │   ├── train.csv
│   │   ├── test.csv
│   │   └── data_dictionary.csv
│   │
│   └── processed/


