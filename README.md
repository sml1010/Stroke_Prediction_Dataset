# Stroke_Prediction_Dataset
Trabajo Final de Minería de Datos Clínicos y Biológicos (3º Ingeniería de la Salud)

En este cuaderno intenté predecir si una persona sufriría un ictus con los parámetros dados. Lo más llamativo de este conjunto de datos es que presenta una clase objetivo desequilibrada.

Seguí un enfoque general en el conjunto de datos:

Limpieza de datos y EDA
Escalado de los datos
Gestión del desequilibrio de clases con el método SMOTEENN
Comparación de modelos de aprendizaje automático
Ajuste de hiperparámetros con CV de búsqueda aleatoria
Encontrar los mejores parámetros con CV de búsqueda en cuadrícula
Además, también probé la selección futura e intenté implementar el modelo con las características seleccionadas. Sin embargo, la selección de características no modificó significativamente la precisión del modelo.

Fuente del conjunto de datos: Datos de accidentes cerebrovasculares del conjunto de datos de atención médica de Kaggle.

Este conjunto de datos se utiliza para predecir la probabilidad de que un paciente sufra un accidente cerebrovascular según parámetros de entrada como el sexo, la edad, diversas enfermedades y el tabaquismo. Se extrae un subconjunto de los datos originales mediante el método de filtrado para fines de aprendizaje automático y visualización de datos.

Acerca de los datos: Cada fila de los datos proporciona información relevante sobre una persona, por ejemplo, edad, sexo, tabaquismo, incidencia de accidentes cerebrovasculares, entre otra información. "Desconocido" en el campo "Fumar" significa que la información no está disponible. "N/A" en otros campos de entrada implica que no es aplicable.

