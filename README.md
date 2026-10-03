# Predicción de la Calidad del Vino mediante Características Fisicoquímicas

**Proyecto Integrador — Recursamiento 2026**
Extracción de Conocimiento en Bases de Datos — Universidad Tecnológica de Tula-Tepeji
Alumno: Alberto Yael Zongua Hernández — Ingeniería en Desarrollo y Gestión de Software, Grupo 10 IDGS-G1
Docente: Ing. José Luis Herrera Gallardo, MTI

## Descripción

Este proyecto busca modelar la relación entre las propiedades fisicoquímicas del vino verde portugués (tinto y blanco) y su calidad sensorial, mediante técnicas de regresión, clasificación y análisis no supervisado, con el fin de apoyar el control de calidad en la producción vitivinícola sin depender exclusivamente de paneles de cata.

## Dataset

- **Nombre:** Wine Quality
- **Fuente:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/186/wine+quality)
- **Archivos:** `data/raw/winequality-white.csv` (4,898 registros) y `data/raw/winequality-red.csv` (1,599 registros)
- **Variables:** 11 características fisicoquímicas (entrada) + `quality` (salida, escala 0–10)
- **Cita:** Cortez, P., Cerdeira, A., Almeida, F., Matos, T., & Reis, J. (2009). *Modeling wine preferences by data mining from physicochemical properties*. Decision Support Systems, 47(4), 547–553.

## Objetivo general

Desarrollar un proceso de análisis de datos que permita modelar la relación entre las propiedades fisicoquímicas del vino y su calidad sensorial, mediante regresión, clasificación y análisis no supervisado.

## Metodología

El proyecto sigue **CRISP-DM** (Cross Industry Standard Process for Data Mining): comprensión del negocio, comprensión de los datos, preparación de los datos, modelado, evaluación y despliegue.

## Variables objetivo

- **Regresión:** `quality` (puntuación continua, 0–10).
- **Clasificación:** `quality` discretizada en tres categorías — baja (≤5), media (=6), alta (≥7).

## Estructura del repositorio

```
.
├── data/
│   └── raw/              # Dataset original, sin modificar
├── docs/                 # Entregables del recursamiento (PDF de cada unidad)
├── notebooks/            # Notebooks de exploración y modelado
├── src/                  # Scripts reutilizables (limpieza, features, modelos)
└── README.md
```

## Herramientas

Python · pandas · NumPy · scikit-learn · matplotlib / seaborn · Jupyter Notebook / Google Colab · SQLite · Git / GitHub · Power BI / Plotly

## Cronograma del recursamiento

| Fecha | Unidad | Valor |
|---|---|---|
| 25 sept 2026 | Actividad 0 — Inicio y registro | Seguimiento |
| 2 oct 2026 | Unidad I — Planeación del proyecto | 20% |
| 16 oct 2026 | Unidad II — Preparación de datos | 15% |
| 30 oct 2026 | Unidad III — Análisis supervisado | 25% |
| 13 nov 2026 | Unidad IV — Análisis no supervisado | 25% |
| 20 nov 2026 | Unidad V — Cierre y dashboard | 15% |