# football
# Análisis de Jugadores de Fútbol de Italia - Temporada 2023/24

Este proyecto combina la importación de datos desde Kaggle con técnicas de web scraping para analizar a los jugadores de fútbol de la temporada 2023-2024. El foco está en los equipos de la liga italiana.

## Requisitos previos

- Python 3.8+
- Pandas
- Jupyter Notebook
- Librerías adicionales:
  ```bash
  pip install kaggle kagglehub
  `

## Estructura del Notebook

- **Importación de Datos (CSV desde Kaggle)**  
  Se descargan y procesan datos estructurados sobre jugadores de fútbol desde una fuente en Kaggle.

- **Web Scraping de Equipos Italianos**  
  Se realiza scraping para obtener información detallada de jugadores pertenecientes a todos los equipos de la liga italiana.

- **Concat y Merge**  
  Juntamos los datos para trabajar sobre un solo archivo de datos.

- **limpieza, agrupamiento y conclusiones**  
  Redifinir columnas, limpiar duplicados y nulos y agrupar para sacar conclusiones para nuestro estudio.

``

## Cómo usar

1. Clona este repositorio o descarga los archivos.
2. Asegúrate de tener las credenciales de Kaggle (`kaggle.json`) configuradas si accedes a datos privados.
3. Ejecuta el notebook `football.ipynb` en Jupyter.
4. Sigue las secciones paso a paso: primero el análisis desde CSV, luego el scraping.

## Objetivo

Extraer, combinar y analizar datos de jugadores de fútbol desde múltiples fuentes, con énfasis en la Serie A italiana para la temporada 2023/24.

## Próximos pasos

Con estos insights podremos recomendar algunos fichajes. Se podria buscar mas estadisticas como el valor e cada jugador para ajustarlo a un presupuesto.
En el futuro ampliar la cantidad de ligas.

---

**Ojeadores Equipazo** comprometidos con el buen analisis del mercado de jugadores para facilitar la busqueda a los equipos. ¡Hasta pronto!