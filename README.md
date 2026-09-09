# Modelo econométrico de atractividad comercial municipal en México

## Descripción

Proyecto econométrico desarrollado con datos públicos de México para analizar los factores demográficos, educativos, laborales y socioeconómicos asociados con la variación de la densidad comercial municipal entre 2020 y 2025.

## Pregunta de investigación

¿En qué medida las condiciones demográficas, educativas, laborales y socioeconómicas de los municipios mexicanos en 2020 se relacionan con el crecimiento de su densidad comercial entre 2020 y 2025?

## Metodología

El proyecto se desarrolla utilizando CRISP-DM:

1. Business Understanding
2. Data Understanding
3. Data Preparation
4. Modeling
5. Evaluation
6. Deployment / presentación de resultados

## Fuentes de datos

- INEGI - DENUE 2020
- INEGI - DENUE 2025
- INEGI - Censo de Población y Vivienda 2020
- ILMM 2020
- SGCONAPO
- CONEVAL - Indicadores de pobreza municipal 2020

## Unidad de análisis

Municipios de México.

## Periodo de análisis

2020-2025.

## Herramientas

- Python 3.12
- Pandas
- NumPy
- Statsmodels
- Scikit-learn
- Jupyter Notebook
- Visual Studio Code
- Git / GitHub


## Estado del proyecto

### Avance actual

La construcción, validación y homologación de la base maestra municipal se encuentran concluidas. La base final utilizada para el análisis contiene **2,440 municipios** con información demográfica, educativa, laboral, socioeconómica y comercial.

Dentro del flujo **CRISP-DM**, las etapas de comprensión y preparación de los datos ya fueron completadas. Para la **regresión lineal simple** también se concluyeron las etapas de modelado y evaluación.

Actualmente se cuenta con:

- análisis descriptivo y exploratorio;
- análisis de correlación de Pearson;
- cuatro modelos de regresión lineal simple;
- evaluación de formas funcionales alternativas;
- pruebas de significancia estadística;
- diagnóstico de heterocedasticidad;
- errores estándar robustos HC3;
- análisis de observaciones influyentes y sensibilidad;
- evaluación predictiva fuera de muestra;
- métricas de error e intervalos de predicción.

**Estado de la regresión lineal simple:** concluida y documentada.

**Siguiente etapa:** desarrollo y evaluación de la **regresión lineal múltiple**, incorporando simultáneamente las variables explicativas seleccionadas.