# Portafolio de Implementación Módulo 2 

Dentro de esta carpeta, se encuentran dos modelos de regresión de Machine Learning. El primero, es un modelo creado de forma manual, el cual utiliza regresión lineal simple; y el segundo es un modelo de árboles de decisión aplicados a regresión creado con ayuda de la librería Sci-Kit Learn. 

## Base de datos

*Nombre:* California Housing prices, basado en los precios de las casas en California en 1990

*Recuperado de:* Dataset de [Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices)

*Número de registros:* 20,640

*Número inicial de columnas:* 10

**Columnas a utilizar en el proyecto 1 :** 2, 

  - _Median income_: mediana de los ingresos mensuales de casas vecinas a la casa en venta. Medido en 10 miles de dólares. 
  -  _Median house value_: mediana de los precios de casas en una manzana. Datos se encuentran en dólares. _(variable dependiente)_
    
**Columnas a utilizar en el proyecto 2 :** 3, 

  - _Median income_: mediana de los ingresos mensuales de casas vecinas a la casa en venta. Medido en 10 miles de dólares.
  - _Housing median age_: mediana de las edades de las casas de una manzana
  -  _Median house value_: mediana de los precios de casas en una manzana. Datos se encuentran en dólares. _(variable dependiente)_

## Proyecto 1: Algoritmo de ML manual
El objetivo de este proyecto, es poder generar un modelo de regresión lineal simple del precio de las casas según el nivel de ingresos de las casas aledañas a esta. Esto se logra a través de un código que aplica gradiente descendiente y realiza el entrenamiento de forma manual. El proyecto puede ser encontrado en el [siguiente archivo](https://github.com/sofireyesm1/A00831314_Evidencia_1/blob/main/A00831314_T1_ML.ipynb).

## Proyecto 2: Framework con Sci-Kit Learn y Reporte de desempeño
En este segundo proyecto, se utilizó la librería Sci-Kit Learn para aplicar un árbol de decisión regresor para predecir el valor de las casas de un distrito en California, en base de la edad de la casa, así como el ingreso medio de las familias que vivan en casas aledañas. Es importante recalcar que el archivo se encuentra dvidido en 2 partes (o dos entregas); el proyecto de aplicación mencionado (Entregable 2), y el análisis de desempeño del mismo (Entregable 3). Este último análisis consta de utilizar herramientas de diagnóstico (sego, varianza y ajuste) para identificar la calidad del modelo, y posteriormente se aplican ciertas mejoras al modelo según el análisis realizado. El proyecto se encuentra en el  [siguiente archivo](https://github.com/sofireyesm1/A00831314_Evidencia_1/blob/main/A00831314_T2_ML.ipynb).

## Estructura del repositorio
- [A00831314_T1_ML.ipynb](https://github.com/sofireyesm1/A00831314_Evidencia_1/blob/main/A00831314_T1_ML.ipynb) : Contiene el reporte y código del primer modelo de ML de regresión lineal simple.
- [A00831314_T2_T3_ML.ipynb](https://github.com/sofireyesm1/A00831314_Evidencia_1/blob/main/A00831314_T2_ML.ipynb) : Contiene el reporte y código del segundo modelo de ML de árbol de decisión regresor, así como el reporte y código del análisis de desempeño de este segundo modelo. 
- ReadMe (archivo actual): Archivo con toda la descripción del repositorio
- [housing.csv](https://github.com/sofireyesm1/A00831314_Evidencia_1/blob/main/housing.csv): Base de datos utilizada en los dos modelos.

## Aplicación de cambios requeridos

A continuación se especifican los cambios pedidos en la retroalimentación de los entregables y cómo fueron cumplidos: 

* **Proyecto 1: Algoritmo de ML manual**
*  * **1 y 2** **_El modelo se entrena sobre un subset de entrenamiento de un dataset y Se corren algunas predicciones para validar la salida del modelo, usando datos diferentes a los de entrenamiento:_** Para esto, se dividió el dataset en entrenamiento y hizo iteraciones con diferentes valores de delta con este mismo subset, esto con el fin de encontrar el mejor modelo según el menor valor de MAPE para las predicciones.
  * **3** **El readme contiene una descripción breve de la estructura del repositorio (qué es cada archivo/carpeta):_** En este mismo archivo se encuentra una sección para la estructura de la carpeta.
  * **4** **El readme contiene una sección de cambios implementados, donde se mencione el cambio indicado por el docente y lo que se hizo para resolverlo (solo aplica para entrega final):_** Esta es la sección implementada para mencionar los cambios realizados.
  * **5** **El reporte incluye un enlace al lugar donde se puede encontrar el dataset utilizado:_** Al inicio del notebook se encuentra una liga de la página donde se consiguió el dataset.
  * **6** **El reporte incluye una comparación entre las predicciones generadas y los valores que debieron obtenerse:_** Al final del archivo se encuentra la sección de predicción con el subset de prueba, donde se visualiza mediante un scatterplot de los valores reales vs. los obtenidos con el modelo. De igual manera, se utiliza la métrica MAPE para medir el error porcentual de las predicciones.

* **Proyecto 2: Algoritmo de ML con uso de Framework**
  * No existieron cambios a realizar en este documento.

