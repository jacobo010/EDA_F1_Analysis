# EDA F1 Analysis

<p align="center">
  <img src="src/img/f1_image.png" width="500" height="400" alt="Logo de Fórmula 1 y análisis EDA" />
</p>

---
Versiones del proyecto:
- [ES](#spanish-version)
- [EN](#english-version)
---

## Spanish version
## Descripción del proyecto

Este proyecto desarrolla un **Análisis Exploratorio de Datos (EDA)** sobre la historia de la Fórmula 1, con el objetivo de evaluar el impacto del equipo en el rendimiento de un piloto.

Se combinan técnicas de:

- Web scraping
- Limpieza y transformación de datos
- Integración de múltiples datasets
- Análisis exploratorio
- Estadística inferencial

---

## Hipótesis principal

> ¿Influye significativamente el equipo en el que compite un piloto en sus probabilidades de convertirse en campeón del mundo de Fórmula 1?

---

## Objetivos

- Identificar los equipos y pilotos más exitosos históricamente.
- Analizar la frecuencia de victorias y podios.
- Estudiar la distribución de posiciones finales.
- Evaluar diferencias estadísticamente significativas entre equipos mediante ANOVA.
- Explorar la relación entre piloto, constructor y rendimiento.

---

## Tecnologías utilizadas
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/BeautifulSoup-43B02A?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Requests-2CA5E0?style=flat&logo=python&logoColor=white" />
</p>

---

## Estructura del proyecto

```
├── src/
│ ├── utils/ # Funciones y archivos utilitarios
│ ├── main.ipynb # Notebook principal
│ ├── data/ # Datos crudos
│ ├── img/ # Imágenes y recursos gráficos
│ └── notebooks/ # Notebooks de limpieza y análisis de los datos
└── README.md # Documentación principal
```

---

## Metodología

### Web scraping

- Extracción de campeones del mundo de pilotos y constructores desde Wikipedia.
- Limpieza y estructuración de los datos obtenidos.
- Integración con el dataset principal.

### Limpieza y preparación de datos

- Eliminación de columnas irrelevantes.
- Tratamiento de valores nulos.
- Unificación de múltiples tablas mediante `merge`.
- Creación de un dataset analítico consolidado.

### Análisis exploratorio

- Distribución de variables categóricas.
- Identificación de equipos con mayor participación histórica.
- Conteo de victorias y podios.
- Análisis de estados de carrera.
- Comparaciones piloto–equipo.

### Análisis estadístico

Se aplicó una prueba **ANOVA de un factor** para determinar si existen diferencias estadísticamente significativas en el rendimiento promedio entre distintos equipos.

---

## Principales hallazgos

- **Dominancia histórica:** Algunos equipos lideran consistentemente.  
- **Consistencia vs campeonatos:** Relación fuerte entre equipo y títulos.  
- **Brecha de rendimiento:** Diferencias notables entre equipos top e intermedios.  
- **Evidencia estadística:** ANOVA respalda diferencias entre constructores.

---

## Posibles mejoras futuras

- Segmentación por eras (V8, turbo , híbrida).  
- Modelos predictivos de probabilidad de campeonato.  
- Análisis de correlación entre clasificación y resultado final.  
- Desarrollo de dashboard interactivo (Streamlit o Power BI).

---

## English version

> **Note:** The main notebook (`main.ipynb`) is only available in Spanish. The english version will be available in the future.

## Project description

This project develops an **Exploratory Data Analysis (EDA)** on the history of Formula 1, aiming to evaluate the impact of the team on a driver's performance.

The project combines techniques such as:

- Web scraping
- Data cleaning and transformation
- Integration of multiple datasets
- Exploratory analysis
- Inferential statistics

---

## Main hypothesis

> Does the team a driver competes for significantly influence their chances of becoming a Formula 1 World Champion?

---

## Objectives

- Identify historically successful teams and drivers.
- Analyze the frequency of wins and podiums.
- Study the distribution of final positions.
- Evaluate statistically significant differences between teams using ANOVA.
- Explore the relationship between driver, constructor, and performance.

---

## Technologies Used
<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=matplotlib&logoColor=white" />
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=flat&logo=scipy&logoColor=white" />
  <img src="https://img.shields.io/badge/BeautifulSoup-43B02A?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white" />
  <img src="https://img.shields.io/badge/Requests-2CA5E0?style=flat&logo=python&logoColor=white" />
</p>

---

## Project structure
```
├── src/
│ ├── utils/ # Utility functions and scripts
│ ├── main.ipynb # Main notebook
│ ├── data/ # Raw data
│ ├── img/ # Images and graphical resources
│ └── notebooks/ # Data cleaning and analysis notebooks
└── README.md # Main documentation
```

---

## Methodology

### Web scraping

- Extracted driver and constructor World Champions from Wikipedia.
- Cleaned and structured the extracted data.
- Integrated the information with the main dataset.

### Data cleaning and preparation

- Removed irrelevant columns.
- Handled missing values.
- Merged multiple tables to create a consolidated analytical dataset.

### Exploratory analysis

- Distribution of categorical variables.
- Identification of teams with the highest historical participation.
- Count of wins and podiums.
- Analysis of race statuses.
- Driver–team comparisons.

### Statistical analysis

A **one-way ANOVA** was applied to determine if there are statistically significant differences in average performance between different teams.

---

## Key findings

- **Historical dominance:** Some teams consistently lead.  
- **Consistency vs championships:** Strong relationship between team and titles.  
- **Performance gap:** Notable differences between top and mid-tier teams.  
- **Statistical evidence:** ANOVA supports differences between constructors.

---

## Possible future improvements

- Segmentation by eras (V8, Turbo, Hybrid).  
- Predictive models for championship probability.  
- Analysis of correlation between qualifying and final results.  
- Development of an interactive dashboard (Streamlit or Power BI).

---
