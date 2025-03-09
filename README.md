# InmoValor_SA

## Proyecto de Análisis y Predicción de Precios de Viviendas

Este proyecto utiliza técnicas de análisis de datos y modelos de machine learning para predecir los precios de viviendas utilizando el dataset "House Prices - Advanced Regression Techniques" de Kaggle. El proyecto se organiza en varias entregas con diferentes Jupyter notebooks para cada etapa del análisis.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

### Análisis
#### Entrega_1
- **Análisis_Exploratorio.ipynb**: Análisis preliminar del dataset y exploración visual de variables.
- **Análisis de Correlación.ipynb**: Estudio de relaciones entre características y precios.
- **Clustering.ipynb**: Aplicación de técnicas de agrupamiento para segmentar datos.
- **Preguntas_exploratorio.ipynb**: Profundización en preguntas específicas sobre el dataset.
- **Regresion_lineal.ipynb**: Implementación de modelos de regresión lineal simples.

#### Entrega_2
- **Árbol_regresion.ipynb**: Modelos de árboles de regresión para predicción de precios.
- **decision_tree_graphviz**: Visualización gráfica de árboles de decisión.
- **RandomForest.ipynb**: Implementación de modelos Random Forest.
- **Validación_cruzada.ipynb**: Técnicas de validación cruzada para evaluar modelos.
- **Variables_Respuesta_clasificacionsCasa.ipynb**: Análisis de variables de respuesta para clasificación.
- **Cambiar_profundidad.ipynb**: Comparación de ajuste de parámetros de profundidad en árboles de clasificación.

### HTML
- **Entrega_1**: Versiones HTML de los notebooks de la primera entrega.
- **Entrega_2**: Versiones HTML de los notebooks de la segunda entrega.

### Archivos Adicionales
- **data_description.txt**: Descripción detallada de las variables del dataset.
- **HDT 3. Modelos de Regresión Lineal.pdf**: Documento de informe sobre el uso de regresión lineal.
- **HDT 4. Árboles de Decisión.pdf**: Documento de informe sobre el uso de árboles de decisión.
- **test.csv**: Conjunto de datos de prueba.
- **train.csv**: Conjunto de datos de entrenamiento.

## Requisitos

Asegúrate de tener instaladas las siguientes librerías para ejecutar los notebooks:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `sklearn`
- `scipy`
- `graphviz` (para visualizaciones de árboles)

Puedes instalarlas usando `pip`:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn scipy graphviz
```

## Cómo ejecutar

1. Clona este repositorio en tu máquina local:
```bash
git clone https://github.com/tu-usuario/InmoValor_SA.git
```

2. Accede a la carpeta del proyecto:
```bash
cd InmoValor_SA
```

3. Abre los notebooks en Jupyter:
```bash
jupyter notebook
```

4. Navega a través de las carpetas "Análisis/Entrega_1" o "Análisis/Entrega_2" y selecciona el notebook que deseas ejecutar.

## Documentación

Los archivos PDF incluidos contienen informes sobre el uso de los modelos con los datos.
- "HDT 3. Modelos de Regresión Lineal.pdf" - Teoría sobre modelos de regresión lineal
- "HDT 4. Árboles de Decisión.pdf" - Teoría sobre árboles de decisión y técnicas relacionadas