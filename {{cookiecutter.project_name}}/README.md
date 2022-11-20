{{cookiecutter.project_name}}
==============================

{{cookiecutter.description}}

Project Organization
------------

    ├── data
    │   ├── external                 <- Data from third party sources.
    │   ├── final                    <- Final data to be used in training.
    │   ├── processed                <- The intermediate data.
    │   └── raw                      <- The original, immutable data dump.
    │    
    ├── models                       <- Trained models anc checkpoints.
    │
    ├── notebooks                    <- Jupyter notebooks. Naming convention is a number (for ordering) and description.
    │
    ├── requirements_dev.txt         <- The requirements file for development env e.g.
    │                                   generated with `pip freeze > requirements_dev.txt`.
    ├── requirements_prod.txt        <- The requirements file for production env e.g.
    │                                   generated with `pip freeze > requirements_prod.txt`.
    │
    ├── src                          <- Source code for use in this project.
    │   ├── __init__.py              <- Makes src a Python module.
    │   │
    │   ├── data                     <- Scripts to download or generate data.
    │   │   ├── prepare_data.py      <- Preparing data for training.
    |   |   └── __init__.py          <- Making the folder a package.
    │   │
    │   ├── features                 <- Scripts to turn raw data into features for modeling.
    │   │   ├── generate_features.py <- Creating features for training.
    │   │   └── __init__.py          <- Making the folder a package.
    │   │
    │   ├── training                 <- Scripts to train models
    │   │   ├── train.py             <- A script to train model
    │   │   └── __init__.py          <- Making the folder a package.
    │   │
    │   └── evaluation               <- Model Validation and evaluation things
    │      ├── test.py               <- A script to train model
    │      └── __init__.py           <- Making the folder a package.
    │   
    │
    └── README.md                    <- The top-level README for developers using this project.

------------
