# Kaggle-Competition

# WEEK 7 PROJECT

## PREDICT THE SALARIES OF DATA SCIENCE JOBS

![image](https://github.com/Ironhack-Data-Madrid-Mayo-2022/Kaggle-Competition/blob/main/images/Bag_of_Money.jpg)


### RECURSOS
----------------------------------------------------------------------------------------------------------------------------

  + Data salaries csv
  + Test cvs
  + Sample.csv (example of results that must upload to kaggle)



### OBJETIVOS
----------------------------------------------------------------------------------------------------------------------------


   + Entrenar y pruebar algunos modelos de aprendizaje automático
   + Subir los resultados del mejor modelo de aprendizaje automático entrenado
   + Hacer una solicitud de extracción con ppt en la carpeta ppt
  

### PROCESO
#### Primera prueba

   + Obtener datos
   
     Se cargan los dos archivos csv, Data salaries csv y test csv, y se examinan los datos. 
     Unimos los dos archivos mediante concat.
     
   + Definir objetivo
   
     El objetivo del ejercicio consiste en predecir el salario al mínimo error posible.
     
   + Limpieza de los datos
   
     - Label Encoding en la columna company_size, de modo que a las empresas de tamaño pequeño les asigne el valor 0, empresas de tamaño medio valor 1 y empresas de tamaño grande valor 2.
     
     - Dummies en columna employment_type, experience_level y employee_residence.
     
     - Commpany_location, creo un diccionario en el que incluyo el salario medio por cada país y reemplazo los valores.
     
     - Label Encoding en la columna remote_ratio, dandole valores de 0, 1 y 2 respectivamente.
     
     - Columna job_title, agrupo los puestos trabajo por categorías, dejando un total de 13 categorías. Luego hago dummies en esta columna.
     
   + Definir modelo
   
     - En este trabajo he utilizado modelos de Regresión Lineal tales como LinearRegression, Lasso, Ridge y ElasticNet.
     
   + Entrenamiento
   
     - Se procede al entrenamiento del modelo con los datos que le suministramos.
     
   + Predicción y Evaluación
   
     - Según las predicciones obtenidas en nuestro testeo observamos que el modelo que mejor funciona, para nuestro trabajo, es Ridge.



### RESULTADOS
----------------------------------------------------------------------------------------------------------------------------

Los resultados de la competición se pueden ver en el siguiente enlace a Kaggle.

https://www.kaggle.com/competitions/bt-ironhack-agosto-2022-ml-competition/leaderboard


![image](https://github.com/Vert-ix/Vert-ix/Week-7-Project-Kaggle-Competition-/images/kaggle_competition.png)
  