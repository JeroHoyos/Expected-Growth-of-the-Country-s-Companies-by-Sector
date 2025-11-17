# 📈 Crecimiento Esperado de las Empresas del País por Sector  
### Participación en Datos al Ecosistema 2025

## 🏆 Sobre el proyecto  
Este repositorio corresponde a nuestra participación en **Datos al Ecosistema 2025**, una iniciativa de la Universidad Nacional de Colombia que busca transformar los datos abiertos en soluciones con impacto real.  
Desarrollamos este proyecto como respuesta al reto **“Crecimiento esperado de las empresas del país por sector”**, enfocado en estimar el crecimiento económico empresarial de Colombia a partir de información histórica.

---

## 🧩 Descripción del reto  
Actualmente, las entidades cuentan con reportes y cortes anuales que permiten entender *qué pasó* con las empresas, pero no disponen de un mecanismo predictivo que anticipe *qué pasará* en términos de crecimiento sectorial, proyecciones de ganancias o dispersión entre empresas.

El reto propone construir una solución basada en analítica descriptiva y predictiva para responder preguntas estratégicas como:
- ¿Qué sectores tienen mayor potencial de rentabilidad?
- ¿Cómo se proyectan las ganancias según tamaño o ubicación empresarial?
- ¿Qué patrones se evidencian entre sectores económicos?

---

## 🎯 Objetivo General  
Desarrollar un **modelo predictivo** capaz de estimar las **ganancias proyectadas** de las empresas del país, complementado con un **dashboard interactivo** que facilite la toma de decisiones estratégicas basadas en datos.

---

## 🔍 Objetivos Específicos  

- **OE1.** Limpiar, procesar y analizar el set de datos de las 10.000 empresas más grandes del país.  
- **OE2.** Explorar técnicas de *machine learning* para generar un modelo predictivo de ganancias o crecimiento.  
- **OE3.** Validar el modelo mediante métricas de desempeño.  
- **OE4.** Desarrollar un dashboard interactivo que permita consultar resultados por sector, ubicación o tamaño empresarial.  
- **OE5.** Generar una herramienta que apoye la toma de decisiones basada en datos.  

---

## 🚀 Impacto esperado  
- Fortalecer la capacidad institucional para analizar y proyectar el desempeño empresarial.  
- Identificar sectores con mayor potencial de crecimiento económico.  
- Facilitar la visualización de proyecciones y comparativas mediante herramientas interactivas.  


Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
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
"# Expected-Growth-of-the-Country-s-Companies-by-Sector" 
