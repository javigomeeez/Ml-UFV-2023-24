# Ml-UFV-2023-24
En este Jupyter , proporciono un flujo de trabajo para simular el analisis de la aceptación crediticia por parte de un banco basandome en presunciones de estres economico 
EL notebook se divide en dos partes , en primer lugar desarrollaremos las funciones de tensores que nos permitiran abordar el caso practico mas adelante
Despues provedemos a simular los indicadores financioros con las funciones creadas
Normalizamos los indicadores y les aplicamos el estres economico de bajada del 50%
Evaluamos la puntuación crediticia , la calculamos y actualizamos en función de los estresores
Convertimos en df y añadimos la columna categorica que nos permite identificar los clientes con el credito aprobado

#Uso del notebook
Deberemos tener instalado pytorch y pandas
Ejecutaremos el notebook en orden para poder aprovechar el flujo de creación de funciones
En caso de ser necesario se pueden modificar los parametros y las funciones para ajustarse a necesidades especificas

#Contribuciones futuras
Implementación de modelos predictivos , probablemente regresiones para poder predecir en base a nuevos inputs
