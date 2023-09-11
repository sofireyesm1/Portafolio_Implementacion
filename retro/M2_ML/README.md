# Portafolio de Implementación Módulo 2 

Dentro de este repositorio, se encuentran dos modelos de regresión de Machine Learning. El primero, es un modelo creado de forma manual, el cual utiliza regresión lineal simple; y el segundo es un modelo de árboles de decisión aplicados a regresión creado con ayuda de la librería Sci-Kit Learn. 

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

## Proyecto 1: Framework manual
El objetivo de este proyecto, es poder generar un modelo de regresión lineal simple del precio de las casas según el nivel de ingresos de las casas aledañas a esta. Esto se logra a través de un código que aplica gradiente descendiente y realiza el entrenamiento de forma manual. El proyecto puede ser encontrado en el [siguiente archivo](https://github.com/sofireyesm1/Portafolio_Implementacion/blob/main/retro/M2_ML/A00831314_T1_ML.ipynb).

## Proyecto 2: Framework con Sci-Kit Learn y Reporte de desempeño
En este segundo proyecto, se utilizó la librería Sci-Kit Learn para aplicar un árbol de decisión regresor para predecir el valor de las casas de un distrito en California, en base de la edad de la casa, así como el ingreso medio de las familias que vivan en casas aledañas. Es importante recalcar que el archivo se encuentra dvidido en 2 partes (o dos entregas); el proyecto de aplicación mencionado (Entregable 2), y el análisis de desempeño del mismo (Entregable 3, no cuenta para este portafolio).  El proyecto se encuentra en el  [siguiente archivo](https://github.com/sofireyesm1/Portafolio_Implementacion/blob/main/retro/M2_ML/A00831314_T2_T3.ipynb).

## Estructura del repositorio
- [A00831314_T1_ML.ipynb](https://github.com/sofireyesm1/Portafolio_Implementacion/blob/main/retro/M2_ML/A00831314_T1_ML.ipynb) : Contiene el reporte y código del primer modelo de ML de regresión lineal simple.
- [A00831314_T2_T3_ML.ipynb](https://github.com/sofireyesm1/Portafolio_Implementacion/blob/main/retro/M2_ML/A00831314_T2_T3.ipynb) : Contiene el reporte y código del segundo modelo de ML de árbol de decisión regresor, así como el reporte y código del análisis de desempeño de este segundo modelo. 
- ReadMe (archivo actual): Archivo con toda la descripción del repositorio
- [housing.csv](https://github.com/sofireyesm1/Portafolio_Implementacion/blob/main/retro/M2_ML/housing.csv): Base de datos utilizada en los dos modelos. 
Ambos entregables están basados en la siguiente base de datos:
