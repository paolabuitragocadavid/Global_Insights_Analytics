
# Documentación técnica — Global Insights Analytics

## Descripción

Esta carpeta reúne la documentación técnica y los
archivos de soporte del proyecto Global Insights Analytics,
desarrollado en la Unidad 6 de Visualización Avanzada
de Datos de la Especialización en Big Data y Analítica
de Datos de la Corporación Universitaria de Cataluña.

Su propósito es documentar las fuentes de información,
los procedimientos de adquisición y transformación
de datos y la trazabilidad de los resultados.

## Fuentes de información

El proyecto integra información procedente de:

1. Banco Mundial:
   - Población total.
   - PIB per cápita en dólares corrientes.

2. Our World in Data / UIT:
   - Porcentaje de personas que utilizan Internet.

3. Organización para la Cooperación y el
   Desarrollo Económicos (OCDE):
   - Estudios económicos y contexto documental
     relacionado con digitalización.

## Documentación de las fuentes

Los archivos de manifiesto permiten registrar
información sobre la procedencia, identificación
y características de las fuentes utilizadas.

### source_manifest.csv

Registra los metadatos relacionados con
las fuentes de datos cuantitativas utilizadas
durante el procesamiento.

### document_manifest.csv

Documenta la identificación y procedencia
de los documentos empleados para el análisis textual.

## Procesamiento documental

### document_cards.json

Contiene información estructurada asociada
a los documentos analizados.

### document_sentences.csv

Contiene registros de oraciones extraídas
y procesadas para la clasificación temática.

## Trazabilidad y reproducibilidad

La documentación complementa el cuaderno
de Google Colab y permite comprender:

- La identificación de las fuentes utilizadas.
- La procedencia y el periodo de los datos.
- Los procedimientos de transformación.
- Los controles de calidad y consistencia.
- La integración de datos estructurados y textuales.
- Las limitaciones metodológicas del análisis.

## Consideraciones metodológicas

El proyecto analiza 13 países durante el periodo
2015–2023, con 117 observaciones país–año.

Los documentos OCDE corresponden a publicaciones
de 2024–2025 y se utilizan como información
contextual, sin considerarlos una serie temporal
equivalente a los indicadores cuantitativos.

Los resultados tienen carácter exploratorio y
no constituyen predicciones de rentabilidad
ni estimaciones de demanda comercial.

## Herramientas utilizadas

- Google Colab.
- Python.
- Pandas.
- NumPy.
- Procesamiento y análisis de texto.
- Archivos CSV y JSON.

## Autora

Paola Andrea Buitrago Cadavid

Especialización en Big Data y Analítica de Datos

Corporación Universitaria de Cataluña

Noviembre de 2026
