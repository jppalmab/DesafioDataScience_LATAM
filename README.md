# README.md

En este documento esta la solucion al desafio LATAM enviado el dia Domingo 11 de Diciembre y tuvo una duracion de 5 dias para ser entregado el dia Viernes 16 de Diciembre.

El desafio consistio en explorar y proponer un modelo de Machine Learning para predecir la probabilidad de que un avion se atrase o no. Algunas definiciones importantes es que el atraso se considera para todo vuelo que tenga una diferencia mayor a 15 minutos entre la hora inicial y la hora de operacion.

Se realizo un set de test de algoritmos de clasificacion para luego profundizar en XGBoost. Se eligio este modelo porque los modelos basados en arbol tienen una excelente visualizacion de la importancia de las variables en una prediccion en particular. Si bien la performance del modelo no es satisfactoria como para una implementacion, este desafio es y fue un ejercicion interesante, entretenido y valioso.

La parte del analisis exploratorio se realizo con una funcion de pandas_profiling, sin embargo, he visto en algunos entornos y maquinas que no corre del todo bien. El producto de esta libreria esta en un archivo en .html en el repositorio, sin embargo, si la visualizacion no es satisfactoria o hay problemas en el notebook, estare encantado de complementar enviandolo por email (sin embargo, espero que todo funcione correctamente).

Algunos archivos a encontrar en el respositorio:

* CV jppalmab: en esta carpeta se encuentra mi curriculum vitae.
* Challenge - Data Scientist.pdf: es el pdf de las instrucciones del desafio.
* dataset_SCL.csv: es el dataset con el que se trabajo en el desafio.
* requirements.txt: es un documento de texto que tiene las versiones de las librerias utilizadas en el notebook, la implementacion esta en el punto cero del notebook de solucion.
* EDA_preliminar: es un dashboard en html que tiene una exploracion de la base de datos en su estado inicial.
* synthetic_features: es una base de datos creada exclusivamente con las variables requeridas en el desafio.
* XGBoost_Tree: es una imagen del arbol de decisiones que construyo el modelo, util para ver los caminos que selecciono de manera grafica.
* fir.xlsx: es un archivo de excel que tiene distintos grados de profundidad en el analisis de que variables son explicativas en el modelo e incluso sus interacciones.
* solution.ipynb: es el jupiter notebook con la solucion al desafio que alberga tanto el codigo como la explicacion y la ruta de pensamiento y desarrollo del desafio.