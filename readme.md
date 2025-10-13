# Trabajos practicos de la asignatura: Procesamiento de Lenguaje Natural

Repositorio con los trabajos practicos de la asignatura Procesamiento de Lenguaje Natural dictada en la Maestria en Inteligencia Artificial de la FIUBA.

## Requisitos

- Python 3.9 o superior

Crear un entorno virtual (opcional pero recomendado) y luego instalar las dependencias:
```sh
pip install -r requirements.txt
```

## Contenido

### Desafio 1 – Similaridad y clasificación con 20 Newsgroups
- `desafio_1.ipynb`: Se trabaja con el dataset 20 Newsgroups para explorar técnicas de representación y clasificación de texto.
- Vectorización de documentos con `TfidfVectorizer` y `CountVectorizer`.
- Exploración de similitud entre documentos: vecinos más cercanos y matriz término-documento transpuesta para estudiar términos similares.
- Clasificación por prototipos (zero-shot) y experimentos con Naïve Bayes Multinomial/Complement para maximizar macro F1.

### Desafio 2 – Word2Vec con relatos de Lovecraft
- `desafio_2.ipynb`: Se entrena un modelo Word2Vec utilizando el corpus de relatos de Lovecraft.
- Limpieza del corpus y tokenización con `text_to_word_sequence`.
- Entrenamiento de un modelo Word2Vec Skip-gram con callbacks de pérdida por época.
- Análisis de similitud entre palabras seleccionadas y visualización 2D de embeddings (TSNE/umap) para discutir relaciones léxicas.

### Desafio 3 – Modelos de lenguaje carácter a carácter con relatos de Lovecraft
- `desafio_3.ipynb`: Se exploran modelos de lenguaje carácter a carácter para generación de texto utilizando redes neuronales recurrentes RNN, LSTM y GRU.


### Desafio 4 – Traducción secuencia a secuencia
- `desafio_4.ipynb`: Se implementa un modelo de traducción de español a inglés secuencia a secuencia (seq2seq), utilizando una arquitectura encoder-decoder con redes LSTM y capas de embedding pre-entrenadas de GloVe para ambos idiomas.

