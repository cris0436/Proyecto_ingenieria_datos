# ing_datos

Proyecto académico de ETL como parte de una práctica de ciencia de datos.

## Autor
Johan Rodriguez y Cristian Cabezas

## data base
https://data.cdc.gov/National-Institute-for-Occupational-Safety-and-Hea/Prevalence-of-Hearing-Loss-in-the-United-States-by/a2mg-p2ni/about_data?CDC_AA_refVal=https%3A%2F%2Fwww.cdc.gov%2Fniosh%2Fdata%2Fdatasets%2Fsd-1001-2014-0%2Fdefault.html


## Project Organization

```
├── LICENSE            <- License of the project
├── HISTORY.md         <- The HISTORY changes track
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
└── etl   <- Source code for use in this project.
    │
    ├── __init__.py             <- Makes etl a Python module
    │
    ├── config.py               <- Store useful variables and configuration
    │
    ├── dataset.py              <- Scripts to download or generate data
    │
    ├── features.py             <- Code to create features for modeling
    │
    ├── modeling                
    │   ├── __init__.py 
    │   ├── predict.py          <- Code to run model inference with trained models          
    │   └── train.py            <- Code to train models
    │
    └── plots.py                <- Code to create visualizations
```

## Requirements
Python 3.13

## Licencia
MIT license