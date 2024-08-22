# Data-Science-II

Motivación:
La elección de datos para este estudio se basa en la creciente disponibilidad de información detallada sobre características de audio de canciones, accesibles a través de APIs como la proporcionada por Spotify. Estas características incluyen dimensiones clave como energía, valencia, tempo y otros atributos que capturan aspectos fundamentales de la composición musical. La motivación radica en aprovechar estas características para explorar cómo pueden utilizarse en modelos de machine learning para predecir géneros musicales, lo cual tiene implicaciones significativas en aplicaciones como recomendación de música, análisis de tendencias y personalización de experiencias de usuario en plataformas de streaming.

Audiencia Objetivo:
Este estudio está dirigido a investigadores y profesionales del campo de la ciencia de datos y la inteligencia artificial, así como a desarrolladores y diseñadores de sistemas de recomendación musical. También es relevante para empresas de música digital y plataformas de streaming que buscan mejorar la precisión de sus sistemas de recomendación y comprensión del comportamiento del usuario. Además, es de interés para académicos y estudiantes interesados en aplicaciones prácticas de análisis de datos en el dominio de la música y la cultura digital.

Este abstracto proporciona una breve introducción a los datos utilizados, la razón para elegirlos y la audiencia a la que está dirigido el estudio, destacando la importancia y las posibles aplicaciones de la predicción de géneros musicales mediante el uso de características de audio.

Cuestiones a resolver:
Precisión en la Predicción de Géneros Musicales: ¿Qué tan precisos pueden ser los modelos de machine learning para predecir automáticamente el género de una canción basándose únicamente en características de audio?

Relevancia de las Características de Audio: ¿Qué características de audio (como energía, valencia, tempo, etc.) son más relevantes para la clasificación precisa de géneros musicales?

Comparación de Modelos de Machine Learning: ¿Cuál de los modelos probados (SVM, Random Forest, Gradient Boosting, etc.) proporciona el mejor rendimiento en términos de precisión, recall y F1-score para la clasificación de géneros musicales?

Aplicabilidad en Sistemas de Recomendación Musical: ¿Cómo pueden estos modelos mejorados beneficiar la precisión y la personalización de los sistemas de recomendación musical en plataformas de streaming?


Conclusión: En este proyecto, se buscó mejorar el desempeño de los modelos de Machine Learning para la clasificación de géneros musicales mediante la creación de variables sintéticas y la aplicación de técnicas de reducción de dimensionalidad como el Análisis de Componentes Principales (PCA). A través del análisis, se identificaron interacciones significativas entre características de audio, como la combinación de `acousticness` con `liveness` y `energy` con `loudness`, que se incorporaron en los modelos. Tras reentrenar los modelos de **Support Vector Machine (SVM)**, **Random Forest**, y **Gradient Boosting**, se observó que el rendimiento en el conjunto de entrenamiento mejoró, aunque se mantuvo constante en el conjunto de prueba, lo que sugiere que las nuevas variables sintéticas proporcionaron una representación más rica de los datos sin introducir overfitting significativo. La aplicación de PCA reveló que los primeros dos componentes principales explicaban una parte considerable de la varianza en los datos, destacando las variables más relevantes. En resumen, el proyecto demostró que la ingeniería de características puede mejorar el desempeño de los modelos y proporcionar una comprensión más profunda de la estructura de los datos, lo cual es crucial para la clasificación precisa de géneros musicales.


Generalización y Escalabilidad: ¿Qué tan bien generalizan estos modelos a nuevos conjuntos de datos y qué consideraciones deben tenerse en cuenta para escalar el modelo a un conjunto de datos más grande?

Interpretación de los Modelos: ¿Qué insights pueden obtenerse sobre las preferencias musicales y la estructura de los géneros a través del análisis de los modelos entrenados?

Impacto Cultural y Social: ¿Cuál es el impacto potencial de mejorar la precisión en la clasificación de géneros musicales en términos de accesibilidad y diversidad cultural en la música?
