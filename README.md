# Reconocimiento-de-emociones
### Integrantes:
- Auqui Manuel
- Guambo Leoni
- Mendez Mayerli
- Ortiz Jorge
- Valencia Luis
---
Bienvenido a la guía básica para implementar el código de este proyecto de reconocimiento de emociones (disgusto, enojo, felicidad, neutralidad, sorpresa y tristeza) utilizando Python y OpenCV [1]. A continuación, te explicaremos que debes hacer con cada uno de ellos. 

## Paso 1
Necesitas instalar las siguientes librerías.

```
pip install numpy
pip install opencv-contrib-python
pip install imutils
```

## Paso 2
Dentro del repositorio se encuentran 3 archivos:
- [capturandoRostros.py](https://github.com/ManuEly19/Reconocimiento-de-emociones/blob/master/capturandoRostros.py)
- [entrenamiento.py](https://github.com/ManuEly19/Reconocimiento-de-emociones/blob/master/entrenando.py)
- [reconocimientosEmociones.py](https://github.com/ManuEly19/Reconocimiento-de-emociones/blob/master/reconocimientoEmociones.py)

Necesitamos crear una nueva carpeta llamada “Data” y a continuación dentro de cada uno de los archivos remplazar la dirección que se encuentra en la imagen por la dirección de su carpeta creada recientemente.

![image](https://user-images.githubusercontent.com/74938678/187807313-1dbc34b7-0534-472f-a61f-b8739c4b76da.png)
## Paso 3
El primer script que tenemos que ejecutar es el archivo [capturandoRostros.py](https://github.com/ManuEly19/Reconocimiento-de-emociones/blob/master/capturandoRostros.py).
Dentro del archivo debemos asegurarnos de que una de las siguientes líneas de código que se observa en la siguiente imagen se encuentre sin comentar y ejecutar el Script. Una ves terminada tenemos que comentar la línea sin comentar y asegurarnos que otras de las siguientes líneas se encuentran sin comentar. Debemos repetir el proceso por cada una de las emociones que se encuentran en cada línea. 

![image](https://user-images.githubusercontent.com/74938678/187807375-01c53cc8-1a42-4d32-87ba-8fe37c67d929.png)

La cámara se encenderá y deberas replicar con tu rostro la emoción que este sin comentar. Como resultado de esta acción crearemos subcarpetas de imágenes con los nombres de cada emoción, estas carpetas servirán para entrenar los modelos de reconocimiento de emociones.  

![image](https://user-images.githubusercontent.com/74938678/187807397-390da892-f89e-4cbf-a291-73f56b19c983.png)

## Paso 4
Ejecutamos el archivo [entrenamiento.py](https://github.com/ManuEly19/Reconocimiento-de-emociones/blob/master/entrenando.py).
Como resultado obtendremos 3 archivos .xml que contendrán el modelo de reconocimiento de emociones entrenado y listo para usarse. 

![image](https://user-images.githubusercontent.com/74938678/187807427-1b695588-d268-43fb-af7a-906378ac5416.png)

## Paso 5
Dentro del archivo [reconocimientosEmociones.py](https://github.com/ManuEly19/Reconocimiento-de-emociones/blob/master/reconocimientoEmociones.py) dejamos sin comentar alguno de los métodos que se desea probar, como se observa en la siguiente imagen y finalmente ejecutamos el script.  

![image](https://user-images.githubusercontent.com/74938678/187807468-5e0113df-764f-4dfd-9cfa-a7d5b8722395.png)

Como resultado obtendremos el reconocimiento de sus emociones en tiempo real.

![image](https://user-images.githubusercontent.com/74938678/187808820-9faa7409-c770-4fc7-ad40-660b22200fe9.png)

## Referencias

[1] 	G. Solano, «Omes,» 02 jul 2022. [En línea]. Available: https://omes-va.com/reconocimiento-de-emociones-opencv-python/. [Último acceso: 31 ago 2022].


