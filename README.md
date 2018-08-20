# Análisis de datasets de la FIFA para que Chile llegue lejos

Chile necesita llegar de buena manera al mundial y en base a un análisis de datasets de la FIFA se podrá ver cuales son las características del juego que más ayudan a las selecciones a ganar. La metodología ocupada fue extraer los datos desde [kaggle](https://www.kaggle.com/mathan/fifa-2018-match-statistics/home), y transformarlo para cada visualización ocupando la herramienta de plotly.  
Como conclusiones, se obtuvo que la selección debe tener un juego con menos pose de balón y más táctico, la cantidad de faltas no es determinante, que se debe ser efectivo en el ataque y no compremeter la defensa. Son propuestas que hacen menos vistoso el juego pero han dado resultado y se observa una tendencia de los últimos campeones del mundo en disminuir la cantidad de tiros al arco y aumentar la cantida de tarjetas amarillas.

## Pre-requisitos
Debe tener la librería de plotly y configurar una [cuenta](https://plot.ly/python/getting-started/) o modificar para correr offline.
```
$ pip show plotly
Name: plotly
Version: 3.1.1
Summary: Python plotting library for collaborative, interactive, publication-quality graphs.
Home-page: https://plot.ly/python/
Author: Chris P
Author-email: chris@plot.ly
License: MIT
Location: /Users/fabianfernandez/anaconda2/envs/taller/lib/python3.6/site-packages
Requires: six, nbformat, decorator, retrying, requests, pytz
```
