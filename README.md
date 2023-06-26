# TFG

En este repositorio se encuentra el código realizado para el TFG realizado por Ricardo Peralta Egea.

La documentación del proyecto se puede encontrar en : (está a la espera de ser publicado)

## Resumen
En este proyecto de fin de grado se examinan los enfoques actuales en el campo de empresas, investigaciones y organizaciones en relación al concepto de Inteligencia Artificial Sostenible (Green AI). Se pone especial énfasis en la reducción de datos durante la fase de entrenamiento, ya que al tener menos datos se reducirá la carga computacional, logrando así un entrenamiento más rápido y sostenible en términos de consumo de recursos.

Para la realización de las pruebas he usado el dataset de uso libre fashion-mnist. Este contiene 70,000 imágenes con 10 categorías de productos de moda en una escala de grises y con dimensiones 28x28. El conjunto de entrenamiento está formado por 60,000 muestras y el de test por 10,000. 

En este repositorio se encuentran dos de las técnicas que he implementado. La primera se encuentra en el archivo llamado "indicator.ipynb" esta es una técnica que implenta un medidor basado en la entropía y la distancia para seleccionar que muestras trabjarán mejor en el entrenamiento. 

La segunda técnica se basa en la separación de manera estratificada del conjunto. en el archivo "Stratified.ipynb" se encuentran las pruebas que realicé.

Finalmente en "prueba red.ipynb" se encuentran las pruebas que hice con ambos métodos descritos anteriormente para una misma red convolucional.

## Versiones

Python 3.10.9 en Jupyter Notebook. 

con las librerías
 - Scikit-learn en la versión 1.2.1 
 - Tensorflow con versión 2.12.

El dataset de fashion-mnist lo descargué de aquí:
https://www.kaggle.com/datasets/zalando-research/fashionmnist
