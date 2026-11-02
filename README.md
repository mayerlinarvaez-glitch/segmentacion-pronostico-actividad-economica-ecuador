
# Segmentación y pronóstico de la actividad económica provincial del Ecuador

## Proyecto de titulación – Maestría

**Título:** Segmentación y pronóstico de la actividad económica provincial del Ecuador mediante técnicas de Clustering y modelos de series temporales.

**Autores:**
- Mayerli Nicole Narváez Choez
- Pablo Hernán Intriago Andrade

**Universidad:** Universidad de Las Américas (UDLA)  
**Docente:** Manuel Eugenio Morocho Caymcela  
**Año:** 2026

---

## 1. Descripción del proyecto

Esta investigación desarrolla un modelo analítico para segmentar las provincias del Ecuador según sus patrones de actividad económica y pronosticar la evolución de sus ventas mediante técnicas de clustering y modelos de series temporales.

El estudio utiliza información agregada de ventas declaradas, con desagregación provincial, temporal y por actividad económica, para identificar patrones y generar información que contribuya al análisis y la planificación económica territorial.

## 2. Objetivo general

Desarrollar un modelo analítico que permita segmentar las provincias del Ecuador según sus patrones de actividad económica y pronosticar la evolución de sus ventas mediante técnicas de Clustering y modelos de series temporales, con el propósito de generar información que contribuya al análisis y planificación económica territorial.

## 3. Fuente de información

Los datos utilizados provienen del conjunto de datos **Ventas–Compras** del Servicio de Rentas Internas (SRI) de Ecuador.

- Período de análisis: enero de 2020 a junio de 2026.
- Cobertura territorial: 24 provincias.
- Frecuencia: mensual.
- Variable principal: TOTAL_VENTAS.
- Fuente oficial: https://www.sri.gob.ec/web/intersri/datasets

La base original no se publica en este repositorio.

## 4. Metodología

La investigación aplica la metodología CRISP-DM y contempla dos componentes analíticos:

### Segmentación territorial
- K-means.
- Clustering jerárquico (método Ward).
- DBSCAN.
- Validación mediante Silhouette y Davies-Bouldin.

### Pronóstico de ventas
- SARIMA.
- Holt-Winters.
- Evaluación mediante MAE, RMSE, MAPE y WAPE.
- Validación temporal de los modelos.

## 5. Resultados principales

- Se identificaron cuatro grupos de provincias con patrones diferenciados de actividad económica.
- La solución de K-means y Ward presentó un índice de Rand ajustado (ARI) de 1,00.
- Holt-Winters obtuvo menor MAPE en 18 de las 24 provincias.
- En el análisis sectorial, el 74,2 % de las series seleccionadas alcanzó un WAPE igual o inferior al 20 % con el modelo recomendado.

## 6. Contenido del repositorio

- **Tesis final:** documento académico en formato PDF.
- **Notebook de análisis:** archivo Jupyter Notebook (`.ipynb`) con los procedimientos y resultados del análisis.

## 7. Consideraciones

Los valores de ventas corresponden a registros tributarios nominales declarados y no representan directamente el PIB provincial ni el crecimiento económico real. Los resultados deben interpretarse considerando el alcance y las limitaciones de la información utilizada.

## 8. Autores

Mayerli Nicole Narváez Choez  
Pablo Hernán Intriago Andrade

Universidad de Las Américas (UDLA), Ecuador.
