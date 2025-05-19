College Stress and Mental Health
==============================

This project will explore the impact of academic stress on mental health in college students, primarily during and after the COVID-19 pandemic. I will use collect information from a dataset surveyed from the Healthy Minds Study, after cleaning, analyzing, and modeling the dataset.

==============================

Dependencies

The project uses these libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- jupyter
=========================

Setting up the Environment
1. Create a virtual environment using venv
2. Install all required packages (pip install -r requirements.txt)

Running the data processing pipeline
1. Run the raw data from data/raw/
2. Clean and format the data
3. Save the cleaned version to data/processed/

Evaluating models
1. Run train_model.py to train the model using the processed data.
2. Run predict_model.py to create predictions and save it into reports/

Reproducing results
1. Follow the above steps in order. 
========================

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- This file
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Cleaned data used for modeling
    │   ├── processed      <- The final version of data
    │   └── raw            <- Original HMS dataset
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks: EDA, testing, regression analysis
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


--------

<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
