# Aves_chilenas

<img src="https://www.redobservadores.cl/wp-content/uploads/2018/04/dorado_portada-Ivo-Tejeda-1180x652.jpg">

## Tabla de contenidos

1. [Descripción del Proyecto](#descripción-del-proyecto-clipboard)
2. [Herramientas Utilizadas](#herramientas-utilizadas-wrench)
3. [Estructura del Proyecto](#estructura-del-proyecto-open_file_folder)
4. [Cómo usar este proyecto](#cómo-usar-este-proyecto-question)
5. [Contenido del Jupyter notebook](#contenido-del-jupyter-notebook-page_facing_up)


### Descripción del Proyecto :clipboard:
Este proyecto utiliza el conjunto de datos disponible en Kaggle (https://www.kaggle.com/datasets/CooperUnion/anime-recommendations-database) para realizar un sistema de recomendación simple.
En este proyecto es posible indicar el nombre de un anime y obtener 10 recomendaciones similares al título ingresado.

### Herramientas Utilizadas :wrench:
- Python 3.9.17
- Bibliotecas de análisis de datos: Pandas, NumPy, Scipy.
- Bibliotecas de visualización: Matplotlib, Seaborn.
- Biblioteca de aprendizaje automático: scikit-learn.
  
### Estructura del Proyecto :open_file_folder:
- anime.csv: Archivo CSV que contiene información sobre los animes, como sus títulos, géneros, calificaciones y más.
- rating.csv: Archivo CSV que contiene las calificaciones que los usuarios han dado a los animes.
- recomendador_anime.ipynb: Jupyter notebook que contiene la implementación del sistema de recomendación.

### Cómo usar este proyecto :question:
1. Descarga el conjunto de datos desde Kaggle: https://www.kaggle.com/competitions/titanic/data
2. Coloca los archivos CSV descargados (anime.csv, rating.csv) en la misma carpeta que este proyecto.
3. Abre el Jupyter notebook recomendador_anime.ipynb y ejecuta las celdas de código paso a paso para explorar y analizar los datos. En la parte final se encuentra la función que permite realizar la recomendación de anime.

### Contenido del Jupyter notebook :page_facing_up:
- Exploración básica de datos
- Preprocesamiento de datos
- Modelado
