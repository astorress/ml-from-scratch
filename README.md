# ML from Scratch

Colección de notebooks de **Machine Learning, Deep Learning, estadística y matemáticas** para estudiar conceptos fundamentales de forma práctica.

## Contenido del repositorio

> Todos los archivos están en formato Jupyter Notebook (`.ipynb`).

### 1) Fundamentos matemáticos y estadísticos
- `AlgebraLineal.ipynb`
- `CalcVectorial.ipynb`
- `EstadisticaFundamental.ipynb`

### 2) Aprendizaje supervisado
- `LinearRegression.ipynb`
- `LogisticRegression.ipynb`
- `KNN.ipynb`
- `NaiveBayes.ipynb`
- `Perceptron.ipynb`
- `SVM.ipynb`
- `DecisionTree.ipynb`
- `RandomForest.ipynb`
- `Adaboost.ipynb`
- `LDA.ipynb`
- `MLP.ipynb`

### 3) Aprendizaje no supervisado y reducción de dimensionalidad
- `KMeans.ipynb`
- `HierarchicalClustering.ipynb`
- `PCA.ipynb`
- `TSNE.ipynb`
- `IsolationForest.ipynb`
- `Autoencoders.ipynb`

### 4) Deep Learning
- `CNN.ipynb`
- `RNN.ipynb`
- `GANs.ipynb`
- `TransferLearning.ipynb`

### 5) Transformers y atención
- `AttentionMechanisms.ipynb`
- `Transformers.ipynb`

### 6) Reinforcement Learning
- `ReinforcementLearning.ipynb`
- `RLLaberinto.ipynb`
- `SudokuRL.ipynb`
- `SudokuDQN.ipynb`

### 7) AutoML, Meta-learning y optimización
- `AutoML.ipynb`
- `MetaLearning.ipynb`
- `Hyperparameters.ipynb`

### 8) Notebooks integradores / aplicados
- `PrediccionClasificacionPronostico.ipynb`

---

## Requisitos recomendados

- Python 3.10+
- Jupyter Notebook o JupyterLab

Instalación rápida sugerida:

```bash
python -m venv .venv
source .venv/bin/activate  # En Windows: .venv\Scripts\activate
pip install --upgrade pip
pip install jupyter numpy pandas matplotlib seaborn scikit-learn
```

> Algunos notebooks (por ejemplo, de Deep Learning) pueden requerir librerías adicionales como `tensorflow` o `torch`.

## Cómo usar este repositorio

1. Abre Jupyter en la raíz del proyecto:
   ```bash
   jupyter notebook
   ```
2. Elige un notebook según el tema.
3. Ejecuta las celdas en orden y ajusta hiperparámetros/ejemplos para experimentar.

## Ruta de estudio sugerida

Si quieres seguir un orden progresivo:

1. `EstadisticaFundamental.ipynb`, `AlgebraLineal.ipynb`, `CalcVectorial.ipynb`
2. `LinearRegression.ipynb`, `LogisticRegression.ipynb`, `KNN.ipynb`, `NaiveBayes.ipynb`
3. `DecisionTree.ipynb`, `RandomForest.ipynb`, `Adaboost.ipynb`, `SVM.ipynb`
4. `KMeans.ipynb`, `PCA.ipynb`, `TSNE.ipynb`, `HierarchicalClustering.ipynb`
5. `MLP.ipynb`, `CNN.ipynb`, `RNN.ipynb`, `TransferLearning.ipynb`
6. `AttentionMechanisms.ipynb`, `Transformers.ipynb`
7. `ReinforcementLearning.ipynb`, `RLLaberinto.ipynb`, `SudokuDQN.ipynb`

## Objetivo

Servir como base práctica para aprender ML desde cero, reforzando teoría con implementación y experimentación en notebooks.
