# Object detection in dense scene with SKU-110 dataset

## Project Organization

------------

    ├── README.md          <- The top-level README for developers using this project.
    ├── env                <- CI configuration
    ├── datasets
    │   └── sku110       <- Name of the dataset
    │       ├── images        <- Intermediate data that has been transformed.
    │       └── annotations      <- The final, canonical data sets for modeling.
    │
    ├── docs               <- Documentation of the project design, engineering method, etc...
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering)
    │                         and a short `-` delimited description, e.g.
    │                         `1.0-initial-data-exploration`.
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
    └── src                <- Source code for use in this project.
       ├── __init__.py    <- Makes src a Python module
       │
       ├── data           <- Scripts to download or generate data
       │   └── make_dataset.py
       │
       ├── features       <- Scripts to turn raw data into features for modeling
       │   └── build_features.py
       │
       ├── models         <- Scripts to train models and then use trained models to make
       │   │                 predictions
       │   ├── base_models.py         <- Abtract classes that implemented models should inherit from. 
       │
       └── visualization  <- Scripts to create exploratory and results oriented visualizations
           └── visualizer.py

--------
