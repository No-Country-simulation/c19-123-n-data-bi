
![image](https://github.com/user-attachments/assets/eb8b6005-92ea-4d18-b264-22c524008930)

# Proyecto de  Simulación sobre Análisis de datos

![image](https://github.com/user-attachments/assets/4896bd6e-31e9-45e1-a3d9-a6854ec8265f)(https://insideairbnb.com/explore/)


# 1. Preparación del Dataset

## Origen de la Fuente de Datos
Dentro del repositorio de Airbnb se comparte data Publica donde se puede consultar con data con seis meses de antigüedad aproximadamente.
![Pasted image 20240802152155](https://github.com/user-attachments/assets/49ef8257-0995-46b2-8020-f469ece6310c)

Uno de los principales retos que se presenta para el analista, es determinar  que información distinta se presenta la |  <br>listings.csv.gz  vs   listings.csv  
mediante pandas  determinamos que 

![Pasted image 20240802152734](https://github.com/user-attachments/assets/75073060-46df-41bb-90c6-66f70bf081ef)

Por lo tanto
sabemos que:

![Pasted image 20240802152812](https://github.com/user-attachments/assets/8a84155f-ef94-4dd0-82ca-0d4aec3b9e0d)

Si comparamos el campo [NAME]

![Pasted image 20240802152901](https://github.com/user-attachments/assets/1f5e578a-7521-451e-a052-1644719a16c5)

De esta forma conservaremos  el campo NAME del archivo listining que proviene de la carpeta comprimida

### Limpieza de valores Nulos

La columna que lleva el registro del pais y el estado cuenta con valores nulos 
![Pasted image 20240802153334](https://github.com/user-attachments/assets/ed9606e9-d9b0-4f9c-b0be-d985c636590d)

Esta columna es de suma importancia por que se utilizara en futuros análisis de datos para que los dashboard se puedan filtrar por país y por ciudad, por lo que mediante técnicas de imputación logramos llenar los valores nulos utilizando la librería   KNNImputer  de sklearn .



![Pasted image 20240802153722](https://github.com/user-attachments/assets/c9e02271-f385-476d-9bae-582c38d96efc)


AL terminar de normalizar nuestro primer dataset 


![Pasted image 20240802153935](https://github.com/user-attachments/assets/a67ef1b2-f663-44bf-bdaa-6bb09e7fa912)



Ya podemos dedicarnos a la construcción del modelo de datos y tableros de control que den respuesta a las preguntas de negocio.




# 2. Creación de la Base de datos













# 3. Preguntas de Negocio y conclusiones


























