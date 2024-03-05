# Primer avance proyecto

El código de este proyecto consiste en un script en Python que realiza web scraping de datos desde el sitio web kworb.net/ utilizando BeautifulSoup y Requests.

## Descripción del Proyecto

El script recopila datos como el nombre de las canciones, el número total de reproducciones, reproducciones como artista principal, reproducciones en solitario, reproducciones como artista destacado, y reproducciones diarias. Luego, realiza análisis estadísticos y visualizaciones de estos datos para ayudar a comprender mejor.

## Cómo Ejecutar el Código

Para ejecutar el código, sigue estos pasos:

1. Se deben de tener instaladas las siguientes bibliotecas de Python: `requests`, `BeautifulSoup`, `pandas`, `numpy` y `matplotlib`.
   
2. Descarga el script y ejecútalo.

3. Una vez ejecutado, en algunas secciones el script solicitará el nombre de un artista de interés que se encuentre dento de los proporcionados en los urls al inicio del código.

## Dependencias Necesarias

El proyecto depende de las siguientes bibliotecas de Python:

- `requests`: Para hacer solicitudes HTTP a los sitios web y obtener el contenido HTML.
- `BeautifulSoup`: Para analizar y extraer datos del HTML de los sitios web.
- `pandas`: Para estructurar y manipular los datos obtenidos en forma de DataFrames.
- `numpy`: Para realizar cálculos numéricos.
- `matplotlib`: Para visualizar los datos mediante gráficos y diagramas.
- `streamlit`: Para construir una interfaz de usuario interactiva para el análisis de los datos.
