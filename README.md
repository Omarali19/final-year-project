## A Data Science Approach to Football: Performance Analysis, Predictive Modelling and Visualisation

Final Year Project analysing 7,462 football matches across Premier League, Bundesliga, and La Liga (2018-2025 seasons). Complete data science pipeline from acquisition to predictive modeling and interactive dashboard.

# Objectives
1. **Produce and validate** a comprehensive football match dataset (7 seasons, 3 leagues)
2. **Identify and quantify** key performance patterns (home advantage, league differences)
3. **Develop and evaluate** engineered features capturing team form and momentum
4. **Determine comparative effectiveness** of ML approaches for match outcome prediction
5. **Provide explainable insights** into influential match factors
6. **Deliver an interactive dashboard** for stakeholder exploration

# Current Progress & Status

| Phase | Status | Key Outputs |
|-------|--------|-------------|
| **Data Acquisition & Processing** | ✅ Complete | `all_leagues_clean.csv` - 7,462 matches |
| **Exploratory Data Analysis** | ✅ Complete | EDA report, visualisations, key insights |
| **Feature Engineering** | ✅ Complete | `modeling_dataset.csv` - 20+ predictive features |
| **Predictive Modelling** | Next Phase | Model training and evaluation |
| **Dashboard Development** | Pending | Streamlit interactive application |

# Repository Structure
final-year-project/

├── data/ # Data files

│ ├── raw/ # Original downloaded data

│ └── processed/ # Cleaned and engineered data

├── notebooks/ # Analysis notebooks (run in order)

│ ├── 01_data_collection.ipynb

│ ├── 02_eda.ipynb

│ ├── 03_feature_engineering.ipynb

│ └── 04_model_training.ipynb (coming soon)

├── src/ # Source code

│ └── preprocessing.py # Data cleaning functions

├── output/ # Analysis outputs & visualizations

├── requirements.txt # Python dependencies

└── README.md # This file




