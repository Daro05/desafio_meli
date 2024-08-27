# Mercado Libre Challenge

## Descripción

Este repositorio contiene la solución al desafío técnico para Mercado Libre. El proyecto consta de dos partes principales:

1. **Análisis Exploratorio de Descuentos en el Marketplace:** Se realiza un análisis de las publicaciones con descuento utilizando la API pública de Mercado Libre.
2. **Modelado Predictivo de Ventas Históricas:** Se desarrolla un modelo para predecir la cantidad de ventas históricas (`sold_quantity`) de un producto en base a sus características.

## Estructura del Proyecto

```plaintext
desafio_meli/
│
├── README.md                  # Descripción del proyecto y cómo reproducirlo
├── data/                      # Datos
│   ├── raw/                   # Datos crudos descargados
│   └── processed/             # Datos procesados y listos para eda
    └── data_prov/             # Datos para modelo       
        └──raw/                # Datos crudos descargados
        └──processed/          # Datos procesados y listos para modelo
├── notebooks/                 # Notebooks Jupyter
│   ├── 00_data_download.ipynb # Descarga la data y procesa los datos 
│   ├── 01_eda_meli.ipynb      # Análisis exploratorio de los datos
│   └── 02_model_meli.ipynb    # Desarrollo del modelo de predicción (`sold_quantity`)
└── requirements.txt           # Lista de dependencias para reproducir el proyecto

Por cuestiones de tamaño la carpeta data se encuentra en este enlace:
https://drive.google.com/drive/folders/1pFmz8HirpVKNSwftCqY9nc9p_RohIchA?usp=share_link

## Requisitos del Sistema
Antes de comenzar, asegúrate de tener instalado lo siguiente:

Python 3.8+
pip para la instalación de paquetes

Configuración del Entorno
### Clona este repositorio en tu máquina local:

```bash
git clone https://github.com/tu_usuario/tu_repositorio.git
cd tu_repositorio
Crea y activa un entorno virtual (opcional pero recomendado):
```bash
Copiar código
python -m venv venv
source venv/bin/activate  # En Windows: venv\Scripts\activate
Instala las dependencias necesarias:
```bash
Copiar código
pip install -r requirements.txt
Archivos y Directorios
data/: Contiene los datos crudos y procesados. Los datos sin procesar deben colocarse en data/raw/, y los datos procesados se guardarán en data/processed/ después de la ejecución del preprocesamiento.
notebooks/: Contiene notebooks de Jupyter. El 00_data_download.ipynb es el punto de partida para ejecutar el flujo completo.

Instrucciones para la Ejecución

Se ejecuta el 00_data_download.ipynb para conseguir los datos
Analisis exploratorio:
El notebook 01_eda_meli.ipynb al correr todas la celdas obtienes el analisis exploratorio
Entrenamiento del Modelo:
El notebook 02_model_meli.ipynb también incluye pasos para entrenar modelos de Random Forest y Xgboost. 


Troubleshooting
Si encuentras problemas con las dependencias, asegúrate de que todas las versiones de las librerías estén actualizadas según lo especificado en requirements.txt.

Contribuciones
Si deseas contribuir a este proyecto, por favor abre un Pull Request o un Issue en GitHub para discutir cambios importantes.

Licencia
Este proyecto está bajo la Licencia MIT - mira el archivo LICENSE para más detalles.

