# Análisis y Reporte sobre el desempeño del modelo

Esta carpeta incluye el archivo sobre el Entregable "Análisis y Reporte sobre el desempeño del modelo" posterior a la retroalimentación. Dicho archivo contiene 2 partes señaladas, siendo la **PARTE 2** la referente a esta entrega. En esta se realiza el análisis de desempeño del modelo de regresión con un Árbol de decisión regresor aplicado con la librería de Sci-Kit Learn. 

El análisis de desempeño se conduce con métricas para medir el sesgo, varianza y fit del modelo; para posteriormente reajustar sus hiperparámetros y evaluar nuevamente el modelo obtenido. 

A continuación se especifican los cambios pedidos en la retroalimentación del entregable y cómo fueron cumplidos: 

* **1** **_El reporte incluye una descripción breve de los datos incluidos en el dataset (cantidad de registros/muestras, número de características, número de clases de salida o rango de valores de salida):_** Al inicio del documento se describe dicha información en la sección llamada *Información sobre la base de datos: California Housing Prices*
* **2** **_El reporte incluye una descripción del tipo de problema a resolver (regresión o clasificación):_** Al inicio del documento se incluye dicha información en la sección llamada *Información sobre la base de datos: California Housing Prices*
* **3** **_El conjunto de validación se utiliza para escoger el modelo final (refinamiento de hiper-parámetros):_** En la sección de *Reajuste del modelo* se realiza de forma manual el ajuste del hiperparámetro Minimum Weight Fraction Leaf comparando el valor del MAPE con diferentes valores de este, tanto para el set de entrenamiento como el de validación.
* **4** **_Se detecta correctamente el grado de bias o sesgo: bajo medio alto:_** En la sección de detección del sesgo, se aplica Residuos Normalizados para tener una idea más clara de cuántas veces del valor real, están alejadas las predicciones, en lugar de centrarse en el sesgo estadístico.
* **5 y 6** **_Se detecta correctamente el grado de varianza: bajo medio alto y La decisión del grado de varianza se soporta con una tabla, gráfico, o similar:_** En la sección de detección de la varianza, se procede a utilizar la gráfica obtenida de los MAPEs para cada k-fold y finalmente se especifica de forma explícita el grado de varianza.
* **7** **_Se utilizan técnicas de regularización para mejorar el desempeño del modelo:_** En la sección de *Reajuste del modelo* específicamente después del reajuste de hiperparámetros, se hace uso de la poda o Reduced Error Pruning a través de la prueba de distintos valores para el parámetro Cc_alpha el cual ayuda a controlar la complejidad del modelo a través de costos. 
