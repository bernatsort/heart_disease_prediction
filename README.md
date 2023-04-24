# Heart disease prediction

## Descripción del proyecto
Este proyecto consiste en la detección de cardiopatías en pacientes mediante el uso de datos clínicos utilizando técnicas de Machine Learning y Deep Learning. 

## Estructura del proyecto
Los archivos y carpetas relevantes del proyecto son los siguientes:".

- "code.ipynb": este archivo contiene el código del proyecto, donde se realiza el análisis exploratorio de los datos, se preprocesan y se entrenan diferentes modelos de ML y DL para predecir la presencia de enfermedad cardíaca en los pacientes.

- "heart_2020.csv": archivo de datos sin procesar utilizado en el proyecto.

- "train_data.csv" y "test_data.csv": estos archivos contienen los datos divididos en un 80% y 20% respectivamente del archivo heart_2020.csv.

- "train_data_preprocessed.csv" y "test_data_preprocessed.csv": archivos que contienen los datos preprocesados de entrenamiento y test respectivamente.

- "X_train_balanced_70" y "X_train_balanced_90": estos archivos contienen los datos de entrenamiento (sin la variable objetivo "HeartDisease") balanceados con un porcentaje del 70% y 90% respectivamente.

- "y_train_balanced_70" y "y_train_balanced_90": estos archivos contienen las etiquetas o labels (variable "HeartDisease") correspondientes a los datos de entrenamiento balanceados con un porcentaje del 70% y 90% respectivamente.

- "weights": esta carpeta contiene los pesos del modelo inicial de la red neuronal (modelo 1) para que los distintos entrenamientos sean más comparables (los cargamos en cada modelo antes del entrenamiento, excepto para el modelo 4 de redes neuronales). También contiene los pesos del modelo de red neuronal 4.


## Para realizar este proyecto se han usado las siguientes especificaciones:
- bPython: 3.9.16 | packaged by conda-forge | (main, Feb  1 2023, 21:38:11) 
- [Clang 14.0.6 ]
- Pandas: 1.5.3
- Numpy: 1.23.2
- Matplotlib: 3.7.1
- Seaborn: 0.12.2
- Sklearn: 1.2.1
- Catboost: 1.1.1
- TensorFlow: 2.12.0

TensorFlow has access to the following devices:
· PhysicalDevice(name='/physical_device:CPU:0', device_type='CPU')
· PhysicalDevice(name='/physical_device:GPU:0', device_type='GPU') 
