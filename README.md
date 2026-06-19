# sprint7-final-project
Este repositorio continene el analisis del proyecto final del sprint 7 de telecom.
Los dataset incluyen:
plans → información de los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra)
users → información de los clientes (edad, ciudad, fecha de registro, plan, churn)
usage → detalle del uso real de los servicios (llamadas y mensajes)

#Pasos realizados

Se realiza un analisis estadistico preliminar luego se realiza una limpieza de los datos atipicos:
En age se reemplaza el sentinel -999 con la mediana.
En city se reemplaza el sentinel "?" por valores nulos (pd.NA).
Se marcan como nulas las fechas fuera de rango (superiores a 2024).

Abrir el archivo en google colab: [S7_Version_Estudiante_Project_ConnectaTel.ipynb](https://colab.research.google.com/github/dcorrealm/sprint7-final-project/blob/main/S7_Version_Estudiante_Project_ConnectaTel.ipynb),
O:

1. Abre el archivo '.ipynb' en github
2. Haz clic en **Open in Colab*
