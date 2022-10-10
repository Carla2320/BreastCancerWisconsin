# BreastCancerWisconsin

### Problema
Supongamos que usted trabaja en el servicio de salud y recibe muestras que provienen de
mujeres con cáncer de mama.
Los médicos han extraído características y las han anotado, su trabajo es crear un modelo
que sea capaz de identificar si un paciente tiene o no cáncer.
Recordemos que un falso positivo no es tan preocupante como un falso negativo, ya que en
el futuro se le hacen más pruebas a las pacientes y hay oportunidades de descubrir que
estábamos en un error.
Sin embargo, un falso negativo puede llevar a que el cáncer se desarrolle sin supervisión
durante más tiempo del necesario y podría llevar a daños más graves o incluso la muerte de
la paciente.

## SOLUCIÓN
Se probó con 3 modelos: Regresión Logistica, árbol de decisiones y random forest
### REGRESIÓN LOGISTICA

![image](https://user-images.githubusercontent.com/46575854/194784848-4a9b8048-0871-45f2-9488-ebbfa91255a9.png)

En este modelo se obtuvo la predicción de un 0.98 y se obtuvo en la matriz de confusión con 2 falsos negativos y 1 falso negativo. 

### Árbol de decisiones

![image](https://user-images.githubusercontent.com/46575854/194785020-e1075108-9085-4598-aa42-03d3fc398b65.png)

En este modelo se obtuvo la predicción de un 0.94 y se obtuvo en la matriz de confusión con 7 falsos positivos y 3 falsos negativos.

### Random forest

![image](https://user-images.githubusercontent.com/46575854/194785179-e221d4b6-ac81-4694-bb87-b4ccc5571a91.png)

En este modelo se obtuvo la predicción de un 0.97 y se obtuvo en la matriz de confusión con 1 falso positivo y 4 falsos negativos.

##CONCLUSIÓN

Como se puede observar el que tiene menos casos de falsos negativos es el modelo de regresión logistica y de igual manera la predicción es superior a los demás modelos.


