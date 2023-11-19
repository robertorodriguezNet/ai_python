# ai_python

## Starting in AI

Hay que instalar Python con pip.

## Preparar VSC

- Instalar
  - Python (Microsoft).
  - Jupyter (Microsoft).
    - Permite programar en libretas de python.
- Archivos para programar en libretas: ipynb.

## Machine Learning

- Datos
  - Utilizados para entrenar el modelo.
- Modelo
  - Utiliza los datos en el proceso de entrenamiento para optimizarse.
- Predicción
  - Utiliza el modelo entrenado para predecir en datos nuevos.

### Tipos de Machine Learning (u03: Tipos de Machine Learning)

- Aprendizaje supervisado.
  - Hay un conjunto de datos con características.
  - Contamos con la etiqueta correcta para cada conjunto de datos.
  - Ej.: Predicción del precio de casas.
    - Características: baños, cuartos, superficie, piscina, ...
    - Cada conjunto de características cuenta con una etiqueta, que es el precio.

| #baños | #habitaciones | #superficie | #piscina |  precio  |
|:------:|--------------:|------------:|:--------:|---------:|
|   2    |      3        |      70     |    no    |  130.000 |
|   3    |      4        |      65     |    si    |  125.000 |
|   3    |      5        |     110     |    si    |  340.000 |
|   1    |      3        |      40     |    no    |   90.000 |

- Aprendizaje no supervisado.
- Aprendizaje por refuerzo.

## Bibliotecas

- Pandas.

## Términos

- *Regresión:* Predecir un dato numérico continuo.
  