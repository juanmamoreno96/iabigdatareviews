# Detección de reseñas positivas y negativas de una tienda de ropa usando XLM-RoBERTa (base-sized model)

## Problema a resolver

- PROBLEMA: Debido a las altas devoluciones que se están produciendo en una tienda de ropa local, se necesita reducir el número de éstas para poder yo como dueño de la tienda ver cuales son las causas por los que el usuario devuelve la prenda. Así poder mejorar las caracteristicas de las prendas o qué tipo de ropa quieren los compradores que tenga en dicha tienda
- SOLUCIÓN: Para abordar el análisis de reseñas y la detección de reseñas positivas y negativas, se ha elegido el modelo: XLM-RoBERTa (base-sized model), de HuggingFace (https://huggingface.co/FacebookAI/xlm-roberta-base).

## Objetivo

- El objetivo de este proyecto es clasificar una opinión de un producto en POSITIVA o NEGATIVA mediante el uso de técnicas de procesamiento de lenguaje natural y Deep Learning.

## Técnica y Métodos

- Uso de notebook en Google Colab para la utilización de su GPU.

- El modelo fue entrenado con lenguaje español utilizando el dataset de Kaggle traducido (https://www.kaggle.com/datasets/shavilyarajput/clothing-shoes-and-jewellery-reviews), que contiene varias reviews de productos de una tienda de ropa.
- Se utilizó la métrica de evaluación del modelo: Accuracy, debido a que el equilibrio de la distribución de los ejemplos era bueno.

# Interfaz grafica 
Se ha creado una interfaz gráfica del modelo que se puede encontrar en el siguiente enlace --> https://reviewsiabigdata.streamlit.app/

# Archivos

- **Deteccion_Reviews_Tienda_Ropa_RoBERTa_Español.ipynb:** Notebook del entrenamiento del modelo con todas sus clases y procesamientos del dataset.
- **Modelo_Tienda_review.pt:** Modelo ya entrenado.
- **app.py:** Archivo donde se encuentra la implementación de la interfaz gráfica.
- **requirements.txt:** Librerías necesarias para que funcione la interfaz gráfica del modelo.
- **docs/reviews_bert_memoria.docx:** Memoria del trabajo
