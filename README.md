# Proyecto M7 Ganadores Oscar

## Descripción
El siguiente proyecto que seleccionamos como caso de estudio, es un conjunto de datos que trata sobre estadísticas demográficas de los ganadores del premio Oscar de la Academia: https://www.kaggle.com/datasets/fmejia21/demographics-of-academy-awards-oscars-winnersinformación

### Contexto del conjunto de datos
La base de datos considera información sobre la raza, religión, edad y otros detalles demográficos de todos los ganadores del Oscar desde 1928 en las siguientes categorías:

* Mejor Actor
* Mejor Actriz
* Mejor Actor de Reparto
* Mejor Actriz de Reparto
* Mejor Director

El dataset contiene 27 columnas, a continuación se realizará un analisis Exploratorio de la información (EDA) con el fin de entender la data, realizar las limpiezas necesarias, identificar y clasificar las variables, eliminar de ser necesarios filas y columnas, etc.
con el objetivo de poder con el dataset mas limpio y ordenado, realizar proyecciones futuras mediante modelos de regresion, comparar resultados de distintos modelos,  ver sus niveles de confianza y tomar decisiones sobre cual es nuestra mejor opción.

## EDA
Se realiza limpíeza de información (datos nulos), completitud, eliminación de variables no representativas, y se decide agregar una nueva variable para claisifcar el Genero de los ganadores del Oscar. Esta variable nueva se convertira despues en nuestra variable objetivo al momento de modelar.


## Transformación de Datos
Despues de varios analisis y limpieza de la información, las variables categoricas son transformadas con Get Dummies

## Modelado
De acuerdo con el tipo de información del dataframe y las variables seleccionadas, el modelo mas adecuado de Machine Learning a aplicar es un Modelo de Regresión Logística.
Se obtuvo una precisión de un 100%
