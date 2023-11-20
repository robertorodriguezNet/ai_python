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

- **Datos**
  - Utilizados para entrenar el modelo.
  - Hay que limpiar los datos antes de poder usarlos.
  ![Datos](/images/datos.png "Los datos deben ser consistentes")
  - Se debe definir las características relevantes para el modelo.
  - Con los datos limpios, se separan las características de las etiquetas para que el modelo pueda utilizarlos para enterenar.
  - Se separan los datos en un conjuto de **entrenamiento** (80% de los datos) y en otro de **pruebas** (20% de los datos).
    - Entrenamiento: el modelo usa estos datos para ajustar su estructura interna y mejorar.
    - Pruebas: se usa para evaluar al modelo y ver cómo quedó entrenado.
  
- **Modelo**
  - Utiliza los datos en el proceso de entrenamiento para optimizarse.
  
- **Predicción**
  - Utiliza el modelo entrenado para predecir en datos nuevos.

### Tipos de Machine Learning (u03: Tipos de Machine Learning)

- **Aprendizaje supervisado.**
  - Hay un conjunto de datos con características.
  - Contamos con la etiqueta correcta para cada conjunto de datos.
  - Usos: Clasificación de imágenes, diagnósticos médicos, reconocimiento de voz, ...
  - Ej.: Predicción del precio de casas.
    - Características: baños, cuartos, superficie, piscina, ...
    - Cada conjunto de características cuenta con una etiqueta, que es el precio.

| #baños | #habitaciones | #superficie | #piscina |  precio  |
|:------:|--------------:|------------:|:--------:|---------:|
|   2    |      3        |      70     |    no    |  130.000 |
|   3    |      4        |      65     |    si    |  125.000 |
|   3    |      5        |     110     |    si    |  340.000 |
|   1    |      3        |      40     |    no    |   90.000 |

- **Aprendizaje no supervisado.**
  - Hay datos pero no etiquetas.
  - El modelo busca patrones y relaciones.
  - Ej.: Se cuenta con un gran número de clientes y a partir de ellos se crean *clústers* o grupos.
  ![Grupos a partir de datos](/images/grupos.png "Grupos a partir de datos")
  
- **Aprendizaje por refuerzo.**
  - Un agente aprende en un ambiente por medio de acciones y retroalimentación.
  - A cada acción se le dice si fue correcto o incorrecto, dándole puntos numéricos.
  - El agente buscará ajustarse para realizar acciones que le den más punto.
  - Ej: Jugar al ajedrez.

## Bibliotecas

- **Pandas.**
  - Código abierto.
  - Permite visualizar, leer y analizar datos de forma sencilla.
  - Ej. *u03_primeros_modelos/regresion_lineal/fahrenheit-celsius.ipynb*.
    - Se usa para obtener los datos a partir de un fichero csv.
      - `datos = pandas.read_csv("foo.csv");`
  
- **NumPy.**
  - Permite trabajar con arrays de datos de múltiples dimensiones.

- **Scikit-learnin.**
  - Herramientas para modelos.

- **MathPlotLib.**
  - Crea gráficos y visualización de datos.
  
- **TensorFlow.**
  - Para Deep Learning y redes neuronales.

- **seaborn**
  - Muestra gráficas.
    - Ver ejemplos:
      - *u03_primeros_modelos\fahrenheit-celsius.ipynb*
  
## Glosario

- **Clasificación:** El modelo predice una categoría.
  - *Ej*:  El modelo predice, en base a una categoría, si la foto de una mascota es un perro o es un gato.
  
- **Regresión:** El modelo predice un dato numérico continuo.
  