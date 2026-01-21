# Análisis de Precios de Viviendas en California
[PROYECTO DE SKILL] Acá realizo un análisis y limpieza de datos común de un dataset de Kaggle, llamado "California Housing Prices".

## Descripción del Proyecto

El notebook procesa datos del censo de California para encontrar correlaciones estadísticas entre sus diferentes características y el precio de las viviendas. Se aplican técnicas de limpieza de datos, manipulación con Pandas y análisis de correlación lineal.

### Tecnologías utilizadas:
* **Python**
* **Pandas**
* **Seaborn/Matplotlib**

## Hallazgos Clave

Tras el análisis de los datos, se han determinado las siguientes correlaciones con el valor de la vivienda:

1.  Ingreso Medio (median_income): Existe una fuerte correlación positiva (0.68). Las zonas con mayores ingresos medios tienen precios de vivienda significativamente más altos.
2.  Ubicación Geográfica:
    - Vivir cerca del océano (<1H OCEAN, NEAR BAY) tiene una correlación positiva.
    - Vivir en el interior (INLAND) tiene una correlación negativa notable (-0.48), indicando precios más bajos lejos de la costa.
3.  Habitaciones: La cantidad total de habitaciones (total_rooms) tiene una correlación baja (0.13), lo que sugiere que el tamaño de la casa importa menos que la ubicación y el ingreso de la zona.

## Estructura del Repositorio

* `costos_casas_california.ipynb`: Notebook principal con el código de análisis.
* `housing.csv`: Dataset (Datos del Censo 1990).
* `README.md`: Documentación del proyecto.

**Este es un proyecto básico que tiene por objetivo mejorar mis habilidades en el análisis y limpieza de datos.**
