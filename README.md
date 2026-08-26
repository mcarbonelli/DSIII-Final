# Entrega Final — Data Science III
## Análisis de Sentimiento en Redes Sociales con NLP y Deep Learning (Electrín S.A.)

Este repositorio contiene la **Entrega Final** de la materia **Data Science III**.

### Contenido del Repositorio
* **`Entrega_Final_DSIII_MauricioCarbonelli.ipynb`**: Notebook Jupyter con el desarrollo completo de punta a punta, estructurado en 3 partes:
  1. **Parte A (NLP):** Carga de datos, EDA con gráficos y WordClouds, pipeline de limpieza (regex, tokenización, stopwords) y vectorización **TF-IDF (unigramas y bigramas)**.
  2. **Parte B (Deep Learning Mínimo):** Baselines clásicos (Regresión Logística y Naive Bayes) y **Red Neuronal Simple** (1 capa oculta con ReLU y salida Sigmoide) implementada en Keras / TensorFlow.
  3. **Parte C (Profundización de Deep Learning):** **Red Neuronal Profunda (DNN)** con múltiples capas densas, *Batch Normalization*, regularización *Dropout*, regularización L2 y optimizador *Adam*, evaluando matrices de confusión, curvas de aprendizaje y un simulador de inferencia en tiempo real.
* **`comentarios_instagram_electrin.csv`**: Dataset con 900 comentarios clasificados de forma binaria (`0: Negativo/Reclamo`, `1: Positivo/Agradecimiento`) sobre publicaciones de Instagram de la empresa de distribución eléctrica ficticia **Electrín**.

### Ejecución en Google Colab
El notebook está preparado para ejecutarse directamente en **Google Colab** consumiendo el dataset desde este repositorio público.
