# promo_d_da_modulo3_sprint1_Silvia_Cassia
Repositorio de los ejercicios de pair programming de Silvia y Cassia del Sprint 1 del Modulo 3 del bootcamp de Data Analytics


En este sprint hemos realizado tratamiento de datos y creación de modelos de regresión lineal, regresión logística y regresión y clasificación utilizando Decision Tree y Random Forest. 

Hemos utilizado las librerias pandas, numpy, seaborn, matplotlib, warnings (para quitar los avisos), sidetable, scipy, sklearn, math, statsmodels y tqdm.

Para ambos tipos de modelos hemos realizado un análisis exploratorio de los datos, estudiado nulos y duplicados, analizado outliers y su posible tratamiento. 

Para los modelos de regresión lineal y regresión lineal mediante Decision Tree y Random Forest hemos intentado normalizar la variable respuesta, estandarizado las variables predictoras numéricas y realizado el encoding de las variables predictoras categóricas. A continuación, hemos intentado un modelo de regresión lineal (como práctica, pues ya sabíamos que no se cumplían las asunciones necesarias en nuestros datos) y ANOVA, para finalmente elegir modelos de Decision Tree y Random Forest debido a la naturaleza de nuestros datos. Las predicciones finales junto con nuestra opinión sobre ellas se pueden encontrar en el archivo regresion-lineal-12.

Para los modelos de regresión logística y clasificación mediante Decision Tree y Random Forest hemos estandarizado las variables predictoras numéricas y realizado el encoding de las variables predictoras categóricas y de la variable respuesta. A continuación, hemos realizado los distintos modelos y estudiado la matriz de confusión de regresión logística. Finalmente, basándonos en las métricas, hemos elegido un modelo de Random Forest que se encuentra en el archivo regresion-logistica-5+6; no recomendamos su ejecución ya que debido al elevado número de registros (aproximadamente 130K), el tiempo de ejecución de la celda de gridsearch para Random Forest es superior a 4 horas. 