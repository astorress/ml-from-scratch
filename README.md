# ML from Scratch

Curso práctico de Machine Learning, Deep Learning y Reinforcement Learning en notebooks de Jupyter, desde la regresión lineal hasta Transformers.

## Enfoque

Casi todas las notebooks siguen la misma estructura:

1. **Objetivo:** qué problema resuelve el algoritmo.
2. **Intuición:** cómo funciona, con un ejemplo sencillo.
3. **Demostración matemática:** la formulación y su derivación.
4. **Implementación con código:** el algoritmo desde cero con NumPy o PyTorch, comparado con la versión de scikit-learn cuando existe.

Las notebooks se guardan con sus resultados ejecutados, así que se pueden leer directamente en GitHub.

## Notebooks

Las carpetas y las notebooks están numeradas en el orden sugerido de estudio.

### 00 · Introducción

| # | Notebook | Contenido |
|---|----------|-----------|
| 01 | [Regresión, Clasificación y Pronóstico](notebooks/00-introduccion/01-regresion-clasificacion-pronostico.ipynb) | Diferencias entre los tres tipos de problema, zonas grises y un mismo problema visto desde los tres enfoques |

### 01 · Aprendizaje supervisado

| # | Notebook | Contenido |
|---|----------|-----------|
| 01 | [Regresión Lineal](notebooks/01-aprendizaje-supervisado/01-regresion-lineal.ipynb) | Mínimos cuadrados y la "mejor" recta |
| 02 | [Regresión Logística](notebooks/01-aprendizaje-supervisado/02-regresion-logistica.ipynb) | Clasificación binaria con la función sigmoide |
| 03 | [KNN](notebooks/01-aprendizaje-supervisado/03-knn.ipynb) | Clasificación por vecinos más cercanos |
| 04 | [Naive Bayes](notebooks/01-aprendizaje-supervisado/04-naive-bayes.ipynb) | Clasificación con el teorema de Bayes |
| 05 | [LDA](notebooks/01-aprendizaje-supervisado/05-lda.ipynb) | Análisis discriminante lineal y proyección óptima |
| 06 | [SVM](notebooks/01-aprendizaje-supervisado/06-svm.ipynb) | Hiperplano de margen máximo y kernels |
| 07 | [Árbol de Decisión](notebooks/01-aprendizaje-supervisado/07-arbol-decision.ipynb) | Construcción de reglas por impureza |
| 08 | [Random Forest](notebooks/01-aprendizaje-supervisado/08-random-forest.ipynb) | Ensamble de árboles con bagging |
| 09 | [AdaBoost](notebooks/01-aprendizaje-supervisado/09-adaboost.ipynb) | Boosting adaptativo de clasificadores débiles |

### 02 · Aprendizaje no supervisado

| # | Notebook | Contenido |
|---|----------|-----------|
| 01 | [K-Means](notebooks/02-aprendizaje-no-supervisado/01-kmeans.ipynb) | Clustering por centroides |
| 02 | [Clustering Jerárquico](notebooks/02-aprendizaje-no-supervisado/02-clustering-jerarquico.ipynb) | Fusión de clusters y dendrogramas |
| 03 | [PCA](notebooks/02-aprendizaje-no-supervisado/03-pca.ipynb) | Reducción de dimensionalidad por componentes principales |
| 04 | [t-SNE](notebooks/02-aprendizaje-no-supervisado/04-tsne.ipynb) | Visualización no lineal, experimentos y buenas prácticas |
| 05 | [Isolation Forest](notebooks/02-aprendizaje-no-supervisado/05-isolation-forest.ipynb) | Detección de anomalías por aislamiento |

### 03 · Deep Learning

| # | Notebook | Contenido |
|---|----------|-----------|
| 01 | [Perceptrón](notebooks/03-deep-learning/01-perceptron.ipynb) | Introducción a las redes neuronales y regla de aprendizaje |
| 02 | [Teorema de Aproximación Universal](notebooks/03-deep-learning/02-teorema-aproximacion-universal.ipynb) | Una red con una capa oculta aproximando funciones arbitrarias |
| 03 | [MLP](notebooks/03-deep-learning/03-mlp.ipynb) | Perceptrón multicapa y backpropagation |
| 04 | [CNN](notebooks/03-deep-learning/04-cnn.ipynb) | Redes convolucionales para imágenes |
| 05 | [RNN](notebooks/03-deep-learning/05-rnn.ipynb) | Redes recurrentes para secuencias |
| 06 | [Word Embeddings](notebooks/03-deep-learning/06-word-embeddings.ipynb) | Skip-Gram con negative sampling desde cero |
| 07 | [One-Hot vs Embeddings](notebooks/03-deep-learning/07-one-hot-vs-embeddings.ipynb) | Por qué PCA falla sobre one-hot y cómo los embeddings capturan similitud (t-SNE, UMAP, autoencoder) |
| 08 | [Autoencoders](notebooks/03-deep-learning/08-autoencoders.ipynb) | Compresión, espacio latente y detección de anomalías |
| 09 | [GANs](notebooks/03-deep-learning/09-gans.ipynb) | GAN vanilla, DCGAN, CGAN y WGAN sobre MNIST |
| 10 | [Mecanismos de Atención](notebooks/03-deep-learning/10-mecanismos-atencion.ipynb) | Bahdanau, Luong, self-attention y multi-head attention |
| 11 | [Transformers](notebooks/03-deep-learning/11-transformers.ipynb) | Arquitectura completa desde cero, BERT vs GPT y Hugging Face |

### 04 · Reinforcement Learning

| # | Notebook | Contenido |
|---|----------|-----------|
| 01 | [Reinforcement Learning](notebooks/04-reinforcement-learning/01-reinforcement-learning.ipynb) | MDP, recompensas, Q-Learning y experimentos |
| 02 | [RL en Laberintos](notebooks/04-reinforcement-learning/02-rl-laberinto.ipynb) | Q-Learning, SARSA, DQN y REINFORCE comparados en laberintos |
| 03 | [Sudoku 4x4 con RL](notebooks/04-reinforcement-learning/03-sudoku-4x4-rl.ipynb) | Agente tabular que resuelve Sudokus pequeños |
| 04 | [Sudoku 9x9 con DQN](notebooks/04-reinforcement-learning/04-sudoku-9x9-dqn.ipynb) | Deep Q-Network con experience replay en PyTorch |

### 05 · Hiperparámetros

| # | Notebook | Contenido |
|---|----------|-----------|
| 01 | [Optimización de Hiperparámetros](notebooks/05-hiperparametros/01-optimizacion-hiperparametros.ipynb) | Grid Search, Random Search, optimización bayesiana, algoritmos genéticos, Successive Halving e Hyperband |
| 02 | [Random Search vs Grid Search](notebooks/05-hiperparametros/02-random-search-vs-grid-search.ipynb) | Comparación experimental de ambas búsquedas |

## Estructura

```
.
├── notebooks/
│   ├── 00-introduccion/
│   ├── 01-aprendizaje-supervisado/
│   ├── 02-aprendizaje-no-supervisado/
│   ├── 03-deep-learning/
│   ├── 04-reinforcement-learning/
│   └── 05-hiperparametros/
├── requirements.txt
└── README.md
```

## Cómo usar

Requisitos: Python 3.10 o superior.

```bash
git clone https://github.com/astorress/ml-from-scratch.git
cd ml-from-scratch

python -m venv .venv
source .venv/bin/activate        # Windows: .venv\Scripts\activate
pip install -r requirements.txt

jupyter notebook
```

Abre cualquier notebook de la carpeta `notebooks/` y ejecuta las celdas en orden.

También puedes abrir cualquier notebook en [Google Colab](https://colab.research.google.com): *File → Open notebook → GitHub* y pega la URL del repositorio.

### Notas

- **Dependencias:** las secciones 00, 01, 02 y 05 solo necesitan la sección base de `requirements.txt` (NumPy, SciPy, pandas, Matplotlib y scikit-learn). Deep Learning y Reinforcement Learning requieren además PyTorch, y algunas notebooks puntuales usan TensorFlow o Hugging Face Transformers.

## Repositorios relacionados

- [math-for-ml](https://github.com/astorress/math-for-ml): álgebra lineal, sistemas de ecuaciones, cálculo vectorial y estadística para ML.
- [algoritmos-from-scratch](https://github.com/astorress/algoritmos-from-scratch): complejidad, búsqueda, ordenamiento, grafos, optimización y computación cuántica desde cero.
- [data-science-lab](https://github.com/astorress/data-science-lab): casos prácticos de data science aplicado con librerías.
