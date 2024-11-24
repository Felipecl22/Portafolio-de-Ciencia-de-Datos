# Métodos de Machine Learning "Guía de modelos":

# 1. Aprendizaje supervisado:

En el aprendizaje supervisado, el algoritmo recibe un conjunto de datos de entrenamiento que incluye entradas y las correspondientes salidas deseadas (etiquetas). El objetivo del algoritmo es aprender una función que pueda mapear las entradas a las salidas correctas. Durante el entrenamiento, el algoritmo ajusta sus parámetros para minimizar la discrepancia entre las salidas predichas y las salidas reales. Una vez que se entrena el modelo, se puede usar para predecir las salidas de nuevas entradas para las que no se conoce la salida real. Ejemplos de problemas de aprendizaje supervisado incluyen clasificación (predecir una etiqueta de clase) y regresión (predecir un valor numérico).

# 2. Aprendizaje no supervisado:

En el aprendizaje no supervisado, el algoritmo recibe un conjunto de datos de entrenamiento que consiste solo en entradas, sin ninguna información sobre las salidas correspondientes. El objetivo del algoritmo es descubrir patrones o estructuras intrínsecas en los datos sin la guía de salidas conocidas. Esto puede implicar agrupar los datos en clusters basados en similitudes entre las observaciones (clustering), reducir la dimensionalidad de los datos manteniendo la mayor parte de la información (como en el análisis de componentes principales), o encontrar relaciones entre variables (como en el análisis de asociación). En resumen, en el aprendizaje no supervisado, el algoritmo debe inferir la estructura subyacente o la distribución de los datos sin la ayuda de etiquetas previas.

# Aprendizaje supervisado:

Gradient Boosting
Naive Bayes
SVM (Support Vector Machine)
Árbol de Decisión (Decision Tree)
Random Forest
KNN (K-Nearest Neighbors)
Regresión Logística (Logistic Regression)
Regresión Múltiple (Multiple Regression)
Regresión Lineal (Linear Regression)

# Aprendizaje no supervisado:

K-Means

# 2. Clasificación de los algoritmos según su aplicabilidad para regresión y clasificación:

Regresión y clasificación:

Gradient Boosting
SVM (Support Vector Machine)
Árbol de Decisión (Decision Tree)
Random Forest
KNN (K-Nearest Neighbors)
Regresión Logística (Logistic Regression)
Regresión Múltiple (Multiple Regression)
Regresión Lineal (Linear Regression)

Solo clasificación:

Naive Bayes

Solo clustering:

K-Means

# Mejores métodos para regresión y clasificación:

Para regresión:

Gradient Boosting
Regresión Múltiple (Multiple Regression)
Regresión Lineal (Linear Regression)
SVM (Support Vector Machine) (para problemas de regresión)
Random Forest (para problemas de regresión)
KNN (K-Nearest Neighbors) (para problemas de regresión)
Para clasificación:

Gradient Boosting
SVM (Support Vector Machine)
Árbol de Decisión (Decision Tree)
Random Forest
KNN (K-Nearest Neighbors)
Regresión Logística (Logistic Regression)
Naive Bayes

# 3. Lista de métodos de regresión y algunas consideraciones sobre cuándo podría ser apropiado utilizar cada uno:

Regresión Lineal (Linear Regression):

Cuándo usarlo: Es útil cuando se asume una relación lineal entre las variables predictoras y la variable objetivo. También es rápido de entrenar e interpretar. Sin embargo, puede no funcionar bien si la relación entre las variables no es lineal.

Regresión Múltiple (Multiple Regression):

Cuándo usarlo: Similar a la regresión lineal, pero permite múltiples variables predictoras. Útil cuando se tiene más de una variable independiente que afecta a la variable dependiente.

Random Forest:

Cuándo usarlo: Aunque es más comúnmente utilizado para clasificación, también puede ser utilizado para regresión (Random Forest Regressor). Es útil cuando se tienen variables predictoras tanto lineales como no lineales, y se quiere manejar de forma robusta la multicolinealidad y la no linealidad.

Gradient Boosting:

Cuándo usarlo: Es muy efectivo para problemas de regresión cuando se tienen datos heterogéneos y complejos. Puede capturar relaciones no lineales y manejar bien los datos faltantes. Sin embargo, puede ser propenso a sobreajustarse si no se controlan los hiperparámetros adecuadamente.

Support Vector Machine (SVM):

Cuándo usarlo: Aunque es más comúnmente utilizado para clasificación, también puede ser utilizado para regresión (Support Vector Regression, SVR). Es útil cuando se tienen datos con estructuras no lineales y se busca una solución robusta, especialmente en conjuntos de datos de pequeño a mediano tamaño.

K-Nearest Neighbors (KNN): Cuándo usarlo: Puede ser útil cuando se tiene poca información sobre la distribución de los datos o cuando se sospecha que la relación entre las variables predictoras y la variable objetivo puede ser localmente no lineal. Sin embargo, puede ser computacionalmente costoso para grandes conjuntos de datos y puede ser sensible a la elección del parámetro k.

En resumen, la elección del método de regresión depende en gran medida de la naturaleza de los datos y de las relaciones que se espera modelar. La regresión lineal y múltiple son opciones sólidas para relaciones lineales simples, mientras que Random Forest y Gradient Boosting pueden manejar relaciones más complejas. SVM y KNN son útiles cuando se necesitan modelos más flexibles o cuando se enfrentan problemas con estructuras no lineales.

# 4. Lista de métodos de clasificación y algunas consideraciones sobre cuándo podría ser apropiado utilizar cada uno:

Árbol de Decisión (Decision Tree):

Cuándo usarlo: Es útil cuando se desea una interpretación clara del modelo y cuando se tienen variables categóricas o numéricas. Los árboles de decisión pueden manejar relaciones no lineales y son robustos ante valores atípicos y datos faltantes. Sin embargo, tienden a sobreajustarse a menos que se utilicen técnicas de regularización.

Random Forest:

Cuándo usarlo: Es una extensión de los árboles de decisión y es útil cuando se busca una mayor precisión y robustez. Puede manejar una gran cantidad de datos con alta dimensionalidad y es menos propenso al sobreajuste que un solo árbol de decisión. Es eficaz en una amplia gama de conjuntos de datos, incluidos aquellos con características categóricas o numéricas.

Gradient Boosting:

Cuándo usarlo: Similar a Random Forest, es útil cuando se desea alta precisión y puede manejar una variedad de tipos de datos. Gradient Boosting puede ser especialmente eficaz en conjuntos de datos desequilibrados y es menos propenso al sobreajuste si se ajustan adecuadamente los hiperparámetros. Sin embargo, puede ser computacionalmente costoso y más sensible a los hiperparámetros que Random Forest.

SVM (Support Vector Machine):

Cuándo usarlo: Es útil cuando se tienen datos de alta dimensionalidad y se busca una solución robusta que pueda manejar tanto datos lineales como no lineales. SVM es especialmente efectivo en espacios de características de alta dimensión y puede generalizar bien incluso en conjuntos de datos pequeños. Sin embargo, puede ser computacionalmente costoso con grandes conjuntos de datos y puede requerir una cuidadosa selección de hiperparámetros.

K-Nearest Neighbors (KNN):

Cuándo usarlo: Es útil cuando se tienen datos con estructuras no lineales y se busca una solución simple y fácil de interpretar. KNN es robusto ante ruido y puede capturar relaciones complejas en los datos. Sin embargo, puede ser computacionalmente costoso, especialmente con grandes conjuntos de datos, y puede ser sensible a la elección del parámetro k.

Regresión Logística (Logistic Regression):

Cuándo usarlo: Es útil cuando se desea una interpretación probabilística de las predicciones y se tiene una relación lineal o casi lineal entre las variables predictoras y la variable objetivo. Es eficiente computacionalmente y puede manejar datos de alta dimensionalidad. Sin embargo, puede no ser tan flexible como otros métodos no lineales y puede sufrir de sesgo si la relación entre las variables es no lineal.

Naive Bayes:

Cuándo usarlo: Es útil cuando se tienen datos con múltiples características independientes y se busca una solución rápida y simple. Naive Bayes es especialmente efectivo en conjuntos de datos de alta dimensionalidad y puede manejar datos categóricos y numéricos. Sin embargo, su suposición de independencia entre las características puede no ser realista en muchos casos, lo que puede llevar a una precisión reducida en conjuntos de datos complejos.

# 5. Otros métodos comunes utilizados en aprendizaje supervisado y no supervisado:

En aprendizaje supervisado:

Validación cruzada (Cross Validation):

Es una técnica utilizada para evaluar el rendimiento de un modelo de aprendizaje supervisado. Consiste en dividir el conjunto de datos en subconjuntos de entrenamiento y prueba de manera iterativa, entrenando el modelo en una parte de los datos y evaluándolo en otra. Esto ayuda a estimar cómo se comportará el modelo con datos nuevos y no vistos.

Análisis de discriminante lineal (LDA - Linear Discriminant Analysis):

Es una técnica utilizada para encontrar la combinación lineal de características que mejor separa múltiples clases en los datos. LDA busca maximizar la separación entre clases mientras minimiza la dispersión dentro de cada clase. Es útil para la reducción de dimensionalidad y la clasificación.

Regularización:

Es una técnica utilizada para evitar el sobreajuste al agregar términos de penalización a la función de costo. Dos formas comunes de regularización son la regularización L1 (Lasso) y la regularización L2 (Ridge). Estas técnicas ayudan a reducir la complejidad del modelo y mejorar su capacidad de generalización.

Funciones de pérdida (Loss Functions):

Son funciones que miden la discrepancia entre las predicciones del modelo y los valores reales. En clasificación, la función de pérdida comúnmente utilizada es la entropía cruzada, mientras que en regresión, se utiliza el error cuadrático medio (MSE) o el error absoluto medio (MAE).

En aprendizaje no supervisado:

Análisis de componentes principales (PCA - Principal Component Analysis):

Es una técnica de reducción de dimensionalidad que transforma el conjunto de datos en un nuevo conjunto de variables (llamadas componentes principales) que son combinaciones lineales de las características originales. El objetivo es capturar la mayor cantidad posible de la variabilidad de los datos en menos dimensiones, lo que facilita la visualización y el análisis de los datos.

Análisis de discriminante lineal (LDA - Linear Discriminant Analysis):

Aunque LDA se utiliza principalmente en aprendizaje supervisado para clasificación, también se puede aplicar en aprendizaje no supervisado como una técnica de reducción de dimensionalidad. En este contexto, se busca maximizar la separación entre clases en lugar de utilizar etiquetas de clase.

Validación cruzada (Cross Validation):

Si bien también se utiliza en aprendizaje supervisado, la validación cruzada puede ser útil en aprendizaje no supervisado para evaluar la efectividad de técnicas de agrupamiento como el k-means, donde no hay etiquetas de clase para la evaluación directa.

Método del codo (Elbow Method):

Es una técnica utilizada para determinar el número óptimo de clusters en un algoritmo de clustering, como K-Means. Consiste en trazar la suma de las distancias al cuadrado de los puntos al centroide más cercano en función del número de clusters y seleccionar el punto en el que la disminución de la suma de las distancias comienza a disminuir drásticamente, formando una "curva de codo".

Silhouette Score:

Es una medida de cuán bien están separados los clusters en un conjunto de datos. Cuanto mayor sea el valor del coeficiente de silueta, mejor es la separación entre los clusters. Se utiliza para evaluar la calidad de un clustering y puede ayudar a determinar el número óptimo de clusters.

Reducción de la dimensionalidad no supervisada:

Además del PCA, existen otras técnicas de reducción de dimensionalidad no supervisadas como el t-SNE (t-distributed Stochastic Neighbor Embedding) y el UMAP (Uniform Manifold Approximation and Projection) que se utilizan para visualizar conjuntos de datos de alta dimensionalidad en un espacio de menor dimensión preservando la estructura local o global de los datos.

Estos son solo algunos de los métodos adicionales que se utilizan comúnmente en machine learning para mejorar la calidad de los modelos y el análisis de los datos. Cada uno de ellos tiene su propia aplicación y puede ser útil en diferentes situaciones dependiendo del problema y de los datos disponibles.

Análisis de Componentes Principales (PCA) tiene varias aplicaciones importantes:

Reducción de dimensionalidad:

PCA se utiliza comúnmente para reducir la dimensionalidad de los datos al transformar un conjunto de variables correlacionadas en un conjunto de variables no correlacionadas (llamadas componentes principales). Esto es útil para visualizar y analizar conjuntos de datos de alta dimensionalidad, así como para eliminar la redundancia y el ruido de los datos.

Visualización de datos:

PCA se utiliza para visualizar datos de alta dimensionalidad en un espacio de menor dimensión mientras se conserva la mayor parte de la variabilidad de los datos. Esto permite explorar la estructura subyacente de los datos y encontrar patrones o agrupaciones que pueden no ser evidentes en las dimensiones originales.

Compresión de datos:

PCA puede ser utilizado para comprimir datos al reducir el número de dimensiones necesarias para representar los datos mientras se conserva la mayor cantidad posible de información. Esto es útil en aplicaciones donde se necesita almacenar o transmitir grandes cantidades de datos de manera eficiente. Preprocesamiento de datos: PCA se puede utilizar como una técnica de preprocesamiento de datos para mejorar el rendimiento de otros algoritmos de machine learning al reducir la dimensionalidad y eliminar la multicolinealidad entre las variables predictoras.

En resumen, PCA tiene una amplia gama de aplicaciones en el análisis de datos y el machine learning, y es una herramienta fundamental para la exploración, visualización y reducción de la dimensionalidad de conjuntos de datos complejos.
