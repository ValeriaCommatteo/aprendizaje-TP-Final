![alt text](image.png)

## Tecnicatura Superior en Ciencia de Datos e Inteligencia Artificial
*Aprendizaje Automático
*Autor: Valeria Commatteo

Machine Learning Model: "Prediccion de Produccion de Agua (Ushuaia - Rio Grande)"

## Objetivo del Proyecto: 
Desarrollar un modelo de Aprendizaje Automático que sea capaz de predecir la producción de agua en función de diferentes variables temporales, como el tiempo, y posiblemente otras como el clima y la demanda. La idea es que, a través de esta predicción, podamos anticipar posibles problemas en la producción de agua, lo que nos permitiría identificar con antelación situaciones en las que la producción no sea suficiente para cubrir la demanda. De este
modo, podríamos implementar mejoras operativas o realizar ajustes en el sistema de producción para prevenir estos eventos antes de que afecten a la población o a los recursos de la región. Este modelo será una herramienta valiosa para gestionar el suministro de agua de manera más eficiente, especialmente en un contexto donde la sostenibilidad y la optimización de los recursos hídricos son cada vez más importantes.

## Contexto y Relevancia:

## Preguntas de Investigación:

## Descripción del Dataset y Origen

## Herramientas utilizadas: 
            * Librerías pandas, numpy, matplotlib, Scikit-learn
            * Repositorio github, git
            * Lenguaje python
            * power bi, excel para ETL
            * Estructura cookiecutter

## Organización del proyecto
```
├── LICENSE            <- Open-source license if one is chosen
├── Makefile           <- Makefile with convenience commands like `make data` or `make train`
├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources.
│   ├── interim        <- Intermediate data that has been transformed.
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default mkdocs project; see mkdocs.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── pyproject.toml     <- Project configuration file with package metadata for {{ cookiecutter.module_name }}
│                         and configuration for tools like black
│
├── references         <- Data dictionaries, manuals, and all other explanatory materials.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.cfg          <- Configuration file for flake8
│
└── {{ cookiecutter.module_name }}                <- Source code for use in this project.
    │
    ├── __init__.py    <- Makes {{ cookiecutter.module_name }} a Python module
    │
    ├── data           <- Scripts to download or generate data
    │   └── make_dataset.py
    │
    ├── features       <- Scripts to turn raw data into features for modeling
    │   └── build_features.py
    │
    ├── models         <- Scripts to train models and then use trained models to make
    │   │                 predictions
    │   ├── predict_model.py
    │   └── train_model.py
    │
    └── visualization  <- Scripts to create exploratory and results oriented visualizations
        └── visualize.py
```

--------
