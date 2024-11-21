# Reducción de dimensionalidad con PCA sobre canciones más reproducidas en Spotify

Este proyecto realiza un análisis de reducción de dimensionalidad utilizando el método PCA (Análisis de Componentes Principales) en un conjunto de datos que contiene información de las canciones más reproducidas en Spotify hasta el año 2023. El objetivo es preparar los datos para procesos de Data Science y facilitar su análisis.

## Descripción

El proyecto utiliza un notebook de Python que lee un archivo CSV llamado `Spotify-Most-Streamed-Songs.csv`. Este dataset incluye características relacionadas con las canciones más reproducidas, como popularidad, duración, energía, entre otras. A través de técnicas de preprocesamiento y PCA, se reducen las dimensiones de los datos para extraer información útil de manera más eficiente.

## Requisitos

El entorno de trabajo utiliza **Anaconda** para gestionar las dependencias. Puedes instalar el entorno necesario utilizando el archivo `environment.yml` incluido en este repositorio.

### Paquetes principales utilizados:

- `numpy`: Para operaciones matemáticas y manipulación de arrays.
- `pandas`: Para cargar y procesar el CSV.
- `matplotlib`: Para visualización de datos.
- `seaborn`: Para gráficos estadísticos.
- `scikit-learn`: Para preprocesamiento y la implementación del algoritmo PCA.

## Archivos incluidos

- `Spotify-Most-Streamed-Songs.csv`: El dataset de las canciones más reproducidas en Spotify.
- `dimensionality_reduction.ipynb`: El notebook principal con el análisis y reducción dimensional.
- `environment.yml`: Archivo para configurar el entorno de Anaconda con todas las dependencias necesarias.

## Instalación

1. Clona el repositorio en tu máquina local:
  ```bash
  git clone https://github.com/ValerioBeauregard/Spotify-Most-Streamed-Songs-PCA-reduction.git
  ```
2. Cambia al directorio del proyecto:
  ```bash
  cd Spotify-Most-Streamed-Songs-PCA-reduction
  ```
3. Crea el entorno de Anaconda con el archivo environment.yml:
  ```bash
  conda env create -f environment.yml
  ```
4. Activa el entorno:
  ```bash
  conda activate spotify_pca
  ```
5. Abre el notebook:
  ```bash
  jupyter notebook dimensionality_reduction.ipynb
  ```

## Visualización
El proyecto incluye visualizaciones para:
- Análisis exploratorio de los datos.
- Gráficos de varianza explicada por los componentes principales.
- Representaciones de los datos reducidos.
