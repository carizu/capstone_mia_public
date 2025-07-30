# Proyecto Capstone MIA

Este repositorio contiene un conjunto de notebooks para el análisis, procesamiento y clasificación de normativas y circulares. A continuación se presenta un índice con una breve explicación de cada notebook para facilitar la navegación y comprensión del proyecto.

## Índice de Notebooks

1. [01_EDA_Metadata.ipynb](notebooks/01_EDA_Metadata.ipynb)  
   Exploración y análisis inicial de los metadatos disponibles en el conjunto de datos. Se realiza un Análisis Exploratorio de Datos (EDA) para entender la estructura y características de los datos.

2. [02_Extraccion_Datos.ipynb](notebooks/02_Extraccion_Datos.ipynb)  
   Proceso de extracción de datos desde las fuentes originales. Incluye la carga y consolidación de archivos CSV con normativas y circulares.

3. [03_Preprocesamiento_EDA_Clasifica_Normativas.ipynb](notebooks/03_Preprocesamiento_EDA_Clasifica_Normativas.ipynb)  
   Preprocesamiento de los datos y análisis exploratorio para la clasificación de normativas. Se preparan los datos para su posterior modelado.

4. [04 Preprocesamiento_Embbedings_Redis.ipynb](notebooks/04 Preprocesamiento_Embbedings_Redis.ipynb)  
   Generación de embeddings para los textos de las normativas y su almacenamiento en Redis para facilitar búsquedas y consultas eficientes.

5. [05 Clasificar_Normativas_Nuevas_v4.ipynb](notebooks/05 Clasificar_Normativas_Nuevas_v4.ipynb)  
   Implementación y evaluación de modelos para la clasificación automática de nuevas normativas.

6. [06 Agente_Vigilante_Normativo.ipynb](notebooks/06 Agente_Vigilante_Normativo.ipynb)  
   Desarrollo de un agente vigilante normativo que monitorea y clasifica normativas nuevas de forma automática, integrando los procesos anteriores.

## Estructura de Carpetas

- `notebooks/`: Contiene todos los notebooks del proyecto.
- `raw_data/`: Datos crudos originales, incluyendo archivos CSV con circulares y resoluciones por año, así como archivos de normativas clasificadas y limpias.

## Uso

Cada notebook está diseñado para ser ejecutado secuencialmente, siguiendo el flujo desde la exploración inicial hasta la implementación del agente vigilante normativo.

---

Repositorio original: [https://github.com/carizu/capstone_mia_public](https://github.com/carizu/capstone_mia_public)
