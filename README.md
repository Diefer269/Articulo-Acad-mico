# Articulo-Acad-mico
Diseño y Evaluación para Detección de Retinopatía

Dentro del Archivo TESIS.ipynb encontrames el codigo para la carga del dataset, junto con el proceso aplicado al entrenamiento, impresión de resultados y la evaluación de las metricas.

## Puntos A Tener En Cuenta
# Carga del Dataset
Debido al peso del dataset para subirlo de forma directa al colab o por drive.
La carga del dataset se realizo por medio de un API key proporcionado por roboflow para la extracción y carga del data set, eso se especifica en el archivo.

# Entrenamiento de los modelos
Para el entrenamiento de los modelos, se realizo el uso del mismo:
- Optimizador: Adam
- Función de Perdida: Cross-Entrophy Loss
- Dimencionamiento: 224 x 224
Esto se implemente de igual manera en los 4 modelos para el entrenamiento y así poder tener la misma evaluación para demostrar cual tiene la mejor eficiencia, rendimiento y resultado
