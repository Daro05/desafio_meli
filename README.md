# Mercado Libre Challenge

## Descripción

Este repositorio contiene la solución al desafío técnico para Mercado Libre. El proyecto consta de dos partes principales:

1. **Análisis Exploratorio de Descuentos en el Marketplace:** Se realiza un análisis de las publicaciones con descuento utilizando la API pública de Mercado Libre.
2. **Modelado Predictivo de Ventas Históricas:** Se desarrolla un modelo para predecir la cantidad de ventas históricas (`sold_quantity`) de un producto en base a sus características.

## Estructura del Proyecto

```plaintext
desafio_meli/
│
├── README.md                   # Descripción del proyecto y cómo reproducirlo
├── data/                       # Scripts de descarga y preparación de datos
│   ├── raw/                    # Datos crudos descargados
│   └── processed/              # Datos procesados y listos para análisis/modelo
├── notebooks/                  # Notebooks Jupyter
│   ├── 01_exploratory_analysis.ipynb  # Análisis exploratorio de los datos
│   └── 02_modeling.ipynb       # Desarrollo del modelo de predicción
├── scripts/                    # Scripts para generar datasets y entrenar modelos
│   ├── data_preprocessing.py   # Preprocesamiento de datos
│   ├── feature_engineering.py  # Generación de features
│   └── train_model.py          # Script para entrenar y evaluar el modelo
└── requirements.txt            # Lista de dependencias para reproducir el proyecto
