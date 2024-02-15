# Proyecto de Análisis de Datos: Reducción de Siniestros Viales en Buenos Aires



## Descripción del Proyecto

Este proyecto se propone emplear el análisis de datos como herramienta fundamental para abordar la problemática de los siniestros viales en la Ciudad Autónoma de Buenos Aires (CABA). La elevada densidad de tráfico y poblacional en la ciudad ha convertido los siniestros viales en una preocupación de suma importancia. El objetivo principal de este análisis es proporcionar información relevante que permita a las autoridades locales tomar medidas efectivas destinadas a reducir la cantidad de víctimas fatales en estos incidentes.

## Contenido del README

- [Contexto](#contexto)
- [Entidades Involucradas](#entidades-involucradas)
- [Metodología y Tecnologías](#metodología-y-tecnologías)
- [Estructura del Repositorio](#estructura-del-repositorio)
- [KPIs Calculados](#kpis-calculados)
- [Conclusiones](#conclusiones)

## Contexto

En Argentina, los siniestros viales siguen siendo la principal causa de muertes violentas, con miles de personas falleciendo cada año. Este análisis se basa en el dataset de Homicidios proporcionado por Buenos Aires Data y se centra en el periodo de 2016 a 2021, que es el periodo de datos que tenemos.

## Entidades Involucradas

- Observatorio de Movilidad y Seguridad Vial (OMSV), bajo la órbita de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires.

## Metodología y Tecnologías

- **Extraccion, Transformacion y carga de datos (ETL):** La estraccion y carga de datos, estan resueltas en Python y Pandas, en un notebook de Jupyter (ETL.ipynb), y la carga de datos, se hizo hacia nuestro dashboard en PowerBI.

- **Análisis Exploratorio de Datos (EDA):** Se exploraron los datos en un notebook de Jupyter. Se realizaron pasos documentados con claridad, incluyendo la búsqueda de valores faltantes, valores atípicos y registros duplicados, se hicieron analisis extras, para poder tener una comprension mayor sobre los datos que tenemos.

- **Dashboard Interactivo:** Se desarrolló un dashboard interactivo mediante PowerBI, facilitando la exploración detallada de los datos. Este proceso implicó modificaciones en PowerQuery, la creación de una tabla de calendario y la integración de dos conjuntos de datos adicionales: uno relacionado con el flujo vehicular en la Ciudad Autónoma de Buenos Aires (CABA) y otro referente a la población anual en la misma localidad.

- **KPIs:** Se calcularon y presentaron tres KPIs clave relacionados con la seguridad vial en CABA y se ubicarion junto con sus variables objetivo, en una tabla llamada 'Metricas_KPI'.

- **Repositorio de GitHub:** Se utilizó un repositorio de GitHub para almacenar y compartir el código y los resultados del proyecto.

## Estructura del Repositorio

- **ETL_EDA:** Carpeta que contiene el notebook de Jupyter utilizado para el EDA y el cálculo de KPIs.


- **ARCHIVOS:** Carpeta que almacena los datasets utilizados en el proyecto.


- **README.md:** Este archivo, que proporciona información general sobre el proyecto.


## KPIs Calculados

1. **Reducción en la Tasa de Homicidios:** Reduccion en un 10% de la tasa de homicidios en siniestros viales de los últimos seis meses, en CABA, en comparación con la tasa de homicidios en siniestros viales del semestre anterior.

2. **Reducción en la Cantidad de Accidentes Mortales de Motociclistas:** Reduccion en un 7% de la cantidad de accidentes mortales de motociclistas en el último año, en CABA, respecto al año anterior.


## Conclusiones

Este proyecto, brindo mucha informacion sobre los accidentes y muertes en buenos aires, informacion que se ve detallada en el EDA, y informacion adicional, expresada en una presentacion del Dasboard.


## Fuente de Datos

- [Buenos Aires Data - Homicidios](https://data.buenosaires.gob.ar/dataset/victimas-siniestros-viales)

