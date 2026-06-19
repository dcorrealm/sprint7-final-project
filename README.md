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

Abrir el archivo en google colab: https://drive.google.com/file/d/1es2KQVNkEFv71Ol0o0X7Ye9aQJ_dDQ8S/view?usp=sharing,
O:

1. Abre el archivo '.ipynb' en github
2. Haz clic en **Open in Colab*
