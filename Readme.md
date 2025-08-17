# Proyecto Alura Store: Análisis de Datos de Ventas

## Propósito del Análisis

Este proyecto tiene como objetivo analizar los datos de ventas de cuatro tiendas (`tienda_1.csv`, `tienda_2.csv`, `tienda_3.csv`, `tienda_4.csv`) para evaluar su rendimiento y proporcionar una recomendación informada sobre cuál de ellas sería la mejor opción para vender.

El análisis se centra en los siguientes puntos clave:

- Cálculo del ingreso total por tienda.
- Identificación de las categorías de productos más y menos vendidas.
- Determinación de la calificación promedio de los clientes por tienda.
- Listado de los productos individuales más y menos vendidos en cada tienda.
- Cálculo del costo de envío promedio por tienda.
- Exploración de la distribución geográfica de las ventas.

Los hallazgos de este análisis buscan ofrecer una visión clara de las fortalezas y debilidades de cada tienda desde una perspectiva de ventas y satisfacción del cliente.

## Estructura del Proyecto y Organización de Archivos

El proyecto se organiza en un único cuaderno de Google Colab (`nombre_del_tu_cuaderno.ipynb`) que contiene todo el código y el análisis.

- **Archivos de Datos:** Los datos de ventas para cada tienda se cargan directamente desde URLs de GitHub. No se almacenan localmente en este proyecto.
  - `tienda_1.csv`
  - `tienda_2.csv`
  - `tienda_3.csv`
  - `tienda_4.csv`

- **Cuaderno de Colab:** Contiene:
    - Celdas de código para la importación de librerías y datos.
    - Funciones utilitarias para la limpieza y procesamiento de datos.
    - Celdas de código para realizar cada análisis (ingreso total, ventas por categoría, calificaciones, etc.).
    - Celdas de código para generar visualizaciones (gráficos).
    - Celdas Markdown para explicaciones, títulos y el informe final.

## Ejemplos de Gráficos e Insights Obtenidos

Durante el análisis, se generaron varios gráficos para visualizar los datos. Algunos ejemplos de los insights clave incluyen:

- **Ingreso Total por Tienda:** Se visualiza la facturación total de cada tienda, identificando cuál genera mayores ingresos. (Ver gráfico de barras verticales en el cuaderno).
- **Ventas por Categoría:** Se muestran las categorías de productos más populares en general y por tienda, indicando las áreas de mayor demanda. (Ver gráfico de barras horizontales consolidadas en el cuaderno).
- **Valoración Promedio:** Un gráfico de dispersión muestra la satisfacción promedio de los clientes en cada tienda. (Ver gráfico de dispersión en el cuaderno).
- **Distribución Geográfica:** Gráficos de dispersión y heatmaps ilustran dónde se concentran las ventas. (Ver gráficos geográficos en el cuaderno).

**Insight Clave del Informe Final:** Basado en los análisis, la **Tienda 1** fue recomendada como la mejor opción para la venta debido a su **mayor ingreso total**, a pesar de pequeñas variaciones en costos de envío y calificación promedio en comparación con las otras tiendas.

## Instrucciones para Ejecutar el Notebook

Para replicar el análisis y ver los resultados, sigue estos pasos:

1.  Abre el cuaderno de Google Colab (`nombre_del_tu_cuaderno.ipynb`).
2.  Ejecuta cada celda en orden, desde la primera hasta la última. Puedes hacerlo manualmente (Shift + Enter) o utilizando la opción "Ejecutar todas las celdas" en el menú "Entorno de ejecución".
3.  Asegúrate de tener conexión a internet, ya que los datos se cargan directamente desde URLs.
4.  Los resultados de cada análisis y los gráficos se mostrarán debajo de las respectivas celdas de código. El informe final se encuentra al final del cuaderno en una celda Markdown.
