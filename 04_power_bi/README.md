
# Power BI — Global Insights Analytics

## Descripción

Implementación del dashboard Global Insights Analytics
en Microsoft Power BI Desktop, desarrollado como parte
del Trabajo Final Integrador de la Unidad 6 de
Visualización Avanzada de Datos.

El tablero permite analizar y comparar indicadores
socioeconómicos y de conectividad digital de 13 países
durante el periodo 2015–2023.

## Archivo del proyecto

Global_Insights_Analytics(3).pbix

Este archivo contiene el modelo de datos, las medidas
DAX, los indicadores y las visualizaciones desarrolladas.

## Modelo de datos

El modelo incluye:

- fact_digital_market: tabla principal de indicadores.
- dim_pais: dimensión de países.
- dim_anio: dimensión temporal.

## Indicadores clave (KPI)

1. Países analizados.
2. Uso medio de Internet (%).
3. PIB per cápita medio (USD).
4. Población total.
5. Índice exploratorio medio.

## Visualizaciones desarrolladas

1. Evolución del uso de Internet.
2. Ranking interactivo de países.
3. PIB per cápita frente al uso de Internet.
4. Matriz de correlación de Spearman.
5. Distribución del uso de Internet por país.
6. Mapa de calor país–año.

## Interactividad

El dashboard incorpora segmentadores para seleccionar:

- Países.
- Año inicial.
- Año final.
- Indicador del ranking.

## Consideraciones de publicación

El archivo PBIX contiene tres visualizaciones
desarrolladas mediante Python.

Estas visualizaciones funcionan en Power BI Desktop,
pero presentan restricciones en la opción pública
"Publicar en web" de Power BI Service.

La versión web interactiva del proyecto puede
consultarse en Netlify:

https://global-insigths-dash-paola-buitrago.netlify.app/

## Herramientas

- Microsoft Power BI Desktop.
- DAX.
- Python.
- Pandas.
- NumPy.
- Matplotlib.
