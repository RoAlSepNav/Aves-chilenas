# Aves chilenas 🐦

<img src="https://www.redobservadores.cl/wp-content/uploads/2018/04/dorado_portada-Ivo-Tejeda-1180x652.jpg">

## Tabla de contenidos

1. [Descripción del Proyecto](#descripción-del-proyecto-clipboard)
2. [Herramientas Utilizadas](#herramientas-utilizadas-wrench)
3. [Estructura del Proyecto](#estructura-del-proyecto-open_file_folder)
4. [Cómo usar este proyecto](#cómo-usar-este-proyecto-question)


### Descripción del Proyecto :clipboard:
Este proyecto se basa en la utilización de datos provenientes de la API de aves chilenas, la cual se encuentra disponible en https://aves.ninjas.cl/api/birds. Mediante un script en Python, se extraen estos datos y se genera un archivo CSV para su posterior uso en Power BI. Con esta información, se desarrolla un buscador de aves chilenas que facilita su identificación y estudio.


### Herramientas Utilizadas :wrench:
- Python 3.9.17
- Biblioteca de acceso a API: Requests
- Biblioteca de manipulación de datos en formato CSV: CSV
- Herramienta de visualización de datos: Power BI
  
### Estructura del Proyecto :open_file_folder:
- aves.csv: Script de Python para consumir la API y generar el archivo CSV.
- info_aves.csv: Archivo CSV con los datos extraídos de la API.
- aves.pbix: Reporte de Power BI basado en los datos extraídos.
  

### Cómo usar este proyecto :question:
Para utilizar este proyecto, sigue estos pasos:
1. Asegúrate de tener instalado Python 3.9.17 en tu sistema.
2. Clona o descarga este repositorio en tu máquina local.
3. Ejecuta el script `aves.csv` para consumir la API de aves chilenas y generar el archivo `info_aves.csv` con los datos extraídos. Puedes hacerlo mediante el siguiente comando:
   ```bash
   python aves.py
4. Una vez que se ha generado el archivo info_aves.csv, puedes utilizarlo en Power BI para crear visualizaciones y análisis. Abre el archivo aves.pbix con Power BI y carga el archivo CSV como fuente de datos.
5. Explora el reporte generado en Power BI para identificar y estudiar las aves chilenas utilizando las herramientas de visualización y análisis disponibles.

