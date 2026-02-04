# CDA_TECMX-mortalidad-materna
Análisis exploratorio de determinantes de la mortalidad materna utilizando dataset de Kaggle.


# Maternal Mortality Ratio (MMR) 1990–2021 — CDA Scoping

## Problema
La Razón de Mortalidad Materna (MMR) es el número de muertes maternas por cada 100,000 nacidos vivos. 
Este proyecto describe cómo ha cambiado la MMR a nivel mundial entre 1990 y 2021, con énfasis en identificar países donde la MMR sigue siendo alta o donde el progreso se ha frenado. El foco es generar evidencia útil para orientar prioridades (dónde poner más atención, qué países están estancados y cuáles mejoran con mayor consistencia) y posteriormente analizar determinantes de mejora.

## Objetivos
1. Construir un ranking/semáforo simple de países según nivel actual de MMR, ritmo de mejora y señales de estancamiento en los últimos años.
2. Estimar, a grandes rasgos, qué países están más lejos de una meta de referencia como reducir la MMR a <70 por cada 100,000 nacidos vivos, como apoyo para priorización.
3. Agrupar países por trayectorias (mejora rápida, mejora lenta, estancados, volátiles).

## Acciones
Con los resultados, un equipo de salud pública (ministerio/ONG/cooperación) puede:
1. Priorizar países (o grupos de países) para asistencia técnica y focalización de recursos, especialmente aquellos con MMR alta y estancamiento reciente.
2. Activar monitoreo/alertas cuando un país deje de mejorar o muestre retrocesos, para revisar posibles causas (shocks del sistema, cambios de política, conflictos, etc.).
3. Preparar un brief simple para tomadores de decisión explicando dónde está el problema, qué tan grande es y por qué esos países aparecen como prioritarios.
4. Explorar determinantes que expliquen el estado de situación de cada país.

## Datos
Dataset base: “Maternal Mortality Dataset” (Kaggle), con MMR por país para 1990–2021 y variables de contexto (ISO3, país, continente, grupos de desarrollo humano, regiones UNDP, HDI rank 2021).
Datasets adicionales: Mortalidad materna y embarazo y supervisión por el Centro para Control y Prevención de Enfermedades (CDC) de Estados Unidos. Maternidad materna por UNICEF, datos de panel. 
Granularidad: país-año (no es data clínica individual).  
Datos adicionales deseables (no obligatorios para esta tarea): indicadores como partos atendidos por personal calificado, cobertura prenatal, gasto en salud y shocks (pandemias, conflictos), para mejorar interpretación de cambios. Así como datos de paises con mejores avances.

## Consideraciones éticas
1. Transparencia: explicar claramente la metodología.
2. Equidad y estigma: el resultado debe usarse para priorización y apoyo. Así como observar buenas prácticas.
3. Privacidad: al ser datos agregados país-año, el riesgo de privacidad individual es bajo, pero se debe cuidar la integridad y el uso responsable de resultados.

## Implementación y uso 
Entregable práctico: reporte corto con (a) ranking/semáforo, (b) tendencias 1990–2021, (c) grupos por trayectorias y (d) notas de interpretación (c) buenas prácticas
Uso operativo: servir como lista priorizada para decidir dónde profundizar diagnóstico o a qué países dar seguimiento primero. 
Monitoreo: actualizar cuando haya nuevos datos y revisar si cambian las conclusiones (y por qué).

Bases de datos:

https://www.kaggle.com/datasets/iamsouravbanerjee/maternal-mortality-dataset/data "Maternal Mortality Dataset (Kaggle)
https://www.cdc.gov/maternal-mortality/php/pregnancy-mortality-surveillance-data/index.html
https://data.unicef.org/topic/maternal-health/maternal-mortality/
