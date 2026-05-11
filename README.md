# Identificación de Resistencia Bacteriana mediante Aprendizaje No Supervisado

Este proyecto aplica técnicas de Machine Learning No Supervisado para el análisis de datos genéticos, con el objetivo de acelerar la identificación de bacterias y genes de resistencia a antibióticos. El enfoque principal es reducir el tiempo de diagnóstico en casos críticos como el shock séptico.

## Descripción del Proyecto

El diagnóstico tradicional de infecciones bacterianas puede tardar más de 24 horas, mientras que la tasa de mortalidad en pacientes críticos aumenta un 7.6% por cada hora de retraso. 

Utilizando tecnologías de Secuenciación de Tercera Generación (TGS) y algoritmos de clustering, este proyecto busca organizar y categorizar señales genómicas de forma inmediata, permitiendo una toma de decisiones clínica mucho más rápida y eficiente.

## Metodología Aplicada

El análisis se estructura en 6 etapas clave de aprendizaje no supervisado:
1. Mapa de Calor: Análisis de correlaciones entre las variables del dataset.
2. Método del Codo: Determinación del número óptimo de grupos (K).
3. K-Means Clustering: Agrupamiento basado en centroides para la categorización de especies.
4. DBSCAN: Identificación de grupos por densidad y filtrado de ruido o anomalías.
5. Clustering Jerárquico Aglomerativo: Construcción de taxonomías bacterianas.
6. Análisis de Dendrograma: Visualización de las relaciones y distancias entre los grupos identificados.

## Recursos

*   Dataset: [Microbes Dataset en Kaggle](https://www.kaggle.com/datasets/sayansh001/microbes-dataset) - Características morfológicas y genéticas de diversos microorganismos.
*   Notebook de Desarrollo: [Google Colab - Análisis No Supervisado]([https://colab.research.google.com/drive/1Ia0qzgZCxaY2dnpqcLGkiB5OO9gEQVFM?usp=sharing](https://colab.research.google.com/drive/1Ia0qzgZCxaY2dnpqcLGkiB5OO9gEQVFM?usp=sharing)) - Código fuente en Python e implementación de modelos.

## Tecnologías Utilizadas

*   Lenguaje: Python 3.x
*   Librerías principales: 
    *   Scikit-learn (Clustering y Preprocesamiento)
    *   SciPy (Algoritmos de enlace y Dendrogramas)
    *   Seaborn y Matplotlib (Visualización técnica)
    *   Pandas y NumPy (Manipulación de estructuras de datos)

## Contexto Académico

Proyecto desarrollado para la asignatura de Métodos de Aprendizaje No Supervisado en la Escuela Politécnica Nacional (EPN), Ecuador.
