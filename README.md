# sprint7
Proyecto de Sprint 7 


# Análisis Exploratorio de Datos de Autos Usados

Esta aplicación web, desarrollada con Streamlit, permite realizar un análisis exploratorio interactivo sobre un conjunto de datos de anuncios de vehículos usados en EE. UU.

## ¿Qué hace esta app?

- Carga y visualiza datos desde un archivo CSV (`vehicles_us.csv`).
- Permite al usuario generar:
  - Un histograma de la variable `odometer` (kilometraje del vehículo).
  - Un gráfico de dispersión (`scatter plot`) que relaciona `odometer` con `price`.
- Usa gráficos interactivos de Plotly para explorar los datos de forma visual y dinámica.

## Tecnologías utilizadas

- Python
- Pandas
- Plotly Express
- Streamlit

## Cómo ejecutar el proyecto

1. Clona este repositorio.
2. Crea un entorno virtual e instala las dependencias:
   ```bash
   pip install -r requirements.txt
3. Ejecuta la app:
    streamlit run app.py

## Estructura del proyecto

sprint7/
├── app.py
├── vehicles_us.csv
├── notebooks/
│   └── EDA.ipynb
└── README.md

## Notas Finales
Este proyecto forma parte del Sprint 7 del bootcamp de análisis de datos, y busca simular el desarrollo de una aplicación web de visualización de datos para un cliente potencial.