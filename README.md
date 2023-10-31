# project-ia2

# :fire: GeoCode

### Cartografía asistida por inteligencia artificial utilizando imágenes aéreas

## Resumen
Este proyecto consiste en segmentar imágenes aéreas de la zona metropolitana de Bucaramanga para llevar a cabo la diferenciación y clasificación del uso del suelo. La segmentación se realizará variando por diferentes factores, como el nivel de detalle requerido, la capacidad computacional y las clases asignadas.

Para lograr esta generación automática, se está empleando cartografía preexistente creada de forma manual para entrenar un modelo de redes neuronales que sea capaz de hacer el señalamiento de predios y de caracterización del uso de suelo del área metropolitana de Bucaramanga. El modelo tendrá como input la imagen cruda de la ortofoto y como output la caracterización necesaria, es decir la cartografía.

## Objetivos
- Segmentar imágenes aéreas de la zona metropolitana de Bucaramanga para llevar a cabo la diferenciación y clasificación del uso del suelo.
5 clases para segmentación:
  - Área caminable :children_crossing:
  - Área construida :construction:
  - Carretera :truck:
  - Zonas verdes :seedling:
  - Recortes Juntos :white_check_mark:
  
- Utilizar cartografía preexistente para entrenar un modelo de redes neuronales que sea capaz de hacer el señalamiento de predios y de caracterización del uso de suelo.
- Utilizar el modelo entrenado para generar cartografía automática del área metropolitana de Bucaramanga.
## Herramientas utilizadas
Python (Numpy, Pandas, Scikit-Learn, Matplotlib, Pytorch, Tensorflow) :technologist:
