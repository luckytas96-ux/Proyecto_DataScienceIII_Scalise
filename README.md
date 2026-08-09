# Proyecto Final - Data Science III

**Autor:** Lucas Scalise

**Comisión:** 86780

## Análisis de Sentimientos en Reseñas de IMDb

Este proyecto tiene como objetivo analizar y clasificar automáticamente reseñas de películas como positivas o negativas mediante técnicas de **Procesamiento de Lenguaje Natural (NLP), Machine Learning y Deep Learning**.

## Dataset

Se utilizó el **IMDb Dataset of 50K Movie Reviews**, compuesto por 50.000 reseñas de películas clasificadas como positivas o negativas.

El dataset es obtenido automáticamente desde Kaggle mediante kagglehub, por lo que no es necesario descargarlo o cargarlo manualmente.

## Etapas del proyecto

El proyecto incluye:

- Exploración y análisis de los datos.
- Limpieza y preprocesamiento de texto.
- Tokenización.
- Eliminación de stopwords.
- Lematización.
- Análisis mediante nubes de palabras.
- Vectorización mediante TF-IDF.
- Entrenamiento de modelos de Machine Learning.
- Construcción de una red neuronal inicial.
- Mejora de la red mediante nuevas capas, Dropout y Early Stopping.
- Comparación de los modelos.
- Predicción sobre nuevas reseñas.
- Conclusiones finales.

## Modelos utilizados

Se entrenaron y evaluaron cuatro alternativas:

| Modelo | Accuracy |
|---|---:|
| Red neuronal mejorada | 89.38% |
| Regresión Logística | 89.04% |
| Red neuronal inicial | 88.61% |
| Naive Bayes | 85.42% |

La **red neuronal mejorada** obtuvo el mayor accuracy, aunque con una diferencia reducida respecto de la Regresión Logística.

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- TensorFlow / Keras
- WordCloud
- KaggleHub
- Google Colab


