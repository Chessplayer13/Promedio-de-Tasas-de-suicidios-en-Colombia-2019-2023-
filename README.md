# Mapa de Tasa Promedio de Suicidios en Colombia (2019–2023)

Este proyecto contiene el análisis y visualización de la tasa promedio de suicidios en Colombia entre los años 2019 y 2023. El resultado final es un mapa coroplético donde se representan las tasas promedio por departamento, ajustadas por población proyectada.

## Estructura del repositorio

- **`Mapa/`**: Contiene los archivos del shapefile necesarios para construir el mapa de Colombia por departamentos.
- **`Poblaciones/`**: Contiene los archivos con las proyecciones de población por departamento y año, utilizadas para el cálculo de las tasas.
- **`Tasa de Suicidios en Colombia`** El archivo `.ipynb` contiene todo el proceso de análisis, cargue y limpieza de datos, cálculos y visualización. También incluye explicaciones en celdas Markdown.

⚠️ **Nota:**  
la carpeta Defunciones con sus archivos (csv) no fue incluido en el repositorio por su gran tamaño. Sin embargo, en el notebook se explica su procedencia, estructura esperada y cómo fue procesado. Esto permite replicar el análisis o ampliarlo con nuevos años si se cuenta con los datos.

## Fuentes de datos

- **Defunciones por suicidio**: Microdatos de Estadísticas Vitales (EEVV) – DANE  
- **Proyecciones de población**: Departamento Administrativo Nacional de Estadística (DANE)  
- **Geometría del mapa**: Shapefile del DANE u otra fuente oficial (especificado en el notebook)

## Resultado

El producto final es un mapa que muestra la tasa promedio de suicidios por cada 100.000 habitantes, por departamento, durante el periodo 2019–2023. Se usó una clasificación por *Natural Breaks (Jenks)* y cada departamento está etiquetado con su tasa respectiva.

## Requisitos

- Python 3.x
- pandas, geopandas, matplotlib, mapclassify
- Jupyter Notebook

## Créditos

Elaboración propia.  
La tasa corresponde al promedio de suicidios por cada 100.000 habitantes entre 2019 y 2023, calculada con base en población proyectada por el DANE.  
Fuente: Microdatos Estadísticas Vitales (EEVV) – DANE.

