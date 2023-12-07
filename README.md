# project-ia2

# :fire: GeoCode

### Cartografía asistida por inteligencia artificial utilizando imágenes aéreas
<img src="https://github.com/ramiro999/project-ia2/blob/main/bannerRedimencionado.png"/>


## Integrantes:

Ramiro Ávila, Cristian Rey, Irvin Silva 

## Objetivo:
Segmentar imágenes aéreas de la zona metropolitana de Bucaramanga para llevar a cabo la diferenciación de 6 clases para segmentación. 

## Dataset:

Se trabajó con un conjunto de datos de acceso abierto realizado por el Centro espacial Mohammed Bin Rashid en Dubai, Emiratos Árabes Unidos. 

##Modelos:

Modelo U-net
Autoencoder
Indice de Jaccard
Dice Loss


## Resumen
Este proyecto consiste en segmentar imágenes aéreas de la zona metropolitana de Bucaramanga para llevar a cabo la diferenciación y clasificación del uso del suelo. La segmentación se realizará variando por diferentes factores, como el nivel de detalle requerido, la capacidad computacional y las clases asignadas.

Para lograr esta generación automática, se está empleando cartografía preexistente creada de forma manual para entrenar un modelo de redes neuronales que sea capaz de hacer el señalamiento de predios y de caracterización del uso de suelo del área metropolitana de Bucaramanga. El modelo tendrá como input la imagen cruda de la ortofoto y como output la caracterización necesaria, es decir la cartografía.



  
- Utilizar cartografía preexistente para entrenar un modelo de redes neuronales que sea capaz de hacer el señalamiento de predios y de caracterización del uso de suelo.
- Utilizar el modelo entrenado para generar cartografía automática del área metropolitana de Bucaramanga.
## Herramientas utilizadas
Python (Numpy, Pandas, Scikit-Learn, Matplotlib, Pytorch, Tensorflow) :technologist:
